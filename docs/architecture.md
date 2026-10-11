# MetroSense City — System Architecture

## Overview

MetroSense City is designed to digitize inspection workflows
and simplify test-report generation for Non-Automatic
Weighing Instruments (NAWI).

## Main Components

### 1. Frontend
Provides the interface for instrument management,
inspection forms, and report viewing.

### 2. Backend
Processes application requests and validates data.

### 3. Calculation Engine
Calculates measurement errors and evaluates results
against applicable configured metrological requirements.

### 4. Database
Stores instrument information, test observations,
and inspection records, if implemented.

### 5. Report Generation
Produces standardized test reports from inspection data.

### 6. Audit Trail
Tracks important record changes and report versions,
where these capabilities are implemented.

## Basic Workflow

1. Select a weighing instrument.
2. Enter inspection details.
3. Record test observations.
4. Calculate measurement errors.
5. Evaluate applicable limits.
6. Review the test results.
7. Generate and retrieve the report.

## Implementation Status

This document describes the intended architecture.
Actual components and capabilities depend on the
features implemented in the current application.
