# hello-snap
Simple hello world snap

## Getting started
1. Change the name in the snapcraft yaml to something like hello-mycoolnickname
2. Build with `snapcraft` or `snapcraft --use-lxd` or `snapcraft --destructive-mode`
 - destructive-mode would be fastest, and not harmful in this case since there are no dependencies installed or changes to the system made
3. Install locally with `sudo snap install <hello-mycoolnickname.snap> --dangerous` 
 - dangerous is needed because there is no assertion for the snap yet
4. Run the command
5. Remove the snap

## Things to try
* Change the snap command
* Publish the snap to the store
* Promote the snap to stable

The build environment can be cleaned with `snapcraft clean --destructive-mode` if that mode was used previously.

