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

![Tux, the Linux mascot](/assets/images/tux.png)

## Get Started with Intel® VTune™ Profiler for Linux* OS

*Environment Setup*
```
echo "source /opt/intel/oneapi/vtune/2021.6.0/vtune-vars.sh" >> ~/.bashrc
source ~/.bashrc
```

**Step 1: Start VTune Profiler**

1. GUI
```
vtune-gui
```

2.
```
vtune
```

**Step 2: Configure and Run Analysis**

|             | Setting             | Default Value            |
| ----------- | ------------------- | ------------------------ |
| Where       | Target System       | Local Host               |
| What        | Analysis Target     | Launch Application       |
| How         | Analysis Type       | Performance Snapshot     |

**Step 3: View and Analyze Performance Data**


*Cannot start data collection because the scope of ptrace system call is limited. To enable profiling, please set /proc/sys/kernel/yama/ptrace_scope to 0. To make this change permanent, set kernel.yama.ptrace_scope to 0 in /etc/sysctl.d/10-ptrace.conf and reboot the machine.*
