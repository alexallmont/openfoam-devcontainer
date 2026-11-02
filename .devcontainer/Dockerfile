# Use openfoam-default rather than openfoam-dev so tutorials are included.
# Use 2306+ to support latest platforms, including macOS.
FROM opencfd/openfoam-default:2306

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y \
    git \
    gcovr
