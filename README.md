<p align="center">
  <img src="assets/banner.svg" alt="Hi, I'm Tahir. Computer Engineer, NUST CEME, 2020 to 2024" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17">
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" alt="WebAssembly">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
</p>

I'm a Computer Engineering graduate from **NUST College of Electrical & Mechanical Engineering** (BE, 2020–2024). I like building things from first principles: a 3D renderer that doesn't touch the GPU, a CPU you can watch execute instructions one clock cycle at a time, a logic simulator that minimises its own circuits.

**How I build:**
- The core of every project is plain **C++ or Python**, with unit tests.
- It's compiled to **WebAssembly**, so it runs entirely in your browser: no server, and nothing to install.
- Each project is one course from my degree, rebuilt as something you can open and use.

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/software-3d-renderer"><img src="assets/06-renderer.png" alt="Software 3D renderer: intersecting cube, sphere and torus on a chequered floor"></a>
      <h3>Software 3D Renderer</h3>
      <p>A complete rendering pipeline written from scratch, <b>with no GPU</b>:</p>
      <ul>
        <li>clipping in homogeneous space;</li>
        <li>scan-line rasterisation and a z-buffer;</li>
        <li>flat, Gouraud and Phong shading;</li>
        <li>perspective-correct textures;</li>
        <li>a pixel inspector.</li>
      </ul>
      <p>It also has an algorithm lab that animates Bresenham, the midpoint circle, scan-line fill and clipping.</p>
      <sub><b>EC-301 Computer Graphics</b> · C++ → WebAssembly · React</sub><br>
      <a href="https://github.com/tahirbuild/software-3d-renderer">Code</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/skin-lesion-analyzer"><img src="assets/03-skin-lesion.png" alt="Skin lesion analyzer showing the segmentation steps and a classification"></a>
      <h3>Skin Lesion Analyzer</h3>
      <p>It segments a skin lesion in a dermoscopic image and classifies it into six classes, including <b>basal and squamous cell carcinoma</b>.</p>
      <ul>
        <li>A classical image-processing pipeline (hair removal, Otsu thresholding, morphology).</li>
        <li>A MobileNetV3 CNN.</li>
        <li>Everything runs in the browser through Pyodide and ONNX Runtime.</li>
      </ul>
      <sub><b>EC-312 Digital Image Processing</b> · Python · OpenCV · PyTorch · ONNX</sub><br>
      <a href="https://github.com/tahirbuild/skin-lesion-analyzer">Code</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/mips-simulator"><img src="assets/04-mips.png" alt="MIPS simulator with source code and an animated datapath"></a>
      <h3>MIPS Single-Cycle Simulator</h3>
      <p>Write MIPS assembly, assemble it, and step through execution one clock cycle at a time. An animated datapath shows the value on every wire and every control signal.</p>
      <p>It includes a two-pass assembler with pseudo-instructions, MARS-style syscalls and step-back.</p>
      <sub><b>EC-120 Computer Organization</b> · C++ → WebAssembly · React</sub><br>
      <a href="https://github.com/tahirbuild/mips-simulator">Code</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/logic-circuit-simulator"><img src="assets/05-logic.png" alt="Logic circuit simulator showing a BCD to 7-segment decoder"></a>
      <h3>Logic Circuit Simulator</h3>
      <p>Build circuits from gates and flip-flops and watch them simulate live, with truth tables and timing diagrams.</p>
      <ul>
        <li>A K-map and Quine–McCluskey minimiser that shows its working, including Petrick's method.</li>
        <li>One click turns a minimised expression into a working circuit.</li>
      </ul>
      <sub><b>EC-210 Logic Design</b> · C++ → WebAssembly · React</sub><br>
      <a href="https://github.com/tahirbuild/logic-circuit-simulator">Code</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/vector-drawing-editor"><img src="assets/02-vector-editor.png" alt="Vector drawing editor with shapes, layers and an inspector"></a>
      <h3>Vector Drawing Editor</h3>
      <p>Draw, group, restyle and reorder shapes, with unlimited undo and redo and SVG export.</p>
      <p>It's an object-oriented C++ design: a polymorphic shape hierarchy, the Composite pattern for groups, and the Command pattern for undo.</p>
      <sub><b>CS-212 Object Oriented Programming</b> · C++ → WebAssembly · React</sub><br>
      <a href="https://github.com/tahirbuild/vector-drawing-editor">Code</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/tahirbuild/student-grade-manager"><img src="assets/01-grade-manager.png" alt="Student grade manager with a table of students, grades and GPA"></a>
      <h3>Student Grade Manager</h3>
      <p>Stores student records, computes letter grades and credit-weighted GPA, and searches, sorts and saves them.</p>
      <p>The same C++ builds a classic console program and a web app.</p>
      <sub><b>CS-114 Fundamentals of Programming</b> · C++ → WebAssembly · React</sub><br>
      <a href="https://github.com/tahirbuild/student-grade-manager">Code</a>
    </td>
  </tr>
</table>

<p align="center"><sub>More coming, one per course: data structures, computer architecture (caches and pipelines), and more.</sub></p>
