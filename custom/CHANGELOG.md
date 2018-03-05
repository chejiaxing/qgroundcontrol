## DataPilot Release Changelog

### V1.3.4 - Mar 5 2018

*   Moved log download directory from ~/somewhere to ~/Documents/DataPilotPlanner/Logs where it belongs. Added a notice at the bottom of the screen showing the path where logs are downloaded.

### V1.3.3 - Mar 4 2018

*   Reduce upload bandwidth for Remote Sync (upload missions from ST16 to Desktop). The link was not coping with the upload and the ST16 would run out of memory buffering it.

### V1.3.2 - Mar 4 2018

*   Fix KML load. It was not defining the extension type to look for.

### V1.3.1 - Mar 4 2018

*   Flip Gimbal Yaw indicator. Gimbal now sends its position inverted.

### V1.3.0 - Feb 26 2018

*   Promoting version number to 1.3.0 (No code changes)

### V1.2.71 - Feb 26 2018

*   Keep track of camera mode switch done by the autopilot (during missions). Needs updated camera firmware as well.

### V1.2.70 - Feb 26 2018

*   Calibrating the E10T camera for its new 4.4mm lens

### V1.2.69 - Feb 24 2018

*   Set camera time using parameter instead of messages. Again, the camera firmware will need to be updated for this to work.

### V1.2.68 - Feb 23 2018

*   Hiding Max Vertical/Horizontal Velocity from the Safety Panel until it's fully tested.

### V1.2.67 - Feb 23 2018

*   DataPilot now sends the time to the camera periodically. This is to make sure the camera has the correct time. The camera firmware will need changes to accept and consume this.

### V1.2.66 - Feb 21 2018

*   Prevent mouse bleed through toolbar (causing a "Go To" underneath it)

### V1.2.65 - Feb 21 2018

*   Hide mission status (Elevation data) for mobile builds (ST16)

### V1.2.64 - Feb 21 2018

*   Fix image capture while in video mode (auto switch)

### V1.2.63 - Feb 21 2018

*   Prevent mouse clicks to bleed through disabled elements ("Go To" when hitting disabled "Pause" in Fly View)

### V1.2.62 - Feb 21 2018

*   Fix Emergency Stop popup appearing before params are loaded.

### V1.2.61 - Feb 21 2018

* Fix KML Import

### V1.2.58 - Feb 18 2018

* Hide camera section from mission start

### V1.2.57 - Feb 16 2018

* Upstream merge to remove PREFLIGHT_STORAGE calls

### V1.2.56 - Feb 14 2018

