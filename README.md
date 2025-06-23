Here is your **clean, professional, no-fluff `README.md`** content that you can copy and paste directly into your GitHub repo:

---

```markdown
# Postman Student Expert Certification – Aarish Irfan

This repository contains the API collections, environment, and final submission setup used to complete the Postman Student Expert certification.

## Collections

- `Collection Test.postman_collection.json`  
  Contains intermediate skill checks (Halfway Check, Final Check) and the final `submit` request used for certification.

- `Postman Library API v2.postman_collection.json`  
  Implements CRUD operations for a sample book API using GET, POST, PATCH, and DELETE requests.

## Environment

- `Postman API Fundamentals Student Expert Environment.postman_environment.json`  
  Includes environment variables used during test execution. This file supports the collections above and can be imported into Postman.

## Certification Submission Details

The following POST request was made to complete the certification:

**Endpoint:**

```

POST [https://lesson-completion.postmanlabs.com/submit](https://lesson-completion.postmanlabs.com/submit)

````

**Request Body:**

```json
{
  "email": "arishirfan98@gmail.com",
  "postmanCollectionJsonUrl": "{{submission}}",
  "publishedCourseId": "2q2g1okzsn62y8",
  "lessonId": "gof6mgkytvk8u"
}
````

**Response:**

```json
{
  "status": "ok",
  "message": "Congratulations! The lesson 'Submit your Postman collection' is now marked as complete."
}
```

## How to Use

1. Download or clone this repository.
2. Open Postman and import the collection and environment files.
3. Run requests individually or as a full collection run.
4. Review request scripts, responses, and test results.

## Tools Used

* Postman Desktop Application
* RESTful APIs
* GitHub for version control
* JSON for structured API data
