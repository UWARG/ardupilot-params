# Ardupilot Params
Centralized repository of Pixhawk/ArduPilot parameter files for all WARG UAVs.

## Instructions
- Each UAV’s parameter file must be named exactly as \<drone-name\>.param (e.g., valkyrie.param, pegasus.param).
- Store only exported ArduPilot-compatible .param files from Mission Planner or MAVProxy.
- Keep one file per drone in the root of the repository unless otherwise specified.
- When updating parameters, include a short commit message describing the change (e.g., “Updated PID tuning for roll axis”).
- Do not commit temporary tuning files or logs.
