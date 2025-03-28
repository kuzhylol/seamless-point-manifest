# Sync seamless-point project
mkdir -p seamless-point && cd seamless-point

repo init -u git@github.com:kuzhylol/seamless-point-manifest.git -b yocto-next

repo sync -j$(nproc)
