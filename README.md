# optical_pumping-quantum_computing

\section{Introduction}

In optical pumping, circularly polarised photons selectively filtered from linearly polarised light $\pi$,
\begin{equation}\label{polarization}
\setlength{\abovedisplayskip}{3pt}
    \pi = \frac{1}{\sqrt{2}}[\sigma _{+} \pm \sigma_{-}]
\setlength{\belowdisplayskip}{3pt}
\end{equation}
 redistribute the electronic states of a sample of rubidium atoms. ($\sigma _{+}$ represents right-hand circularly polarised light and $\m \sigma_{-}$ represents left-hand circularly polarised light). Free rubidium atoms are modelled as a simple hydrogenic system with only the single valence electron investigated. This polarisation imposes a selection rule on the system, therefore providing a constraint on the possible electronic transitions. 

In quantum computing, a qubit, the basic unit of quantum information, is described as a coherent superposition of two quantum states, labelled $|0\rangle$ and $|1\rangle$. \cite{nielsen}. Quantum operations on qubits, i.e. quantum logic gates, form the basis of quantum circuits where initialising the system of qubits is equivalent to identifying the initial state of each qubit.

In particular, we hypothesise the selection rules defined by the polarisation of light may be used in optical pumping to quench our system to a higher energetic state, $|0\rangle$ or a lower  energetic state $|1\rangle$, therefore completely determining the initial state of the system. 

Quantum Supremacy, the hypothesis that quantum processors execute algorithms at an exponentially faster rate compared to classical processors has been supported by experimental evidence by Google \cite{arute}. Quantum algorithms offer a more than polynomial complexity advantage over the most optimal classical algorithms including simulations in solid state physics \cite{aspuru}, approximation of Jones polynomials \cite{wocjan}, and solving Pell's equation \cite{hallgren}.

It is therefore crucial that further experiments are carried out to investigate feasible regimes in which quantum logic gates can be simulated. In optical pumping we demonstrate that for a short timescale the cloud of rubidium gas can be modelled as a collection of qubits with well-posed initial conditions.
