<style>
  /* 1. Style for inline code (text wrapped in single backticks `like this`) */
  :not(pre) > code {
    color: #0072B2 !important;            /* Dark text color for high contrast */
    background-color: #f0f0f0 !important; /* Light gray background box */
    padding: 2px 5px !important;
    border-radius: 4px !important;
    font-size: 0.9em !important;
  }

  /* 2. Style for multi-line code blocks (fenced with ```) */
  pre code, pre code.hljs {
    color: #0072B2 !important;            /* Dark text color for high contrast */
    background-color: #f0f0f0 !important; /* Light gray background box */
    display: block !important;
    padding: 10px !important;
    border-radius: 5px !important;
  }
</style>

# **Gel electrophoresis (Southern)**

Usage amount per slot:

| Material                                         | Concentration | Final concentration | Location         |
| :---------                                       | :-----:       | :---:               | :----------:     |
| PCR product                                      | --            | --                  | 4&deg;C          |
| TAE buffer <sup>&#8251;</sup>                    | 50X           | 0.5X                | II               |
| Agarose gel <sup>&dagger;</sup>                  | --            | 3%                  | II               |
| SYBR<sup>&reg;</sup> stock solution <sup>*</sup> | 1000X         | 1X                  | II               |
| Loading Dye                                      | 6X            | 1X                  | 4&deg;C (c)      |
| RTU-100 (Ladder marker)                          | --            | --                  | 4&deg;C (c)      |
|||||

<sup>&#8251;</sup> To prepare the 0.5X TAE buffer, make at least 1 L, as each run requires at least 500 mL 0.5X TAE buffer.

<sup>&dagger;</sup> The big gel slot requires around 40 mL gel solution; the small gel slot requires 20 mL gel solution. For example, to make a 3% big gel, add 1.2 g agarose powder (ultra pure grade) to 40 mL 0.5X TAE buffer.

<sup>*</sup> To prepare 1000X SYBR stock solution, dilutes 100 &mu;L SYBR<sup>&reg;</sup> raw solution with 900 &mu;L DMSO. This chemical is used to stain the DNA and detected by UV radiation.

<!-- <div style='page-break-after: always;'></div> -->

# Procedure

## **Step 1: Make gel**

1. Prepare the gel. After adding agarose powder into the 0.5X TAE buffer, melt them with microwave. Gently shake the vial during each time points.
> - use mid-low firepower, 1 mins &rarr; 30 secs &rarr; add ddH<sub>2</sub>O &rarr; 20 secs &rarr; 10 secs

2. Add 0.001 volume of SYBR&reg; stock solution into the gel solution immediately ( 1000X &rarr; 1X ), gently shake to mix them well;

> - For example, 40 mL gel requires 40 <i>&mu;</i>L 1000X SYBR stock solution.
3. Pour the gel into the gel container and wait for solidification (around 15 mins);

## **Step 2: Set up the electrode machine**

1. Prepare the electropheresis machine, the electrode direction should be from negative to positive;

2. After the gel was solidified, put the gel container together with the gel into the elctrophoresis machine;

3. Add some TAE buffer (same strength with the gel; 0.5X in this case) into the electropheresis machine 
and make sure the gel was fully submerged in the buffer;

## **Step 3: Load sample**

1. Add loading dye to the PCR product. The loading dye final concentration should be 1X. For example, 2 &mu;L 6X loading dye + 10 &mu;L PCR product;

2. Gently inject 2 &mu;L ladder marker into the first and the last wells of the gel;

3. Gently inject the blank and the PCR products ( around 6 &mu;L ) into the wells;

## **Step 4: Start running**

1. Set the voltage as <b>135 V</b> and the runtime as <b>40 mins</b>;

> - 5 ~ 10 V / cm for DNA size < 1 kb;  
> - 4 ~ 10 V / cm for DNA size between 1 ~ 12 kb;  
> - 1 ~ 3 V / cm for DNA size greater than 12 kb.  
> <i>For our machine, the distance between the electrodes is around 13.5 cm.</i>

## **Step 5: Gel-imaging**

1. Turn on the machine ( Bio-Rad Gel Doc XR+ ).

2. Put in the gel.

3. Start up the `Image Lab` software.

4. `New protocol` &rarr; `Gel imaging`.

6. `Application` &rarr; `Select` &rarr; `Nucleic acid` &rarr; <code>SYBR<sup>&reg;</sup> Safe</code>.

7. `Position Gel` &rarr; `Filter 1` &rarr; adjust gel position.

8. `Run protocol`.

9. `Export for publication` ( Export for analysis is 16-bit images ).

<br><hr><h2 style="text-align: center">Done !!!</h2><hr>

<br>

If you encounter any issues with the protocol, please report them at:  
[https://github.com/P10911004-NPUST/jklai/issues](https://github.com/P10911004-NPUST/jklai/issues).