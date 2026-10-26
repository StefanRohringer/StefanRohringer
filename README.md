<h1 align="center">Stefan Rohringer</h1>

<p align="center">
  <b>Robotics &amp; AI Architect</b><br>
  Computer Vision · Industrial Automation · Physical AI · Agentic AI
</p>

<p align="center">
  <a href="https://de.linkedin.com/in/stefan-rohringer-038741293"><img src="https://img.shields.io/badge/LinkedIn-Stefan%20Rohringer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center">
  <a href="#videos">🎬 Videos</a> ·
  <a href="#projekte">🛠️ Projekte</a> ·
  <a href="#schwerpunkte">🧠 Schwerpunkte</a>
</p>

---

<a name="videos"></a>

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

<a name="projekte"></a>

## 🛠️ Projekte

### 🦾 Robotik-Hardware

#### [Touch-Sensing Fin-Ray Gripper](https://github.com/StefanRohringer/Touch-Sensing-Fin-Ray-Gripper)

<p align="center">
  <img src="https://raw.githubusercontent.com/StefanRohringer/Touch-Sensing-Fin-Ray-Gripper/main/bilder/greifer.gif" width="360" alt="Greifer schließt sich um eine Traube, bis alle vier Lamellen Kontakt melden, und greift dann mit dem Fingernagel ein SMD-Bauteil">
</p>

Greiferfinger mit Tastsinn für den Seeed reBot DevArm: Jeder Finger trägt zwei weiche Fin-Ray-Lamellen aus TPU, in jeder sitzt ein kleiner Magnet, dahinter ein Magnetometer (MLX90393). Alle vier Lamellen melden Kontakt einzeln, so spürt der Roboter beim Schließen, dass er das Teil hält, und beim Ablegen, dass es aufsetzt. Mit Fingernagel-Variante für winzige SMD-Bauteile (0603/0402), Druckdateien, Maßzeichnungen, Anschlussplan, interaktiver 3D-Ansicht, Firmware für den Raspberry Pi Pico und Live-Monitor für den PC.

<img src="https://img.shields.io/badge/3D--Druck-555?style=flat-square" alt="3D-Druck"> <img src="https://img.shields.io/badge/Taktile%20Sensorik-555?style=flat-square" alt="Taktile Sensorik"> <img src="https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white" alt="MicroPython"> <img src="https://img.shields.io/badge/Open%20Hardware-555?style=flat-square" alt="Open Hardware">

### 🤖 Lokale KI-Systeme

#### [QuLSI](https://github.com/StefanRohringer/QuLSI)

Quantized Local Superintelligence: selbst gehosteter KI-Assistent, der komplett auf eigener Hardware läuft. Lokales LLM, Sprache, Kameras, Gedächtnis, Mail, Kalender und Smart Home.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Lokales%20LLM-555?style=flat-square" alt="Lokales LLM">

#### [me-system](https://github.com/StefanRohringer/me-system)

Deterministisches (12×7)+10-Wissensnetz aus technischen Dokumenten. Kein LLM, keine Cloud, läuft auf einem Raspberry Pi.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">

### 🔒 Sicherheit für KI-Agenten

#### [me-guard](https://github.com/StefanRohringer/me-guard)

Lokales Vertrauens- und Integritätssystem für KI-Agenten-Skills: signiert, prüft und scannt Skills, bevor sie ausgeführt werden. 100 % offline und deterministisch.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Offline-555?style=flat-square" alt="Offline">

### 🧪 Experimente

#### [binaer-experiment](https://github.com/StefanRohringer/binaer-experiment)

Kann ein LLM Programme direkt als Maschinencode schreiben? Testumgebung und Ergebnisse im Vergleich mit C.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Maschinencode-555?style=flat-square" alt="Maschinencode">

---

<a name="schwerpunkte"></a>

## 🧠 Schwerpunkte

<p>
  <img src="https://img.shields.io/badge/Robotik-555?style=for-the-badge" alt="Robotik">
  <img src="https://img.shields.io/badge/Computer%20Vision-555?style=for-the-badge" alt="Computer Vision">
  <img src="https://img.shields.io/badge/Industrial%20Automation-555?style=for-the-badge" alt="Industrial Automation">
  <img src="https://img.shields.io/badge/Physical%20AI-555?style=for-the-badge" alt="Physical AI">
  <img src="https://img.shields.io/badge/Agentic%20AI-555?style=for-the-badge" alt="Agentic AI">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/3D--Druck-555?style=for-the-badge" alt="3D-Druck">
</p>
