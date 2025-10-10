Quantum Algorithm for Binary Vector Encoding and Retrieval Utilizing the Permutation Trick

See the paper at: http://arxiv.org/abs/2510.07354

We present a novel quantum storage algorithm for $k$ binary vectors of dimension $m$ into a superposition of a $m$-qubit quantum state based on a permutation technique. We compare this algorithm to the storage algorithm proposed by Ventura and Martinez. The proposed permutation technique is simpler and can lead to an additional reduction through the \textit{reduce} algorithm.
To retrieve a binary vector from the superposition of $k$ vectors represented by a $m$-qubit quantum state, we must use a modified version of Grover’s algorithm, as Grover’s algorithm does not function correctly for non-uniform distributions. We propose a permutation trick that enables an exhaustive search by Grover’s algorithm in $O(\sqrt{k})$ steps for $k$ patterns, independent of $n=2^m$. We compare this trick to the Ventura and Martinez trick, which requires $O(\sqrt{n})$ steps for $k$ patterns. 

The software runs with qiskit 2.2. If you have an older version
and get an error at result=simulator.run(qc.decompose().decompose(),shots=10000).result()
just add another decompose(), if still the error is present, add another decompose() repeat till error disappears.
