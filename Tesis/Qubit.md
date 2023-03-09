En Computación Cuántica un qubit es el análogo a un bit en computación clásica. También se tienen Qubytes los cuales son análogos a los clásicos bytes. Como con la computación clásica un qubit tiene dos estados mesurables/ medibles, pero aquí hay un poco mas que eso.

Cuando mide un qubit se dice que el estado cuántico colapsa a un valor de 0 o 1. Sin embargo, antes de medirlo, los dos estados observables tienen una cierta probabilidad, pero como ingenieros cuánticos podemos modificar las probabilidades de un estado cuántico y, además, podemos emplear múltiples qubits que se afectan entre si.

Un qubit es representado como un vector. El qubit de estado cero es representado como una simple matriz [1,0]^T El estado Uno es representado por la matriz [0,1]. Estos son conocidos como sus estados base. el superíndice T denota la transposición de la matriz y permite que la matriz se presente horizontalmente.

Estos dos estados básicos son ortonormales, lo cual significa que son ortogonales y normalizados. Juntos son llamados la base computacional o computational basis.

Ortogonal significa que el producto interno de matrices es 0 (producto punto).
$$\begin{equation}
	\begin{bmatrix}
		1\\0
	\end{bmatrix}
	\cdot
		\begin{bmatrix}
			 0\\
			 1
		\end{bmatrix}
		= 1\times0+ 0\times1 = 0 
	\end{equation}
$$
Normalizado significa que las probabilidades de los estados observables suman 1.
La determinación de la probabilidad de los estados cuánticos es fundamental para la teoría cuántica de la información/teoría de la información cuántica.

En la Cuántica el estado cero es representado por el Ket zero en notación de Dirac.
$$\ket{0}$$
Por el contrario, un qubit con un estado uno puede ser escrito como:
$$\ket{1}$$
En notación de Dirac los valores dentro del pipe y del bracket angulado son productos tensoriales.




