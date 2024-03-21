Batch Registration of tiff recordings.

This Script can be used to do registration of calcium imaging recordings (tiff files) using the algorithms implemented
in the suite2p package. It will ask you to select a directory that includes only your tiff files. After that it will
automatically start the registration. If the recording file could be found it will ask you if you would like to do a
rigid or non-rigid registration.

If you want you can change the batch size by calling:
    >> python suite2p_pre_processing.py -500

Default settings:
    batch size of 300 frames
    frame rate: 2 Hz
    300 frames to use to compute reference image for registration


Nils Brehm  - 2024