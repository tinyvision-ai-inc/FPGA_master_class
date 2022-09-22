# Hands on FPGA Class

Hardware design and more narrowly, digital electronics forms the basis for almost all devices that modern society takes for granted. We believe in learning by doing and have put together a progression of topics as well as a curated list of resources to help students to get a quick introduction to the field. This is not a substitute for a more formal and deeper course that may be found at a University. Focus is on learning by doing and getting an intuitive understanding of how things work.

This course augments the excellent series on an [Introduction to FPGA's by Shawn Hymel](https://github.com/ShawnHymel/introduction-to-fpga) as well as many other introductory FPGA courses. As such, it is not really a course in itself according to the traditional definition, but rather a collection of pointers to relevant material so students can choose to learn from a variety of resources in whatever way works best for them.

This course is a self-paced, hands-on class and we hope that by the time you complete all the modules, you will have gained an understanding of how digital electronics works at a level sufficient to put together simple projects on your own. The course has a broad audience of learners from a typical high school level upwards.

## Hardware

Access to an FPGA board is not essential and we have identified a few online simulators that can provide as close an experience as possible to a real world FPGA. However, there is no substitute for playing with real hardware and experiencing the non-idealities of the real world where real learning happens.

We will use the open-source [UPDuino](https://github.com/tinyvision-ai-inc/UPduino-v3.0) as the FPGA platform which you can purchase directly from [www.tinyVision.ai](https://tinyvision.ai/products/upduino-v3-1), [Lectronz](https://lectronz.com/products/upduino-v3-1-low-cost-lattice-ice40-fpga-board) (for EU orders) or [Tindie](https://www.tindie.com/products/tinyvision_ai/upduino-v31-low-cost-lattice-ice40-fpga-board/).

If the UPDuino is out of stock or otherwise unavailable, there are alternative FPGA boards that will allow you to follow along with most of the material.
The UPDuino has a lattice iCE40-UP5K FPGA, purchasing a board that does as well is the best way to ensure a similar experience. Other boards/FPGAs are supported by the open source toolchains to varying degrees.  
A good resource for selecting one of the more affordable options as well as a guide on what the differences are, is detailed in this [fantastic blog post by Joel Williams](https://joelw.id.au/FPGA/CheapFPGADevelopmentBoards). That being said, due to the unique quirks of every board, unforseen problems/difficulties may occur. We are not able to offer support for 3rd party boards, in other words **Your mileage may vary**.  

## Course Methodology
The pace of this course can be varied significantly depending on your time availability and committment. Each module is intended to take a few hours overall to go through the reading material and also perform the experiments on hardware. Initial modules focus on providing the student with resources to get up and running on the hardware as well as environment setup which can be challenging. We will rely as much as possible on open-source tools to enable the audience to be as wide as possible.

The material should ideally be augmented by weekly interactions with a teacher/expert in the field. We plan to use weekly online AMA (Ask-Me-Anything) sessions following the format below:
1. Introduction to the upcoming topic
2. Real world examples of what the topic would be useful for to help students understand why they wouild want to learn the topic
3. Intuitive understanding of the topic where applicable
4. Open floor to questions/feedback from the previous week.

## Weekly Modules

### [Week 1: What is an FPGA and Toolchain setup](Week1.md)

### [Week 2: Getting started with Verilog, logic design](Week2.md)

### [Week 3: Clocks, verilog experimentation](Week3.md)

### [Week 4: State machines](Week4.md)

### [Week 5: Memories: RAM, ROM](Week5.md)

### [Week 6: Interfacing with the real world: Digital systems architecture](Week6.md)

### [Week 7: Interfacing with the real world: Clock domain crossings, reusing code/IP](Week7.md)

### [Week 8: Interfacing with the real world: HDL Alternatives, and useful projects](Week8.md)

## [Resource list](/resource_list.md)
 A curated collection of various sites/books/videos/tutorials and more to help guide those wanting to learn about FPGAs but not quite sure where to begin.
 The list is an abbreviated subset of [the more detailed google sheet](https://bit.ly/Learn_FPGA).
 
 Anything not already listed that is relevant to FPGAs? [Please let us know](https://forms.gle/zcpHWAm1DT5WMZzA8) so it can be shared with fellow learners

# License
All code in this repository, unless otherwise noted, is licensed under the Zero-Clause BSD / Free Public License 1.0.0 (0BSD).

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
