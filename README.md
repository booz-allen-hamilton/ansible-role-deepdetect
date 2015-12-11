# ansible-role-deepdetect
Ansible Role for installing DeepDetect and downloading pre-trained model as described in [http://www.deepdetect.com/tutorials/imagenet-classifier/](http://www.deepdetect.com/tutorials/imagenet-classifier/).
This is meant to be referenced as git submodule from other projects.

DeepDetect installs at `/opt/deepdetect`

Package installs and compiles as root, and must be run as `root` or with `sudo` since binary expects write permission in DeepDetect install directory.

Known to work on Ubuntu 14.04 (Trusty)

## Troubleshooting
* GCC error on compile step
    * Try increasing virtual machine memory capacity