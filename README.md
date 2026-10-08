# ⚡ 100W Synchronous Buck & Boost Converter (ESP32)

**Description | ការពិពណ៌នា**: A professional power electronics project featuring a Synchronous Boost Converter (12V to 24V) and Buck Converter (24V to 12V) capable of delivering 100W at 100kHz. It features closed-loop voltage regulation using an ESP32 microcontroller, complete with MATLAB/Simulink simulations and KiCad PCB designs.

គម្រោងរចនាប្រព័ន្ធបំប្លែងតង់ស្យុង (Power Electronics) ប្រភេទ Synchronous Boost (12V-24V) និង Buck (24V-12V) កម្លាំង 100W ដំណើរការនៅប្រេកង់ 100kHz។ ប្រព័ន្ធនេះប្រើប្រាស់ ESP32 សម្រាប់បញ្ជា PWM និងគ្រប់គ្រងវ៉ុល (Closed-loop regulation) រួមទាំងមានការធ្វើ Simulation ក្នុង MATLAB និងគូសប្លង់ PCB យ៉ាងលម្អិតក្នុងកម្មវិធី KiCad។

---

## 📁 Files Included (ឯកសារក្នុងគម្រោង)

1. `Buck&Boost.pdf`
   * របាយការណ៍គម្រោងលម្អិត (Full Project Report) រួមមានការគណនារូបមន្ត, ការវិភាគ Simulation, និងការរចនាប្លង់សៀគ្វី (Schematic & 3D PCB)។

2. `ESP32_Controller.ino`
   * C++ Firmware សម្រាប់បញ្ចូលទៅក្នុង ESP32 ដើម្បីបញ្ចេញរលក PWM (100kHz) និងត្រួតពិនិត្យស្ថិរភាពតង់ស្យុងតាមរយៈ (PI Controller)។

3. `KiCad_PCB_Files/`
   * ថតឯកសារ (Folder) ផ្ទុកនូវប្លង់សៀគ្វីដើមដែលគូសដោយកម្មវិធី KiCad ងាយស្រួលសម្រាប់ការយកទៅកែច្នៃ ឬព្រីនបន្ទះសៀគ្វីបន្ត។

4. `MATLAB_Simulation/`
   * ឯកសារ Simulink (.slx) សម្រាប់ធ្វើការ Simulation ផ្ទៀងផ្ទាត់ស្ថិរភាពនៃរង្វិលជុំ (Closed-loop System & Bode Plot)។

---

## 🛠️ Technologies Used (បច្ចេកវិទ្យាប្រើប្រាស់)
* **Microcontroller:** ESP32
* **Switching Devices:** IRF3205 / IRFZ44N MOSFETs
* **Gate Drivers:** IR2109 / IR2184
* **Software Tools:** KiCad (PCB Design), MATLAB/Simulink, Arduino IDE
