 BLOODBRIDGE
 CLOUD-BASED BLOOD BANK INVENTORY AND DONOR MANAGEMENT SYSTEM

A scalable AWS-powered platform for connected blood bank operations.

 1. PROJECT OVERVIEW

BloodBridge is a cloud-based platform designed to manage blood donors, donation records, and blood inventory across multiple blood storage centers.

It provides a centralized system that helps blood bank staff and administrators maintain donor information, track blood availability, manage stock levels, and monitor blood expiry dates efficiently.

The platform uses AWS cloud services to provide scalability, reliability, and better management of blood bank operations.

2. TEAM MEMBERS

1. Sahasra Kakunuru – 2520030222
2. Khyati Karri – 2520030279

Project Guide: Dr. S. Vinay Kumar

3. PROBLEM STATEMENT

Traditional blood bank management systems often maintain donor records and blood inventory separately. This creates several problems:

 Donor information may be stored in different registers or systems.
 Blood stock availability may not be updated regularly.
 Manual coordination between storage centers takes time.
 Tracking blood expiry dates can be difficult.
 Locally hosted systems may face scalability challenges.

Our project, BloodBridge, proposes a centralized cloud-based platform to overcome these challenges and improve blood bank management.

 4. PROJECT OBJECTIVES

 Centralize donor information and donation records.
 Maintain blood inventory in one platform.
 Track blood groups, quantities, and expiry dates.
 Improve visibility of blood availability across multiple centers.
 Support faster coordination among authorized staff.
 Provide secure user access and data management.
 Improve application scalability and reliability using AWS.

 5. MAIN FEATURES

 1. Donor Registration
Allows staff to register new donors and maintain their personal details, contact information, and basic eligibility information.

 2. Donation History
Maintains donor donation records, including donation dates, centers, and relevant donation details.
 3. Blood Inventory Management
Tracks available blood units based on blood group, component, quantity, location, and expiry date.
 4. Storage Center Management
Maintains information about multiple blood storage centers and their available stock.
 5. Search and Reporting
Helps staff search donor details, check blood availability, and generate operational summaries.

 6. User and Access Management
Provides user authentication and role-based access for administrators and authorized staff.

 6. WORKING OF THE PROJECT

1. Staff Login: Authorized staff and administrators sign in to the BloodBridge application.
2. Donor Registration: Staff register donors and maintain their information.
3. Donation Records: Donation details are recorded in the system.
4. Inventory Updates: Collected blood units are added with their blood group, component, quantity, and expiry date.
5. Availability Checking: Staff check available blood stock across different storage centers.
6. System Monitoring: CloudWatch monitors application and infrastructure performance.
                                                                                                                                        7. AWS SERVICES AND TECHNOLOGIES USED

1. Amazon EC2: Hosts and runs the application instances.
2. Amazon RDS: Stores donor details, donation records, and blood inventory information.
3. Amazon CloudWatch: Monitors application performance, logs, metrics, and alarms.
4. Elastic Load Balancer: Distributes incoming application traffic across application instances.
5. Auto Scaling: Automatically adjusts EC2 computing capacity based on application demand.
6. Docker: Packages the application and its dependencies into containers.

 Proposed AWS Architecture
 Users access the BloodBridge web application.
 Load Balancer distributes incoming requests.
 Dockerized application instances run on Amazon EC2.
 Auto Scaling adjusts computing resources according to demand.
 Amazon RDS stores donor, donation, and inventory data.
 Amazon CloudWatch monitors application health and performance.

 8. SECURITY AND RELIABILITY

 User authentication and role-based access control.
 Encrypted connections for secure communication.
 Restricted database access.
 Database backups and recovery procedures.
 Load balancing for better availability.
 Auto Scaling for changing workloads.
 CloudWatch monitoring, logs, and alarms.

 9. BENEFITS

 Centralized donor and inventory information.
 Faster blood stock lookup.
 Improved coordination between storage centers.
 Better record management and consistency.
 Easy tracking of blood availability and expiry dates.
 Scalable cloud infrastructure.
 Improved monitoring of application performance.
 Efficient blood bank operations.

 10. FUTURE ENHANCEMENTS

 SMS and email alerts for urgent blood requirements.
 Donor appointment scheduling.
 Donor eligibility reminders.
 Blood expiry notifications.
 Blood demand forecasting.
 Analytics dashboard for donation trends.
 Mobile-friendly interface.
 Secure APIs for system integration.

 11. CONCLUSION

BloodBridge provides a proposed cloud-based solution for managing blood bank operations efficiently. It connects donor information, donation history, and blood inventory through a centralized platform.

By integrating AWS services such as Amazon EC2, Amazon RDS, CloudWatch, Load Balancing, and Auto Scaling, the system provides a foundation for secure, scalable, and reliable blood bank management.
