# MediGuide: Treatment Recommender

MediGuide is a medical treatment recommendation web app for people dealing with illnesses. The user would be able to create a profile that contains a history
of all their symptoms and the severity for each of these symptoms. Based on these inputs, a list of the top 10 most common conditions and treatments will be
generated for the user. Additionally, the user is able to update and delete their profile.

The MySQL database that is hosted through Google Cloud Platform has over a million entries, which ensures a more accurate list of conditions and treatments.
Other features of the web app that improved user functionality includes implementing CRUD operations, triggers, and a stored procedure.

The workflow for the web app goes: login page -> profile page (input symptoms, update or delete previous symptoms, delete profile) -> top 10 most common
conditions and treatments page -> back to profile page

https://www.youtube.com/watch?v=Leo55naPx1k
