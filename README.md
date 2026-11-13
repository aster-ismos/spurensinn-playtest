# spurensinn-playtest
Depot for Spurensinn Playtest builds

## How to Play
* Click on Releases
* Choose appropriate Release (Round 1, 2, etc)
* Download .zip
* Extract .zip
* Start Spurensinn.exe
(If prompted, More info > Run Anyway)

# For Remote:
### How to Record Your Gameplay

Please record your play session so we can watch it together afterwards. You only need **one** of the tools below. OBS Studio works on every PC and is free and open source.

> **Privacy:** Please record **only the game window**. Do not record your webcam, and keep your microphone muted unless we ask you to talk during the session.

#### Option A: OBS Studio (recommended)

1. Download OBS Studio from <https://obsproject.com/> and install it.
2. When you open OBS for the first time, the Auto-Configuration Wizard starts. Choose **Optimize just for recording**.
3. Start `Spurensinn.exe` first, so OBS can find the game.
4. In OBS, go to the **Sources** box, click **+** and choose **Game Capture**.
   - Set **Mode** to **Capture specific window** and select **Spurensinn**.
   - If the preview stays black, remove it and use **Window Capture** instead.
5. In the **Audio Mixer**, mute **Mic/Aux** (click the speaker icon).
6. Click **Start Recording**, then play.
7. When you are done, click **Stop Recording**.
8. To find the video, go to **File** > **Show Recordings**.

Tip: in **Settings** > **Output**, you can change where recordings are saved. Leave the **Recording Format** at **Hybrid MP4** (or choose **MP4**).

#### Option B: NVIDIA App (only for NVIDIA graphics cards)

If your PC has an NVIDIA graphics card, the NVIDIA App may already be installed. It is free, but not open source. No NVIDIA account is needed.

1. If it is not installed, download the NVIDIA App from <https://www.nvidia.com/en-us/software/nvidia-app/> and install it.
2. Open the NVIDIA App, go to **Settings** and make sure **NVIDIA Overlay** is turned on.
3. Start `Spurensinn.exe` and press **Alt + Z** to open the overlay.
4. Check that the **webcam** and **microphone** icons are turned off.
5. Press **Alt + F9** to start recording, then play.
6. Press **Alt + F9** again to stop. The video is saved in your **Videos** folder.

---

### How to Reduce Video File Size

1. Download the open source video transcoder HandBrake from <https://handbrake.fr/> and install it.
2. Open HandBrake and drag your video into the window.
3. Under **Preset**, choose **Fast 720p30** or **Fast 1080p30**.
4. At the bottom, next to **Save As**, choose where to save the new file.
5. Click **Start Encode**.
6. Share the smaller file in the provided shared folder.
