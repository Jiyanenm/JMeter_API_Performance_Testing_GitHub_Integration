# Goals of Performance Testing.

Integrating JMeter with GitHub using the JMeter Maven plugin enables you to automate performance testing within your CI/CD pipeline

## The main objectives include:

Validating response times to ensure user satisfaction.
Confirming that the system remains stable under expected and peak loads.
Identifying bottlenecks such as database locks, memory leaks, or CPU spikes, that can degrade performance.

## Prerequisite:

### JMeter is installed
### Java is installed
### Maven is installed
### Eclipse or IntelliJ is installed
### Account in GitHub

### Clone the project : git remote add origin https://github.com/Jiyanenm/JMeter_API_Performance_Testing_GitHub_Integration.git

Run the JMeter tests using the command line
Use the below command to run the JMeter script using the command line.

### mvn clean verify

<img width="1198" height="676" alt="image" src="https://github.com/user-attachments/assets/9e918daa-df23-423f-9016-d2fdfd4dc1fb" />

View the JMeter Test Result

<img width="830" height="799" alt="image" src="https://github.com/user-attachments/assets/550a059f-07de-4186-a62f-25a425516c2d" />

Right-click on the Index.html and select Open In->Browser->Chrome (any browser of your wish).

<img width="1199" height="672" alt="image" src="https://github.com/user-attachments/assets/6001e135-87d4-490d-99f0-c0ec4d5c6c02" />

If you want to create your own repo please you can Push the Maven JMeter project to GitHub

## Use the below commands to push the JMeter_GitHub_Integration project to GitHub.

echo "# JMeter_Github_Integration" >> README.md
git init
git add .
git commit -m "Jmeter Tests"
git branch -M main
git remote add origin "YOUR REPO URL"
git push -u origin main


## Create GitHub Actions and Workflows

I have a repository available in GitHub – JMeter_GitHub_Integration as shown in the below image. Go to the “Actions” tab.  Click on the “Actions” tab.

<img width="1125" height="800" alt="image" src="https://github.com/user-attachments/assets/e7773ab7-30b6-4658-a880-f26d28a1e976" />

### Select the type of Actions
You will see that GitHub recommends Actions depending on the project. In our case, it is recommending actions suitable for a Java project. I have selected the “Java with Maven” option as my project is built in Maven.

<img width="1200" height="646" alt="image" src="https://github.com/user-attachments/assets/47b377ee-44b7-4a07-9b30-8c944db17b5f" />


## Generation of Sample pipeline
If you choose an existing option, it will automatically generate a .yaml for the project as shown below.

<img width="1199" height="665" alt="image" src="https://github.com/user-attachments/assets/2712c6f6-549c-475c-a33b-7372535656a7" />

Commit the changes
After the changes, hit the “Start Commit” button.

<img width="1039" height="795" alt="image" src="https://github.com/user-attachments/assets/d3e8d56d-20d0-444a-a9da-7311526fb192" />

This will give the option to add a description for the commit. It will also enable the user to commit either to the main branch or commit to any other branch that exists in the project. Click on the “Commit new file” button to set up the workflow file.

<img width="784" height="799" alt="image" src="https://github.com/user-attachments/assets/42682872-c8d7-4232-9471-ba5b6e390640" />

## Verify that the workflow is running
Next, head over to the “Actions” tab, and you will see your YAML workflow file present under the tab. The yellow sign represents that the job is in the queue.

In Progress – When the job starts building and running, you will see the status change from “Queued” to “in progress”.

<img width="1198" height="310" alt="image" src="https://github.com/user-attachments/assets/5ee7ee94-1442-44cc-8ad8-944d2a44fec5" />

Passed – If the build is successful, you will see a green tick mark. 

<img width="1198" height="304" alt="image" src="https://github.com/user-attachments/assets/1d740020-dfdd-40d5-a1fa-90869297d4d0" />

Click on the workflow and the below screen is displayed. It shows the status of the run of the workflow, the total time taken to run the workflow, and the name of the .yml file.

<img width="1200" height="513" alt="image" src="https://github.com/user-attachments/assets/1e765ba7-5a35-4b57-a142-27ea76ffaabe" />


## Verify the JMeter Report published in GitHub
From the logs of the Workflow, you can see that the Test Report step was executed successfully.

<img width="1198" height="451" alt="image" src="https://github.com/user-attachments/assets/31e98ff5-d6e6-4dd1-90ec-b290c0a6c9b2" />

Once the pipeline run, a JMeter Report folder will be generated as shown in the below image:

<img width="1199" height="687" alt="image" src="https://github.com/user-attachments/assets/afd73e6f-9402-4dab-aead-10db85949c88" />

When we click on the folder JMeter Report, a zipped file will be downloaded. We can extract it to see all the files contained within it.

Open the folder and we will see all the files including index.html and others.

<img width="1200" height="619" alt="image" src="https://github.com/user-attachments/assets/d0238a8c-8a78-4123-953e-c1ca0586ef45" />

Open the index.html and we will see the report.

<img width="1199" height="677" alt="image" src="https://github.com/user-attachments/assets/4b17099c-722a-4802-9501-53a4bed214c8" />

## Congratulations on making it through this tutorial and hope you found it useful! Happy Learning!! Cheers!!

# BUY ME COFEEEE++ ENJOY!
