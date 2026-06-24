# Automatic Control Laboratory Projects

Academic MATLAB/Simulink portfolio completed in a four-person team for the Automatic Control I laboratory at Friedrich-Alexander-Universität Erlangen-Nürnberg.

The work covered nonlinear, electromechanical, automotive, and hydraulic systems. The emphasis was on mathematical modelling, operating-point linearisation, stability analysis, classical and state-space control design, simulation, and interpretation of closed-loop behaviour.

## Tools

- MATLAB
- Simulink
- Control System Toolbox
- Symbolic Math Toolbox

## Methods used

- Nonlinear differential-equation modelling
- Jacobian-based linearisation
- State-space and transfer-function representations
- Pole, zero, and eigenvalue analysis
- Bode and Nyquist methods
- P, PI, and PID controller design
- Ziegler–Nichols and CHR tuning
- Pole placement and LQR
- Feedforward and two-degree-of-freedom control
- Disturbance compensation
- Saturation and anti-windup analysis

## 1. Magnetic Levitation Control

Modelled the electrical coil dynamics and nonlinear magnetic-force subsystem of a magnetic levitation plant. Calculated an equilibrium current, linearised the magnetic dynamics around an operating point, and derived separate transfer functions for the electrical and mechanical subsystems.

The control work included:

- PI design for the electrical inner loop
- Analysis of why PI control was insufficient for the unstable magnetic subsystem
- PID loop shaping for the outer loop
- Nyquist-based closed-loop stability verification
- Gain-margin and phase-margin analysis
- Reference prefilter and feedforward evaluation

**Main learning:** an unstable plant can require additional phase lead beyond what a PI controller can provide, and cascaded-loop design depends on a sufficiently fast and reliable inner loop.

## 2. Quarter-Car Active Suspension

Derived a four-state quarter-car model containing vehicle-body and wheel/tire dynamics. Implemented the state-space matrices in MATLAB and converted the MIMO model to transfer functions for individual input-output paths.

The analysis included:

- Eigenvalue and pole interpretation
- Oscillatory stability assessment
- Pole and zero analysis
- Frequency-response evaluation
- Proportional output-feedback design
- Pole-placement and LQR exercises on state-space examples

**Main learning:** state-space models make coupled suspension dynamics explicit, while transfer paths and frequency responses help connect the model to measurable outputs and controller design.

## 3. Elastically Mounted Rotary Arm

Analysed an elastically mounted rotary-arm plant using transfer-function and frequency-domain methods. Identified critical oscillation conditions and used Ziegler–Nichols rules as a starting point for PI control.

The trajectory and feedforward work included:

- Fifth-order polynomial reference generation
- Position, velocity, acceleration, and jerk boundary conditions
- Feedforward-input calculation from trajectory derivatives
- Actuator-limit checks through transition-time adjustment
- Comparison of 1-DOF and 2-DOF structures
- Separation of reference tracking from disturbance rejection

**Main learning:** feedback is responsible for robustness and disturbance rejection, while feedforward and 2-DOF structures can shape reference behaviour without changing the disturbance-loop denominator.

## 4. Two-Tank Process Control

Modelled a nonlinear hydraulic process using Torricelli’s law and analysed its measured step response. Approximated the process with a first-order-plus-dead-time model and used the identified parameters for CHR PI tuning.

The project also covered:

- Feedforward disturbance compensation
- Pump saturation
- Integral windup
- Back-calculation anti-windup

**Main learning:** a controller that performs well in the linear operating region can degrade under saturation, and anti-windup is necessary when an actuator cannot follow the unconstrained controller demand.

## 5. Nonlinear Control-Loop Analysis

Studied a nonlinear two-state system in MATLAB and Simulink. Calculated Jacobian matrices symbolically and obtained linear models around multiple equilibrium points.

The work included:

- Stability comparison between equilibria
- State-space to transfer-function conversion
- Proportional-gain stability conditions
- Nonlinear and linearised Simulink models
- Disturbance-response comparison
- Discussion of linear-model limitations away from the operating point

**Main learning:** a linearised controller is locally valid; larger reference or disturbance changes can expose nonlinear behaviour that the local model does not represent.

## Academic and authorship notice

These projects were completed as four-person academic team exercises. This page describes the verified technical scope of the shared laboratory work and does not claim sole authorship of every calculation, script, model, or report section.

University instruction material, raw submissions, student identifiers, unofficial communication screenshots, duplicate archives, and files with unverified individual authorship are not published here.
