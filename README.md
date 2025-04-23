
git clone https://github.com/PX4/PX4-Autopilot.git --recursive
Edit Tools > ubuntu.sh, remove g++ multilib and g multilib
pip install 'empy<4'
export QT_QPA_PLATFORM=xcb

https://www.youtube.com/watch?v=aVsTqPDTeYI
https://github.com/sidharthmohannair/Installing-QGroundControl-on-Ubuntu-ARM64-using-Flatpak

pip3 install 'empy==3.3.4' --force-reinstall

flatpak run --device=all org.mavlink.qgroundcontrol

export LIBGL_ALWAYS_SOFTWARE=1
export LIBGL_ALWAYS_SOFTWARE=1
