<h1>Campus Navigation System</h1>
<p><em>A Python-based navigation system for VIT Bhopal University campus.</em></p>

<h2>About the Project</h2>
<p>
This Project helps students, faculty, and visitors navigate the college campus and helps find classrooms, washrooms, water coolers, and empty classrooms (based on different slots) for study sessions in Academic Block-1 by showing paths or directions between various locations. It is designed to improve campus accessibility and provide an interactive experience.
</p>

<h2>Features</h2>
<ul>
  <li>Find the shortest path between buildings and in the building.</li>
  <li>Visual representation of the campus layout and Academic Building 1 Layout.</li>
  <li>User-friendly interface built with Python.</li>
  <li>Handles complex layouts and multiple paths.</li>
</ul>

<h2>Look of the Interface</h2>
<p><em>
  <img src="NavigationSystemElements/Images/Campus.jpg" width="350" title="Campus">
</em></p>

<h2>Folder Structure</h2>
<pre>
<code>
Smart-Navigation-System/  
├── NavigationSystemElements/     # Contains map data as JSON files for paths and marker data as CSV files
│   ├── Blue/                     # JSON files for Boys Hostel Co-ordinates
│   ├── Green/                    # JSON files for Ground and Ponds Co-ordinates
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
