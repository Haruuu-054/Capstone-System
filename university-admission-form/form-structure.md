# Multi-Step Admission Form Structure

## Overview
The admission application form consists of 5 main steps plus a confirmation page, with a consistent header and progress indicator throughout.

## Common Elements
- **Header**: University logo and name "Manuel S. Enverga University Foundation-Candelaria Inc." with "Quezon Philippines" subtitle
- **Progress Bar**: Step indicator showing current progress (e.g., "Step 1/5") with a visual progress bar
- **Navigation**: "Continue" button at the bottom right of each step
- **Container**: White card on light pink/gray background for form content
- **Section Headers**: Maroon colored headings for each section
- **Input Fields**: Consistent styling with labels above fields

## Step 1: Personal Details
- **Section Title**: "Personal Details"
- **Fields**:
  - Last Name (text input)
  - First Name (text input)
  - Middle Initial (text input)
  - Suffix (if applicable) (text input)
  - Date of Birth (date input)
  - Place of Birth (text input)
  - Age (number input)
  - Gender (select/dropdown)
  - Citizenship (text input)
  - Civil Status (text input)
  - Religion (text input)
  - Ethnicity (if applicable) (text input)

## Step 2: Contact and Address Information
- **Section Title**: "Contact and Address Information"
- **Fields**:
  - Street (text input)
  - Barangay/Village (text input)
  - Municipality (text input)
  - Province (text input)
  - Zip code (text input)
  - Home Address (text input)
  - Temporary Address (if different from home) (text input)
  - Mobile number (text input)
  - Telephone number (text input)
  - Preferred contact number (text input)
  - Preferred contact email (text input)

## Step 3: Educational Background
- **Section Title**: "Educational Background"
- **Fields**:
  - Last school attended (text input)
  - Strand Taken (text input)
  - School address (text input)
  - School type (text input)
  - Year graduated (text input)
  - Awards/Honors received (if applicable) (textarea)

## Step 4: Family Background
- **Section Title**: "Family background"
- **Fields**:
  - Father's Name (text input)
  - Mother's Name (text input)
  - Occupation (Father) (text input)
  - Occupation (Mother) (text input)
  - Contact number (Father) (text input)
  - Contact number (Mother) (text input)
  - Parent's Address (text input)
  - Number of Siblings (text input)
  - Legal Guardian (text input)
  - Family Income (text input)

## Step 5: Program Preferences
- **Section Title**: "Program preferences"
- **Fields**:
  - **Preferred Course**:
    - Course/Program (text input)
    - Major (if applicable) (text input)
    - School Year Term (text input)
  - **Alternate Course 1**:
    - Course/Program (text input)
    - Major (if applicable) (text input)
    - School Year Term (text input)
  - **Alternate Course 2**:
    - Course/Program (text input)
    - Major (if applicable) (text input)
    - School Year Term (text input)
  - Submit button: "Submit your Application"

## Confirmation Page
- **Message**: "Admission Application Successfully Sent!"
- **Subtext**: "you can now access the Admission Tracker."
- **Button**: "Continue"

## State Management
- Each step's data will be stored in browser localStorage
- Navigation between steps will preserve entered data
- Form validation will occur before proceeding to next step
- Progress bar will update based on current step

## Responsive Design
- Form will adapt to different screen sizes
- On mobile, fields will stack vertically
- On desktop, fields will be arranged in columns where appropriate
- Input field width will adjust based on expected content length
