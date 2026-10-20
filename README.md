<div align="center">

<img src="./banner.svg" alt="Aymaan, Electrical Engineering at McMaster. From RTL to silicon." width="100%"/>

<a href="https://github.com/denvercoder1/readme-typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=3DFFB5&center=true&vCenter=true&width=640&height=40&lines=RTL+Design+%26+Verification;Logic+Synthesis+%26+Static+Timing+Analysis;CDC+%26+FIFO+Design;DFT+%26+Physical+Design" alt="Typing animation of my focus areas" />
</a>

<br/>

![Verilog](https://img.shields.io/badge/Verilog-0d1a26?style=for-the-badge&labelColor=0d1a26&color=3dffb5)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-0d1a26?style=for-the-badge&labelColor=0d1a26&color=3dffb5)
![TCL](https://img.shields.io/badge/TCL-0d1a26?style=for-the-badge&labelColor=0d1a26&color=3dffb5)
![Synopsys](https://img.shields.io/badge/Synopsys-0d1a26?style=for-the-badge&labelColor=0d1a26&color=7fa8b8)
![Cadence](https://img.shields.io/badge/Cadence-0d1a26?style=for-the-badge&labelColor=0d1a26&color=7fa8b8)
![McMaster](https://img.shields.io/badge/McMaster_University-0d1a26?style=for-the-badge&labelColor=0d1a26&color=7a003c)

</div>

---

## 👋 About me

Third-year Electrical Engineering student at **McMaster University**, building toward a career in **ASIC/FPGA design and digital hardware**. I like the whole path a design takes, from a blank Verilog file to a placed and routed chip.

```verilog
module aymaan (
    input  wire clk,
    input  wire rst_n,
    output reg  [7:0] learning
);
    // always be shipping
    always @(posedge clk or negedge rst_n) begin
        if (!rst_n) learning <= 8'd0;
        else        learning <= learning + 1'b1;
    end
endmodule
```

<br/>

## 🧭 The flow I'm working through

<img src="./flow.svg" alt="Chip design flow: RTL, Synthesis, STA, DFT, PnR, GDSII" width="100%"/>

<br/>

## 🔬 What I'm into

| | |
|---|---|
| 🧩 **RTL Design** | Verilog and SystemVerilog |
| ⚙️ **Logic Synthesis** | RTL to gate-level netlist |
| ⏱️ **Static Timing Analysis** | Finding and fixing timing problems |
| 🔀 **CDC and FIFO Design** | Moving data safely between clocks |
| 🧪 **Design for Test** | Making chips testable |
| 🔋 **Low-Power VLSI** | Spending fewer picojoules |
| 🗺️ **Physical Design** | Place-and-route |

<br/>

## 📚 Currently learning

```text
[##########] Verilog / SystemVerilog, from syntax to complex systems
[########--] TCL scripting for design constraints
[########--] Timing analysis: STA concepts, analysis and fixes
[#######---] Low-power VLSI design fundamentals
[#######---] Logic synthesis: RTL to gate-level netlist
[######----] CDC and FIFO design
[#####-----] Design for Test (DFT)
[####------] Formal verification (Synopsys Formality flow)
[####------] Physical design with Cadence (PnR)
```

<br/>

## 💼 Experience

| Role | Where |
|---|---|
| 🔧 Reliability & Maintenance Engineering Intern | **Sofina Foods** |
| 🎓 B.Eng. Electrical Engineering | **McMaster University** |

<br/>

<!--
OPTIONAL: GitHub stats. Swap YOUR_USERNAME for your GitHub username, then delete this comment wrapper.

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&hide_border=true&bg_color=0d1a26&title_color=3dffb5&icon_color=3dffb5&text_color=c9d4dc" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&hide_border=true&bg_color=0d1a26&title_color=3dffb5&text_color=c9d4dc" />
</div>
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1020,100:1c6b59&height=120&section=footer&text=From%20RTL%20to%20silicon.&fontColor=3dffb5&fontSize=24&fontAlignY=70" width="100%" alt="From RTL to silicon."/>

</div>
