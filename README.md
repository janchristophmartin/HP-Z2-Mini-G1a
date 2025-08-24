# HP-Z2-Mini-G1a
HP Z2 Mini G1a Workstation with Ryzen AI Max+ and Radeon RX 8060S - Mods &amp; Setup Notes


 HP Z2 Mini G1a Workstation - SSD Upgrade and Cooling

My HP Z2 Mini G1a came with a Samsung 2TB NVME SSD which is far below my internal storage needs, and I wanted to make use of the second M.2 NVME slot on the mainboard. While the service guide clearly lists the part number P33960-001 for a separate heatsink, it was nowhere to obtain in Germany and HP's part picker listed it at more than 60€ which I found a bit steep.

Opening the case made clear, that there's not much space between the SSDs and the fans for the CPU heatsink. Plus the original heatsink appears quite flimsy with a height of just around 3.5 mm and the bracket being the closest part to the fan underside.

So here's my final recommendation after trying out several third-party SSD heatsinks:
Go for the BeQuiet! MC1, it should leave slightly more space to the fans than the original - even with the supplied 1mm thermal pads. At the same time, it appears a bit beefier (5mm height) than the original heatsink (3.5mm height). Plus, it supports dual-sided SSDs with its metal bracket design.

Some quick temperature testing with Sandisk Dashboard and CrystalDiskMark in an otherwise idle system show peak temperatures below 50°C, going back to 40°C CPU temperature level within less than a minute.

No recommendation for:

    BeQuiet! MC1 Pro: collides with the fan housing by almost 2mm, even with 0.5 mm thermal pads

    EZDIY-FAB: touches the fan housing, even with the original 0.5 mm thermal pads
