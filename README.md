\usepackage{physics}
\usepackage{math}

# HatanO-NelsoN ModeL

### PAPER 1: Localization Transitions in Non-Hermitian Quantum Mechanics

#### Abstract:

We study the localization transitions which arise in both one and two dimensions when quantum
mechanical particles described by a random Schrödinger equation are subjected to a constant imaginary
vector potential. A path-integral formulation relates the transition to flux lines depinned from columnar
defects by a transverse magnetic field in superconductors. The theory predicts that, close to the
depinning transition, the transverse Meissner effect is accompanied by stretched exponential relaxation
of the field into the bulk and a diverging penetration depth.

Notes: 
1. Imaginary Vector Potential: A vector potential is a fundamental concept in quantum mechanics, especially in the context of electromagnetism. An imaginary vector potential may be introduced to study the effects of an imaginary magnetic field or to represent complex interactions within the system.
2. Flux Lines Depinning from Columnar Defects: In superconductors, flux lines (vortices) can become pinned to defects or impurities in the material. Depinning refers to the process where these flux lines overcome the pinning forces and start to move in response to an external influence, such as a magnetic field.
3. Columnar Defects: Columnar defects can be created by introducing impurities, defects, or changes in the crystal lattice structure of a material in a controlled manner. Techniques like ion implantation or irradiation are commonly used to create such defects. The term "columnar" implies that these defects have a linear or elongated structure, often resembling columns or tubes within the material. Columnar defects can strongly influence the electronic properties of a material. In superconductors, for example, they can pin vortices (flux lines), preventing them from moving freely. This pinning effect is crucial for understanding the behavior of superconductors in the presence of external magnetic fields.
4. Flux Pinning: In the context of superconductivity, columnar defects play a critical role in pinning magnetic flux lines (vortices) within the superconducting material. This pinning prevents the vortices from moving when an external magnetic field is applied, which is essential for maintaining the superconducting state in the presence of magnetic fields.
5. Magnetic flux lines: In the context of magnetism, particularly in the presence of a magnetic field, flux lines refer to the imaginary lines that represent the direction and distribution of magnetic flux. These lines are often used to visualize the magnetic field's strength and direction. Magnetic flux (Φ) is a measure of the total magnetic field passing through a given surface. The magnetic field lines or flux lines are used to visualize how the magnetic flux passes through space. The direction of the magnetic field lines points from the north pole of a magnet to its south pole, and these lines form closed loops. Near a permanent magnet or in the vicinity of a current-carrying wire, you can see the arrangement of magnetic flux lines.
6. Path-Integral Formulation: The path-integral formulation is a mathematical approach in quantum mechanics that treats the propagation of a quantum particle as the sum over all possible paths the particle can take. It provides a powerful tool for understanding quantum systems, especially those with complex interactions or disorder.
7. Transverse Magnetic Field: This is an external magnetic field applied perpendicular to the material's surface. It can exert forces on the flux lines in a superconductor, causing them to move and leading to interesting phenomena like the Meissner effect.
8. Meissner effect: Fundamental phenomenon in superconductivity, a state of matter where certain materials can conduct electric current with zero electrical resistance and expel magnetic fields from their interior. When a material undergoes a transition to the superconducting state (usually at very low temperatures), it expels nearly all magnetic flux lines from its interior. This expulsion results in a state of zero magnetic field within the bulk of the superconductor. In other words, it becomes perfectly diamagnetic.
9. Critical Magnetic Field: There is a critical magnetic field strength, known as the "critical field" or "upper critical field," above which the Meissner effect breaks down, and the superconductor returns to its normal (non-superconducting) state.
10. Type I and Type II Superconductors: Superconductors are classified into two main types based on their response to magnetic fields:

    (a) Type I Superconductors: These materials exhibit a sharp and complete Meissner effect. They have a low critical magnetic field and typically expel all magnetic flux.

    (b) Type II Superconductors: These materials exhibit a more complex behavior. They can partially expel magnetic flux but can also allow vortices (flux lines) to penetrate their interior when subjected to strong magnetic fields. Type II superconductors have a higher critical magnetic field.
11. Transverse Meissner Effect: The Meissner effect is a fundamental property of superconductors where they expel magnetic fields from their interior. The transverse Meissner effect specifically refers to the response of a superconductor to a magnetic field applied perpendicular to the material, causing the expulsion of the magnetic field.
12. Diverging Penetration Depth: The penetration depth in superconductivity refers to how deep an external magnetic field can penetrate into the material. In the context of this theory, it is suggested that this penetration depth diverges (becomes infinitely large) close to the depinning transition.


