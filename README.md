# minitorch
The full minitorch student suite. 

## Module 1 — Task 1.5: Scalar training

```bash
python project/run_scalar.py --dataset Simple --hidden 2
python project/run_scalar.py --dataset Xor --hidden 10
python project/run_scalar.py --dataset Diag --hidden 10
python project/run_scalar.py --dataset Split --hidden 10
```

All runs use 50 points, learning rate 0.5, and 500 epochs. 

| Dataset | Hidden size | Final accuracy | Final loss | Training log |
| --- | ---: | ---: | ---: | --- |
| Simple |  2 | 48/50 (98%) | 3.2561  |[Log](training_logs/simple.txt) |
| Xor    | 10 | 48/50 (98%) | 5.4864  |[Log](training_logs/xor.txt) |
| Diag   | 10 | 50/50 (100%)| 0.1225  |[Log](training_logs/diag.txt) |
| Split  | 10 | 48/50 (96%) | 3.9141  |[Log](training_logs/split.txt) |

To access the autograder: 

* Module 0: https://classroom.github.com/a/qDYKZff9
* Module 1: https://classroom.github.com/a/6TiImUiy
* Module 2: https://classroom.github.com/a/0ZHJeTA0
* Module 3: https://classroom.github.com/a/U5CMJec1
* Module 4: https://classroom.github.com/a/04QA6HZK
* Quizzes: https://classroom.github.com/a/bGcGc12k
