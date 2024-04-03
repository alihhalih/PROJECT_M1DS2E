# The Project
This project is a modest attempt at replicating how job posting websites work. 
First, we begin by scraping specific elements from a job postnig website, and store these elements in a dataframe. Then, users can interact with a constructed interface to find jobs matching their criteria, and eventually allowing them to apply for the selected jobs directly from the companies websites. Furthermore, users can choose to have their job-matching criteria directly sent to their email adresses. 

Among the criterias a user can choose from:
- **Keyword** : this can relate to job titles, or the company's name.

- **Contract type** : users can choose between a 'CDI', 'CDD', 'Stage', 'Alternance', 'Contrat d'apprentissage' or 'freelance' job.

- **City and Postal Code** 

- **Remote work** : users can choose between completely remote jobs, and jobs allowing only partial or occasional remote work. 

We use ***Selenium*** to scrape job postings from the Indeed website, and ***Tkinter*** (along with ***customtkinter***) to build an easy-to-use interface (among other packages of course) 

Below is a snippet of the interface:
Users can interact with the interface to search for jobs matching their criteria, and be directly sent to the job posting on the company's website to apply.

![image](https://github.com/alihhalih/PROJECT_M1DS2E/assets/161328112/5eb11a21-3a84-4b86-9c5c-78db9896e065)

Furthermore, users can choose to receive the job offers by email by clicking on the checkbox. When this action is completed, a new part of the interface will reveal itself. Users can then save their criteria, and click on the 'send jobs by mail' button. 

![image](https://github.com/alihhalih/PROJECT_M1DS2E/assets/161328112/44b69bf3-0174-40ae-8e8e-0f9e57f59ce2)

And here is a snippet of the email format that is sent to users:
![image](https://github.com/alihhalih/PROJECT_M1DS2E/assets/161328112/40f62a4b-d278-471e-8cdf-8a7ba016a32d)
