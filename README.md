# raycaster-go
Golang raycaster engine based on the [raycaster example](https://github.com/faiface/pixel-examples/blob/master/community/raycaster/raycaster.go) for the [Pixel](https://github.com/faiface/pixel) 2D Game Library.

## Developer setup
To install and run from source the following are required:
1. Download, install, and setup Golang https://golang.org/dl/
2. Use the `go get` command to download the Pixel 2D Game Library and its pre-requisites: 
    * `[GOPATH]$  go get -u github.com/faiface/pixel`
    * `[GOPATH]$  go get -u github.com/faiface/glhf`
    * `[GOPATH]$  go get -u github.com/faiface/mainthread`
    * `[GOPATH]$  go get -u github.com/go-gl/mathgl/mgl32`

    If running on Windows, GL For Windows is also required:
    * `[GOPATH]$  go get -u github.com/go-gl/glfw/v3.2/glfw`
3. Clone/download this project to your `GOPATH/src` folder, for example: `GOPATH/src/raycaster-go`
4. Now you can use the `go run` command to run `raycast.go`:
    * `[GOPATH/src/raycaster-go]$ go run raycast.go`

## Controls
* Move and rotate using WASD or Arrow Keys
