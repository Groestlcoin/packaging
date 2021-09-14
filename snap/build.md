# Build the snap for Snapcraft

- Push the latest version to master (if applicable), e.g. https://github.com/Groestlcoin/packaging/commit/14c656f024026e944bda3c905abf811a437aa388

- Create a new branch for the major release "VV.x" from master (used to build the snap package) and request the
  track (if applicable), e.g. https://forum.snapcraft.io/t/track-request-for-groestlcoin-core-snap/17359/12

- Notify Jackielove4u so that he can start building the snap package

  - Leave owner and series as-is
  - Select architectures that are compiled via guix
  - Leave "automatically build when branch changes" unticked
  - Tick "automatically upload to store"
  - Tick the "edge" box
  - Put "VV.x" in the track field
  - Click "create snap package"
  - Click "Request builds" for every new release on this branch (after updating the snapcraft.yml in the branch to reflect the latest guix results)
  - Promote release on https://snapcraft.io/groestlcoin-core/releases
