# rubrik-connector-enablement-4.1EA
Build
This will probably only work in Rubrik's build environment (for now). Login to the Centos VM and run scons with the following build targets:
```
cd src/cpp
scons build/debug/rba/backup_agent_main
scons build/debug/rba/agent_benchmark_main
scons build/debug/rba/backup_agent_test
scons build/debug/rba/bootstrap_agent_main
```
