# Assignment2-ICIT-
CPU VS GPU VS TPU VS NPU


Introduction

For a long time, one chip did almost everything inside a computer. Today that is no longer true. As games, video editing, and artificial intelligence demanded more and more power, engineers began building processors for specific jobs. The four most important ones are the CPU, the GPU, the TPU, and the NPU. This assignment explains what each one does, and then compares them by looking at what they have in common and where they differ.

CPU

The CPU, or central processing unit, is the part of a computer that does most of the everyday thinking. When you open a browser, type in a document, or start up your operating system, the CPU is the one handling it. It has only a handful of cores, usually somewhere between four and sixteen in a normal laptop or desktop, but each of those cores is very fast and very flexible. It can jump from one kind of task to another without much trouble, and it is good at jobs where every step depends on the one before it.
The catch is that a CPU does things one after another, or at best a few at a time. If you ask it to do millions of small, identical calculations, it gets slow, because it was never designed for that. That weakness is the reason the other three chips exist.

GPU

The GPU, or graphics processing unit, was first made to draw pictures on a screen. Drawing an image means doing the same small calculation for millions of pixels, so engineers built chips with thousands of tiny cores that all work at the same time. One of those cores is weak compared to a CPU core, but thousands of them together can chew through huge amounts of simple work very quickly.
Later, people noticed that training AI models involves exactly this kind of work, mostly multiplying big tables of numbers. GPUs turned out to be perfect for it, and that is a big reason AI took off in the last decade. Today they are used for gaming, video editing, scientific simulations, and training large AI models. The downsides are that they use a lot of power, they can be expensive, and they are not much use for tasks that cannot be split into many small pieces.

TPU

The TPU, or tensor processing unit, was created by Google. Google was running so much AI work in its data centers that even GPUs were not efficient enough, so it designed its own chip built around one thing: the matrix math that neural networks rely on. Inside a TPU, data flows through a grid of calculation units in a steady rhythm, so results get passed along directly instead of constantly going back and forth to memory. This saves both time and energy.
For the specific job it was built for, a TPU can be very fast and use less power than a GPU. The trade-off is flexibility. It does not handle general tasks well, and most people can only use TPUs through Google's cloud services. They matter most to the companies and researchers training very large AI models, not to the average person at home.

NPU

The NPU, or neural processing unit, is the one you are most likely to be carrying around without knowing it. It is a small chip built into phones, newer laptops, and other devices, and its job is to run AI features without draining the battery. Things like face unlock, voice assistants, live translation, photo enhancement, and blurring your background on a video call often run on it.
NPUs are designed mainly for inference, which means using an AI model that has already been trained rather than training a new one. They are not nearly as powerful as a big GPU, but they are very efficient. Because the work happens on the device itself, it is also faster for the user, and personal data like photos or voice recordings does not have to be sent to a server.


Similarities and Differences

Similarities

All four chips are processors, which means they take in data, perform calculations on it, and send back results. They are all built from billions of tiny transistors on silicon, and all of them follow instructions written in software. They also work together rather than separately. A single device or data center often uses several of them at once, with the CPU managing the overall program and handing specific jobs to the others. Finally, each one exists to solve the same basic problem: getting more work done faster while using less energy.

Differences

The biggest difference is how specialized each chip is. The CPU is the generalist and can run almost any kind of task, but it handles only a few things at a time. The GPU trades some of that flexibility for thousands of small cores that work in parallel, which makes it far better at large, repetitive workloads like graphics and AI training. The TPU goes further and is designed almost entirely around the matrix math used in neural networks, which makes it very efficient at that one job but not useful for much else. The NPU is similar in spirit but built for small devices, focusing on running trained AI models using very little battery.
They also differ in where they are found. CPUs are in nearly every computer, phone, and gadget. GPUs are in gaming PCs, workstations, and data centers. TPUs are mostly in Google's data centers and accessed through its cloud. NPUs are built into phones and newer laptops.
Power use and purpose differ too. GPUs and TPUs are made for heavy, large-scale work like training AI models and consume a lot of power. NPUs are designed for light, everyday AI tasks and sip energy. CPUs sit in the middle, balanced for general use.

Conclusion

In short, the CPU is the flexible all-rounder, the GPU is the parallel powerhouse, the TPU is the data-center specialist for AI, and the NPU is the efficient AI helper in everyday devices. None of them replaces the others. Modern technology works best when each chip handles the kind of work it was designed for, and that idea of matching the hardware to the job is likely to keep shaping how computers are built in the future.
