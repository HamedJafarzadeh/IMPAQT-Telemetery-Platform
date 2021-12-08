In recent years, terrestrial wireless sensor networks and Internet of Things (IoT) technologies have developed rapidly. However, due to the limitations of Electromagnetic (EM) signal propagation in water, there is less development and advancement in the underwater wireless sensor networks domain. As part of the IMPAQT project, a novel wireless underwater telemetry platform using acoustics has been developed. In the course of the project development, we find-out that there is a lack of datasets for underwater acoustic communications and ocean floor noise. Hence, we are publishing these datsets publicly as part of our paper published in `IARIA 2021 Telecommunication journal`.

There are three types of files in the directory : 

- **.sr file extensions : these files can be opened with [Sigrok Pulseview]
(https://sigrok.org/wiki/Downloads) software.
- **.bin file extensions : these files are the RAW analog data that can captured directly from a 42kHz filter with a passband of 6kHz. These files can be imported in Python or Matlab. They are basically two channel datas, first channel is the analog data and second channel is used to interpret the data. Both channels are captured at 400kHz. You can also import these files in Sigrok PulseView. Import them as `Raw Analog without header` and enter 2 in the channel number field and 400000 in the sample rate field.


The files in this directory are as follow : 

- `BPSK-50BPS :` This Binary-Phase-Shift-Keying modulation dataset is recorded at 400kHz out of 42kHz filter with a passband of 6kHz. The data represents binary sequence of '10101011 01000001` underwater in a water container

- `OOK-50BPS :` This On-Off-Keying modulation dataset is recorded at 400kHz out of 42kHz filter with a passband of 6kHz. The data represents binary sequence of '10101011 01000001` underwater in a water container

- `OOK-BeforeDamping-100BPS :` This On-Off-Keying modulation dataset is recorded at 400kHz out of 42kHz filter with a passband of 6kHz. The data represents binary sequence of '10101011 01000001` underwater in a water container.

- `OOK-AfterDamping-100BPS :` This On-Off-Keying modulation dataset is recorded at 400kHz out of 42kHz filter with a passband of 6kHz. The data represents binary sequence of '10101011 01000001` underwater in a water container. The logic-one duration in this transmission reduced to control the free oscillation period of the piezo transducer

- `Ocean noise at a Pier :` This dataset is a record of Ocean noise at 400kHz out of 42kHz filter with a passband of 6kHz. 

If you found these datasets useful, we would appreciate you cite our publications.

[IMPAQT Miniaturized Underwater Acoustic Telemetry Platform: Transmitter Node System Design](https://cora.ucc.ie/handle/10468/10896)


