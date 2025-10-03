# CV Automation System
Download Workflow [⬇️](https://github.com/MohammedAdel224/n8n/blob/main/CV%20Automation%20System/CV%20Automation%20System.zip)  

![Workflow Screenshot](https://github.com/MohammedAdel224/n8n/blob/main/CV%20Automation%20System/Workflow.png)

## What does this workflow do?
1. Receiving Gmail emails witch contains CV/Resume attachment.
2. Upload CV/Resume to Google Drive.
3. Extract information from the CV/Resume using Google Gemini.
4. Review CV/Resume, compare it with available vacancies and give it a score form 0-100%.
5. Add Extracted data to Google Sheets file.
6. Send email to HR when +90% candidate CV/Resume received.
7. Send a report email to the manager at the end of the day.

## Before You Start
* On Google Drive
   * Create `Daily Reports` folder
   * Create `Database` folder
   * In `Database` folder create
      * `All CVs` Sheets file
      * `Daily Reports Files IDs` Sheets file
      * `Vacancies` Docs file
* Prepare Credentials
  * From Google Console Cloud, get your client secret and client id. [Watch How 🎦](https://youtu.be/vsHnStTN4x8)
  * From Google Console Cloud, enable Gmail, Drive, Sheets and Docs APIs
  * From Google AI Studio, get your Gemini API key. [Watch How 🎦](https://youtu.be/DCWAdPqf0hw)

## Watch the video
[![How to create a simple CV automation system using n8n](https://img.youtube.com/vi/8e1aihq_4LY/0.jpg)](https://www.youtube.com/watch?v=8e1aihq_4LY)
