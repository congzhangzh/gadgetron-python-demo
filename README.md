# gadgetron-python-demo
for fun and runable

# prepare env (prefer in mini conda)
```bash
pip install gadgetron gadgetron-dataflow-monitor
```

# start gadgetron first
```bash
gadgetron
```

# demo time
## passthrough
```bash
gadgetron_ismrmrd_client -f testdata.h5 -C passthough_demo.xml
```
## datflow monitor
```bash
gadgetron_ismrmrd_client -f testdata.h5 -C dataflow_monitor.xml
```
## plot image and save
```bash
gadgetron_ismrmrd_client -f testdata.h5 -C plotsave_demo.xml
```
## dataflow monitor and plot image and save
```bash
gadgetron_ismrmrd_client -f testdata.h5 -C dataflow_monitor_plotsave_demo.xml
```