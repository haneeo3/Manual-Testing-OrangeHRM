Testplan.md
#  Test Plan – OrangeHRM Manual Testing

##  Project Overview
**Application Under Test (AUT)**: OrangeHRM (Open Source HR Management System)  
**URL**: https://opensource-demo.orangehrmlive.com/  
**Test Credentials**:  
- Username: `Admin`  
- Password: `admin123`

---

##  Objective
To verify the functional behavior and UI of OrangeHRM's core features — including login, leave management, recruitment, and the admin panel — ensuring that the application meets its requirements and provides a smooth, bug-free experience for its users.

---

##  Scope
###  In Scope
- Functional testing of:
  - Login functionality
  - Admin panel features
  - Leave request process
  - Recruitment module
- UI and usability checks
- Error message validation and form validation

###  Out of Scope
- Performance testing
- Security testing
- Backend/database testing
- Integration with third-party tools

---

##  Test Approach
- **Testing Method**: Manual testing
- **Test Design**: Test cases created for each feature
- **Test Execution**: Perform tests in Chrome browser
- **Test Reporting**: Log bugs in `Bug_Reports.md` and results in `Test_Cases.xlsx`

---

##  Test Environment
| Item          | Details                                |
|---------------|----------------------------------------|
| OS            | Windows 10                             |
| Browser       | Chrome (Latest Version)                |
| Application   | OrangeHRM demo (https://opensource-demo.orangehrmlive.com/) |
| Test Data     | Predefined credentials and demo data   |

---

##  Entry Criteria
- Application is accessible
- Test credentials available
- Test plan and test cases prepared and approved

---

##  Exit Criteria
- All test cases executed
- All critical and major bugs logged and reviewed
- Test summary report prepared

---

##  Deliverables
- Test Plan (`Test_Plan.md`)
- Test Cases (`Test_Cases.xlsx`)
- Bug Report (`Bug_Reports.md`)
- Test Execution report

---

##  Schedule
| Activity          | Estimated Duration |
|-------------------|--------------------|
| Test Planning     | 1 day             |
| Test Design       | 1 day             |
| Test Execution    | 2 days            |
| Bug Reporting     | Ongoing           |

---

##  Risks & Assumptions
- Application is stable and accessible throughout testing
- No major changes will be made to OrangeHRM during testing
- Test data is reset or easily re-creatable after testing

---

##  Roles & Responsibilities
| Role           | Responsibility                       |
|----------------|-------------------------------------|
| Haneef (Tester)| Design test cases, execute tests, log bugs |

---

##  Approvals
Public demo - No Need for Approval.
---

**End of Test Plan**
