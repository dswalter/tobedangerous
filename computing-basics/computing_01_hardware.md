You don't need to how to solder your own circuits to conduct data analyses, but a general idea of the parts of a computer and how they fit together will come up frequently, so you might as well get familiar. 

## Parts:

### Motherboard 

![motherboard](https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/HP-HP9000-715-50-Workstation-Motherboard_08.jpg/320px-HP-HP9000-715-50-Workstation-Motherboard_08.jpg)


This is the central nervous system for the computer. Everything plugs into the motherboard, which communicates between parts. It allows the CPU to talk the other parts of the computer about everything from powering on to running the operating system to telling the fans when to cool things off.

### CPU (short for Central Processing Unit, also known as "processor"). 
![CPU](https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Intel_CPU_Pentium_4_640_Prescott_bottom.jpg/320px-Intel_CPU_Pentium_4_640_Prescott_bottom.jpg)

The CPU is the brain of the computer. It's a computer chip (often designed by Intel or AMD) that actually performs the computations you want out of your computational device. Your chip may have multiple threads, which allows it to perform more than one task at a time (we'll talk more about parallel processing later). In general, more threads are better (and more expensive) than fewer threads, but the gains are seldom linear (4 threads is almost never exactly 4 times faster than 1, for reasons.) It used to be that if you wanted a computer capable of doing statistical or machine learning computations quickly, you'd want to spend a lot of money on the processor. That calculus has changed slightly in the era of the GPU; most processors these days are plenty fast. Just make sure you get one that plays well with a GPU if you're going to be doing deep learning. 

### Graphics Card, also called the GPU or Video Card
![GPU](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/ASUS_GTX-650_Ti_TOP_Cu-II_PCI_Express_3.0_x16_graphics_card.jpg/320px-ASUS_GTX-650_Ti_TOP_Cu-II_PCI_Express_3.0_x16_graphics_card.jpg)

Graphics cards are chips that are specialized for performance on video games. The CPU is a great generalist, but it has to compromise performance in certain ways to accomodate the many different tasks it has to perform as the brain of the computer. A dedicated graphics card doesn't have to worry about as many things, so they are designed to perform many parallel matrix multiplications simulateously (something required for correctly shading objects in a video game). Fortuitously, that same capability is tremendously useful in machine learning (and especially deep learning, which requires a lot of matrix multiplication). GPU computing in the hard sciences had been going on for over a decade already, but in 2012, GPU computing hit the mainstream with Krizhevsky et al.'s 2012 ImageNet paper. (LINK).

### Hard drive (HDD or SSD)
![HDD_vs_SSD](https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Disassembled_HDD_and_SSD.JPG/640px-Disassembled_HDD_and_SSD.JPG)

You probably already have a good handle on what the hard drive does; it's where you store your information. The hard drive is like a filing cabinet. 
Solid state drives use flash memory rather than spinning disks, since it doesn't have to wait for the part of the disk it was reading from to spin back into view. Unless you're on a really tight budget, you want to make sure you're doing work on a computer with a solid state drive, rather than an HDD. Having an SSD makes it much faster every time you grab something from the filing cabinets. 

### Random Access Memory, also called RAM or just 'memory'
![RAM](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3c/DDR_RAM-3.jpg/320px-DDR_RAM-3.jpg)

I like the metaphor of desk space for RAM. RAM is the quick-access memory that the computer uses to store information you are currently working with. If you were to spread a bunch of papers on a desk, the amount of ram would be the size of the desk. 
If you have a substantial amount of ram, you can keep many things on your desk at once. In data science, this means you can perform analyses or fit models on much larger datasets quickly and easily. RAM is also flash memory, but it's much fatser than an SSD, since it doensn't store as much. You can't always keep your dataset in RAM because of $$, but it's always nice when you can. 

It can store a lot more than you can store on your desk, but if you have to keep going back and pulling information from files, it's going to be slow.

### Power supply
![PSU](https://upload.wikimedia.org/wikipedia/commons/thumb/2/24/OCZ_600W_power_supply_unit.JPG/320px-OCZ_600W_power_supply_unit.JPG)

Each part of the computer requires electricity to run. The power supply takes power from where you plugged it in and provides power directly (to the hard disk and graphics card) or through the motherboard (to the CPU and RAM).


General computer-buying advice:
It used to be more cost-effective to buy the pieces for a computer and put it together yourself. These days, it's not necessarily tons of advantage, since you're getting a price markup for each component. There's a decent chance you could put a desktop together that performs well and has exactly what you want. But because of the GPU revoluation in machine learning, a deep learning researcher has very similar build requirements as a serious PC gamer, so you can just buy a gaming laptop (buy one with an NVIDIA GPU because of [CUDA](http://www.nvidia.com/object/cuda_home_new.html)).


