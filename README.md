**Library Book Lending System**

A console-based Library Management System*developed using Java, JDBC, and Oracle Database.
The application follows a layered architecture (Bean → DAO → Service) to manage book lending operations efficiently.


**Features**

* Add and manage books
* Issue books
* Return books
* Validation and custom exception handling
* JDBC-based Oracle database integration
* Clean layered architecture design

 **Architecture**

```
Client (Console)
        ↓
LibraryMain.java
        ↓
Service Layer (LibraryService)
        ↓
DAO Layer (BookDAO / IssueDAO)
        ↓
Oracle Database
```

 **Project Structure**

```
src
│
├── com.library.app
│   └── LibraryMain.java
│
├── com.library.bean
│   ├── Book.java
│   └── Issue.java
│
├── com.library.dao
│   ├── BookDAO.java
│   └── IssueDAO.java
│
├── com.library.service
│   └── LibraryService.java
│
└── com.library.util
    ├── DBUtil.java
    ├── ActiveIssueException.java
    ├── BookUnavailableException.java
    └── ValidationException.java
```

<img width="850" height="223" alt="image" src="https://github.com/user-attachments/assets/dd7213db-a129-4ead-ba14-21dd1ab28654" />








