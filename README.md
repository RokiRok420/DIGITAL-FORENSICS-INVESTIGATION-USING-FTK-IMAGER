# DIGITAL-FORENSICS-INVESTIGATION-USING-FTK-IMAGER

## 1. Introduction

Digital Forensics is the process of collecting, preserving, examining, and analyzing digital evidence from computers, storage devices, and other digital media. Its primary objective is to investigate digital data while maintaining the integrity, authenticity, and reliability of the original evidence.

In this project, FTK Imager is used to acquire and analyze digital evidence. A forensic image of the selected evidence source is created and then examined to identify files, folders, metadata, timestamps, deleted data, and other relevant digital artifacts.

This project demonstrates the fundamental stages of a digital forensic investigation, including evidence acquisition, preservation, verification, examination, and documentation.

## 2. Objectives

The main objectives of this project are:

1. To understand the fundamental concepts of Digital Forensics.
2. To acquire digital evidence using FTK Imager.
3. To create a forensic image of a selected evidence source.
4. To maintain and verify evidence integrity using cryptographic hash values.
5. To analyze files and folders within the forensic image.
6. To examine file metadata and timestamps.
7. To identify deleted files or recoverable data, if available.
8. To document the forensic process with screenshots and observations.
9. To understand the importance of evidence preservation in forensic investigations.
10. To prepare a structured forensic investigation report.

## 3. Tools and Requirements

The following tools and resources are used for this investigation:

| Tool or Resource | Purpose |
|---|---|
| FTK Imager | Acquiring, imaging, and examining digital evidence |
| Windows OS | Operating environment |
| Storage device or logical drive | Source of digital evidence |
| Computer or laptop | Performing the investigation |
| Screenshot tool | Documenting investigation steps |
| Hash verification | Checking evidence integrity |

## 4. Step 1: FTK Imager Installation

