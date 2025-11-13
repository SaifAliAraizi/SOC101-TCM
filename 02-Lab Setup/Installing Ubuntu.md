References
- https://ubuntu.com/download/desktop
- 24.04 LTS Download: https://ubuntu.com/download/desktop/thank-you?version=24.04&architecture=amd64
- Past Ubuntu releases: https://releases.ubuntu.com/

Commands

Update system packages
sudo apt update

Install required packages
sudo apt install bzip2 tar gcc make perl git

Install the generic kernel headers
sudo apt install linux-headers-generic

Install our system-specific kernel headers
sudo apt install linux-headers-$(uname -r)