^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for industrial_reconstruction
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0-samxl-0 (2026-11-05)
--------------------------
- Process queued frames on stop and create the mesh output directory

0.1.0 (2026-03-19)
------------------
- Initial version of the package from the upstream: https://github.com/ros-industrial/industrial_reconstruction
- Use counting frame as parameter
- Convert RGBA to RGB becuase zivid outputs rgba8 as the image encoding
- Increase TF buffer for manual reconstruction
- Change depth encoding from 16uc1 to 32fc1 because zivid uses that
- Reduce sampling frames for manual reconstruction with the UR
- Use correct tag for open3d dep (on jazzy)
