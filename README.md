# KEY

### Copper structure characterization for low-speed designs

Movtivation:

Validate JLC PBC's cheapest controlled impedance 4L board offer for 1 GHz signals.

The goal:

1. Propose common copper structures as 'test cases'.
2. Make the design feel like a template to validate a stackup or stackup change.

Methodology:
1. Capture common copper structures like transitions, stubs and length matching structures.
2. Use standard SMA connectors to interface with a NanoVNA or similar.
3. Measure the desired frequency range and extract S11 and S21 for the different test cases.
4. Evaluate the results and generate design feedback.

### Design History museum

main: First approach to creating a test vehicle that included calibration and a few high-speed tests based on signal integrity problems seen -in scientific papers- in >30 GHz designs.



RevB branch: Major redesign to better reflect the intention of validation low-speed structures. Improves on the calibration section as it now inlcudes a correct SOLT calibration coupon.
