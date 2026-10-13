<!-- Migrated from OSF szch3, wiki page "Data Management". Original: https://osf.io/szch3/wiki/Data%20Management/ · last edited 2025-03-21. -->

# Data Management

**File/Folder Naming**
<br>Data should be named in an informative way. Any data should formatted as such:<br>

    <animal/experiment identifier>_<year,4 digits>-<month>-<day>_<whatever else you think is informative>

with the information in the <> filled in. Note where the underscores (_) and dashes (-) are.

<br>
**Data Storage**
<br>Data are stored on the lab network-attached storage (NAS). The network ID of this device is DENMANLAB. 
<br>You can connect to it through the network interface on your computer:
- On Mac, go to Finder, press ⌘+K, and connect to `smb://denmanlab`.
- On Windows, open File Explorer and enter  "\\\\denmanlab" in the top bar.

You will then need to enter your username and password, which will have been provided to you when you started in the lab. If you are having trouble accessing it, contact Dan. 

**Backup Policy**<br>
All raw data need to be backed up as soon as they are collected. Behavior sessions are automatically kept in two locations, on the acquisition machine hard drive and the NAS. 

Electrophysiology and imaging data should be moved onto larger internal drives in the acquisition machines (note: these are typically **not** the drives data are written to during experiments) and also copied on the NAS following experiments 

The NAS is backed up automatically to an off site location. This is true backup, and is expected to be accessed only in emergency data loss cases.