**Official download page:** [FTK Imager — Exterro](https://go.exterro.com/l/43312/2023-05-03/fc4b78)

### Installation Procedure

1. Open the official download page.
2. Request or download the FTK Imager installer according to the available instructions.
3. Verify that the installer comes from a trusted official source.
4. Run the installer with the appropriate permissions.
5. Follow the installation wizard.
6. Launch FTK Imager after installation.
7. Confirm that the application opens successfully.

**Screenshot:** 
<img width="917" height="718" alt="wi_h0AjwqgdKHb7DPnXacQbtpbk-xk-ctI84K09xmKHyyg9e7McF1xVIPf1v3uo1cUwCKS0aqkwCTOgVZ29tmj30zQoGJcNUBrJApTie_GxWnhvm9ag6wQ93QFvVz9Q6cHrOhqvOqRahug_lKGdomANMF8ry0FUfk5hIvPYkJGYtCLcnk2erxlql6Pxb3Sd8" src="https://github.com/user-attachments/assets/b817dde8-36c0-4a3b-80d8-b92b58b7c66e" />

## 5. Step 2: FTK Imager Interface

After launching FTK Imager, examine the main interface and identify the areas used for forensic examination.

The interface typically provides:

- **Evidence Tree:** Displays evidence sources, images, directories, and files.
- **File List:** Shows the contents of the selected directory.
- **File Content Viewer:** Displays supported file content or hexadecimal data.
- **Properties and Metadata:** Shows available file attributes and other information.
- **Evidence Source Options:** Allows users to add physical drives, logical drives, image files, and other supported evidence sources.

The exact interface may vary depending on the installed version.

**Screenshot:** 
<img width="902" height="601" alt="c1z-z3vPL_lrMNZzepTkHNwCmGuv2K3Pz__OESjnpPw901c7a6-e6UQ5vDt8GaaM487Q1d-nUPy9VryR-1isyQyyGk6E98wI_j1oqnOD2le3r_uOdGww80WyaFDB5VyKn1c38ZFRnSVjiXlD-zLo4hDcotvyk8WyuTzcOcvU6zstrN9JznRZninkMQhUXoE1" src="https://github.com/user-attachments/assets/d9811d4b-67e7-479f-ad39-0eed61a548bf" />


## 6. Step 3: Selecting the Evidence Source

The next step is to identify the digital evidence source that will be examined.

Possible evidence sources include:

- A removable USB storage device.
- A logical drive.
- A physical storage device.
- An existing forensic image file.

For this project, select an authorized test device or a prepared forensic sample.

### Procedure

1. Connect the test storage device, if applicable.
2. Open FTK Imager.
3. Navigate to the option for adding an evidence item.
4. Select the appropriate source type.
5. Choose the intended evidence source.
6. Confirm that the selected source appears in the evidence tree.
7. Record the source description and other relevant details.

**Important:** Use only a device or data source that you are authorized to examine. For evidentiary work, avoid modifying the original source and use appropriate write-blocking procedures when applicable.

**Screenshot:**
<img width="874" height="674" alt="YZw4vRAZExxqxQ_UmVozqAhJxCu78na9swnMBA7U_QkTE9xLh331Dl9qefT9upG0-AzTHBz08Ht4hz_YGqB_VeoHWFO4KgVb4Mu5X4OXofHNbPpXFdAOF0vCeewZ2sj5cvJYHeI-zPhK6R77Unm8EItKCs5YYfejzadRmsJrH1C94VZuDPOgLFGSq8ccCVeo" src="https://github.com/user-attachments/assets/41f12e2c-3cca-4efd-ae10-f08fb8e4b8b5" />


## 7. Step 4: Creating a Forensic Image

A forensic image is a bit-for-bit or otherwise forensically acquired representation of a storage source, depending on the acquisition method and format used.

Creating an image allows investigators to examine a preserved copy rather than repeatedly accessing the original evidence.

FTK Imager supports forensic image formats such as E01 and raw images, subject to the selected acquisition workflow.

### Procedure

1. Select the intended evidence source.
2. Open the appropriate disk-imaging or acquisition option.
3. Choose the correct source type.
4. Select a supported destination image format, such as E01 or raw.
5. Enter the requested case information, if applicable.
6. Select a destination folder with sufficient storage space.
7. Configure the available verification options.
8. Start the acquisition.
9. Wait for the imaging process to complete.
10. Review the acquisition summary and any reported errors.

**Screenshot:** 
<img width="437" height="401" alt="KzPFvSNY7z0hQR2JL9ULzb3SxcqJAJzazWJxau0gwotT-SVKJ8rTlk4CwI9jro_265633LRIMnyOiU69JAruyluia5q9fG_qEmKw1PHb4UbVUfkTRn64UlxwYvY59OblRdl0FwT-4a9XN07dgVd0fzgB_Ft2bXUzqrvAupU0ey8rtKhPH1Bt5o3QJwpjrXRV" src="https://github.com/user-attachments/assets/966c2596-c336-4600-a10e-8fe36fdc7ea2" />

## 8. Step 5: Verifying Evidence Integrity

Evidence integrity is a fundamental requirement in digital forensics. Cryptographic hashes can help determine whether the acquired data matches the data read during acquisition or whether a forensic image has changed since a previous verification.

Common hash algorithms include:

- **MD5:** A 128-bit hash used in legacy workflows and some forensic tools.
- **SHA-1:** A 160-bit hash used in some existing forensic workflows.
- **SHA-256:** A 256-bit hash commonly used for modern file-integrity verification.

### Procedure

1. Enable the relevant verification options during acquisition, where supported.
2. Record the calculated hash values in the acquisition report.
3. Review the verification results.
4. If appropriate, independently calculate or verify the hash of the completed image.
5. Compare the values that represent the same data and use the same hashing method.
6. Record whether verification succeeded or failed.

A matching hash provides strong evidence that the compared data is unchanged with respect to that hash algorithm. However, the values must be compared correctly: a source-media hash and a container-file hash may represent different data and therefore may not match.

**Screenshot:**
<img width="948" height="784" alt="od1uXKTCPbUgz_vvQ9iR6uK49djZIBcyzcTEkjjgFIqWHfZBFT1yc-K3Iu-16k6M9SNFlAbDMmpld1EcHK8l1zrUJD1--3jyV7ITc04BBmi-AA7mGmGuP25IZM3AHb9PZMinPc-vHU4jIRa25LpRTRILfSI4BHv6OWgwhPH4Nz9oJRN-NgF6bWsdAyDJRYCU" src="https://github.com/user-attachments/assets/8dbe086d-c925-46f4-b724-78dd160026ad" />

## 9. Step 6: Adding the Forensic Image

Once acquisition is complete, load the image into FTK Imager for examination.

### Procedure

1. Open FTK Imager.
2. Select the option to add an evidence item.
3. Choose the forensic image file as the source.
4. Browse to the saved image.
5. Load the image.
6. Expand the evidence tree to inspect its contents.
7. Confirm that the expected partitions, directories, and files are accessible.


## 10. Step 7: File and Folder Examination

File-system examination helps investigators understand the structure and contents of the acquired evidence.

During this stage, inspect:

- Directory structures.
- File names and extensions.
- File sizes.
- Available file-system attributes.
- Potentially relevant documents and media files.
- Suspicious or unexpected files.
- Available file metadata.

### Procedure

1. Expand the directories in the evidence tree.
2. Select individual folders for examination.
3. Review the displayed files and attributes.
4. Open supported files using the appropriate viewer.
5. Record relevant findings and their locations within the evidence.
6. Export files for further examination only when necessary and permitted.

**Screenshot:** 
<img width="1024" height="734" alt="6" src="https://github.com/user-attachments/assets/e3ffb75d-488c-4473-aeb1-d874841bc607" />

## 11. Step 8: Metadata and Timestamp Analysis

Metadata provides contextual information about files and other digital objects.

Depending on the file system and file type, available information may include:

- File name and extension.
- File size.
- Creation timestamp.
- Modification timestamp.
- Access timestamp, if available.
- File-system attributes.
- File-system location or path.
- Additional document metadata, where supported.

Timestamps should be interpreted carefully because time zones, file-system behavior, copying, extraction, and system-clock differences can affect their meaning.

A timestamp alone does not prove when a person created, accessed, or modified a file.


## 12. Step 9: Deleted File Examination

Deleted-file examination attempts to identify files or data that may have been marked as deleted but remain partially or fully recoverable.

Depending on the file system and acquisition method, FTK Imager may display deleted entries or permit examination of available unallocated data.

### Procedure

1. Inspect the evidence tree for deleted entries or relevant file-system records.
2. Examine any deleted files exposed by the tool.
3. Review available metadata and content.
4. Determine whether the file appears complete, partially overwritten, or otherwise damaged.
5. Document the evidence path and recovery limitations.
6. Export recoverable data only when necessary and authorized.

Not every deleted file can be recovered. Data may have been overwritten, trimmed, encrypted, or excluded from the acquired evidence.



## 13. Step 10: Documentation and Evidence Reporting

Documentation creates a clear record of the forensic process and helps another analyst understand and reproduce the investigation.

The report should include:

- Project title and objective.
- Date and time of acquisition.
- Evidence source description.
- Tool name and version.
- Acquisition format and destination.
- Calculated hash values.
- Verification results.
- Files and artifacts examined.
- Relevant metadata and timestamps.
- Deleted-file findings, if any.
- Screenshots supporting the observations.
- Limitations and final conclusions.

Maintain a record of the actions performed, and clearly distinguish direct observations from interpretations.

## 14. Results and Observations

Complete the following table using the actual results obtained during your investigation.

| Parameter | Result |
|---|---|
| Evidence Source | To be recorded |
| Acquisition Tool | FTK Imager |
| Image Format | E01 / Raw / actual format used |
| Image File Location | To be recorded |
| MD5 Hash | To be recorded, if calculated |
| SHA-1 Hash | To be recorded, if calculated |
| SHA-256 Hash | To be recorded, if calculated |
| Integrity Verification | Actual result |
| Files Examined | Actual count or description |
| Deleted Files Identified | Actual findings |
| Significant Artifacts | Actual findings |

Do not fill this table with assumed values. The results must reflect the evidence and tool output from your own investigation.

## 15. Applications of Digital Forensics

Digital forensics is used in a range of professional settings:

1. Cybercrime investigations.
2. Incident response and security investigations.
3. Investigation of unauthorized access.
4. Recovery and examination of digital artifacts.
5. Corporate security and internal investigations.
6. Examination of storage media.
7. Support for legal proceedings and evidence-based reporting.
8. Investigation of data theft and suspicious activity.

## 16. Limitations

This project focuses on basic forensic acquisition and examination using FTK Imager.

Some limitations include:

- Encrypted files or volumes may not be accessible without the appropriate credentials or keys.
- Deleted data may be partially overwritten or unrecoverable.
- Unsupported file formats may require additional tools.
- Metadata and timestamps may be incomplete or misleading.
- The quality of the findings depends on the acquisition method and the evidence available.
- FTK Imager alone may not provide every capability required for a complete forensic investigation.

## 17. Safety and Evidence Handling

- Examine only devices and data that you are authorized to access.
- Use a write blocker where appropriate to protect original storage media.
- Store forensic images securely and restrict access.
- Calculate and record relevant hashes.
- Preserve acquisition logs and screenshots.
- Work from a verified forensic copy whenever practical.
- Do not modify the original evidence unnecessarily.
- Avoid uploading sensitive evidence to public services.
- Maintain chain-of-custody records when working with real investigations.

## 18. Conclusion

This project demonstrates the fundamental workflow of digital forensic investigation using FTK Imager. It covers evidence acquisition, forensic image creation, hash verification, file-system examination, metadata inspection, deleted-file investigation, and report preparation.

The project highlights the importance of preserving evidence integrity, maintaining accurate documentation, and interpreting digital artifacts carefully.

FTK Imager provides a practical starting point for learning digital evidence acquisition and examination. More advanced investigations may require additional forensic tools and procedures depending on the type of evidence and the questions being investigated.

## 19. References

- FTK Imager download page: https://go.exterro.com/l/43312/2023-05-03/fc4b78
- Exterro official website: https://www.exterro.com/
- National Institute of Standards and Technology (NIST): https://www.nist.gov/
- NIST Computer Forensics Tool Testing (CFTT): https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt

## 20. Project Information

**Project Name:** Digital Forensics Using FTK Imager  
**Domain:** Cybersecurity and Digital Forensics  
**Primary Tool:** FTK Imager  
**Operating System:** Windows  
**Project Type:** Practical Learning and Evidence Examination

