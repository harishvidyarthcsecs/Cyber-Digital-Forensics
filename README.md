# Cyber and Digital Forensics Lab Reports — CR23532

N Harish Vidyarth | Roll No: 241901035

| # | Experiment | Status |
|---|---|---|
| 1 | Study of Computer Forensics and Different Tools Used for Forensic Investigation | theory complete |
| 2 | Live Forensics Case Investigation Using Autopsy | procedure written, lab screenshots pending |
| 3 | Recover Deleted Files Using Forensics Tools | procedure written, lab screenshots pending |
| 4 | Find Last Connected USB on Your System (USB Forensics) | procedure written, lab screenshots pending |
| 5 | View Last Activity of Your PC | procedure written, lab screenshots pending |
| 6 | Extraction of Browser Artifacts | procedure written, lab screenshots pending |
| 7 | Comparison of Two Files for Forensics Investigation by Compare IT Software | done (real output on macOS sample files) |
| 8 | Collecting Email Evidence in Victim PC | procedure written, lab screenshots pending |
| 9 | Hiding and Extracting a Text File Behind an Image or Audio File Using Command Prompt | done (real output on macOS sample files) |
| 10 | Extract EXIF Data from Image Files Using ExifReader Software | done (real output on macOS sample files) |

## What is real vs. still needs a lab run

- **Experiment 1** is a descriptive study. Its observation is the requested summary of the commercial, open-source, and field tools listed in the course manual.
- **Experiment 7** contains real diff, cmp, and SHA-256 output from two synthetic text files under evidence/exp07/.
- **Experiment 9** contains a real JPEG-plus-text concatenation, extraction, file identification, hex view, byte counts, comparison, and SHA-256 verification under evidence/exp09/.
- **Experiment 10** contains real sips, file, and SHA-256 output from a synthetic JPEG under evidence/exp10/. No camera, timestamp, or GPS value is claimed.
- **Experiments 2, 4, 5, 6, and 8** need their Windows GUI lab runs and screenshots. No personal browser, mail, USB, or activity history was accessed.
- **Experiment 3** also needs a lab run. Sleuth Kit, Foremost, PhotoRec, FTK Imager, and RecoverMyFiles were not installed in the report-building environment, so no deleted-file recovery output was fabricated.

The unmodified experiment page-split PDFs supplied with the manual are kept under manual-source/.

## Folder guide

- Experiment NN - title.pdf — the ten submission reports.
- evidence/ — synthetic sample files, commands, and raw captured command output for Experiments 7, 9, and 10.
- manual-source/ — unmodified source-page PDFs split by experiment, plus the course syllabus/front matter PDF.

## Integrity note

All completed output blocks were generated from the sample files in this folder. Pending reports use the exact wording “To be completed after the lab run.” in the Result section and do not present manual screenshots as student evidence.

In `evidence/exp10/output.txt`, the first line printed by `sips` (an absolute local file path) was shortened to the file name `sample.jpg` before publishing; all other lines are unedited command output.
