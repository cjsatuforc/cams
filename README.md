# cams

Generates cam profiles (.stl) for the mechanical laser show. Orignally written in Golang but now ported to JS/HTML (thanks [ValkA](https://github.com/ValkA)!).

---
# [Launch web interface](https://evanstanford.github.io/cams/public/index.html)
---

# more info

[<img src="https://raw.githubusercontent.com/EvanStanford/cams/master/screenshot.png" width="650" />](https://www.youtube.com/watch?v=_dtBUiaAqRE)

https://hackaday.io/project/25447-mechanical-laser-show

https://www.thingiverse.com/thing:2383299

# legacy golang usage
```
#Install go, git
mkdir go/src/github.com/EvanStanford/
cd go/src/github.com/EvanStanford/
#Add environment variable GOPATH to go directory
git clone https://github.com/EvanStanford/cams.git
cd cams/profiler/
go get         
go test
#PASS                                                                    
go install
cd ../main/
go install
../../../../../bin/main.exe ../profiler/testfiles/star_path.csv 0.045
ls out/star_path/
```
