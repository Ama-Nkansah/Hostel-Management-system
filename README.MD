# Automating Electricity Billing Systems for AAMUSTED Hostels

This project focuses on automating electricity billing in hostels at Akenten Appiah-Menka University of Skills Training and Entrepreneurial Development (AAMUSTED). By integrating ECG's prepaid metering systems with IoT technology, we aim to provide an accurate, transparent, and conflict-free billing solution.

## Problem Overview

Current electricity billing in AAMUSTED hostels relies on shared costs or flat rates, leading to unfair charges and disputes among occupants. This project proposes a scalable, automated system to track and bill individual electricity consumption in real time, ensuring equity and accountability.

## Technology Stack

- **Hardware**: ECG Prepaid Meters, IoT-enabled energy trackers.  
- **Frontend**: HTML, Tailwind CSS and JavaScript for responsive and interactive dashboards.  
- **Backend**: Node.js with Express.js for API development.  
- **Database**: MongoDB for storing consumption data and billing records.  
- **IoT Integration**: MQTT protocol for real-time communication with devices.  
- **Deployment**: Vercel/GitHub for Hosting.

## Technical Overview

### System Architecture
1. **IoT Integration**: IoT devices capture individual room electricity consumption.  
2. **Data Processing**: Real-time data is transmitted to a cloud server via MQTT.  
3. **Billing Algorithm**: A backend service processes usage data to calculate charges.  
4. **User Dashboard**: Students access a React-based dashboard to view usage and billing information.

### Features
- **Automated Metering**: Tracks individual consumption using IoT energy trackers.  
- **Real-Time Analytics**: Provides live insights into electricity usage.  
- **Transparent Billing**: Students and managers can access detailed billing records.  
- **Conflict Mitigation**: Eliminates disputes by ensuring accurate usage tracking.

## Research Plan

### Phase 1: Data Collection
- Conduct surveys to identify billing challenges faced by students.  
- Analyze ECG’s prepaid metering infrastructure for adaptability.

### Phase 2: Prototype Development
- Integrate IoT devices with ECG meters for usage tracking.  
- Build a backend system to process and allocate electricity costs.

### Phase 3: Pilot Testing
- Deploy the system in selected hostels.  
- Collect feedback and refine the solution for scalability and usability.

## Timeline

| Week | Task                                                   |
|------|--------------------------------------------------------|
| 1    | Surveys, data collection, and requirement analysis.    |
| 2    | System design and initial prototype development.       |
| 3    | IoT integration and backend development.               |
| 4    | Pilot deployment, testing, and system refinement.      |

## Contribution Guide

1. Clone the repository:
   ```bash
   git clone https://github.com/yourgroupname/aamusted-billing-system.git
