# Vibration-Based Fault Diagnosis with Low Delay

This is the code for the paper entitled "**A Hybrid Method for Condition Monitoring and Fault Diagnosis of Rolling Bearings With Low System Delay**", accepted for publication in the IEEE Transactions on Instrumentation and Measurement August 2022. <br>
Authors: Sulaiman Aburakhia, Ryan Myers, and Abdallah Shami. <br>
Organization: The Optimized Computing and Communications (OC2) Lab, ECE Department, Western University, London, Canada. <br>

The system delay of a vibration-based condition monitoring system can be defined as ***the time the system takes to acquire input vibration segment and classify or predict the operational condition of the current state of the equipment***. In vibration-based monitoring, the current state is represented by the input segment of the generated vibration signal. Accordingly, the system delay is the sum of the time duration of input segment and the online processing time. 

<ul>
<li>The time duration of the input segment depends on number of data points in the segment. 
<li>The online processing time is algorithm-dependent; it involves two tasks, feature extraction (including pre-processing) and condition prediction/classification. <br>
</ul>
Hence, online processing time can be generally viewed as a function of the number of data points in the input segment, the size of extracted features, and available computing resources. Based on the above formulation, designing a condition monitoring system with low system delay involves three main requirements: <br>

<ol>
  <li>Extracting features of high sensitivity to fault-related transients to improve system accuracy.</li>
  <li>Extracting features of small size.</li>
  <li>Utilizing input vibration segments of relatively short time duration or equivalently, of small number of data points.</li>
</ol>

Accordignally, the paper utilizes wavelet decomposition and Fourier analysis, and proposes a hybrid method to fulfill the aforementioned requirements and extract a small number of highly discriminative features from short-duration vibration signals.<bR>
  
The Performance of the proposed method is evaluated on [the Case Western Reserve University (CWRU) bearing dataset](https://engineering.case.edu/bearingdatacenter),  [the Paderborn University (PU) bearing dataset](https://mb.uni-paderborn.de/en/kat/main-research/datacenter/bearing-datacenter/data-sets-and-download), and
[the University of Ottawa (uOttawa) bearing dataset](https://data.mendeley.com/datasets/v43hmbwxpm/2). These datasets are selected to simulate various practical situations regarding defect types, rotational speed conditions, and data sampling rate. <br>

## Contact Information
For all inquiries or collaboration opportunities please contact: <br>

Email : saburakh@uwo.ca or Abdallah.Shami@uwo.ca <br>
Github: [SulAburakhia](https://github.com/SulAburakhia) or [Western OC2 Lab](https://github.com/Western-OC2-Lab) <br>
Google Scholar: [OC2 Lab](https://scholar.google.com.eg/citations?user=oiebNboAAAAJ&hl=en); [Sulaiman Aburakhia](https://scholar.google.com/citations?user=8x-pPSYAAAAJ&hl=en)

## Citation

If you find this repository useful in your research, please cite one of the following two articles as:

S. Aburakhia, R. Myers and A. Shami, *"A Hybrid Method for Condition Monitoring and Fault Diagnosis of Rolling Bearings With Low System Delay*," in IEEE Transactions on Instrumentation and Measurement, 2022, doi: 10.1109/TIM.2022.3198477.

@ARTICLE{9855510,
  author={Aburakhia, Sulaiman and Myers, Ryan and Shami, Abdallah},
  journal={IEEE Transactions on Instrumentation and Measurement}, 
  title={A Hybrid Method for Condition Monitoring and Fault Diagnosis of Rolling Bearings With Low System Delay}, 
  year={2022},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TIM.2022.3198477}}
  
## Publication

<ul>
<li>Pre-Print Available.
 </ul>
