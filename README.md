# P.S.Y. (Protocol Session Yield) - User Manual
sorts and renames scans of psy session docs into folders 

1. Document Requirements
For the automatic recognition to work, the scanned document must clearly contain these three lines in the top third of the first page:

    Datum: Must follow the format Datum: DD.MM.YY or Datum: DD.MM.YYYY

        Example: Datum: 15.12.2025  or  15.12.25

    Sitzung Nr: Must be string followed by numbers or numbers

        Example: Sitzung Nr.: 5 , S5 , S05, Prob5

    Patient*in (Chiffre): Must be a character or string followed by numbers

        Example: Patient*in (Chiffre): XY23, X1212, XY1212, XY121225

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

    Structure: Destination_Folder / XY12 / 20251215_IDXY_S_5.pdf

    Fallback: If the text cannot be read (e.g., too blurry, missing fields, or bad rotation), the file is moved to a folder named Unsorted_Scans. Please review these manually.

Created for Windows 11 - No Installation Required.
