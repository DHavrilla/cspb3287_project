CSPB3287 Project Ideation

David Havrilla

Concept

My database is a relational database of the blood donation system (1). The database will include tables of data about the patient/recipient, donor, as well as data about the blood bank where the product is stored. Regarding my topic of choice, I picked from the free datasets since it provides a good starter outline. I think it will be easier to focus on the actual database management this way. I also like the blood donation system topic based on logistical importance. According to the Red Cross (2), some of the blood products, such as platelets, have a shelf life of only 5 days. The importance of both accuracy and availability of the data is critical in this kind of database.

Below is an example of the tables:

Data_of_Patient(patient_name, patient_id, patient_blood_group, patient_disease)

Data_of_Donor(donor_name, donor_id, donor_blood_group, donor_medical_report, donor_address, donor_contact_number)

Data_of_BloodBank(bloodbank_name, bloodbank_address, bloodbank_donor_name, bloodbank_contact_number)

Platform and Tools

I plan to use MySQL Workbench to construct the database. The database will be forwarded and hosted in Google Cloud SQL. Any queries constructed or data inserted and deleted will be performed using SQL Alchemy via Jupyter Notebook.

Hope to Learn

From the database project itself, my goal is to better understand database management systems through practice and experience. I think the creation of a database from scratch with either randomized data or collected data will aid in that capacity. Additionally, I hope to improve on my skills to work with a relational database in terms of hosting with a cloud service.

Demonstration

I plan to demonstrate my database and what I have learned through a private video presentation that can be uploaded to a website, such as YouTube, and accessed via provided link.

References:

(1) https://www.lovelycoding.org/2013/11/top-18-database-projects-ideas-for.engineering-bca-mca-btech-bsc.html

(2) https://www.redcrossblood.org/donate-blood/how-to-donate/types-of-blood-donations/blood-components.html
