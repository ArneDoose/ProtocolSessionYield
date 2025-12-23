# P.S.Y. (Protocol Session Yield) - User Manual
sorts and renames scans of psy session docs into folders 

1. Document Requirements

For the automatic recognition to work, the scanned document must clearly contain these three lines in the top third of the first page:

    Date: Must follow the format Datum: DD.MM.YY or Datum: DD.MM.YYYY

        Example: Datum: 15.12.2025

    Session Number: Must be labeled "Sitzung Nr." followed by the number.

        Example: Sitzung Nr.: 5

    Patient ID: Must be labeled "Patient*in (Chiffre):" followed by the ID.

        Example: Patient*in (Chiffre): XY-123

    Note: The tool attempts to fix rotated scans automatically (up to 10°), but please try to scan documents as straight as possible for the best results.

2. How to Use the Program

    Start: Double-click PSY.exe.

    Select Input:

        Click Select File(s) to pick specific PDFs.

        Click Select Folder to automatically process all PDFs inside a specific folder.

    Select Destination: A popup will ask you to choose the main folder where you want your files stored.

    Wait: The program will analyze the files. This may take a few seconds per page.

3. Results

    Success: Files are renamed and moved into a folder named after the Patient.

        Structure: Destination_Folder / XY-123 / 2025-12-15_Patient-XY_Sitzung-5.pdf

    Fallback: If the text cannot be read (e.g., too blurry, missing fields, or bad rotation), the file is moved to a folder named Unsorted_Scans. Please review these manually.

Created for Windows 11 - No Installation Required.
