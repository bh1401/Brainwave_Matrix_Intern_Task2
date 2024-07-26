# Brainwave_Matrix_Intern_Task2
E-commerce site or any static website with cloud storage
This project involves creating a simple HTML/CSS website and deploying it
to Google Cloud.
Here's a step-by-step guide to creating a simple HTML/CSS website and deploying it to Google Cloud Storage:

Step 1: Create a simple HTML/CSS website

- Create a new folder for your project and add the following files:
    - index.html (main HTML file)
    - styles.css (CSS file for styling)
    - images/ (folder for images)
- Create a basic HTML structure in index.html:
    - Header
    - Navigation
    - Main content
    - Footer
- Add CSS styles in styles.css to customize the layout and design
- Add images to the images/ folder as needed

Step 2: Create a Google Cloud Storage bucket

- Go to the Google Cloud Console and create a new project
- Navigate to the Storage section and create a new bucket
- Choose "Multi-region" or "Region" as the storage class
- Set the bucket name and location

Step 3: Upload website files to Google Cloud Storage

- Use the Google Cloud Console to upload your website files to the bucket
- Create a new folder in the bucket and upload the following files:
    - index.html
    - styles.css
    - images/ (folder with images)
- Make sure to set the permissions to "Public" for the files

Step 4: Configure the bucket for website hosting

- Go to the bucket settings and enable "Website configuration"
- Set the main page (index.html) and error page (404.html)
- Save the changes

Step 5: Set up a custom domain (optional)

- If you want to use a custom domain (e.g., (link unavailable)), follow these steps:
    - Create a new DNS zone in the Google Cloud Console
    - Set up DNS records for your domain
    - Verify domain ownership

Step 6: Test your website

- Go to the bucket URL (e.g., <bucket-name>.(link unavailable)) to test your website
- Make sure all files are loading correctly and the website is displayed as expected

That's it! You've successfully created a simple HTML/CSS website and deployed it to Google Cloud Storage.
