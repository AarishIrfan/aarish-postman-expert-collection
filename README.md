This repository includes the API test collections, environment, and final submission request used to complete the Postman Student Expert certification.

## Collections

- Collection Test.postman_collection.json  
  Contains Halfway Check, Final Check, and Submit request for certification.

- Postman Library API v2.postman_collection.json  
  Covers complete CRUD operations for a book API using GET, POST, PATCH, and DELETE methods.

## Environment

- Postman API Fundamentals Student Expert Environment.postman_environment.json  
  Includes environment variables used in the test collections. Supports dynamic values where applicable.

## Certification Submission

**Submission Endpoint**  
POST https://lesson-completion.postmanlabs.com/submit

**Request Body**
```json
{
  "email": "arishirfan98@gmail.com",
  "postmanCollectionJsonUrl": "{{submission}}",
  "publishedCourseId": "2q2g1okzsn62y8",
  "lessonId": "gof6mgkytvk8u"
}
````

**Response**

```json
{
  "status": "ok",
  "message": "Congratulations! The lesson 'Submit your Postman collection' is now marked as complete."
}
```

## How to Use

1. Download or clone this repository.
2. Open Postman and import the collections and environment files.
3. Run requests individually or execute a full collection run.
4. Review the test scripts, assertions, and API responses.

## Tools Used

* Postman
* RESTful APIs
* GitHub for version control
* JSON-based payloads and response handling
- This version fixes the issue of **blue code block** rendering — it was happening because you were pasting into the editor with unintended indentation or formatting.
- This markdown is **minimal** and **professional**. No emojis. No fluff.
- GitHub will render this in white font in dark mode automatically.

Let me know if you want this version in **PDF or DOCX** for sharing externally.
```
