# Quickstart
<details><summary>Linux</summary>

1. Clone repository:
```
git clone --recursive https://github.com/Kordyban-Roman-CLG/My3DViewer.git
```
```
cd ./My3DViewer
```
2. Bootstrap vcpkg
```
sh ./vcpkg/bootstrap-vcpkg.sh
```
3. Integrate vcpkg
```
./vcpkg/vcpkg integrate install
```
4. Install dependencies
```
./vcpkg/vcpkg install
```
```
sudo apt-get update && sudo apt-get install -y libxinerama-dev libxcursor-dev xorg-dev libglu1-mesa pkg-config libglfw3
```
</details>
<details><summary>Windows</summary>
  
1. Clone repository:
```
git clone --recursive https://github.com/Kordyban-Roman-CLG/My3DViewer.git
```
```
cd .\My3DViewer
```
2. Bootstrap vcpkg
```
.\vcpkg\bootstrap-vcpkg.bat
```
3. Integrate vcpkg
```
.\vcpkg\vcpkg.exe integrate install
```
4. Install dependencies
```
.\vcpkg\vcpkg install
```
</details>
