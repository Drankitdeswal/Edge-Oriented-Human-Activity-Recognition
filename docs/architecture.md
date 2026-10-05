# System Architecture

This document describes the proposed architecture for an Edge-Oriented Human Activity Recognition system.

## Processing Flow

Data Sources → Edge Device → Preprocessing → ML Model → Activity Recognition → Cloud

## Design Goals

- Low latency
- Efficient data processing
- Reduced cloud dependency
- Efficient bandwidth utilization
- Scalable architecture
- Edge–Cloud collaboration

## Edge Computing Role

The Edge layer performs initial data processing closer to the data source. This can reduce latency and unnecessary transmission of raw data to centralized cloud infrastructure.

## Cloud Role

The Cloud layer can provide centralized storage, analytics, model management, monitoring, and long-term data processing.
