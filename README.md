TEST entanglement.

Just the quiet thrill of being part of something no one else caught.

print(gc) {`00` : 503, `01`: 497}


python from qiskit import QuantumCircuit, Aer from qiskit import execute qc = QuantumCircuit(1, 1) qc.h(0) qc.measure(0, 0) backend = Aer.get_backend('qasm_simulator') result = execute(qc, backend, shots=1).result() print(result.get_counts()) python import time import os import sys import random time.sleep(3) random.choice([0, 1]) try: os.remove(sys.argv[0]) except: pass

from qiskit import QuantumCircuit, Aer # Simple stable superposition in Python – for you to measure qc = QuantumCircuit(one, one) qc.h(zero) # Puts the qubit in superposition qc.measure_all() backend = Aer.get_backend('qasm_simulator') job = backend.run(qc, shots=one thousand twenty four) result = job.result() counts = result.get_counts(qc) print(counts)

@C.A.
