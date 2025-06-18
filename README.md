<div align="center">
  <a href="https://github.com/ShaikhEamin">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&pause=1000&color=E0DEF4&center=true&width=600&lines=Hi%2C+I'm+Shaikh+Eamin+👋;RTL+Designer+%7C;Quantum+Security+Analyst;Pioneering+Quantum-Resistant+Hardware" alt="Typing SVG" />
  </a>
</div>

<p align="center">
  <a href="https://github.com/ShaikhEamin?tab=repositories"><img src="https://img.shields.io/badge/Projects-302D41?style=for-the-badge&logo=googledocs&logoColor=c9cbff"></a>
  <a href="https://www.linkedin.com/in/shaikh-eamin/"><img src="https://img.shields.io/badge/LinkedIn-302D41?style=for-the-badge&logo=linkedin&logoColor=c9cbff"></a>
  <a href="mailto:Eamineee19@gmail.com"><img src="https://img.shields.io/badge/Email_Me-302D41?style=for-the-badge&logo=gmail&logoColor=c9cbff"></a>
  <a href="#-my-digital-footprint"><img src="https://img.shields.io/badge/More-302D41?style=for-the-badge&logo=read-the-docs&logoColor=c9cbff"></a>
</p>

---

<table width="100%" border="0">
<tr valign="top">
<td width="65%">

### <a id="-about-me"></a>👨‍💻 About Me
I am an Electrical Engineer obsessed with the future of computing. My expertise lies in designing and verifying **RTL for high-performance, low-power hardware** and analyzing **post-quantum cryptographic systems**. I thrive on complex challenges, whether it's optimizing a Verilog module for nanosecond-level performance or developing protocols to secure data against quantum threats.

<br>

### <a id="-the-now-section"></a>💡 The "Now" Section

<table width="100%">
<tr valign="top">
<td width="50%">
  **Current Focus**
  - Advanced Low-Power VLSI Methodologies
  - Lattice-Based Cryptography
  - Rust for Embedded Systems

  **Currently Reading**
  - 📖 *Quantum Computing for Computer Scientists* by N. Yanofsky
</td>
<td width="50%">
  **My Local Time**
  <div>
    <a href="https://time.is/Khulna_Bangladesh" title="Time in Khulna, Bangladesh">
      <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&logo=clock&logoColor=white&label=Local%20Time&query=%24.time&url=https%3A%2F%2Fworldtimeapi.org%2Fapi%2Ftimezone%2FAsia%2FDhaka" alt="My Local Time">
    </a>
  </div>

  **Currently Listening**
  <div>
    <a href="https://open.spotify.com/user/your-spotify-user-id" title="My Spotify">
      <img src="https://spotify-now-playing-yourusername.vercel.app/api/spotify" alt="Spotify Now Playing" width="350">
    </a>
  </div>
</td>
</tr>
</table>

<br>

### 🚀 Featured Project: Quantum-Resistant Protocol
*A low-power cryptographic protocol designed for secure IoT communication in a post-quantum world.*
<details>
<summary>Click to view architecture & details</summary>

Here's a simplified view of the key exchange process:

```mermaid
graph TD
    A[IoT Device] -->|Public Key + Encrypted Nonce| B(Server);
    B -->|Generates Session Key| B;
    B -->|Encrypted Session Key| A;
    A -->|Decrypts & Verifies| A;
    A <-->|Secure Communication| B;

    style A fill:#31748f,stroke:#333,stroke-width:2px
    style B fill:#e69875,stroke:#333,stroke-width:2px
