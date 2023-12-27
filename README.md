
# 8 BIT BARREL SHIFTER SIMULATION AND DESIGN USING CADENCE VIRTUOSO AND XCELIUM.

- Barrel Shifter is a Combinational circuit that can shift or rotate a data word by specific number of bits in a single clock cycle.
- It takes a single cycle to shift or rotate n bits.
- It is used in modern microprocessors.
- It is used in ARM processors with ALU.
- The implemented Shifter is a “Shift Right Logic circuit ” which shifts the bits towards right by specified number of bits.


![Capture](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/08a85e04-1887-4921-bb76-3c0091a2b629)

## SIMULATION OUTPUTS :

![Barrel Process_result](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/9413033c-8305-4670-b528-c56bc2db7d31)

![Barrel Process_Waveform](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/869e52a5-7e2f-4319-8545-dc4554252fbf)

## DESIGN USING CADENCE VIRTUOSO :

- Schematic design of 2:1 Multiplexer.

![image](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/bc2e48c7-c922-4a80-ad1a-66bf6241e627)


## TEST BENCH :

![Barrel_tb](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/2294846c-09c1-4c60-bc31-1c075c668e09)

![Barrel3](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/78f7b388-153b-4c73-b990-7b0729600324)

## RESULTING WAVEFORM :

- Input Bits (A7 - A0) = 11111111
- Select lines (S2 S1 S0) = 111
- Output (Y7 - Y0)= 00000001

![Barrel](https://github.com/abhaysurya1/barrel-shifter/assets/144906236/02eb6279-04ff-4f23-89a7-e1aed00c6116)
