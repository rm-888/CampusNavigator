<h1>🏫 Campus Navigation System</h1>
<p><em>A Python-based navigation system for VIT Bhopal University campuses.</em></p>

<h2>🚀 About the Project</h2>
<p>
This Project helps students, faculty, and visitors navigate the college campus and helps find classrooms, washrooms, water coolers, and empty classrooms (based on different slots) for study sessions in Academic Block-1 by showing paths or directions between various locations. It is designed to improve campus accessibility and provide an interactive experience.
</p>

<h2>🛠️ Features</h2>
<ul>
  <li>🔍 Find the shortest path between buildings and in the building.</li>
  <li>🗺️ Visual representation of the campus layout and Academic Building 1 Layout.</li>
  <li>💻 User-friendly interface built with Python.</li>
  <li>🚪 Handles complex layouts and multiple paths.</li>
</ul>

<h2>📷 Demo</h2>
<p><em>
  <img src="NavigationSystemElements/Images/Campus.jpg" width="350" title="Campus">
</em></p>
<ul>
  <li>Screenshot of the main interface.</li>
  <li>Example of a path being displayed.</li>
</ul>
<p><em>
  <img src="NavigationSystemElements/Images/ABGroundFloor.jpg" width="350" title="AB Ground Floor">
</em></p>
<ul>
  <li>Screenshot of AB Ground Floor interface.</li>
  <li>Example of a path being displayed.</li>
</ul>
<h2>🛑 Prerequisites</h2>
<p>Before you start, make sure you have the following installed:</p>
<ul>
  <li>Python</li>
  <li>Jupyter NoteBook or JupyterLab</li>
  <li>Libraries:</li>
</ul>
<pre>
<code>pip install folium</code>
<code>pip install pandas</code>
<code>pip install ipywidgets</code>
</pre>

<h2>📂 Folder Structure</h2>
<pre>
<code>
Smart-Navigation-System/  
├── NavigationSystemElements/     # Contains map data as JSON files for paths and marker data as CSV files
│   ├── Blue/                     # JSON files for Boys Hostel Co-ordinates
│   ├── Green/                    # JSON files for Ground and Pounds Co-ordinates
│   ├── Orange/                   # JSON files for Canteens Co-ordinates
│   ├── Pink/                     # JSON files for Girls Hostel Co-ordinates
│   ├── Red/                      # JSON files for College Buildings Co-ordinates
│   ├── Floor1/                   # Contains map data as JSON files and marker data as CSV files
│   │   ├── blue/                 # JSON files for Classrooms Co-ordinates
│   │   ├── green/                # JSON files for Lifts and Stairs Co-ordinates
│   │   ├── orange/               # JSON files for Washrooms Co-ordinates
│   │   ├── pink/                 # JSON files for Music Room Co-ordinates
│   │   ├── red/                  # JSON files for Officials Room Co-ordinates
│   ├── Floor2/                   # Contains map data and Paths as JSON files and marker data as CSV files
│   │   ├── Paths1/               # JSON files for Paths Co-ordinates
│   │   ├── green/                # JSON files for Lifts and Stairs Co-ordinates
│   │   ├── orange/               # JSON files for Washrooms Co-ordinates
│   │   ├── pink/                 # JSON files for Library Co-ordinates
│   │   ├── red/                  # JSON files for Classrooms Co-ordinates
│   ├── Floor3/                   # Contains map data and Paths as JSON files and marker data as CSV files
│   │   ├── Paths3/               # JSON files for Paths Co-ordinates
│   │   ├── green/                # JSON files for Lifts and Stairs Co-ordinates
│   │   ├── orange/               # JSON files for Washrooms Co-ordinates
│   │   ├── pink/                 # JSON files for Faculty Cabins Co-ordinates
│   │   ├── red/                  # JSON files for Classrooms Co-ordinates
│   ├── Images/                   # Demo Image of Projects
├── Main_Code.ipynb               # Python scripts  
├── README.md                     # Project description  
└── LICENSE                       # License information
</code>
</pre>

<h2>🚦 How to Run the Program</h2>
<ol>
  <li><b>Clone the repository:</b>
    <pre>
git clone https://github.com/Deeks779/Smart-Navigation-System.git
cd Smart-Navigation-System
    </pre>
  </li>
  <li><b>Start Jupyter Notebook or JupyterLab:</b>
    <pre>
jupyter notebook
    </pre>
    OR
    <pre>
jupyter lab
    </pre>
  </li>
  <li><b>Open the Notebook:</b> 
    In the Jupyter interface, navigate to the directory containing the project and open the file:
    <pre>Main_Code.ipynb</pre>
  </li>
  <li><b>Run the Notebook:</b>
    <ul>
      <li>Execute the cells sequentially by selecting a cell and pressing <b>Shift + Enter</b>.</li>
      <li>Interact with the widget interface to explore the campus navigation functionality.</li>
    </ul>
  </li>
</ol>

<h2>🤝 Contributing</h2>
<p>Contributions are welcome!</p>
<ol>
  <li>Fork the repository.</li>
  <li>Create your feature branch:</li>
</ol>
<pre>
<code>git checkout -b feature/AmazingFeature</code>
</pre>
<ol start="3">
  <li>Commit your changes:</li>
</ol>
<pre>
<code>git commit -m "Add some AmazingFeature"</code>
</pre>
<ol start="4">
  <li>Push to the branch:</li>
</ol>
<pre>
<code>git push origin feature/AmazingFeature</code>
</pre>
<ol start="5">
  <li>Open a pull request.</li>
</ol>

<h2>✒️ Team Members</h2>
<ul>
  <li><a href="https://www.linkedin.com/in/deeksha-kushwaha">Deeksha Kushwaha [Leader]</a></li>
  <li>Rujula Malhotra</li>          
  <li>Anwesha Chatterjee</li>    
  <li>Arunanshi Kaushish</li>  
  <li>Khushi Gupta </li>
</ul>

<h2>📜 License</h2>
<p>
This project is licensed under the MIT License. See 
<code>LICENSE</code> for more details.
</p>
