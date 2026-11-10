# JEWEL: THE LAST TIMELINE

**Change the past. Restore the flow.**

Get the [v118 Windows venue test](https://github.com/ZweWH/jewel-the-last-timeline-downloads/releases/tag/v118-windows-venue). The release assets are public. Play requires a Jewel event account provided separately.

## Download and play

1. Under **Assets**, download all three `Jewel-v118-Venue-Windows.zip.001` to `.003` parts and `Reassemble-JEWEL-v118.cmd` to the same folder. Allow at least **16 GB free** if the downloads, rebuilt ZIP, and extracted game are on one drive.
2. Run **Reassemble-JEWEL-v118.cmd**. It joins the three parts and verifies the complete ZIP with SHA-256. **SHA256SUMS.txt** also lists the individual part checksums.
3. Extract **Jewel-v118-Venue-Windows.zip** to a writable local folder. Open **START-HERE.txt**, then run **Play Jewel Venue (DX11).cmd**. Keep the extracted Windows folder together.

Use the numbered release assets. GitHub’s automatic **Source code** ZIP and TAR files contain a snapshot of this download guide.

## Host and join

1. Sign in on both PCs using the provided Jewel event account. Both PCs need internet for sign-in and must be able to reach each other on the venue network.
2. On the first PC, select **Host Game** and wait for NY, the Director, to enter Jewel.
3. On the second PC, enter the host PC’s local IPv4 address and port **7777**. Select **Join Game**, choose a role, and wait for the intro to finish. If the connection times out, venue IT can check inbound UDP 7777 on the host.

## Test scope

The launcher uses DirectX 11 at 960 × 540 with a 20 FPS cap for the initial stability check. Sign-in, Sign out, Host and Join passed with two instances on one PC. The two-PC venue test is pending.

[Browse earlier releases](https://github.com/ZweWH/jewel-the-last-timeline-downloads/releases).
