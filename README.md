### Environment for building SLADE dependencies on OS X

This repository must be cloned into `/usr/local`, i.e.  
`git clone https://github.com/alexey-lysiuk/slade-osx-build-env.git /usr/local`

All libraries were built on OS X 10.6.8 Snow Leopard with Xcode 3.2.6 installed.
The following environment variables were set:
```
declare -x CPPFLAGS="-I/usr/local/include"
declare -x CFLAGS="-I/usr/local/include"
declare -x CXXFLAGS="-I/usr/local/include"
declare -x LDFLAGS="-L/usr/local/lib"
```
