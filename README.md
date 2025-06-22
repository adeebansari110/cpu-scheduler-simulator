# 🚀 CPU Scheduler Simulator - Virtual Operating Systems Lab

<div align="center">

![CPU Scheduling](https://img.shields.io/badge/CPU-Scheduling-blue?style=for-the-badge&logo=processor)
![Operating Systems](https://img.shields.io/badge/OS-Virtual%20Lab-green?style=for-the-badge&logo=linux)
![Education](https://img.shields.io/badge/Education-Interactive-orange?style=for-the-badge&logo=graduation-cap)

**An Interactive Web-Based Simulator for Learning CPU Scheduling Algorithms**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Simulator-brightgreen?style=for-the-badge&logo=play)](https://your-demo-link.com)
[![Documentation](https://img.shields.io/badge/Documentation-Read%20Docs-blue?style=for-the-badge&logo=book)](docs.html)
[![About](https://img.shields.io/badge/About-Our%20Team-purple?style=for-the-badge&logo=users)](about.html)

</div>

---

## 🎯 Overview

Welcome to the **CPU Scheduler Simulator** - a comprehensive virtual laboratory designed to help students, educators, and computer science enthusiasts understand and visualize various CPU scheduling algorithms in real-time. This interactive web application provides an immersive learning experience through dynamic Gantt charts, step-by-step explanations, and hands-on experimentation.

### 🌟 Key Features

- **🎮 Interactive Simulator**: Real-time visualization of CPU scheduling algorithms
- **📊 Dynamic Gantt Charts**: Visual representation of process execution
- **📚 Comprehensive Documentation**: Detailed explanations of all algorithms
- **🎨 Modern UI/UX**: Beautiful, responsive design with smooth animations
- **📱 Cross-Platform**: Works seamlessly on desktop, tablet, and mobile devices
- **⚡ Real-Time Calculations**: Instant computation of waiting time, turnaround time, and CPU utilization

---

## 🧠 Supported Algorithms

Our simulator covers all major CPU scheduling algorithms with both preemptive and non-preemptive variants:

### 🔄 **Preemptive Algorithms**
- **Shortest Remaining Time First (SRTF)** - Preemptive version of SJF
- **Priority Scheduling** - Based on process priorities
- **Round Robin** - Time quantum-based scheduling

### ⏳ **Non-Preemptive Algorithms**
- **First Come First Serve (FCFS)** - Simple FIFO scheduling
- **Shortest Job First (SJF)** - Based on burst time
- **Priority Scheduling** - Non-preemptive version

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser!

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/cpu-scheduler-simulator.git
   cd cpu-scheduler-simulator
   ```

2. **Open the application**
   - Simply open `index.html` in your web browser
   - Or serve it using a local server for the best experience

3. **Start Learning**
   - Read the documentation at `docs.html`
   - Try the simulator at `backend/ganttcharts.html`
   - Experiment with different algorithms and parameters

---

## 🎮 How to Use the Simulator

### 1. **Input Process Data**
- Enter arrival times, burst times, and priorities for each process
- Add or remove processes as needed (supports up to 10 processes)
- Set time quantum for Round Robin algorithm

### 2. **Select Algorithm**
- Choose from 6 different scheduling algorithms
- Switch between algorithms to compare results
- View algorithm-specific explanations

### 3. **Analyze Results**
- **Gantt Chart**: Visual timeline of process execution
- **Performance Metrics**: 
  - Average Waiting Time
  - Average Turnaround Time
  - CPU Utilization
  - Throughput
- **Step-by-step Explanation**: Understand the decision-making process

---

## 📊 Performance Metrics Explained

### ⏱️ **Turnaround Time**
The total time from process arrival to completion
```
Turnaround Time = Completion Time - Arrival Time
```

### ⏳ **Waiting Time**
The time a process spends waiting in the ready queue
```
Waiting Time = Turnaround Time - Burst Time
```

### 🎯 **CPU Utilization**
Percentage of time the CPU is busy executing processes
```
CPU Utilization = (Total CPU Time / Total Time) × 100%
```

---

## 🏗️ Project Structure

```
CPUScheduler simulator/
├── 📁 backend/                 # Core simulator files
│   ├── 📁 css/                # Styling for simulator
│   ├── 📁 js/                 # JavaScript algorithms
│   └── ganttcharts.html       # Main simulator interface
├── 📁 images/                 # Educational images
├── 📁 img/                    # UI assets
├── 📁 about/                  # Team information
├── index.html                 # Landing page
├── docs.html                  # Documentation
├── about.html                 # About page
└── style.css                  # Main stylesheet
```

---

## 🛠️ Technical Implementation

### Frontend Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Interactive functionality
- **Bootstrap** - Responsive design framework
- **Chart.js** - Dynamic Gantt chart visualization

### Key Components
- **Algorithm Engine**: Pure JavaScript implementation of scheduling algorithms
- **Visualization System**: Real-time Gantt chart generation
- **Calculation Engine**: Performance metrics computation
- **Responsive Design**: Mobile-first approach

---

## 🎓 Educational Value

### For Students
- **Visual Learning**: See algorithms in action with real-time animations
- **Hands-on Practice**: Experiment with different scenarios
- **Performance Comparison**: Compare algorithm efficiency
- **Concept Reinforcement**: Step-by-step explanations

### For Educators
- **Teaching Tool**: Interactive demonstrations in classrooms
- **Assignment Platform**: Create custom scheduling problems
- **Assessment Tool**: Evaluate student understanding
- **Research Aid**: Algorithm performance analysis

---

## 🔬 Algorithm Details

### First Come First Serve (FCFS)
- **Type**: Non-preemptive
- **Principle**: Processes are executed in order of arrival
- **Use Case**: Simple systems, batch processing
- **Complexity**: O(n²)

### Shortest Job First (SJF)
- **Type**: Non-preemptive
- **Principle**: Process with shortest burst time executes first
- **Use Case**: Batch systems, minimizing average waiting time
- **Complexity**: O(n²)

### Shortest Remaining Time First (SRTF)
- **Type**: Preemptive
- **Principle**: Preemptive version of SJF
- **Use Case**: Real-time systems, minimizing response time
- **Complexity**: O(n²)

### Priority Scheduling
- **Type**: Both preemptive and non-preemptive
- **Principle**: Processes executed based on priority levels
- **Use Case**: Real-time systems, priority-based applications
- **Complexity**: O(n²)

### Round Robin
- **Type**: Preemptive
- **Principle**: Each process gets a fixed time quantum
- **Use Case**: Time-sharing systems, fair resource allocation
- **Complexity**: O(n)

---

## 🌟 Features in Detail

### 🎨 **Modern User Interface**
- Clean, intuitive design with smooth animations
- Responsive layout that works on all devices
- Dark/light theme support
- Accessibility features

### 📈 **Advanced Visualizations**
- Interactive Gantt charts with zoom and pan
- Real-time process state indicators
- Color-coded process execution
- Timeline markers and annotations

### 🔧 **Customization Options**
- Adjustable time quantum for Round Robin
- Configurable context switch overhead
- Custom process priorities
- Multiple process scenarios

### 📊 **Comprehensive Analytics**
- Detailed performance metrics
- Algorithm comparison charts
- Statistical analysis
- Export capabilities

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 🐛 **Report Bugs**
- Use the GitHub issue tracker
- Provide detailed reproduction steps
- Include browser and OS information

### 💡 **Suggest Features**
- Share your ideas for new algorithms
- Propose UI/UX improvements
- Suggest educational enhancements

### 🔧 **Code Contributions**
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

---

## 👥 Team

**Team CE** - Computer Engineering Students

- **Frontend Development**: Modern web technologies
- **Algorithm Implementation**: Pure JavaScript
- **UI/UX Design**: User-centered design principles
- **Documentation**: Comprehensive educational content

---

## 🙏 Acknowledgments

- **Operating Systems Community**: For algorithm references and best practices
- **Open Source Contributors**: For libraries and tools used
- **Educational Institutions**: For feedback and testing
- **Students**: For valuable insights and suggestions

---

## 📞 Contact & Support

- **Website**: [OS Virtual Lab](index.html)
- **Documentation**: [Read Docs](docs.html)
- **Simulator**: [Try Now](backend/ganttcharts.html)
- **About**: [Our Team](about.html)

---

<div align="center">

**Made with ❤️ by Team CE**

[![GitHub Stars](https://img.shields.io/github/stars/yourusername/cpu-scheduler-simulator?style=social)](https://github.com/yourusername/cpu-scheduler-simulator)
[![GitHub Forks](https://img.shields.io/github/forks/yourusername/cpu-scheduler-simulator?style=social)](https://github.com/yourusername/cpu-scheduler-simulator)
[![GitHub Issues](https://img.shields.io/github/issues/yourusername/cpu-scheduler-simulator)](https://github.com/yourusername/cpu-scheduler-simulator/issues)

**⭐ Star this repository if you found it helpful!**

</div>
