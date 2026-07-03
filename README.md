# VolumeMixer
A volume Controller with GUI that can be set to macros or a rotary knob. The script can cycle through active applications and the system volume for full control.
volume-mixer — Stateful per-app volume control

Usage: volume-mixer [next|up|down|mute]

Requires: pactl (pipewire-pulse or pulseaudio), jq

Optional: libnotify (notify-send) for desktop popups

The script will use OSDs own volume bar GUI and Works even in fullscreen mode

The application will conflict with any built in volume GUI and so it is suggested that you turn off any volume notificatons from the system




