Task Scheduler learning

- If anybody would like to see my note, [here is] (./task-scheduler-note.pdf)

## Build and Run

### Prerequisites
- C++ compiler, CMake
- Python3

### Build
```
# 1. clone repo
git clone <url>
cd <repo>

# 2. Create python virtual env, and activate it
python3 -m venv myvenv
source myvenv/bin/activate
# you'll see (myvenv) username@Macbook .... % (if you are mac user as well)

# 3. Install python dependencies
pip install matplotlib numpy

# 4. Compile C++ project
mkdir -p build 
cd build
cmake ..
make

# 5. Run scheduler simulation
./cfs_scheduler

# 6. Generate visualization plots
cd .. 
python3 plot.py
```
