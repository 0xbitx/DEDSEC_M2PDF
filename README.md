
<p align="center">
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExendjcjZjN2Z2cXllMHB3ZXBubTBqeHJmcnl4cms4OTI2ampsbTB5dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vCFdAw72pa8lYaWyNR/giphy.gif", width="300", height="300">
</p>

<h1 align="center"> DEDSEC_M2PDF </h1>
<h4 align="center"> hide payload inside pdf file</h4>

### DESCRIPTION
M2PDF is a powerful tool designed to embed binary or ELF malware into PDF files without corrupting the original document. The injected PDF looks and behaves like a normal PDF file but contains hidden malicious code that can be executed under specific conditions. The tool generates a Python script that demonstrates how the malware is extracted from the PDF. This script can be integrated into your own code or dropper for further use. This tool is intended for educational and research purposes only.

### Features

  * Stealthy Injection: Embeds malware into a PDF file without altering its appearance or functionality.
  * Preserves Original PDF: The injected PDF remains fully functional and visually identical to the original.
  * Payload Extraction: Generates a Python script (extract.py) to extract the embedded payload from the PDF file.
  * Cross-Platform: Works on Windows, Linux, and macOS.
    
### INSTALLATION
     git clone https://github.com/0xbitx/DEDSEC_M2PDF.git
     cd DEDSEC_M2PDF
     chmod +x dedsec_m2pdf
     sudo ./dedsec_m2pdf

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu

## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**
   
<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>
