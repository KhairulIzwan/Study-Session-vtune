# Study-Session-vtune

## Get Started with Intel® VTune™ Profiler

**Improve application and system performance**
```
1. Analyze algorithm choices.
2. Find serial and parallel code bottlenecks.
3. Understand where and how your application can benefit from available hardware resources.
4. Speed up the execution of your application.
```

**Understand the Workflow**

![VTune Workflow](https://github.com/KhairulIzwan/Study-Session-vtune/blob/main/img/workflowVTune.png)

## Get Started with Intel® VTune™ Profiler for Linux* OS

*Environment Setup* **ONLY ONCE!**
```
echo "source /opt/intel/oneapi/vtune/2021.6.0/vtune-vars.sh" >> ~/.bashrc
source ~/.bashrc
```

**Step 1: Start VTune Profiler**

1. Graphical User Interface (GUI)
```
vtune-gui
```

2. Command Line Interface (CLI)
```
vtune
```

**Step 2: Configure and Run Analysis**

|             | Setting             | Default Value            |
| ----------- | ------------------- | ------------------------ |
| Where       | Target System       | Local Host               |
| What        | Analysis Target     | Launch Application       |
| How         | Analysis Type       | Performance Snapshot     |

```
*We will start **Performance Snaphot** as it presents a general overview of issues affecting the performance of your application on the target system*
```

**Step 3: View and Analyze Performance Data**

![Performance Snapshot Summary](https://github.com/KhairulIzwan/Study-Session-vtune/blob/main/img/summaryPS.png)

| Section     | Description         | Notes            |
| ----------- | ------------------- | -----------------|
| A           | Expand each metric for detailed information about contributing factors.      | Local Host               |
| B           | A flagged metric indicates a value outside acceptable/normal operating range. Use tool tips to understand how to improve a flagged metric.     | Launch Application   |
| C           | See guidance on other analyses you should consider running next. The Analysis Tree highlights these recommendations.       | Performance Snapshot     |

*Cannot start data collection because the scope of ptrace system call is limited. To enable profiling, please set /proc/sys/kernel/yama/ptrace_scope to 0. To make this change permanent, set kernel.yama.ptrace_scope to 0 in /etc/sysctl.d/10-ptrace.conf and reboot the machine.*
