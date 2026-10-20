# Project Requirements

## 1. Purpose

The purpose of the PGI Network Management & Optimization Framework is to develop a practical, PGI-specific approach to campus network monitoring, performance analysis, health assessment, and technical documentation.

## 2. Functional Requirements

| ID | Requirement | Description |
|---|---|---|
| FR-01 | Network Monitoring | Monitor the availability and status of authorized network devices. |
| FR-02 | Metrics Collection | Collect available network metrics such as latency, packet loss, bandwidth utilization, and interface status. |
| FR-03 | Dashboard | Present collected network information through a centralized dashboard. |
| FR-04 | Alert Management | Identify configured abnormal conditions and record relevant alerts. |
| FR-05 | Performance Analysis | Analyze available measurements to identify performance issues and trends. |
| FR-06 | Network Health Assessment | Evaluate network condition using defined indicators and assessment criteria. |
| FR-07 | Report Generation | Generate reports containing measurements, identified issues, and assessment results. |
| FR-08 | Device Inventory | Maintain structured records of network devices and their relevant properties. |
| FR-09 | Network Documentation | Maintain logical and physical network documentation where information is available and authorized. |
| FR-10 | Access Management | Restrict framework functions according to assigned user permissions, where implemented. |
| FR-11 | Change Documentation | Record approved network changes and their verification results. |
| FR-12 | Error Handling | Handle monitoring, database, and service failures with appropriate logs and error messages. |

## 3. Non-Functional Requirements

- **Reliability:** The framework should handle temporary failures gracefully.
- **Security:** Access to the framework and its data should be appropriately restricted.
- **Maintainability:** Components and documentation should be organized for future updates.
- **Usability:** The dashboard and reports should be understandable to network administrators.
- **Performance:** Data collection and dashboard requests should operate within defined response-time targets.
- **Traceability:** Assessment results and approved changes should be documented.
- **Data Protection:** Sensitive network information must be protected and excluded from public repository files.

## 4. Evaluation Criteria

The framework will be evaluated using measurable indicators where data and access permit.

Potential indicators include:

- Device availability and uptime
- Network latency and packet loss
- Bandwidth utilization
- Detection and recording of configured alerts
- Network documentation coverage
- Accuracy and completeness of generated reports
- Dashboard response time
- Error handling and recovery behavior

Baseline and post-implementation results will be compared where a suitable implementation and measurement period are available.

## 5. Scope and Constraints

- All production network assessments require appropriate authorization.
- Production configuration changes require approval and suitable backup and rollback procedures.
- Disruptive experiments will be performed only in an authorized test environment.
- Implementation depends on available hardware, monitoring capabilities, permissions, and project time.
- Features that are not implemented will be identified as planned or future work rather than completed functionality.

## 6. Distinctive Project Contribution

The project will investigate the integration of existing monitoring tools with a PGI-specific network health assessment methodology, structured reporting, network documentation, and controlled operational workflows.

The framework is intended to complement existing tools rather than replace them.

## 7. Requirement Status

These requirements are preliminary and will be refined after stakeholder discussions, infrastructure assessment, and supervisor feedback.
