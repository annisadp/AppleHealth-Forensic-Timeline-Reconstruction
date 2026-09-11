# Apple Health Forensic Timeline Reconstruction

A Python-based forensic framework for extracting and timeline reconstructing Apple Health artifacts from iOS databases for digital forensic investigations.

## Overview

Apple Health Forensic Timeline Reconstruction is a forensic extraction tool designed to analyze Apple Health SQLite databases obtained from iOS device acquisitions.

The framework supports multiple iOS database schemas and reconstructs timeline-based artifacts from:

- healthdb.sqlite
- healthdb_secure.sqlite

The tool focuses on extracting digital evidence artifacts while maintaining read-only database access.

## Supported iOS Versions

The framework supports:

- iOS 13.3.1
- iOS 13.4.1
- iOS 15
- iOS 16
- iOS 17

## Extracted Artifacts

The tool currently supports extraction of:

- Achievements
- Workouts
- Headphone Audio Level
- Heart Rate
- Resting Heart Rate
- Steps
- Height
- Weight
- Watch Worn Data
- All Watch Sleep
- Watch By Sleep Period
- Source Devices 
- Wrist Temperature

## Features

- Read-only SQLite database connection
- Apple Cocoa timestamp conversion
- Multi-schema iOS database handling
- Timeline reconstruction
- Cross-database metadata correlation
- Structured forensic reporting

## Installation

Clone this repository:

```bash
git clone https://github.com/annisadp/AppleHealth-Forensic-Timeline-Reconstruction.git