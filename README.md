# ELEVATE-LABS-project
final project

This project aims to predict whether a patient will attend their scheduled medical appointment. Missed appointments negatively impact healthcare efficiency, so identifying high-risk no-shows can help optimize scheduling and resource allocation.

Dataset: Medical appointment records from Brazil (~100K entries).

Key Features: Age, Gender, Appointment Day, SMS reminders, Scholarship, Chronic conditions (e.g., Hypertension, Diabetes), and whether the patient showed up.

Preprocessing: Cleaned invalid ages, converted dates, created "Waiting Days" feature, and encoded categorical variables.

Model Used: Decision Tree Classifier (max depth = 5), trained using an 80/20 train-test split.

Evaluation Metrics: Confusion matrix and classification report showed moderate prediction accuracy.

Insights via Power BI:

Higher no-show rates among younger patients.

Appointments scheduled with long wait times had more no-shows.

SMS reminders alone did not guarantee attendance.

✅ Outcome: The project demonstrates that machine learning combined with data visualization tools like Power BI can support proactive decision-making in healthcare scheduling. Improvements such as using more complex models or additional behavioral data could further boost prediction accuracy.
