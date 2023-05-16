# intel-icc-icx-compiler-basekit

### Installation
```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18236/l_BaseKit_p_2021.4.0.3422.sh
sudo sh <script-name>.sh -a --silent --eula accept
```


### Append following environment variable
```
vi ~/.bashrc
export INTEL_ONEAPI_ROOT=/opt/intel/oneapi
export PATH=$PATH:$INTEL_ONEAPI_ROOT/compiler/2021.4.0/env:$INTEL_ONEAPI_ROOT/compiler/2021.4.0/linux/bin/intel64
```
