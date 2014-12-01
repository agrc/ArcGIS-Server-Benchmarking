## Setup [Architecture 1](https://github.com/agrc/ArcGIS-Server-Benchmarking/blob/master/Architectures.md#architecture-1-baseline)
- [ ] Install `ArcGIS Server` version **10.2.1**
- [ ] Copy cache tiles local
- [ ] Publish map service
- [ ] Use [wrk scripts](https://github.com/steveoh/wrk) to benchmark `A1`.
- [ ] Decomission machine 
- [ ] Commission new machine
- [ ] Repeat with `ArcGIS Server` version **10.2.2**
- [ ] Repeat with `ArcGIS Server` version **10.3**

## Setup [Architecture 2](https://github.com/agrc/ArcGIS-Server-Benchmarking/blob/master/Architectures.md#architecture-2)
- [ ] Acquire `HNAS` and `SAN` storage
- [ ] Set up shares
- [ ] Copy cache tiles to `HNAS`
- [ ] Copy cache tiles to `SAN`
- [ ] Publish map service
- [ ] Install `ArcGIS Server` version **10.2.1**
- [ ] Use [wrk scripts](https://github.com/steveoh/wrk) to benchmark `A2` with `SAN` and `HNAS` storage.
- [ ] Decomission machines
- [ ] Commission new machines
- [ ] Repeat with `ArcGIS Server` version **10.2.2**
- [ ] Repeat with `ArcGIS Server` version **10.3**

## Setup [Architecture 3](https://github.com/agrc/ArcGIS-Server-Benchmarking/blob/master/Architectures.md#architecture-3)
- [ ] Acquire physical machines
- [ ] Acquire `SAN` storage
- [ ] Configure clustered file system
- [ ] Copy cache tiles to storage
- [ ] Publish map service
- [ ] Use [wrk scripts](https://github.com/steveoh/wrk) to benchmark `A3`.
- [ ] Format machines 
- [ ] Repeat with `ArcGIS Server` version **10.2.2**
- [ ] Repeat with `ArcGIS Server` version **10.3**
