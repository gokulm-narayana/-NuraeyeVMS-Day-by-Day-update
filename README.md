# Nuraeye VMS - Comprehensive Feature Walkthrough

This document provides a detailed overview of the Nuraeye Video Management System (VMS), covering every functional aspect of the application from dashboard monitoring to detailed configuration.

## 1. Executive Dashboard
The centralized hub for system oversight, providing real-time metrics and quick access to critical issues.

![Dashboard Overview](./walk/dashboard_overview.png)

**Key Features:**
- **Camera Summary**: Status counts (Total, Online, Offline, Recording).
- **System Health**: Metrics for Storage, Retention, CPU, and Uptime.
- **Widgets**:
    - **Camera Issues**: Links to diagnostic details (see Section 6).
    - **Active Alerts**: Recent incidents needing attention.

---

## 2. Camera Management
A robust interface for managing the entire camera network.

![Camera List](./walk/cameras_list.png)

**Key Features:**
- **Inventory Table**: Real-time status, IP, and location data.
- **Filtering & Search**: Quickly find cameras by specific attributes.
- **Settings Access**: "Settings" button on each row opens detailed configuration (see Section 3).

---

## 3. Camera Configuration (Settings)
Detailed configuration for individual camera units.

![Camera Settings](./walk/camera_settings.png)

**Capabilities:**
- **General Info**: Edit Camera Name, ID/IP, and location.
- **Stream Settings**: Adjust Resolution, Frame Rate (FPS), and Bitrate.
- **Recording Config**: Set retention policies and recording triggers (Continuous/Motion).
- **Maintenance**: Reboot device or update firmware.

---

## 4. Live Monitoring (Multiview)
The command center for active surveillance.

![Multiview Grid](./walk/multiview_grid.png)

**Key Features:**
- **Dynamic Grid**: customizable layouts (1x1 to 4x4).
- **Drag & Drop**: Easily assign cameras to viewports.
- **Live Status**: Real-time indicators for recording and signal status.

---

## 5. Incident Management (Alerts)
A dedicated workflow for handling security alarms.

![Alerts List](./walk/alerts_list.png)

**Key Features:**
- **Unified List**: All system alerts categorized by severity.
- **Smart Filters**: Filter by Time Range, Status (Unread/Resolved), and Severity.

---

## 6. Incident Response (Alert Details)
**Optimized Workflow**: Designed for rapid visual verification.

![Alert Details](./walk/alert_details.png)

**Layout Highlights:**
- **Video First**: Large video player on the left for immediate evidence review.
- **Contextual Info**: Metadata (Severity, Time, Location) stacked on the right.
- **Blue Action Buttons**: "Acknowledge" and "Resolve" are highlighted for quick response.
- **No Scrolling**: optimized layout ensures all critical info is visible at once.

---

## 7. Diagnostics (Issue Details)
Deep dive into camera connectivity and health issues.

![Camera Issue Details](./walk/camera_issue_details.png)

**Features:**
- **Diagnostic Log**: Step-by-step history of connection attempts and errors.
- **Troubleshooting Actions**: "Retry Connection" and "Reboot Camera" controls.
- **Tech Details**: Specific error codes and signal strength metrics.

---

## 8. User & System Menu
Access to personalization and global application settings.

![User Menu](./walk/user_profile_menu.png)

**Options:**
- **Profile**: Manage user account details (Avatar, Email).
- **App Settings**: Global preferences (Theme, Notifications).
- **Logout**: Secure session termination.
