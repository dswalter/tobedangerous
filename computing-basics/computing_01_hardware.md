You don't need to how to sodder your own circuits to conduct statistical anaylses, but a general idea of the parts of a computer and how they fit together will come up frequently, so you might as well get familiar. 

## Parts:

### Motherboard
This is the Central Nervous system for the computer. Everything plugs into the motherboard, which distributes power and communicates between parts. It allows the CPU to communicate with everything, from powering on to running the operating system to telling the fans when to cool things off.

### Processer, also called the CPU. 
The CPU is the brain of the computer. It's a computer chip (usually designed by Intel or AMD) that actually performs the computations you want out of your computational device. Your chip may have multiple threads, which allows it to perform more than one task at a time (we'll talk more about parallel processing later). In general, more threads are better (and more expensive) than fewer threads, but the gains are seldom linear (4 threads is almost never exactly 4 times faster than 1, for reasons.) It used to be that if you wanted a computer capable of doing statistical or machine learning computations quickly, you'd want to spend a lot of money on the processor. That calculus has changed slightly in the era of the GPU, most processors these days are plenty fast. Just make sure you get one that plays well with a GPU if you're going to be doing deep learning. 

### Graphics Card, also called the GPU or Video Card
Graphics cards are chips that are specialized for performance on video games. The CPU is a great generalist, but it has to compromise performance in certain ways to accomodate the many different tasks it has to perform as the brain of the computer. A dedicated graphics card doesn't have to worry about as many things, so they are designed to perform many parallel matrix multiplications simulateously (something required for correctly shading objects in a video game). Fortuitously, that same capability is tremendously useful in machine learning (and especially deep learning, which requires a lot of matrix multiplication). GPU computing in the hard sciences had been going on for over a decade already, but in 2012, GPU computing hit the mainstream with Krizhevsky et al.'s 2012 ImageNet paper. (LINK).


### Hard drive (HDD or SSD)
You probably already have a good handle on what the hard drive does; it's where you storey your information. The hard drive is like a filing cabinet. 
Solid state drives use flash memory rather than spinning disks, since it doesn't have to wait for the part of the disk it was reading from to spin back into view. Unless you're on a really tight budget, you want to make sure you're doing work on a computer with a solid state drive, rather than an HDD. Having an SSD makes it much faster every time you grab something from the filing cabinets. 


### Memory (RAM)
Leaving biology for a second:

I like the metaphor of desk space for RAM. ram is the quick-access memory that the computer uses to store information you are currently working with. If you were to spread a bunch of papers on a desk, the amount of ram would be the size of the desk. 
If you have a substantial amount of ram, you

It can store a lot more than you can store on your desk, but if you have to keep going back and pulling information from files, it's going to be slow.


### Power supply
Each part of the computer requires electricity to run. The power supply takes power from where you plugged it in and


### Monitor/Screen


### Keyboard


### Input device

General computer-buying advice:
It used to be more cost-effective to buy the pieces for a computer and put it together yourself. These days, it's not necessarily tons of advantage, since you're getting a price markup for each component. There's a decent chance you could put a desktop together that performs well and has exactly what you want. But because of the GPU revoluation in machine learning, a deep learning researcher has very similar build requirements as a serious PC gamer, so you can just buy a gaming laptop (buy one with an NVIDIA GPU because of CUDA).


