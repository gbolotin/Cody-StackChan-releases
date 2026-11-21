# StackChan Desktop downloads

This repository holds only the installers and update packages of the StackChan Desktop app.
The source code is private.

| Channel | Which release | Install |
|---|---|---|
| Release | The release marked **Latest** | `StackChanDesktop-stable-Setup.exe` |
| Dev | The newest **Pre-release** (`…-dev.N`) | `StackChanDesktop-dev-Setup.exe` |

Run the Setup file once. The app installs for the current user, appears in the Start menu
and then updates itself: it checks for a new version at start and every 6 hours, downloads it
in the background and offers **Restart** in the sidebar. The sidebar's **Updates** list
switches between the Release and Dev channels.
