<h1>Hardware Security Lab Report</h1>

<h2>Side-Channel Analysis & Fault Injection Experiments</h2>

<p>
  This repository contains a lab report completed as part of my
  <strong>Hardware Security course</strong>. This lab and report were written by self -
  <strong>Assan Jallow</strong> and <strong>Abian Morina</strong>.
  The labs focus on practical hardware security attacks using the
  <strong>ChipWhisperer</strong> platform, including side-channel analysis,
  AES power analysis, and fault injection through clock glitching.
</p>

<hr>
<h2>Github Repository to Lab Files</h2>

<p>
Link -- > https://github.com/newaetech/chipwhisperer-jupyter/tree/main
</p>
<hr>
<h2>📘 Overview</h2>

<p>
  The purpose of this lab report is to demonstrate how embedded systems can
  leak sensitive information through physical behavior such as power
  consumption and timing, and how attackers can manipulate device execution
  using fault injection techniques.
</p>

<p>
  The experiments were performed on embedded firmware running on
  microcontrollers, mainly using ChipWhisperer for trace capture, power
  analysis, and glitch generation.
</p>

<hr>

<h2>🔬 Lab Topics Covered</h2>

<h3>Side-Channel Analysis</h3>

<ul>
  <li>Simple Power Analysis for password recovery</li>
  <li>Hamming Weight leakage observation</li>
  <li>Recovering data from single-bit leakage</li>
  <li>Differential Power Analysis on AES</li>
  <li>Correlation Power Analysis on AES</li>
  <li>AES-128 key recovery from power traces</li>
</ul>

<h3>Fault Injection</h3>

<ul>
  <li>Introduction to clock glitching</li>
  <li>Fault injection on embedded firmware</li>
  <li>Password authentication bypass</li>
  <li>Glitch parameter sweeping</li>
  <li>Fault detection and countermeasures</li>
</ul>

<hr>

<h2>🛠 Tools & Technologies</h2>

<ul>
  <li>ChipWhisperer</li>
  <li>Python</li>
  <li>TinyAES128-C</li>
  <li>XMEGA Microcontrollers</li>
  <li>Power trace analysis</li>
  <li>Statistical leakage analysis</li>
  <li>Clock glitching</li>
</ul>

<hr>

<h2>🚀 Key Lab Exercises</h2>

<h3>1. Password Recovery Using Power Analysis</h3>

<p>
  In this lab, a password verification routine was analyzed using
  <strong>Simple Power Analysis</strong>. By observing differences in power
  traces during character-by-character password checks, the password could be
  recovered one character at a time.
</p>

<h3>2. AES Key Recovery Using DPA</h3>

<p>
  Differential Power Analysis was used to attack an AES firmware
  implementation. The attack relied on power leakage from AES S-box operations
  and showed how key-dependent intermediate values can be recovered from power
  traces.
</p>

<h3>3. AES Key Recovery Using CPA</h3>

<p>
  Correlation Power Analysis was performed using a Hamming Weight leakage
  model. By comparing predicted leakage values with measured power traces, the
  AES-128 key could be recovered efficiently.
</p>

<h3>4. Clock Glitching Fault Injection</h3>

<p>
  Clock glitching was used to introduce timing faults into embedded firmware.
  These faults caused incorrect program behavior, including successful password
  authentication bypass under specific glitch parameters.
</p>

<hr>

<h2>📊 Learning Outcomes</h2>

<ul>
  <li>Understanding how embedded devices leak information physically</li>
  <li>Learning practical side-channel attack techniques</li>
  <li>Using statistical methods to recover cryptographic keys</li>
  <li>Exploring fault injection and clock glitching attacks</li>
  <li>Understanding the importance of secure implementation design</li>
  <li>Studying countermeasures against physical attacks</li>
</ul>

<hr>

<h2>🛡 Countermeasures Discussed</h2>

<ul>
  <li>Masking techniques</li>
  <li>Constant-time execution</li>
  <li>Noise injection</li>
  <li>Redundant execution</li>
  <li>Fault detection mechanisms</li>
  <li>Secure boot and integrity checking</li>
  <li>Hardware-level protections</li>
</ul>

<hr>

<h2>📄 Report Information</h2>

<table>
  <tr>
    <td><strong>Course</strong></td>
    <td>Hardware Security</td>
  </tr>
  <tr>
    <td><strong>Report Title</strong></td>
    <td>Side-Channel Analysis and Fault Injection Experiments</td>
  </tr>
  <tr>
    <td><strong>Authors</strong></td>
    <td>Assan Jallow and Abian Morina</td>
  </tr>
  <tr>
    <td><strong>Date</strong></td>
    <td>March 2026</td>
  </tr>
</table>

<hr>

<h2>🎯 Conclusion</h2>

<p>
  This lab report shows that embedded systems can be vulnerable to physical
  attacks even when strong cryptographic algorithms are used. The experiments
  highlight the importance of implementation-level security, side-channel
  resistance, and fault-tolerant design in hardware security.
</p>

<p>
  Overall, the labs provided hands-on experience with real-world hardware
  security attacks and demonstrated why secure embedded systems must be
  designed with both software and physical attack surfaces in mind.
</p>

<hr>

<h2>👨‍💻 Authors</h2>

<ul>
  <li>Assan Jallow</li>
  <li>Abian Morina</li>
</ul>

<hr>

<h2>🏷 Tags</h2>

<p>
  <code>hardware-security</code>
  <code>side-channel-analysis</code>
  <code>fault-injection</code>
  <code>chipwhisperer</code>
  <code>embedded-security</code>
  <code>AES</code>
  <code>DPA</code>
  <code>CPA</code>
  <code>clock-glitching</code>
</p>
