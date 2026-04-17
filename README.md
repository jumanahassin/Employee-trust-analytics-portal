Employee-trust-analytics-portal
An HR analytics project based on interpersonal trust and employee engagement that utilizes a 24-item scale. Integrates statistical, SQL, Python and Power BI to quantify dimensions of trust, test reliability and create actionable insights to enhance communication, leadership effectiveness and workplace culture.
TrustPulse – Employee Trust Analytics Portal

Project Overview
TrustPulse is a web-based analytics portal developed as part of an MBA project.
It focuses on measuring and analyzing interpersonal trust among employees using a structured survey and visual dashboards.
The system helps organizations understand trust levels, identify risk areas, and improve employee engagement through data-driven insights.

Objectives
Measure employee trust levels using ITS (Interpersonal Trust Scale)
Analyze key trust drivers:
  * Communication
  * Openness
  * Professional Support
  * Managerial Competency
Provide visual insights using dashboards
Support HR decision-making with analytics and ML predictions

Features
Employee Module

* Employee login interface
* Personal & professional data collection
* 24-question trust survey (Likert scale)
* Secure response submission

Admin Module
* Dashboard access
* KPI metrics display
* Risk identification (low trust employees)
* ML-based predictions (Linear Regression & Random Forest)

Analytics Dashboard
* Trust score visualization
* Role-wise & department-wise comparison
* Trust segmentation (Low / Moderate / High)
* Engagement vs Trust analysis
* Feature importance insights

POWERBI INTEGRATION
Interactive dashboards for:
  * Overall Trust
  * Communication
  * Openness
  * Professional Support
  * Managerial Competency

Technologies Used
Frontend: HTML, CSS, JavaScript
Visualization: Power BI
Data Source: Google Forms & Excel
Deployment:GitHub Pages



Project Structure
employee-trust-analytics-portal/
│
├── index.html
├── images/
│   ├── overall.png
│   ├── communication.png
│   ├── openness.png
│   ├── support.png
│   └── competency.png
```

Live Demo
👉 https://jumanahassin.github.io/employee-trust-analytics-portal/

 Dataset
* Collected using Google Forms
* Processed using Excel
* Includes 102 employee responses

Machine Learning Models
Linear Regression
  * Predicts engagement & satisfaction
 Random Forest Classifier
  * Predicts disengagement risk
  * Accuracy: 91.3%



Key Insights
* Communication is the weakest trust factor
* Majority employees fall under **moderate trust**
* Managerial competency strongly influences trust
* Early detection of disengagement is possible using ML



 Academic Context
This project is part of an MBA research study titled:

“A Study on People Analytics Approach to Measuring and Monitoring Interpersonal Trust to Maintain Employee Engagement at the Workplace.”



AuthorJumana Hassin S
MBA (HR & Analytics)


Future Enhancements

1.Real-time database integration
2.Authentication system
3.Advanced ML models
4.Live Power BI embedding

License

This project is for academic and learning purposes.
