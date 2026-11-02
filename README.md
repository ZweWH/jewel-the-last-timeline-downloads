# JEWEL: THE LAST TIMELINE

**Change the past. Restore the flow.**

Download the Windows game from [Releases](https://github.com/ZweWH/jewel-the-last-timeline-downloads/releases).
**No GitHub account is required.** This repository contains the download guide;
the playable game is attached to the release.

## Download and play

1. Open the v089 release and expand **Assets**. Download all three numbered
   **.zip.001**, **.zip.002** and **.zip.003** files, plus **Reassemble-JEWEL-v089.cmd**,
   into one new folder. Also download **READ-ME-FIRST.txt**,
   **DISTRIBUTION-v089.json** and **SHA256SUMS.txt**. Keep the exact filenames.
2. Allow at least **15 GB free space** for downloads, assembly and extraction.
   Double-click **Reassemble-JEWEL-v089.cmd**. Wait for **SUCCESS**: the helper checks
   every part and the complete ZIP. It does not overwrite an existing ZIP or
   delete downloads.
3. Right-click **JEWEL-The-Last-Timeline-v089-Windows.zip**, select **Extract All**,
   then open the extracted **Windows** folder and run **TheEightKeys.exe**.
   Keep the entire Windows folder together.

The three numbered parts form one game download and cannot be extracted
separately. Use these release assets rather than GitHub's automatic **Source code**
ZIP/TAR downloads. Read **READ-ME-FIRST.txt** for extraction troubleshooting.

## Host and join

Both PCs use the same game. The host chooses **Host Game** and plays Director
(NY). On another PC on the same approved LAN, enter the host's IPv4 address,
leave port **7777**, then choose **Join Game**. After joining, use
**Escape → Choose Role** to select a free engineering role before launch, then
**Back to Home → Resume Jewel**. The roles are BIM, Site, Technical, Planning,
QAQC, Safety, Quantity Surveyor and Mechanical. Roles lock after launch.
Closing or leaving the host ends the round.

Client PCs do not need Unreal Editor or build tools. IT can review the included
Visual C++ runtime if a PC needs it or approved LAN traffic if joining is blocked.
The helper does not install prerequisites or change firewall/security settings.
There is no automatic server discovery or internet matchmaking.

## Current test scope

This is the **v089 Development build**. All eight missions, the eight-key finale
and NY movement are retained. Actual packaged tests used two rendered processes
on one PC and covered Host/Join, all eight sequential role choices,
Home/Resume/Leave/Quit, normal BIM launch and unfinished same-application recovery,
NY shrink/flight/restore and run-state caps, zero-key finale rejection and a new
host round. These were software-operated tests.

Real second-PC LAN, clean-PC prerequisites, complete packaged mission/finale runs,
physical keyboard/Xbox, full gait/train/collision coverage, nine-player rendering
and representative performance remain pending. Recorded native/renderer warnings
remain. See the package's **README-JEWEL.txt** and **BuildInfo-v089.json** for
full details. Public availability does not change this test scope.

Original ZIP: **4,549,217,166 bytes**. SHA256:
`47d11ac53b638aae6ea193922496b75a455d83ae599cf4bf62b544d904f5ec53`
