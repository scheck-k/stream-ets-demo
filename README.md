# Demo Page for: Stream-ETS: Low-latency End-to-end Speech Synthesis from Electromyography Signals

Authors: Kevin Scheck, Darius Ivucic, Zhao Ren, Tanja Schultz (Cognitive Systems Lab, University of Bremen, Germany)

Accepted at ITG Conference on Speech Communication, 2023

### Stream-ETS

Surface Electromyography (EMG) captures the activity of muscles in a non-invasive manner.
EMG signals of articulatory muscles can provide information about the speech production process.
As such, EMG signals during (silent) articulation could be used as alternative to the acoustic speech signal  for speech communication.
Use cases are when speakers are in noisy environments or when they suffer from speech impairments.  
For this task, EMG-to-Speech (ETS) models are trained to synthesize the acoustic speech signal from EMG.
For many speech comunication scenarios, e.g., face-to-face communication, the synthesis should ideally occur with minimal latency in a streamable fashion.

In this work, we propose Stream-ETS, a streamable end-to-end ETS system. Its architecture consists of a causal EMG encoder, processing EMG signals to Mel-spectrograms, and a causal neural vocoder, which predicts the acoustic speech signal. Using a GPU, Stream-ETS outputs acoustic speech from 10 millisecond chunks of EMG in approx. 8 milliseconds, making the system perform in real-time with a low-latency. We first pre-train both components and then perform end-to-end fine-tuning. Experiments indicate that end-to-end training increases the naturalness of the speech synthesis.

### Link to the paper: Following soon
