# VpK Snapshot

A desktop app built using Electron.  The applicaiton creates a snapshot of a Kubernetes cluster that is used by VpK (Visually presented Kubernetes).  

VpK Snapshot can be used to create a k8s snapshot at anytime. Once the snapshot has been created it can be viewed and analyzied with the VpK application.  The VpK application can be run as a locally installed Node.js program or run from a Docker container.  

When VpK is launched via a Docker container the snapshot directory is mapped to the container using a volume parameter.  
Refer to VpK documentation for additional information regarding running VpK in a container.

## Usage

### Install Dependencies

```
npm install
```

### Run

```
npm start
npm run dev (with Nodemon)
```

### Package

```
npm run package-mac
npm run package-win
npm run package-linux
```

Once the application has been packaged the newly created executable my be run like any other native application on the associated operating system.  

The packaged application will be placed in the project in a newly created directory __release-builds__ that includes a sud-directory with the executable.


## LICENSE

MIT License

Copyright (c) 2018-2023 k8svisual

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
