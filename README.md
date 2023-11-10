# Docker Desktop Releases and Updates


| S. No | Release Version | Feature/Product | What's New
|-------|------|-----|----|
| 1 | 4.25.0 | Docker Init | Support for ASP.NET Core 8(in addition to 6 and 7 |
|    |       | Containerd  |  containerd integration:
|    |    |   |docker push now supports Layer already exists and Mounted from progress statuses.
|    |     |  |docker save is now able to export images from all tags of the repository.
|    |     |  |Hide push upload progress of manifests, configs and indexes (small json blobs) to match the original push behavior.
|    |    |   |Fixed docker diff containing extra differences.
|    |    |   |Fixed docker history not showing intermediate image IDs for images built with the classic builder.
|    |    |   |Fixed docker load not being able to load images from compressed tar archives.
|    |    |   |Fixed registry mirrors not working.
|    |    |   |Fixed docker diff not working correctly when called multiple times concurrently for the same container.
|    |    |   |Fixed docker push not reusing layers when pushing layers to different repositories on the same registry.
