# QC-lib

This is not even well library built
but to use

```bash
    git clone https://github.com/eremognosis/qc-lib
    cd qc-lib
```

Ensure the necessary
```bash
    sudo apt update && sudo apt -y build-essential
```

Now to do somehing
Lets say build a `main.py`


Before that make a venv

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

```bash

echo "
from statev import Statevector
import numpy as np
## and do whatever
#like

arr = np.array([0,1,0,0])
q = Statevector(arr)
print(q)

" > main.py

python3 main.py

``` 
Similar for others


### Credits:
The October 2025 Version of eremognosis (Raj)
For better quantum and more sane impleentatuon by myself see the qisC project
in [qisC](https://github.com/eremognosis/qisC) with much more features
