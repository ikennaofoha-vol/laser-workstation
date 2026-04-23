# laser-workstation
⚡LASER Workstation

A professional-grade web application for simulating multi-stage laser ablation and substrate cutting. This tool is designed to help engineers calculate the Effective Intensity (GW/cm²) required to isolate copper traces and cut through substrates like Alumina Ceramic or FR4.

🚀Live Link

[Insert your GitHub Pages URL here once it is live]

📊 Google Sheets Integration

This app is powered by a Google Sheet "Headless CMS." To use the app, your Google Sheet must have the following tabs:

1. UI_Config

key

value

main_title

LASER4YOU WORKSTATION

s1_header

Stage 1: Trace Ablation

btn_save

SAVE TO CLAD_LOGS

2. Materials

Category

Name

Threshold

Abs_355

Abs_532

Abs_1064

Conductive

Copper (Standard)

1.0

0.80

0.50

0.05

Substrate

Alumina Ceramic

4.5

0.88

0.40

0.15

3. Laser_Sources

Name

Wavelength

AvgPower

Frequency

PulseWidth

SpotSize

xTool 2W IR

1064

2

20000

15

30

💻 Tech Stack

Frontend: React (via CDN)
Styling: Tailwind CSS
Icons: Lucide-React
Database: Google Sheets via Apps Script API
