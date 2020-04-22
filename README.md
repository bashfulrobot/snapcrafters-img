# snapcrafters-img

Snap package for [Img](https://github.com/genuinetools/img).

Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.

Build container images in Kubernetes without mounting in the docker socket or doing anything to compromise the security of your cluster.

- Currently this snap package only has access to the `home` folder.
- Full blog article: https://blog.jessfraz.com/post/building-container-images-securely-on-kubernetes/

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/img)