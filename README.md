# SGTF-Assay

Below is described an S-gene Target Failure Assay that was validated by Imperial College London during the Alpha wave and used for rapid screening of samples before sequencing during subsequent waves. This assay was validated against the TaqPath™ COVID-19 CE-IVD RT-PCR Kit used by North West London Pathology (NWLP) who we worked together with to implement clinical SARS-CoV-2 diagnostics during the pandemic. The cost of this assay is less than £2 per reaction, in comparison to the TaqPath™ COVID-19 CE-IVD RT-PCR Kit which costs approximately £15 per reaction.

## Primers and Probes
These primers and probes were ordered from IDT. We used FAM with an Iowa Black® FQ quencher, but other companies have equivalent options. The ZEN internal quencher is specific to IDT, but is not necessary. The sequence of the probe as ordered from IDT is: /56-FAM/TGGTTCCAT/ZEN/GCTATACATGTCTCTGGG/3IABkFQ/

| Assay Set   | Type | Sequence | Length | Tm | GC Percent |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 69/70 SGTF   | Forward Primer | CATTCAACTCAGGACTTGTTCTT | 23 | 61.17 | 39.13 |
| 69/70 SGTF   | Probe | TGGTTCCATGCTATACATGTCTCTGGG | 27 | 67.299 | 48.148 |
| 69/70 SGTF   | Reverse Primer | GGTTATCAAACCTCTTAGTACCATTG | 26 | 61.593 | 38.462 |

## Reaction Setup
Setup the RT-qPCR with primer and probe concentrations of 500 nM and 125 nM respectively. This protocol was validated with the TaqMan™ Fast Virus 1-Step Master Mix for qPCR (ThermoFisher Scientific) but can be used with any RT-qPCR mix. We have also extensively used the TaqPath™ 1-Step RT-qPCR Master Mix, CG (ThermoFisher Scientific) which is marked "For Laboratory Use" and therefore can be used for diagnostics.

## Thermocycling Conditions

<table>
    <thead>
        <tr>
            <th>Stage</th>
            <th>Temperature</th>
            <th>Time (MM:SS)</th>
            <th>Number of Cycles</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>55 °C</td>
            <td>10:00</td>
            <td>1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>94 °C</td>
            <td>3:00</td>
            <td>1</td>
        </tr>
        <tr>
            <td rowspan=2>3</td>
            <td>94 °C</td>
            <td>00:15</td>
            <td rowspan=2>40</td>
        </tr>
        <tr>
            <td>57 °C</td>
            <td>00:30</td>
        </tr>
    </tbody>
</table>

## Interpretation of Results
This is a dropout assay and therefore you will expect to not see any amplification when there is a variant that has SGTF. Caution is required with low viral load samples as these may not appear to amplify and may be interpreted as an SGTF variant when in fact they would be below the limit of detection.

## More Information
Email me: [m.crone@imperial.ac.uk](mailto:m.crone@imperial.ac.uk)

## Acknowledgements
Michael Crone <br />
Lucy Mosscrop <br />
Graham Taylor <br />
Cindy Madona <br />
Paul Randell <br />
Paul Freemont <br />
Imperial College Lighthouse Lab
