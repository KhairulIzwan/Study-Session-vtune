# Study-Session-VTune

## Get Started with Intel® VTune™ Profiler

## Workflow

![VTune Workflow](https://github.com/KhairulIzwan/Study-Session-vtune/blob/main/img/workflowVTune.png)

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

**Step 3: View and Analyze Performance Data**

![Performance Snapshot Summary](https://github.com/KhairulIzwan/Study-Session-vtune/blob/main/img/summaryPS.png)

| Section     | Description         | Notes            |
| ----------- | ------------------- | -----------------|
| A           | Expand each metric for detailed information about contributing factors.      |                |
| B           | A flagged metric indicates a value outside acceptable/normal operating range. Use tool tips to understand how to improve a flagged metric.     |    |
| C           | See guidance on other analyses you should consider running next. The Analysis Tree highlights these recommendations.       |      |


<!--1. Run Analysis Performance Snapshot (ps)-->

<!--**The goal of performance optimization is to get the highest possible performance gain with the least possible investment of time and effort.**-->

<!--### Why run PS?-->
<!--1. Highlighting the main problem areas in your application and providing metrics to estimate their severity.-->
<!--2. Focus on the most acute problems, solving which can yield the highest performance gain.-->

<!--## How to Interpret Result Data Performance Snapshot-->

