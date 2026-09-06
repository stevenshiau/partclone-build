This git repo is aimed to build Partclone on Debian and Ubuntu Linux, i.e., an "Overlay Repository" or a "Packaging Repository.
It keeps the original author's source code separate from the debian/ packaging files to avoid cluttering the upstream project.
The idea is:
1. It only contains github action
2. Watch upstream ezio tag release from https://github.com/Thomas-Tsai/partclone
3. If new release, check it out then build.
Hence this repo only contains the packaging rules and the CI/CD pipelines.
