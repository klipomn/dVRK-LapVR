This repo assumes you already have the **Asynchronous Multi-Body Framework (AMBF)** installed and working on your machine.

 _AMBF repo:_ https://github.com/WPI-AIM/ambf

 # Run the simulation
 ```
./run_env_LND_440006.sh
```
Command with LapVR Shell (Alternate):
```
~/ambf/bin/lin-x86_64/ambf_simulator --launch_file launch.yaml -l 1,2,3,4,5,13,16,17,18,19,20,21 -p 200 -t1 --override_max_comm_freq 100 --override_min_comm_freq 100
```
# Run the control script
```
cd LapVR-scripts
python test_friction.py
```

see repository for AR: https://github.com/rayhan3333/Cotrain-AR

