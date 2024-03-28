# wckd
wicked fast ml lib in rust with no rules.

Rough Philosophy:
1. Usability
2. Extreme performance
3. Cuss words in logs


## Development

1. Setup Env

```bash
python3 -m venv .env
source .env/bin/activate
```

2. (Re)Compile and run

```bash
maturin develop
```

Open a python shell now:

```python
import wckd
```

## Usage

### Matrix Multiplication

```python
import wckd
a1 = wckd.array([1, 2, 3])
a2 = wckd.array([3, 4, 5])

a3 = wckd.dot(a1, a2)
```