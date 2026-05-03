# Experiment: Design and Implementation of a 4-Bit Adder in Logisim

## Aim

To design and simulate a 4-bit binary adder using Full Adders in Logisim.

---
## Author

Anshika Bharti
241210019

---

## Theory

A 4-bit adder is a digital circuit used to add two 4-bit binary numbers. It is an extension of the Full Adder concept and is widely used in digital systems for performing arithmetic operations.

### Full Adder

A Full Adder is a combinational circuit that adds three input bits:

* A (input bit)
* B (input bit)
* Cin (carry input)

It produces:

* Sum (S) = A XOR B XOR Cin
* Carry (Cout) = (A AND B) OR (Cin AND (A XOR B))

---

### 4-Bit Adder

A 4-bit adder is constructed by connecting four Full Adders together.

* Each stage adds one bit from the two input numbers along with a carry input.
* The output consists of four sum bits (S3, S2, S1, S0) and one final carry output (Cout).

This arrangement allows the addition of binary numbers up to 4 bits in length.

---

## Tools Used

* Logisim (Digital Circuit Simulator)

---

## Procedure

1. Open Logisim and create a new circuit.
2. Design a Full Adder using logic gates or built-in components.
3. Connect four Full Adders to form a 4-bit adder.
4. Provide inputs A3–A0 and B3–B0.
5. Set the initial carry input (Cin) as required (usually 0).
6. Observe outputs S3–S0 and final carry Cout.
7. Verify the circuit using different input combinations.

---

## Observations

The outputs obtained from the circuit were consistent with expected binary addition results for all tested input combinations.

---

## Result

The 4-bit adder was successfully designed and simulated in Logisim. The circuit correctly performs binary addition of two 4-bit numbers.

---

## Files Included

* 4bit_adder.circ → Implementation of 4-bit adder

---

## Screenshots

(Add your circuit screenshots here)

---

## Applications

* Arithmetic operations in digital systems
* Arithmetic Logic Unit (ALU)
* Microprocessors and embedded systems

---
## Conclusion
The 4-bit adder was successfully designed and implemented in Logisim. The circuit correctly performed binary addition for all input combinations, verifying the working of interconnected Full Adders.
