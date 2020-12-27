---
title: "PacFORMS Update for MV CERT"
date: 2019-11-06
draft: false
---
These are instructions for adding the revised Mountain View DA Summary form to an existing installation of Outpost.

The current version of Outpost, Installer 145C,
[can be found here](https://www.scc-ares-races.org/data/packet/installer/sccsetup145Cpub.exe) and this version
or later should be installed on your computer before installing the files described below. The 145C installer
results in a version of Outpost that reports "Version 3.3.0 c65" when run. The Damage Assessment Summary form
is still in PacFORMS format and will remain that way. It has been updated to include the newest Mountain View
CERT team, Rengstorff/Shoreline.

If you have problems or questions with either installation method, contact Phil Henderson at kf6zsq@yahoo.com.

## Installing Using the Installer

You can download the [PacForms DA Summary installer here](sccMVCert47Cb.exe).

This is a single installer for either the public or Santa Clara County versions of Outpost to add the Mountain
View ARES/CERT DA Summary PacFORM to the Outpost Forms drop-down list.

The install file is similar to that used to install the combined Outpost, PackItForms, and Legacy PacFORMS
files and places all files in their correct locations.

The installer copies the latest version of the Damage Assessment form to the `C:\PacFORMS\exec` directory
and a file called `Launch.local` to the Outpost Data directory. `Launch.local` provides Outpost with the
information required to populate the Outpost Forms drop-down menu. A PDF version of the DA Summary form is
saved to the `C:\PacFORMS\PaperForms` directory.

After downloading and saving the install file to your hard drive, double click on the file and follow
instructions. It is required that Outpost is running when this is done. When the installer is completed,
restart Outpost and check the Forms drop-down menu and make sure that there is one new PacFORM file at
the bottom of the list.

If you have trouble with the installer, you may use the manual installation method described below.

## Installing Manually

The following instructions will work for either the public or Santa Clara County version of Outpost. Also,
if a new release of Outpost comes out after you have done the install, you will NOT have to re-install these files.

Instead of using the installer, copy and save the three files below to the appropriate directories on your
computer: the form file, another file that is used by Outpost to populate the Forms menu, and the PDF version to print.

Double click on the first file to open the instructions. This is an PDF file. Print it so you can follow
the instructions more easily. The instructions will show you how and where to save the other files.

- [Instructions to install files below](how-to-add-da-form.pdf) (PDF File)
- [`MTV_213_CERT_Summary.html`](MTV_213_CERT_Summary.html) (right Click, select "Save File As...")
- [File `Launch.local` for Outpost Data Directory](Launch.local) (right Click, select "Save File As...")
- [PDF "Paper" version of the DA Summary PacFORM](ics-213-mtv-da-summary-20140326.pdf) (right Click, select "Save File As...", Save to `C:\PacFORMS\PaperForms`)
