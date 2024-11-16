# Warranty Claim Request App

## Overview
The Warranty Claim Request App is a PowerApps-based solution that streamlines the process of submitting and managing warranty claims. The app allows users to upload images and video links related to their claims, provides an admin interface for reviewing requests, and supports feedback sharing. The app also includes an admin login page with user credential validation for secure access.

---

## Features
- **Dynamic Form**: Capture detailed warranty claim information, including:
  - Product Details
  - Claim Description
  - Customer Information
  - Warranty Tracking Code (auto-generated in ddmmyy-hhmmss format)
- **Media Uploads**:
  - Users can upload supporting images and video links for their warranty claims.
- **Admin Panel**:
  - An admin login page with secure user credential validation.
  - Admins can view, review, and provide feedback on submitted warranty claims.
- **Feedback Sharing**:
  - Admins can provide feedback on claims, which users can view within the app.
- **Document Management**:
  - Uploaded images and links are stored in a SharePoint Document Library for centralized access.
- **Automated Email Notifications**:
  - Notify relevant teams or individuals when a new warranty claim is submitted.
  - Include claim details, feedback, and links to uploaded media in the emails.
- **Data Storage**:
  - Submit claim data to an Excel file for tracking and reporting.
  - Store uploaded documents in a SharePoint Document Library for easy access.
- **Unique Tracking Codes**:
  - Automatically generate unique tracking codes for each claim for easy identification and traceability.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Automated email notifications and document uploads
- **Excel**:
  - Data storage for claim tracking
- **SharePoint**:
  - Backend for document and media storage
- **Office 365 Outlook Integration**:
  - Email functionality

---

## How It Works
1. **Submit Warranty Claim**:
   - Users fill out the warranty claim form with required details, including images and video links.
   - Data is stored in an Excel file, and supporting media is uploaded to SharePoint.
2. **Admin Review**:
   - Admins log in using secure credentials to access the admin panel.
   - Admins can view submitted claims, including uploaded media and video links.
   - Admins provide feedback, which is stored and sent to the user.
3. **Document and Media Uploads**:
   - Images and video links are automatically uploaded to a SharePoint Document Library using Power Automate flows.
4. **Automated Emails**:
   - Notification emails are sent to the designated team and include claim details, feedback, and links to uploaded media.
5. **Unique Tracking**:
   - A unique tracking code is generated for each claim request, ensuring precise tracking and follow-up.

---

## Benefits
- Simplifies the warranty claim submission process with a user-friendly interface.
- Enhances claim visibility with image and video link uploads.
- Facilitates efficient review and feedback sharing through an admin panel.
- Provides secure access for admins with credential validation.
- Improves traceability with unique tracking codes for each claim.

---

## Future Enhancements
- Integration with Power BI for advanced analytics and reporting.
- Multi-user role support for claim management and escalations.
- Workflow automation for claim approvals.

---

