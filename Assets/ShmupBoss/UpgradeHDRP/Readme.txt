When importing Shmup Boss into your project, please note that it will default to the standard graphic settings. This means that even if you import Shmup Boss into an HDRP project, it will change the graphics settings back into the default render settings which isn't HDRP.

To upgrade into HDRP, click on the "HDRP_2019.4+" asset if you are using Unity 2019.4 to 2020.1 or "HDRP_2020.2+" if you are using Unity 2020.2 or higher. After importing into your project, please go to the edit menu, then to project settings and enter the graphics tab. There you can quickly change the graphics settings into HDRP by clicking on the small presets icon on the top right (the small icon in between the settings and help icons in the graphics tab) and then select the graphics seetings preset provided in the HDRPSettings folder (the only preset which you can see after clicking on the presets icon).

If you get any console message after importing the upgrade HDRP asset and changing the graphics settings preset, you can always go to windows, render pipeline, HDRP wizard and hit the fix all button.

Additionally, please note that Shmup Boss uses the old input system, if for any reason that have changed in your project, you can always go to the project settings, player settings and inside the other settings tab, please make sure that the active input handling is set to "Input Manager (old)".

If you need any help, please feel free to get in touch at the support forum thread here: https://forum.unity.com/threads/1030870/