* Cosmetic changes:
    * Hide Skyward log export (we don't have the current format)
    * Center LED Mode label within combo box
    * Added "Manual Flight" to text for Max Vertical/Horizontal velocity

### V1.2.55 - Feb 14 2018

* Bump hover and capture delay to 4 seconds

### V1.2.54 - Feb 13 2018

* Fix Resume/Continue Mission popping up at wrong time

### V1.2.53 - Feb 12 2018

* Update parameter meta data for new volatile information.

### v1.2.52 - Feb 12 2018

*   Change the way LED control is handled.

### v1.2.51 - Feb 7 2018

*   Mission upload and download fixes to correctly retransmit
    mission items and mission item request when they get lost
    on the link.

### v1.2.50 - Feb 6 2018

*   Fix offline maps multiple selected button states

### v1.2.49 - Feb 4 2018

*   Fix terrain query crash

### v1.2.48 - Feb 2 2018

*   Bump up hover delay to two seconds

### v1.2.47 - Feb 2 2018

*   Added max horizontal velocity to Safety Panel

### v1.2.46 - Feb 2 2018

*   Added max vertical velocity to Safety Panel

### v1.2.45 - Feb 2 2018

*   Added image capture count to camera control

### v1.2.44 - Feb 1 2018

*   Fix incorrect Resume Mission display

### v1.2.43 - Jan 31 2018

*   Turn off ROI and Structure Scan

### v1.2.42 - Jan 31 2018

*   Show temperatures in Fahrenheit or Celsius (option)

### v1.2.41 - Jan 31 2018

*   Fix DataPilotPlanner issues (show connected vehicle)

### v1.2.40 - Jan 31 2018

*   Fix Metric/Imperial display

### v1.2.39 - Jan 26 2018

*   Hide eleveation data from Plan View (not enough room)
*   Allow editing RTH altitude when armed
*   Bringing changes from upstream

### v1.2.38 - Jan 22 2018

*   Add list of missions to select what to sync (Remote Sync)

### v1.2.37 - Jan 19 2018

*   More fixes for E10T (No presets, no custom temp range)

### v1.2.36 - Jan 18 2018

*   French localization

### v1.2.35 - Jan 18 2018

*   Initial fixes for E10T (thermal image size and position)

### v1.2.34 - Jan 17 2018

*   Remote Sync: Don't show "Select Mission" text as there is no list.
*   Remote Sync: Reset map/log list between connections.
*   Remote Sync: Fix error where Select All/None was not working if a change was made manually.

### v1.2.33 - Jan 16 2018

*   Refactor ST16 library into a common set of libraries for DataPilot and the SDK.

### v1.2.32 - Jan 16 2018

*   No code change. Preparing strings for localization.

### v1.2.31 - Jan 15 2018

*   LED control (All On/All Off/Front Off)

### v1.2.30 - Jan 15 2018

*   Build system change

### v1.2.29 - Jan 15 2018

*   Build system change

### v1.2.28 - Jan 12 2018

*   Desktop/Mobile sync (Sync files between DataPilot Planner and DataPilot)

### v1.2.27 - Jan 4 2018

*   Fixed delete videos from video browser

### v1.2.26 - Jan 2 2018

*   Implement local video capture and display
*   Fix ordering of image browser when using the CGOET

### v1.2.25 - Dec 25 2017

*   Fix Structure Scan camera section loading

### v1.2.24 - Dec 22 2017

*   Added file picker for the desktop version (Planner)
*   Fixed an issue where the Planner was not creating a proper offline vehicle (wrong set of cameras).

### v1.2.23 - Dec 22 2017

*   Internal change. Fixing Jenkins build.

### v1.2.22 - Dec 21 2017

*   Internal change. Switching to the Yuneec MAVLink dialect. No external changes.

### v1.2.21 - Dec 16 2017

*   Fix E10T RTSP URL (Thermal)

### v1.2.20 - Dec 16 2017

*   Reduce memory usage for planning/uploading missions

### v1.2.19 - Dec 15 2017

*   Ask user to power cycle the vehicle for new password to take effect.

### v1.2.18 - Dec 14 2017

*   Add UTM/Geo position editing support
*    Plan: Add speed/gimbal value carry-over from previous items

### v1.2.17 - Dec 12 2017

*   Add support for Skyward log files

### v1.2.16 - Dec 12 2017

*   Add gimbal angle support to manual Structure Scan

### v1.2.15 - Dec 12 2017

*   Add support for the E10T (Untested)

### v1.2.14 - Dec 11 2017

*   Add support for ISO/Shutter speed to CGOET 

### v1.2.13 - Dec 4 2017

*   Desktop log download

### v1.2.12 - Nov 30 2017

*   Fine tuning German localization

### v1.2.11 - Nov 28 2017

*   German and Chinese localization (custom part only)

### v1.2.10 - Nov 28 2017

*   Dealing with set wifi password corner cases

### v1.2.9 - Nov 26 2017

*   Display animation while camera is busy (instead of black screen)
*   Disable time lapse when capturing images while in video mode
*   Add CGOET to list of cameras for survey

### v1.2.8 - Nov 16 2017

*   Restore Structure Scan

### v1.2.7 - Nov 14 2017

*   Enable camera settings even if no microSD card is present

### v1.2.6 - Nov 10 2017

*   Add hobbs meter

### v1.2.5 - Nov 8 2017

*   Disable structure scan (incomplete)

### v1.2.4 - Nov 7 2017

*   Show "Format Complete" message

### v1.2.3 - Nov 7 2017

*   No code changes: 
    Deployment of all branches to s3; the branch needs to be enabled on Jenkins

### v1.2.2 - Nov 2 2017

*   Internal localization work. Not visible to the outside yet.

### v1.2.1 - Nov 2 2017

*   Local thermal image capture (ST16 - CGOET)

### v1.2.0 - Nov 2 2017

*   No code changes. First 1.2.0 iteration and branching.

### v1.1.63 - Nov 2 2017

*   Upstream merge only. Last 1.1.x version.

### v1.1.62 - Nov 1 2017

*   Fix text edit field (camera parameters)

### v1.1.61 - Oct 31 2017

*   Thermal image PIP Mode not overlapping indicators. (CGOET)
*   Thermal image mode made persistent. (CGOET)

### v1.1.60 - Oct 31 2017

*   Updating presets (CGOET)

### v1.1.59 - Oct 31 2017

*   Fix first run dialog corner cases
*   Describe new password requirements

### v1.1.58 - Oct 30 2017

*   First time settings.

### v1.1.57 - Oct 27 2017

*   CGOET Presets (First Pass) Needs updated firmware for it to work. v1.0.07 is broken.

### v1.1.56 - Oct 26 2017

*   Don't play camera sound effect during mission.

### v1.1.55 - Oct 25 2017

*   Fixing thermal ROI persitency.

### v1.1.54 - Oct 25 2017

*   Adding flight data and battery status to UTM log.

### v1.1.53 - Oct 24 2017

*   Support for updater app

### v1.1.52 - Oct 23 2017

*   Fix time lapse slider initialization (it was resetting when created)
*   Skip initial double camera sound when doing time lapse

### v1.1.51 - Oct 23 2017

*   Ignore bad temperature readings (0C when taking pictures) (CGOET)

### v1.1.50 - Oct 23 2017

*   Fixed stopping time lapse using physical shutter button
*   Handle minimum interval possible depending on camera used

### v1.1.49 - Oct 23 2017

*   Time Lapse Photo

### v1.1.48 - Oct 22 2017

*   Export UTM logs

### v1.1.46 - Oct 17 2017

*   Temperature Range (CGOET). Note that it needs a new CGOET firmware for it to work.

### v1.1.45 - Oct 16 2017

*   Implemented Area/Spot ROI (CGOET)
*   Adjusted graphics showing "Area" size (CGOET)
*   Added a slider to control the thermal image opacity (when in Blend Mode)
*   Turn off live video when thermal image mode is set to Full

### v1.1.44 - Oct 13 2017

*   Prevent change settings while recording video

### v1.1.43 - Oct 13 2017

*   Major updates to CGOET handling

### v1.1.42 - Oct 12 2017

*   Added proper palette bars to UI.

### v1.1.41 - Oct 11 2017

*   When switching from the ET to some other camera, DataPilot was not "forgetting" the thermal image.

### v1.1.40 - Oct 11 2017

*   Merge upstream changes and fixes

### v1.1.39 - Oct 02 2017

*   Temperature readings from "Custom" area instead of "Full Area". This is until we have a proper Custom/Full toggle function.
*   Fixed issue with editing camera parameters (ET Only)
*   Upstream merge (DataPilot now in sync with upstream QGC)

### v1.1.36 - Sep 28 2017

*   Changed edit fields in CGOET settings

### v1.1.35 - Sep 25 2017

*   Preliminary support for the CGOET

### v1.1.34 - Sep 15 2017

*   Disable settings when image capture is busy.

### v1.1.33 - Sep 13 2017

*   Link video stream timeout with MAVLink connection timeout.

### v1.1.32 - Sep 12 2017

*   Added OBS indicator to the toolbar (flashes green when active)

### v1.1.31 - Sep 12 2017

*   Increased video stream timeout from 2 to 10 seconds (holding last frame before giving up)
*   Keep requesting image capture status while camera reports busy

### v1.1.30 - Sep 12 2017

*   Fixed changelog deploy

### v1.1.25 - Sep 8 2017

*   Adding changelog

### v1.1.24 - Sep 8 2017

*   Enable logging by default

### v1.1.23 - Sep 7 2017

*   Disable hardware shutter button when recording video.

### v1.1.22 - Sep 7 2017

*   Disable settings that cannot be changed while video is being recorded

    * Video Resolution
    * Video Format (for the E90)
    * Reset Camera
    * Format SD Card

### v1.1.21 - Sep 4 2017

*   Add ability to toggle video stream in full screen (hinding all controls)

### v1.1.20 - Sep 2 2017

* Add a timeout for gimbal calibration.
* Restrict spot area within image region.
* Fix wrong logic that enables/disables hardware shutter buttons.
* Prevent RC calibration if bound to a vehicle (RC calibration cannot be done while connected (and bound) to a vehicle.)

### v1.1.19 - Sep 2 2017

* Fix bad initializer for mission export (wrong file imported count)
* Limit negative gimbal pitch

### v1.1.18 - Aug 31 2017

* Disable local video recording (ST16)

