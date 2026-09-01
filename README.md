# Urban Scooter — Web, Mobile, and API Testing

## About the Project

Urban Scooter is a scooter rental service used for a final QA project as part of the TripleTen QA Engineering Bootcamp.

The project involved functional and UI testing across web and Android environments, as well as backend API testing. The objective was to analyze requirements, design and execute test cases, compare actual results with expected behavior, and document identified defects.

## Testing Scope

The project contains 153 test cases divided into three areas:

| Area | Test Cases | Main Coverage |
|---|---:|---|
| Web application | 101 | Order form fields, validation rules, boundary values, layout, and cross-browser behavior |
| Android application | 9 | Notifications, internet connection failure, and UI layout |
| API | 43 | Courier creation, input validation, duplicate data, and courier deletion |
| **Total** | **153** | **Web, mobile, and backend testing** |

## Web Application Testing

The web testing covered the scooter order form and its interface.

Main areas tested:

- Name and surname fields
- Delivery address
- Metro station selection
- Phone number
- Delivery date
- Rental period
- Scooter color selection
- Courier comments
- Form validation and error messages
- Equivalence classes and boundary values
- Layout and responsive behavior
- Cross-browser behavior in Google Chrome and Opera

## Mobile Application Testing

The Android application was tested using an emulator configured through Android Studio.

The mobile testing covered:

- Delivery deadline notifications
- Notification content and navigation behavior
- Application behavior without an internet connection
- Internet connection error pop-ups
- UI comparison against Figma designs
- Functional and visual behavior on Android API 31

Nine mobile test cases were designed and executed. Four passed and five failed.

## API Testing

The API testing focused on courier management using the following endpoints:

- `POST /api/v1/courier`
- `DELETE /api/v1/courier/:id`

The test scenarios covered:

- Successful courier creation
- Required fields
- Valid and invalid input formats
- Equivalence classes and boundary values
- Duplicate login handling
- HTTP response codes
- Error messages and response bodies
- Successful courier deletion
- Attempts to delete nonexistent or previously deleted couriers

API requests and responses were validated using Postman.

## Testing Techniques

- Functional testing
- UI testing
- Mobile application testing
- API testing
- Positive and negative testing
- Equivalence partitioning
- Boundary value analysis
- Cross-browser testing
- Requirements analysis
- Test case design and execution
- Bug identification and reporting

## Tools and Technologies

- Postman
- Android Studio
- Android Emulator
- Android API 31
- Google Chrome
- Opera
- Figma
- Jira
- Google Sheets and Microsoft Excel
- HTTP and JSON

## Project Structure

```text
urban-scooter-qa-testing/
├── README.md
├── test-cases/
│   └── urban-scooter-test-cases.xlsx
└── bug-reports/
    ├── BUG-REPORTS.md
    └── supporting screenshots
```

## Test Documentation

The complete test documentation is available in:

`test-cases/urban-scooter-test-cases.xlsx`

The workbook contains separate worksheets for:

- Web application testing
- Mobile application testing
- API testing

It includes test case IDs, preconditions, test steps, test data, expected results, actual results, execution status, and links to related Jira bug reports where applicable.

## Bug Reporting

Defects identified during testing were documented in Jira with the relevant test data, expected and actual results, and supporting evidence.

The `bug-reports` directory also contains screenshots and a summary of selected defects identified during mobile testing.

## Skills Demonstrated

- Analysis and interpretation of software requirements
- Design and execution of manual test cases
- Web, mobile, and API testing
- Validation of HTTP requests and responses
- Application of equivalence classes and boundary values
- Cross-browser and UI validation
- Defect identification, reproduction, and documentation
- Organization of test evidence and QA documentation
