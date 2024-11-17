# Testing the SHA 256 Hashing Algorithm in C# 🔒

**University:** *UNIVERSITY OF PRISHTINA*  <br>
**Faculty:** *Electrical and Computer Engineering*  <br>
**Program:** *Computer and Software Engineering*  <br>
**Level:** *Master*   <br>
**Students:** *[Jetë Lajçi](https://github.com/Jeta52), [Melisa Alaj](https://github.com/melisaalaj), [Yll Berisha](https://github.com/yllberisha)*   <br>
**Professor:** *[Dr. Sc. Mërgim H. HOTI](https://github.com/MergimHHoti)*   <br>

## Project Overview

**SHA 256** (Secure Hash Algorithm 256) is a cryptographic algorithm that belongs to the *SHA-2* family. Is is used to generate a fixed-length *256-bit* hash from data of varying sizes [[1]](https://securiti.ai/glossary/secure-hash-algorithm-sha-256-bit/).  This algorithm is widely used in information security and blockchain technologies.

<div align="center">
  <img src="https://github.com/user-attachments/assets/5ccdd9fd-6a97-4086-89f5-d0587ce48f0f" alt="Description of the image" width="550" />
  <p><em><i>The generation of a SHA-256 hash value for a long message</i> [<a href="https://www.researchgate.net/figure/The-generation-of-a-SHA-256-hash-value-for-a-long-message_fig1_349744176">2</a>]</em></p>
</div>


In this project, the implementation of SHA 256 includes the following functionalities:  
- **Encrypt Text**  
- **Compare Hashes**  
- **Check File Hash**

## Project Contents

### ➡️ Encrypt Text with SHA-256
This functionality allows you to input text and encrypt it using the SHA-256 algorithm.  

![image](https://github.com/user-attachments/assets/066fff61-3d7e-4c65-8edd-ebddc2c7e7f7)

#### Steps:  
1. Enter the text you want to hash in the input field.  
2. Click the "Compute Hash" button.  
3. The generated hash will be displayed in the chosen format (e.g., Hex Lowercase).  

Options include:  
- **Auto Update:** If this option is enabled, the output will be updated in real time.
- **Input Encoding:** Formats such as UTF-8.  
- **Output Encoding:** Choose between uppercase or lowercase Hexadecimal.  

### ➡️ Compare Hashes
This functionality compares the hashes of input text using different algorithms.  

![image](https://github.com/user-attachments/assets/745b216d-aee5-4d73-9b07-351c68378694)

#### Steps:  
1. Enter the text in the input field.  
2. Select the algorithm you want to use for generating the hash.  
3. Click "Calculate Hashes".  
4. The results will display the generated hash and the time taken for processing.  

### ➡️ Check File Hash
![image](https://github.com/user-attachments/assets/cd66ef8a-1deb-4548-9e06-3dd215150e44)

This functionality includes two main operations:  
1. **Calculate the hash of a file.**  
   - Choose a file from your device.  
   - Click "Calculate Hash" to view the generated SHA-256 hash.  

2. **Verify the hash of a file.**  
   - Enter the known hash in the designated field.  
   - Select the file you want to verify.  
   - Click "Verify Hash" to compare the generated hash with the known hash.  

## Technologies and Tools Used
- **Programming Language:** C#  
- **IDE:** Visual Studio  
- **Framework:** .NET 7.0 (Blazor WebAssembly) 

## Usage Instructions
1. **Clone the Project**  
   ```bash
   git clone https://github.com/melisaalaj/SHA256-Hashing-Testing.git
2. **Open the project in Visual Studio** <br>
   Add the **C# extension** from the Extensions Marketplace.
4. **Ensure required tools are installed**
   ```bash
   dotnet --version
5. **Restore Dependencies**  
   ```bash
   dotnet restore
6. **Run the Application**  
   ```bash
   dotnet run

