# hybrid-slam-original
# Run code: 
```bash
**!sudo apt-get update && apt-get install -y build-essential cmake ninja-build libtbb-dev
!python3 -m pip install pybind11
%cd hybrid-slam-original
!git clone https://github.com/leedongzheo/hybrid-slam-original.git
!python3 -m pip install -e .
!kiss_slam_pipeline --help
%uv pip uninstall kiss-icp

!git clone https://github.com/leedongzheo/hybrid-icp-original.git
%cd hybrid-icp-original/python
!python3 -m pip install -e .
```
