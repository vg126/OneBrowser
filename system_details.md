
## Hardware Specifications

### CPU
- **Model**: Intel Core i7-10750H @ 2.60GHz
- **Cores**: 6 cores, 12 threads
- **Max Frequency**: 5.0 GHz
- **Min Frequency**: 800 MHz
- **Architecture**: x86_64

### Memory
- **Total RAM**: 16 GB (15 GiB available)
- **Currently Used**: 12 GiB
- **Available**: 3.2 GiB
- **Swap**: Disabled (0B)

### GPU
- **Primary**: NVIDIA GeForce GTX 1650 Mobile
  - **VRAM**: 4 GB (4096 MiB)
  - **Currently Used**: 2.7 GB (2749 MiB)
  - **Available VRAM**: ~1.3 GB
  - **CUDA Version**: 12.9
  - **Driver**: 575.64.03
- **Integrated**: Intel UHD Graphics (CometLake-H GT2)

### Storage
- **Primary Drive**: NVMe SSD 256 GB
  - **Used**: 145 GB (66%)
  - **Available**: 77 GB
  - **Mount**: `/dev/nvme0n1p2`

## Software Environment

### Operating System
- **Distribution**: EndeavourOS (Arch Linux)
- **Kernel**: 6.15.7-arch1-1
- **Desktop**: KDE Plasma 6.4.3

### Python Environment
- **Conda**: Miniconda
- **Python Version**: 3.12.9
- **Base Environment**: miniconda
- **Active Environment**: base

### Cloud Storage
- **Google Drive**: 
- **Proton Drive**: 
- **Auto-mount**: Enabled (systemd services)

## Performance Constraints

### Memory Limitations
- **Effective Available RAM**: ~3.2 GB for new processes
- **Memory Pressure**: HIGH (12/15 GB used)
- **No Swap**: System relies entirely on physical RAM


### Currently Running Heavy Processes
- FFXIV DirectX 11: ~1.9 GB VRAM
- Desktop Environment: ~722 MiB VRAM
- Steam/Gaming processes: Multiple instances

### Resource Allocation Recommendations
- **Maximum RAM per process**: ~2-3 GB
- **Maximum VRAM usage**: <1 GB for new processes
- **Disk usage**: Conservative (<10 GB for temporary files)

## Development Environment Ready
- Python 3.12.9 available
- CUDA 12.9 support
- KDE Plasma shortcuts functional
- Cloud drives mounted and accessible
