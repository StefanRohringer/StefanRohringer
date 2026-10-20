<h1 align="center">Stefan Rohringer</h1>

<p align="center">
  <b>Robotics &amp; AI Architect</b><br>
  Computer Vision · Industrial Automation · Physical AI · Agentic AI
</p>

<p align="center">
  <a href="https://de.linkedin.com/in/stefan-rohringer-038741293"><img src="https://img.shields.io/badge/LinkedIn-Stefan%20Rohringer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center">
  <a href="#-videos">🎬 Videos</a> ·
  <a href="#-projekte">🛠️ Projekte</a> ·
  <a href="#-schwerpunkte">🧠 Schwerpunkte</a>
</p>

---

## 🎬 Videos

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="video-1.gif" width="100%" alt="Video: Claude schraubt eine Mutter auf">
      <p><sub>Vorschau im 3-fachen Zeitraffer · <a href="https://github.com/StefanRohringer/StefanRohringer/raw/main/video-1.mp4">🎥 Ganzes Video herunterladen (MP4)</a></sub></p>
      <h3>Claude schraubt: KI-Roboterarm dreht eine Mutter auf</h3>
      <p>Claude steuert den reBot und dreht eine M10-Mutter auf einen senkrechten Gewindebolzen. Die Mutter wird gegriffen und über die Stange gesetzt; am Kraftanstieg im Greifer erkennt er, dass sie aufsitzt. Dann dreht er sie mit 27 Griffen zu je 60°, also 4,5 Umdrehungen.</p>
      <p>
        <img src="https://img.shields.io/badge/Robotik-555?style=flat-square" alt="Robotik">
        <img src="https://img.shields.io/badge/Physical%20AI-555?style=flat-square" alt="Physical AI">
        <img src="https://img.shields.io/badge/Kraftsensorik-555?style=flat-square" alt="Kraftsensorik">
      </p>
      <p>Hardware: <a href="https://github.com/Seeed-Projects/reBot-DevArm">reBot DevArm von Seeed Studio</a></p>
    </td>
    <td width="50%" valign="top">
      <img src="video-2.gif" width="100%" alt="Video: Roboterarm legt ein Ei in den Eierkarton">
      <p><sub>Vorschau im 14-fachen Zeitraffer · <a href="https://github.com/StefanRohringer/StefanRohringer/raw/main/video-2.mp4">🎥 Ganzes Video herunterladen (MP4)</a></sub></p>
      <h3>Ganz vorsichtig: Roboterarm legt ein Ei in den Karton</h3>
      <p>Der reBot greift ein Ei von einem Ständer und legt es behutsam in einen Eierkarton.</p>
      <p>
        <img src="https://img.shields.io/badge/Robotik-555?style=flat-square" alt="Robotik">
        <img src="https://img.shields.io/badge/Physical%20AI-555?style=flat-square" alt="Physical AI">
        <img src="https://img.shields.io/badge/Greifen-555?style=flat-square" alt="Greifen">
      </p>
      <p>Hardware: <a href="https://github.com/Seeed-Projects/reBot-DevArm">reBot DevArm von Seeed Studio</a></p>
    </td>
  </tr>
</table>

---

## 🛠️ Projekte

### 🦾 Robotik-Hardware

<table>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/StefanRohringer/Magnetic-Fin-Gripper">Magnetic-Fin-Gripper</a></h3>
      <img src="https://raw.githubusercontent.com/StefanRohringer/Magnetic-Fin-Gripper/main/bilder/greifer.gif" width="100%" alt="Greifer schließt sich um eine Traube und greift ein SMD-Bauteil">
      <p>Greiferfinger für den Seeed reBot DevArm mit weichen Fin-Ray-Lamellen und magnetischem Tastsinn: In jeder Lamelle sitzt ein Magnet, dahinter ein Magnetometer. Drückt etwas auf eine Lamelle, erkennt das System die Berührung. Mit Fingernagel-Variante für winzige SMD-Bauteile, Druckdateien, Zeichnungen und Firmware für den Raspberry Pi Pico.</p>
      <img src="https://img.shields.io/badge/3D--Druck-555?style=flat-square" alt="3D-Druck">
      <img src="https://img.shields.io/badge/Taktile%20Sensorik-555?style=flat-square" alt="Taktile Sensorik">
      <img src="https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white" alt="MicroPython">
      <img src="https://img.shields.io/badge/Open%20Hardware-555?style=flat-square" alt="Open Hardware">
    </td>
  </tr>
</table>

### 🤖 Lokale KI-Systeme

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/StefanRohringer/QuLSI">QuLSI</a></h3>
      <p>Quantized Local Superintelligence: selbst gehosteter KI-Assistent, der komplett auf eigener Hardware läuft. Lokales LLM, Sprache, Kameras, Gedächtnis, Mail, Kalender und Smart Home.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Lokales%20LLM-555?style=flat-square" alt="Lokales LLM">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/StefanRohringer/me-system">me-system</a></h3>
      <p>Deterministisches (12×7)+10-Wissensnetz aus technischen Dokumenten. Kein LLM, keine Cloud, läuft auf einem Raspberry Pi.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
    </td>
  </tr>
</table>

### 🔒 Sicherheit für KI-Agenten

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/StefanRohringer/me-guard">me-guard</a></h3>
      <p>Lokales Vertrauens- und Integritätssystem für KI-Agenten-Skills: signiert, prüft und scannt Skills, bevor sie ausgeführt werden. 100 % offline und deterministisch.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Offline-555?style=flat-square" alt="Offline">
    </td>
  </tr>
</table>

### 🧪 Experimente

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/StefanRohringer/binaer-experiment">binaer-experiment</a></h3>
      <p>Kann ein LLM Programme direkt als Maschinencode schreiben? Testumgebung und Ergebnisse im Vergleich mit C.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/Maschinencode-555?style=flat-square" alt="Maschinencode">
    </td>
  </tr>
</table>

---

## 🧠 Schwerpunkte

<p>
  <img src="https://img.shields.io/badge/Robotik-555?style=for-the-badge" alt="Robotik">
  <img src="https://img.shields.io/badge/Computer%20Vision-555?style=for-the-badge" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Industrial%20Automation-555?style=for-the-badge" alt="Industrial Automation">
  <img src="https://img.shields.io/badge/Physical%20AI-555?style=for-the-badge" alt="Physical AI">
  <img src="https://img.shields.io/badge/Agentic%20AI-555?style=for-the-badge" alt="Agentic AI">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
</p>
