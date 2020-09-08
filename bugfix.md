# Description
The ```gity``` npm repo is ```https://github.com/stevenmiller888/gity``` but for this bounty somehow wrong repo was cloned ```https://github.com/beheadedmyway/gity``` which is a MAC Client for Git. However I have fixed the ```Arbitrary code execution``` in the npm ```gity``` by cloning the actual repo. The fix is using ```execFile``` instead of insecure ```exec```.
