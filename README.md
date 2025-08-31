# Resume Application
A web-based tool for creating and customizing professional resumes. Input personal info, choose a template, and download in DOCX format. Features include data input guidance, multiple design options, and direct print functionality. Ideal for crafting a personalized resume quickly and efficiently.

## Running the Streamlit App

**Prerequisites**

* Python 3.6 or later ([https://www.python.org/downloads/](https://www.python.org/downloads/))
* pip (usually comes bundled with Python)

**Installation**

1.  Clone the repository using Git:

    ```bash
    git clone https://github.com/JashT14/Resume-Application.git
    ```


2.  Navigate to the project directory:

    ```bash
    cd Resume-Application
    ```

3.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

**Running the App**

1.  Start the streamlit application:

    ```bash
    streamlit run app.py
    ```

    This will typically start the streamlit application on `http://127.0.0.1/` by default. You can access the application in your web browser at that URL.

## Features

### 1. Generate a Document

#### User Data Input
- Users can input their personal and professional information required for creating a resume.
- The application will guide users through different sections such as personal details, educational background, work experience, skills, and other relevant information.

#### Document Generation
- Once all necessary information is provided, users can generate their resume.
- The resume will be created in DOCX format.
- Users can download the generated resume directly to their computer.

### 2. Customize Resume Design

#### Customization Options
- Users who wish to customize their resume design can access the "View Digital Resume" button.
- This feature offers four distinct design templates for the resume, each with unique attributes.

#### Template Features
- The four design templates offer different layouts and styles, catering to various aesthetic preferences and professional needs.
- Users can personalize their resumes by adjusting features such as color, font style, font size, and more.
- These customization options allow users to create a visually appealing and professional resume.

#### Print Option
- After customizing the resume, users can print the final version directly from the application.

## Workflow

1. **Input Data:**
   - Users start by entering their details in the provided fields.
   - Sections include personal information, education, work experience, skills, and other optional sections.

2. **Generate Resume:**
   - After completing all input fields, users can generate their resume.
   - The resume will be compiled into a DOCX file, which can be downloaded.

3. **Customize Resume (Optional):**
   - Users can choose to customize their resume by clicking on the "View Digital Resume" button.
   - They can select one of the four available templates.
   - Users can modify the template to suit their preferences by changing colors, fonts, and text sizes.

4. **Print Resume:**
   - Once satisfied with the customization, users can print their resume directly from the application.

## Conclusion

The Resume Generator and Customization Application provides a comprehensive solution for users to create and personalize their resumes. With the ability to input data, generate a DOCX file, customize templates, and print the final document, users can easily create professional resumes tailored to their needs.

**Additional Notes**

* The `requirements.txt` file lists all the Python packages required by the application.
* The `app.py` script is a common way to start Streamlit application.

Video Demonstration (YouTube): https://youtu.be/TwMhBi1IwFE
