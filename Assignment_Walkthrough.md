**Title:**
[cite_start]Azure Cloud Fundamentals and Data Pipeline Implementation using ADF [cite: 65, 66]

**Objective:**
[cite_start]To understand Azure cloud concepts and build a complete data pipeline using Storage Account and Azure Data Factory. [cite: 67, 68]

---

## [cite_start]Assignment Tasks [cite: 69]

### [cite_start]Task 1: [cite: 70]
[cite_start]Explore Azure Portal [cite: 71]
* [cite_start]Create a Resource Group [cite: 72]

[cite_start]**Deliverable:** [cite: 73]
[cite_start]Screenshot of Resource Group [cite: 74]

[cite_start]**Screenshot:** [cite: 75]
![Screenshot of Resource Group](./images/task1-resource-group.png)

---

### [cite_start]Task 2: Storage Setup [cite: 76]
[cite_start]**Do:** [cite: 77]
* [cite_start]Create a Storage Account [cite: 78]
* [cite_start]Create a Blob Container [cite: 79]
* [cite_start]Upload a CSV file [cite: 80]

[cite_start]**Deliverable:** [cite: 81]
[cite_start]Screenshot of container with uploaded file [cite: 82]

[cite_start]**Screenshot:** [cite: 83]
![Screenshot of container with uploaded file](./images/task2-blob-container.png)

---

### [cite_start]Task 3: ADF Basics [cite: 84]
[cite_start]**Do:** [cite: 85]
* [cite_start]Create Azure Data Factory [cite: 86]
* [cite_start]Explore ADF UI (Author, Monitor, Manage) [cite: 87]
* [cite_start]Create Linked Service (Blob Storage) [cite: 88]
* [cite_start]Create datasets (source + destination) [cite: 89]
* [cite_start]Use Get Metadata activity [cite: 90]

[cite_start]**Deliverable:** [cite: 91]
* [cite_start]Screenshot of Linked Service [cite: 92]
* [cite_start]Screenshot of dataset [cite: 93]
* [cite_start]Screenshot of Get Metadata activity [cite: 94]

[cite_start]**Screenshot: Linked Service** [cite: 95]
![Linked Service](./images/task3-linked-service.png)

[cite_start]**Screenshot: Dataset** [cite: 96]
![Dataset](./images/task3-dataset.png)

[cite_start]**Screenshot: Get Metadata activity** [cite: 97]
![Get Metadata Activity](./images/task3-get-metadata.png)

---

### [cite_start]Task 4: Pipeline Development [cite: 98]
[cite_start]**Do:** [cite: 99]
* [cite_start]Create pipeline using Copy Data activity [cite: 100]
* [cite_start]Configure source and destination [cite: 101]
* [cite_start]Add ForEach activity (optional if multiple files) [cite: 102]

[cite_start]**Deliverable:** [cite: 103]
[cite_start]Screenshot of pipeline design [cite: 104]

[cite_start]**Screenshot: Pipeline Design** [cite: 105]
![Pipeline Design 1](./images/task4-pipeline-design-1.png)
![Pipeline Design 2](./images/task4-pipeline-design-2.png)

---

### [cite_start]Task 5: Pipeline Execution [cite: 106]
[cite_start]**Do:** [cite: 107]
* [cite_start]Run pipeline using Debug/Trigger Deliverable: [cite: 108]
* [cite_start]Screenshot showing pipeline execution (Succeeded) [cite: 109]

[cite_start]**Screenshot: Pipeline Execution (Succeeded)** [cite: 110]
![Pipeline Execution Succeeded](./images/task5-pipeline-execution.png)

---

### [cite_start]Task 6: IAM Roles [cite: 111]
[cite_start]**Do:** [cite: 112]
* [cite_start]Assign roles: o Reader o Contributor [cite: 113]
* [cite_start]Provide access to ADF for Storage [cite: 114]

[cite_start]**Deliverable:** [cite: 115]
[cite_start]Screenshot of role assignment [cite: 116]

[cite_start]**Screenshot: Role Assignment** [cite: 117]
![Role Assignment](./images/task6-role-assignment.png)

---

## [cite_start]Mini Project (Final Task) [cite: 118]

[cite_start]**Problem Statement:** [cite: 119]
[cite_start]Build a complete pipeline that reads a CSV file from Blob Storage and processes it using Azure Data Factory. [cite: 120]

[cite_start]**Requirements:** [cite: 121]
* [cite_start]Source: CSV file in Blob [cite: 122]
* [cite_start]Use: Linked Service + Dataset + Pipeline [cite: 123]
* [cite_start]Process: Copy Data + Metadata check [cite: 124]
* [cite_start]Destination: New file/location [cite: 125]

[cite_start]**Expected Output:** [cite: 126]
* [cite_start]Pipeline executed successfully [cite: 127]
* [cite_start]Data copied to destination [cite: 128]
* [cite_start]Metadata validated [cite: 129]

[cite_start]**Screenshot: Pipeline Executed Successfully** [cite: 130]
![Pipeline Executed Successfully](./images/miniproject-success.png)

[cite_start]**Screenshot: Data copied to destination** [cite: 131]
![Data copied to destination](./images/miniproject-destination.png)

[cite_start]**Screenshot: Metadata Validated** [cite: 132]
![Metadata Validated](./images/miniproject-metadata.png)
