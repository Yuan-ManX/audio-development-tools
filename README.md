# Audio-Processing-Tools-List (APTL)

This is a list of sound, audio processing tools which contains machine learning, audio signal processing, sound synthesis, spatial audio, music information retrieval, music generation, speech recognition, speech synthesis and more.

## Machine Learning (ML)

* [librosa](https://librosa.org/doc/latest/index.html)  Librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.
* [IPython](https://ipython.readthedocs.io/en/stable/index.html)  IPython provides a rich toolkit to help you make the most of using Python interactively.
* [torchaudio](https://github.com/pytorch/audio)  an audio library for PyTorch. Data manipulation and transformation for audio signal processing, powered by PyTorch.
* [praudio](https://github.com/musikalkemist/praudio)  Audio preprocessing framework for Deep Learning audio applications.
* [nnAudio](https://github.com/KinWaiCheuk/nnAudio)  nnAudio is an audio processing toolbox using PyTorch convolutional neural network as its backend. By doing so, spectrograms can be generated from audio on-the-fly during neural network training and the Fourier kernels (e.g. or CQT kernels) can be trained.
* [WavEncoder](https://github.com/shangeth/wavencoder)  WavEncoder is a Python library for encoding audio signals, transforms for audio augmentation, and training audio classification models with PyTorch backend.
* [SciPy](https://scipy.org/)  SciPy (pronounced "Sigh Pie") is an open-source software for mathematics, science, and engineering. It includes modules for statistics, optimization, integration, linear algebra, Fourier transforms, signal and image processing, ODE solvers, and more.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis/)  Python Audio Analysis Library: Feature Extraction, Classification, Segmentation and Applications.
* [dejavu](https://github.com/worldveil/dejavu)  Audio fingerprinting and recognition in Python. Dejavu can memorize audio by listening to it once and fingerprinting it. Then by playing a song and recording microphone input or reading from disk, Dejavu attempts to match the audio against the fingerprints held in the database, returning the song being played.

## Audio Signal Processing (ASP)

* [SoundFile](https://pysoundfile.readthedocs.io/en/latest/)  SoundFile is an audio library based on libsndfile, CFFI and NumPy.
* [Audio DSPy](https://github.com/jatinchowdhury18/audio_dspy)  audio_dspy is a Python package for audio signal processing tools.
* [pyAudioDspTools](https://pyaudiodsptools.readthedocs.io/en/latest/#)  pyAudioDspTools is a python 3 package for manipulating audio by just using numpy.
* [wave](https://docs.python.org/3/library/wave.html)  The wave module provides a convenient interface to the WAV sound format. It does not support compression/decompression, but it does support mono/stereo.
* [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/)  PyAudio provides [Python](http://www.python.org/) bindings for [PortAudio](http://www.portaudio.com/) v19, the cross-platform audio I/O library. With PyAudio, you can easily use Python to play and record audio on a variety of platforms, such as GNU/Linux, Microsoft Windows, and Apple macOS.
* [PortAudio](http://www.portaudio.com/)  PortAudio is a free, cross-platform, [open-source](http://www.portaudio.com/license.html), audio I/O library.  It lets you write simple audio programs in 'C' or C++ that will compile and run on many platforms including Windows, Macintosh OS X, and Unix (OSS/ALSA). It is intended to promote the exchange of audio software between developers on different platforms. Many [applications](http://www.portaudio.com/apps.html) use PortAudio for Audio I/O.
* [Pyo](https://github.com/belangeo/pyo)  pyo is a Python module written in C to help digital signal processing script creation.Python DSP module. With pyo, user will be able to include signal processing chains directly in Python scripts or projects, and to manipulate them in real time through the interpreter
* [sounddevice](https://pypi.org/project/sounddevice/)  This [Python](https://www.python.org/) module provides bindings for the [PortAudio](http://www.portaudio.com/) library and a few convenience functions to play and record [NumPy](https://numpy.org/) arrays containing audio signals.
* [Pydub](https://github.com/jiaaro/pydub)  Manipulate audio with a simple and easy high level interface.
* [TarsosDSP](https://github.com/JorenSix/TarsosDSP)  TarsosDSP is a Java library for audio processing. Its aim is to provide an easy-to-use interface to practical music processing algorithms implemented, as simply as possible, in pure Java and without any other external dependencies.
* [Q](https://cycfi.github.io/q/)  Q is a cross-platform C++ library for Audio Digital Signal Processing. Aptly named after the “Q factor”, a dimensionless parameter that describes the quality of a resonant circuit, the Q DSP Library is designed to be simple and elegant, as the simplicity of its name suggests, and efficient enough to run on small microcontrollers.
* [BasicDSP](https://github.com/trcwm/BasicDSP)  BasicDSP - A tool for processing audio / experimenting with signal processing.
* [Speech Signal Processing Toolkit (SPTK)](http://sp-tk.sourceforge.net/)  The Speech Signal Processing Toolkit (SPTK) is a suite of speech signal processing tools for UNIX environments, e.g., LPC analysis, PARCOR analysis, LSP analysis, PARCOR synthesis filter, LSP synthesis filter, vector quantization techniques, and other extended versions of them.
* [eDSP](https://mohabouje.github.io/edsp-docs/)  *eDSP* (easy Digital Signal Processing) is a digital signal processing framework written in modern C++ that implements some of the common functions and algorithms frequently used in digital signal processing, audio engineering & telecommunications systems.
* [KFR](https://www.kfrlib.com/)  KFR is an open source C++ DSP framework that focuses on high performance. Fast, modern C++ DSP framework, FFT, Sample Rate Conversion, FIR/IIR/Biquad Filters (SSE, AVX, AVX-512, ARM NEON).
* [MWEngine](https://github.com/igorski/MWEngine)  Audio engine and DSP for Android, written in C++ providing low latency performance within a musical context, while providing a Java/Kotlin API. Supports both OpenSL and AAudio.

## Sound Synthesis (SS)

* [pyo-tools](https://github.com/belangeo/pyo-tools)  Repository of ready-to-use python classes for building audio effects and synths with pyo.
* [AudioKit](https://github.com/AudioKit/AudioKit)  AudioKit is an audio synthesis, processing, and analysis platform for iOS, macOS (including Catalyst), and tvOS.
* [Twang](https://github.com/AldaronLau/twang)  Library for pure Rust advanced audio synthesis.
* [Gensound](https://github.com/Quefumas/gensound)  Pythonic audio processing and generation framework. The Python way to audio processing & synthesis.
* [OTTO](https://bitfieldaudio.com/)  The OTTO is a digital hardware groovebox, with synths, samplers, effects and a sequencer with an audio looper. The interface is flat, modular and easy to use, but most of all, it aims to encourage experimentation.
* [Loris](https://github.com/tractal/loris)  Loris is a library for sound analysis, synthesis, and morphing, developed by Kelly Fitz and Lippold Haken at the CERL Sound Group. Loris includes a C++ class library, Python module, C-linkable interface, command line utilities, and documentation.

## Spatial Audio (SA)

* [spaudiopy](https://spaudiopy.readthedocs.io/en/latest/index.html)  Spatial Audio Python Package. The focus (so far) is on spatial audio encoders and decoders. The package includes e.g. spherical harmonics processing and (binaural renderings of) loudspeaker decoders, such as VBAP and AllRAD.
* [Spatial_Audio_Framework (SAF)](https://leomccormack.github.io/Spatial_Audio_Framework/)  The Spatial_Audio_Framework (SAF) is an open-source and cross-platform framework for developing spatial audio related algorithms and software in C/C++. Originally intended as a resource for researchers in the field, the framework has gradually grown into a rather large and well-documented codebase comprising a number of distinct [**modules**](https://github.com/leomccormack/Spatial_Audio_Framework/blob/master/framework/modules); with each module targeting a specific sub-field of spatial audio (e.g. Ambisonics encoding/decoding, spherical array processing, amplitude-panning, HRIR processing, room simulation, etc.).
* [HO-SIRR](https://github.com/leomccormack/HO-SIRR)  Higher-order Spatial Impulse Response Rendering (HO-SIRR) is a rendering method, which can synthesise output loudspeaker array room impulse responses (RIRs) using input spherical harmonic (Ambisonic/B-Format) RIRs of arbitrary order. A MATLAB implementation of the Higher-order Spatial Impulse Response Rendering (HO-SIRR) algorithm; an alternative approach for reproducing Ambisonic RIRs over loudspeakers.
* [SpatGRIS](https://github.com/GRIS-UdeM/SpatGRIS)  SpatGRIS is a sound spatialization software that frees composers and sound designers from the constraints of real-world speaker setups. With the ControlGRIS plugin distributed with SpatGRIS, rich spatial trajectories can be composed directly in your DAW and reproduced in real-time on any speaker layout. It is fast, stable, cross-platform, easy to learn and works with the tools you already know. SpatGRIS supports any speaker setup, including 2D layouts like quad, 5.1 or octophonic rings, and 3D layouts like speaker domes, concert halls, theatres, etc. Projects can also be mixed down to stereo using a binaural head-related transfer function or simple stereo panning.
* [libmysofa](https://github.com/hoene/libmysofa)  Reader for AES SOFA files to get better HRTFs.

## Web Audio Processing (WAP)

* [WebRTC Audio Processing](https://github.com/xiongyihui/python-webrtc-audio-processing)  Python binding of WebRTC Audio Processing.
* [MIDI.js](https://galactic.ink/midi-js/)  🎹 Making life easy to create a MIDI-app on the web. Includes a library to program synesthesia into your app for memory recognition or for creating trippy effects. Convert soundfonts for Guitar, Bass, Drums, ect. into code that can be read by the browser. **[MIDI.js](https://github.com/mudcube/MIDI.js)** ties together, and builds upon frameworks that bring MIDI to the browser. Combine it with [jasmid](https://github.com/gasman/jasmid) to create a web-radio MIDI stream similar to this demo, or with [Three.js](https://github.com/mrdoob/three.js/), [Sparks.js](https://github.com/zz85/sparks.js/), or [GLSL](http://glslsandbox.com/) to create Audio/visual experiments.
* [Web Voice Processor](https://github.com/Picovoice/web-voice-processor)  A library for real-time voice processing in web browsers.
* [Tone.js](https://tonejs.github.io/)  Tone.js is a Web Audio framework for creating interactive music in the browser. The architecture of Tone.js aims to be familiar to both musicians and audio programmers creating web-based audio applications. On the high-level, Tone offers common DAW (digital audio workstation) features like a global transport for synchronizing and scheduling events as well as prebuilt synths and effects. Additionally, Tone provides high-performance building blocks to create your own synthesizers, effects, and complex control signals.

## Music Information Retrieval (MIR)

* [Madmom](https://madmom.readthedocs.io/en/latest/index.html)  Madmom is an audio signal processing library written in Python with a strong focus on music information retrieval (MIR) tasks.

## Music Generation (MG)

* [isobar](https://github.com/ideoforms/isobar)  isobar is a Python library for creating and manipulating musical patterns, designed for use in algorithmic composition, generative music and sonification. It makes it quick and easy to express complex musical ideas, and can send and receive events from various different sources including MIDI, MIDI files, and OSC.
* [MusPy](https://salu133445.github.io/muspy/)  MusPy is an open source Python library for symbolic music generation. It provides essential tools for developing a music generation system, including dataset management, data I/O, data preprocessing and model evaluation.
* [music21](https://web.mit.edu/music21/)  music21 is a Toolkit for Computational Musicology.
* [Mozart](https://github.com/aashrafh/Mozart)  An optical music recognition (OMR) system. Converts sheet music to a machine-readable version. The aim of this project is to develop a sheet music reader. This is called Optical Music Recognition (OMR). Its objective is to convert sheet music to a machine-readable version. We take a simplified version where we convert an image of sheet music to a textual representation that can be further processed to produce midi files or audio files like wav or mp3.
* [MidiTok](https://github.com/Natooz/MidiTok)  A convenient MIDI / symbolic music tokenizer for Deep Learning networks, with multiple strategies .🎶
* [SCAMP](http://scamp.marcevanstein.com/#)  SCAMP is an computer-assisted composition framework in Python designed to act as a hub, flexibly connecting the composer-programmer to a wide variety of resources for playback and notation. SCAMP allows the user to manage the flow of musical time, play notes either using [FluidSynth](http://www.fluidsynth.org/) or via MIDI or OSC messages to an external synthesizer, and ultimately quantize and export the result to music notation in the form of MusicXML or Lilypond. Overall, the framework aims to address pervasive technical challenges while imposing as little as possible on the aesthetic choices of the composer-programmer.
* [Facet](https://github.com/mjcella/facet)  Facet is an open-source live coding system for algorithmic music. With a code editor in the browser and a NodeJS server running locally on your machine, Facet can generate and sequence audio and MIDI data in real-time.Facet is a live coding system for algorithmic music.
* [Mingus](https://github.com/bspaans/python-mingus)  Mingus is a music package for Python. Mingus is a package for Python used by programmers, musicians, composers and researchers to make and analyse music.

## Speech Recognition (ASR)

* [Kaldi](http://kaldi-asr.org/)  Kaldi is a toolkit for speech recognition, intended for use by speech recognition researchers and professionals.
* [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech)  Easy-to-use Speech Toolkit including SOTA/Streaming ASR with punctuation, influential TTS with text frontend, Speaker Verification System, End-to-End Speech Translation and Keyword Spotting.
* [Julius](https://github.com/julius-speech/julius)  Open-Source Large Vocabulary Continuous Speech Recognition Engine. "Julius" is a high-performance, small-footprint large vocabulary continuous speech recognition (LVCSR) decoder software for speech-related researchers and developers. The main platform is Linux and other Unix-based system, as well as Windows, Mac, Androids and other platforms.
* [audino](https://github.com/midas-research/audino)  audino is an open source audio annotation tool. It provides features such as transcription and labeling which enables annotation for Voice Activity Detection (VAD), Diarization, Speaker Identification, Automated Speech Recognition, Emotion Recognition tasks and more.

## Speech Synthesis (TTS)

* [VITS](https://github.com/jaywalnut310/vits)  VITS: Conditional Variational Autoencoder with Adversarial Learning for End-to-End Text-to-Speech. Several recent end-to-end text-to-speech (TTS) models enabling single-stage training and parallel sampling have been proposed, but their sample quality does not match that of two-stage TTS systems. In this work, we present a parallel end-to-end TTS method that generates more natural sounding audio than current two-stage models. Our method adopts variational inference augmented with normalizing flows and an adversarial training process, which improves the expressive power of generative modeling. We also propose a stochastic duration predictor to synthesize speech with diverse rhythms from input text.

## And more
