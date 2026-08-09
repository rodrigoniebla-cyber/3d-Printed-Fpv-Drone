# 3D printed Fpv Drone — 3D Printed FPV Frame (2S, DJI O4 Pro)


## What is this?

A custom 3D-printed FPV drone frame built around a 2S battery and the DJI O4 Pro
digital video system. This drone frame will allow for a 4k 100 fps resolution while remaining just under $400 and without sacrificing performance or camera quality.
<img width="2560" height="1664" alt="image" src="https://github.com/user-attachments/assets/ee0a6f74-23b8-4101-923c-2b7b3e732db9" />

## Why I built it

I wanted to make this drone because, while researching 3D-printed drone frames, there just weren't any options that allowed for a budget build with the O4 Pro camera. This led me to want to create this project: a 3D-printable, economical drone that maintains performance and quality.

## Specs

| | |
|---|---|
| Frame size | "2.5" |
| Battery | 2S LiPo, |
| VTX/Camera | DJI O4 Pro |
| AIO board | Happymodel SuperX HD AIO |
| Motors | BETAFPV Aquila20 Motors 1103 10500KV |
| Propellers | "2.2", Gemfan 3 blade |

## How to build it

1. Print the frame parts — see `CAD/` for source files and `.STL` exports.
2. Solder the motors onto the AIO and connect the O4 Pro via the provided cable. You will have to cut one end and solder the wires this way: <img width="1000" height="1000" alt="wiring for 04" src="https://github.com/user-attachments/assets/6397011f-7441-4a11-9c79-c3ca31d0ecd8" />  <img width="1170" height="1024" alt="oscar lian" src="https://github.com/user-attachments/assets/71569b26-8994-4442-b1a3-1f786e807aaa" />


3. Use the included screws to fasten the AIO to the frame, also using the printed plate <img width="2560" height="1664" alt="image" src="https://github.com/user-attachments/assets/9c84b36e-9112-4cad-a624-d9fc1542351c" />

4. PID tuning and others will be added once it is physically built.
5. The o4 mounting will not require screws rather the print will be paused, a spacer inserted then sealed by the print itself so that it is print in place the spacer is shown below.
   <img width="2256" height="1466" alt="image" src="https://github.com/user-attachments/assets/7665f9a8-ddfb-405b-8fbd-0fa857ccf12b" />


## Files in this repo

- `CAD/` — native Fusion 360 source (`.f3d`) and exported `.STEP` / `.STL` files
- `BOM/` — bill of materials (CSV) with buy links
- `Media/` - screenshots of the project
## Credits
For the 3d model of the motors: 
MultiBuild3D https://grabcad.com/library/1102-betafpv-drone-motor-1 

For the model of the O4 Pro: 
Riley Entropy https://grabcad.com/library/dji-o4-air-unit-pro-1

For the wiring diagrams, Oscar Liang and HappyModel:
oscarliang.com

https://www.happymodel.cn/index.php/2023/09/04/superx-hd-elrs-1-2s-aio-flight-controlelr-built-in-12a-esc-and-uart-elrs-receiver-for-digital-whoop/

## Known issues / in progress

PID tuning and specific wiring diagram will be implemented once the drone is finalized.