Study involving a non-Hermitian quantum Hamiltonian with randomness. This research is motivated by a mapping between two seemingly different physical systems: the behavior of flux lines in a (d+1)-dimensional superconductor and the world lines of d-dimensional bosons. 

World Lines: In the context of quantum mechanics and quantum field theory, "world lines" are a visualization tool used to represent the trajectories or paths that particles follow through spacetime. Each point along a world line corresponds to the position of a particle at a particular moment in time.

Although the field component Hz parallel to the columns acts as a chemical potential for the bosons, the component perpendicular to the columns results in a constant imaginary vector potential. We study localization in this simple example of nonHermitian quantum mechanics, and show how flux lines are depinned from columnar defects by an increasing perpendicular magnetic field Hp.  It is generally believed that all eigenstates are localized in conventional oneand two-dimensional noninteracting quantum systems with randomness. On the other hand, it is almost obvious that a flux line is depinned from defects by a strong perpendicular field component. This indicates that the present non-Hermitian system has extended states in a large Hp region, and that there must be a delocalization transition at a certain strength of Hp.

Non-Hermitian Hamiltonian written as,

$$H \equiv \frac{(p + ih)^2}{2m} + V(x)$$

where $p = -i\hbar\bigtriangledown$ and V(x) is a random potential. The non-Hermitian filed $\textbf{h}$ orginates in the transverse magnetic field as $\textbf{h} = \phi_0 Hp/4\pi$. The flux quantum $\phi_0 = 2\pi\hbar c/2e$ plays the role of a charge and the non-Hermitian factor $i=\sqrt{-1}$ arises from mapping onto imaginary time quantum mechanics. 

The mass (m) of a particle in the system is equivalent to the "tilt modulus" of the flux line.
In this context, the "tilt modulus" refers to a measure of the resistance or energy cost associated with tilting or deforming the flux line within the superconducting material. The Planck parameter (ħ) corresponds to the temperature (T) of the superconductor. In quantum mechanics, temperature is associated with thermal fluctuations, and the value of ħ may be used to represent these fluctuations in the system. The inverse temperature (1/T) of the quantum system corresponds to the thickness (Lt) of the sample along the Hz direction. In statistical mechanics and thermodynamics, the inverse temperature (1/T) is often used as a parameter to describe the thermal properties of a system. 

Since the field $\textbf{h}$ act as a vector potential, we define the current operator as 

$$J = -i\partial{H}/\partial{h} = (p + ih)/m$$

The imaginary part of the current describes the tilt slope of the flux line. The position
of the flux line x at the distance $\tau$ from the bottom surface of the superconductor is given by

$$\langle x \rangle_\tau = Z^{-1} \langle \psi^f | e^{-(L_\tau - \tau)H/\hbar} x e^{-\tau H/\hbar} | \psi^i \rangle$$

where $\psi^i$ and $\psi^f$ describe boundary conditions at the bottom and top surfaces ($\tau=0, L_\tau$) of the superconductor, respectively. The partition function is,

$$Z \equiv \langle \psi^f | e^{-L_\tau H/\hbar} | \psi^i \rangle$$

The commutation realtion $[H, x] = -i\hbar J$ leads immediately to $(\partial/\partial\tau)\langle x \rangle_\tau = -i\langle J \rangle_\tau = Im\langle J \rangle_\tau$. The total displacement of the flux line between the bottom and the top surfaces is given by 

$$ \langle x \rangle_{L_\tau} - \langle x \rangle = \hbar(\partial/\partial h)lnZ = Im\int_0^{L_\tau} \langle J \rangle_\tau d\tau$$

This quantity is an indicator of the delocalization transition; the transverse displacement of a flux line must be order of the system size when it is depinned.

Let us first consider localized states in a small perpendicular field. Assume the eigenfunctions $\psi_n(x)$ and the eigenvalues $\epsilon_n$ are known for h=0. For small h the right and left eigenvectors of H are given by $\psi_n^R(x;h) = e^{h.x/\hbar}\psi_n(x;h=0)$ and $\psi_n^L(x;h) = e^{-h.x/\hbar}\psi_n(x;h=0)$. The energy eigenvalue $\epsilon_n$ is unchanged under this imaginary gauge transformation. 

However, the above wave functions $\psi_n^R$ and $\psi_n^L$ may diverge as $|x| \rightarrow \infty$ and hence may not be normalizable.
