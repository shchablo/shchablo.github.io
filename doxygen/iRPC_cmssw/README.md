# README
In these documents presented the description of classes the clustering algorithm for iRPC implement for CMSSW.

## How to use
```	 
cmsrel CMSSW_10_6_1
cd CMSSW_10_6_1/src/
cmsenv
git cms-init
git cms-addpkg  RecoLocalMuon/RPCRecHit
git remote add konstantin https://github.com/shchablo/cmssw
git fetch konstantin
git checkout konstantin/iRPC-Clustering
scram b -j 8
cd RecoLocalMuon/RPCRecHit/test

```
## Any questions
PhD-student, Shchablo Konstantin <br> 
Institute of Nuclear physics of Lyon  <br>
(Bâtiment Paul Dirac 4, Rue Enrico Fermi 69622 Villeurbanne Cedex, France) <br>
shchablo@ipnl.in2p3.fr or shchablo@gmail.com 

## License
GNU Lesser General Public License v3.0
