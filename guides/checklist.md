# Checklist

Here are all of the items that need to be completed before a student's setup is considered "complete". They should be checked in this order.

1. The student has their face in their Slack profile picture.

    **How to check:**

    You can see [their face in the Slack team](slack.md#update-your-profile).

1. The student has their face in their GitHub profile picture.

    **How to check:**

    You can see [their face on their GitHub profile](github.md#profile-picture).

1. The student has their [`*-code-solutions` repository](setup.md#clone-your-solutions-repository) on GitHub for the current class.

    **How to check:**

    You can see the repository listed on their GitHub profile in the **Repositories** tab.
   
1. The student is running macOS or Windows.

   **How to check:**
   
   Ask them or look at their OS when they are screen sharing.

1. The student has [VS Code set up "correctly"](setup.md#code-editor). **IF THE AUTO INSTALLER FAILED, WE NEED THE ERROR LOG FILE.**

    **How to check:**

    The status bar (bottom stripe) of VS Code is black and not blue or purple. **Note:** In a real pinch, there are manual instructions in the `lfz-code` repo.

1. The student has the [Slack **desktop app**](slack.md#get-the-app) installed on their machine.

    **How to check:**

    You can see it running on their machine.

1. The student has [Git configured correctly](setup.md#configure-git).

    **How to check:**

    When they run `git config --global --list` (in **Terminal** on macOS or **Git Bash** on Windows), their name and email address are shown.

1. The student has [7zip installed (Windows)](https://github.com/Learning-Fuze/lfz-code/blob/master/windows/MANUAL_INSTRUCTIONS.md#install-7zip).

    **How to check:**

    If the student presses `Win + S` and types **7zip**, it shows up as an installed application.

1. The student has [`npm` version `6.x.x`](https://github.com/Learning-Fuze/lfz-code/blob/master/windows/MANUAL_INSTRUCTIONS.md#install-nodejs) installed.

    **How to check:**

    The command `npm -v` should show the version number (in **Terminal** on macOS or **Git Bash** on Windows).

1. The student has a [`repos` directory](setup.md#create-a-repos-directory) in their home directory.

    **How to check:**

    You can see `repos` listed when the student does `ls ~` (in **Terminal** on macOS or **Git Bash** on Windows).

1. The student has [cloned their `*-code-solutions` repository](setup.md#clone-your-solutions-repository) to their local machine.

    **How to check:**

    The student can `cd ~/repos/<cohort number>-code-solutions` and then do `git status` to see that they are on the `master` branch.
