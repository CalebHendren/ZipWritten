# ZipMerge

**Website:** [https://calebhendren.github.io/zipmerge/](https://calebhendren.github.io/zipmerge/)

## About

This program simply adds a new page to the backs of multiple choice scanforms for written and essay questions. This way, when printed front and back, the scanform will be on the front and the written section will be on the back. It is primarily made with ZipGrade in mind. Other services, such as Akindi, are untested, but it should work.

**Example Input and Output files:**  
[https://github.com/CalebHendren/zipmerge/tree/master/Example](https://github.com/CalebHendren/zipmerge/tree/master/Example)

## Bubble Sheet + Written Sheet Merger Usage

> **Note:** Step 1 is optional if you don't want student names and other information pre-printed on the sheets, but at that point, you may as well just merge the two single-page PDF files manually in Adobe Acrobat. But you can still use this if you don't like dealing with Acrobat (my hatred of Acrobat is what prompted me to make this).

### Step 1: Create a class on ZipGrade and import a classlist from your LMS ("eLearn")
See: [https://support.zipgrade.com/hc/en-us/articles/202512649-How-do-I-enter-edit-import-students](https://support.zipgrade.com/hc/en-us/articles/202512649-How-do-I-enter-edit-import-students)

### Step 2: Create a custom answer sheet on ZipGrade
See: [https://support.zipgrade.com/hc/en-us/articles/115001172783-How-do-I-create-custom-answer-sheets](https://support.zipgrade.com/hc/en-us/articles/115001172783-How-do-I-create-custom-answer-sheets)

### Step 3: Download the custom Answer Sheet Packets
(ZipGrade → Classes → Answer Sheet Packets). Student names, the quiz/exam name, and all other information will already be filled out if you completed Step 1.

### Step 4: Prepare your files
Take your Answer Sheet Packets from ZipGrade and the Written Sheet PDF that you created. Go to:  
[https://calebhendren.github.io/zipmerge/](https://calebhendren.github.io/zipmerge/)

### Step 5: Merge your files
1. Select the Answer Sheet Packets as the **Bubble Sheet**
2. Select the Written Sheet as the **Written Answer Sheet**
3. Click **Merge**

## Student ID Processor for ZipGrade Usage

This tool converts student IDs from the format `#A00123456` to a ZipGrade-compatible numeric format `123456` by removing the unnecessary `#A00`.

### Steps:
1.  **Prepare your CSV File:** Export your student roster from your LMS as a CSV file. Student IDs should be in the first column.
2.  **Go to the Website:** Navigate to [https://calebhendren.github.io/zipmerge/](https://calebhendren.github.io/zipmerge/).
3.  **Locate the ID Processor:** Scroll down to the "Student ID Processor for ZipGrade" section.
4.  **Upload CSV:** Click "Choose File" under "Student IDs CSV File (.csv only)" and select your CSV file.
5.  **Process IDs:** Click the "Process IDs" button.
6.  **Download:** The processed CSV file (e.g., `yourfile_processed_IDs.csv`) will be automatically downloaded by your browser. You can then import this file into ZipGrade as part of Step 1 in the above section.

Todo: Find a workaround to get Word documents converted to PDF.