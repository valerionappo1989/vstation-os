FROM fedora:42

RUN dnf install -y \
    vulkan-loader-devel \
    plasma-workspace-devel \
    libplasma-devel \
    gstreamer1-plugin-libav \
    lz4-devel \
    mpv-libs-devel \
    python3-websockets \
    qt6-qtbase-private-devel \
    qt6-qtwebsockets-devel \
    qt6-qtwebchannel-devel \
    git \
    cmake \
    extra-cmake-modules \
    kf6-rpm-macros \
    fedpkg \
    rpkg \
    && dnf clean all

WORKDIR /workspace
