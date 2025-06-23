Here's a **complete professional, detailed, and structured process** for uploading your Postman Student Expert API collection to GitHub. This guide assumes you are using the Postman desktop app and a web browser. It includes everything from exporting files to sharing your public repository — **no fluff, just real steps.**

---

## Objective

To upload your Postman Student Expert API test collections, environments, and submission setup to GitHub in a professional, presentable, and version-controlled manner.

---

## Tools Required

* Postman Desktop Application
* GitHub Account (Free)
* Web browser

---

## Step 1: Export Postman Collections and Environment

### 1.1 Export API Collections

1. Open the Postman desktop app.
2. On the left sidebar, go to **Collections**.
3. Locate your main testing collections:

   * `Collection Test` (contains Halfway Check, Final Check, Submit request)
   * `Postman Library API v2` (CRUD operations on book API)
4. Click the three dots (•••) next to each collection name.
5. Select **Export**.
6. Choose the export format as **Collection v2.1** (recommended).
7. Save both files to a folder on your computer with clear names:

   * `Collection-Test.json`
   * `Postman-Library-API.json`

### 1.2 Export Environment File (if applicable)

1. Click the **Environments** tab in the left sidebar.
2. Find the environment used during your tests.
3. Click the three dots (•••) → **Export** → choose JSON format.
4. Save it as `Environment.json`.

---

## Step 2: Create a GitHub Repository

### 2.1 Sign in to GitHub

* Go to: [https://github.com](https://github.com)
* Log in or sign up if you don’t have an account.

### 2.2 Create New Repository

1. Navigate to: [https://github.com/new](https://github.com/new)
2. Fill in the repository details:

   * **Repository name:** `postman-student-expert-aarish`
   * **Description:** `Postman Student Expert Certification work including API test collections, environment setup, and submission steps.`
   * Select **Public**.
   * Check the box: **Initialize this repository with a README**.
3. Click **Create repository**.

---

## Step 3: Upload Files to GitHub

### 3.1 Upload the JSON Files

1. Inside your new repository, click the **Add file** dropdown.
2. Choose **Upload files**.
3. Drag and drop the following files:

   * `Collection-Test.json`
   * `Postman-Library-API.json`
   * `Environment.json` (optional)
   * Screenshot of your Postman submission success (optional)
4. Scroll down and add a commit message such as:

   ```
   Added Postman Student Expert collection files and submission setup
   ```
5. Click **Commit changes**.

---

## Step 4: Write a README File

### 4.1 Edit README.md

1. In the repository, click `README.md`.
2. Click the pencil icon (Edit).
3. Replace the content with the following:

```markdown
# Postman Student Expert Certification – Aarish Irfan

This repository contains the API testing collections, environments, and submission requests used to complete the Postman Student Expert certification.

## Contents

### 1. Collections
- `Collection-Test.json`: Includes skill check, halfway check, final check, and the certification submission request using a POST method.
- `Postman-Library-API.json`: A RESTful API test suite covering all HTTP methods (GET, POST, PATCH, DELETE) for a Book Library system.

### 2. Environment
- `Environment.json`: Environment variables used during the test execution (if applicable).

### 3. Certification Submission
A POST request was made to the following endpoint:

```

POST [https://lesson-completion.postmanlabs.com/submit](https://lesson-completion.postmanlabs.com/submit)

````

With the following JSON body:

```json
{
  "email": "arishirfan98@gmail.com",
  "postmanCollectionJsonUrl": "{{submission}}",
  "publishedCourseId": "2q2g1okzsn62y8",
  "lessonId": "gof6mgkytvk8u"
}
````

### 4. Result

The API returned a 200 OK status confirming the collection was successfully submitted:

```json
{
  "status": "ok",
  "message": "Congratulations! The lesson 'Submit your Postman collection' is now marked as complete."
}
```

## Tools Used

* Postman Desktop App
* RESTful APIs
* JSON Schema Validation
* GitHub for version control

## How to Use This Repository

1. Download the collection and environment files.
2. Import into Postman.
3. Run the collection or test individual endpoints.
4. Review test scripts and validate responses.

```

4. Scroll down and click **Commit changes**.

---

## Step 5: Share Your Repository

You now have a fully working GitHub portfolio for your Postman certification work.

1. Go to your repository.
2. Copy the URL (e.g., `https://github.com/yourusername/postman-student-expert-aarish`)
3. You can:
   - Add it to your LinkedIn profile under Projects.
   - Include it in your resume.
   - Share it as proof of practical API testing experience.

---

## Optional (Advanced) – Publish API Docs via Postman

1. Open your Collection in Postman.
2. Click the three dots (•••) > **View Documentation**.
3. Click **Publish Collection**.
4. Choose visibility: **Public**.
5. Copy the public documentation link.
6. Add it to your GitHub `README.md` under a section called `Live Documentation`.

---

If you'd like, I can:
- Review your actual exported `.json` files
- Write your LinkedIn post text based on this project
- Help you convert your collection into a CI-ready Newman test suite for interviews

Let me know if you need help on any step.
```
