# Audio-Processing-Tools-List (APTL)

This is a list of sound, audio processing tools which contains machine learning, audio signal processing, sound synthesis, spatial audio, music information retrieval, music generation, speech recognition, speech synthesis and more.

## Machine Learning (ML)

* [librosa](https://librosa.org/doc/latest/index.html)  Librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.
* [IPython](https://ipython.readthedocs.io/en/stable/index.html)  IPython provides a rich toolkit to help you make the most of using Python interactively.
* [torchaudio](https://github.com/pytorch/audio)  an audio library for PyTorch. Data manipulation and transformation for audio signal processing, powered by PyTorch.
* [praudio](https://github.com/musikalkemist/praudio)  Audio preprocessing framework for Deep Learning audio applications.
* [nnAudio](https://github.com/KinWaiCheuk/nnAudio)  nnAudio is an audio processing toolbox using PyTorch convolutional neural network as its backend. By doing so, spectrograms can be generated from audio on-the-fly during neural network training and the Fourier kernels (e.g. or CQT kernels) can be trained.

## Audio Signal Processing (ASP)

* [SoundFile](https://pysoundfile.readthedocs.io/en/latest/)  SoundFile is an audio library based on libsndfile, CFFI and NumPy.
* [Audio DSPy](https://github.com/jatinchowdhury18/audio_dspy)  audio_dspy is a Python package for audio signal processing tools.
* [pyAudioDspTools](https://pyaudiodsptools.readthedocs.io/en/latest/#)  pyAudioDspTools is a python 3 package for manipulating audio by just using numpy.
* [wave](https://docs.python.org/3/library/wave.html)  The wave module provides a convenient interface to the WAV sound format. It does not support compression/decompression, but it does support mono/stereo.
* [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/)  PyAudio provides [Python](http://www.python.org/) bindings for [PortAudio](http://www.portaudio.com/) v19, the cross-platform audio I/O library. With PyAudio, you can easily use Python to play and record audio on a variety of platforms, such as GNU/Linux, Microsoft Windows, and Apple macOS.
* [PortAudio](http://www.portaudio.com/)  PortAudio is a free, cross-platform, [open-source](http://www.portaudio.com/license.html), audio I/O library.  It lets you write simple audio programs in 'C' or C++ that will compile and run on many platforms including Windows, Macintosh OS X, and Unix (OSS/ALSA). It is intended to promote the exchange of audio software between developers on different platforms. Many [applications](http://www.portaudio.com/apps.html) use PortAudio for Audio I/O.
* [sounddevice](https://pypi.org/project/sounddevice/)  This [Python](https://www.python.org/) module provides bindings for the [PortAudio](http://www.portaudio.com/) library and a few convenience functions to play and record [NumPy](https://numpy.org/) arrays containing audio signals.
* [Pydub](https://github.com/jiaaro/pydub)  Manipulate audio with a simple and easy high level interface.
* [TarsosDSP](https://github.com/JorenSix/TarsosDSP)  TarsosDSP is a Java library for audio processing. Its aim is to provide an easy-to-use interface to practical music processing algorithms implemented, as simply as possible, in pure Java and without any other external dependencies.
* [Q](https://cycfi.github.io/q/)  Q is a cross-platform C++ library for Audio Digital Signal Processing. Aptly named after the “Q factor”, a dimensionless parameter that describes the quality of a resonant circuit, the Q DSP Library is designed to be simple and elegant, as the simplicity of its name suggests, and efficient enough to run on small microcontrollers.
* [BasicDSP](https://github.com/trcwm/BasicDSP)  BasicDSP - A tool for processing audio / experimenting with signal processing.
* [Speech Signal Processing Toolkit (SPTK)](http://sp-tk.sourceforge.net/)  The Speech Signal Processing Toolkit (SPTK) is a suite of speech signal processing tools for UNIX environments, e.g., LPC analysis, PARCOR analysis, LSP analysis, PARCOR synthesis filter, LSP synthesis filter, vector quantization techniques, and other extended versions of them.

## Sound Synthesis (SS)

* [pyo-tools](https://github.com/belangeo/pyo-tools)  Repository of ready-to-use python classes for building audio effects and synths with pyo.
* [AudioKit](https://github.com/AudioKit/AudioKit)  AudioKit is an audio synthesis, processing, and analysis platform for iOS, macOS (including Catalyst), and tvOS.
* [Twang](https://github.com/AldaronLau/twang)  Library for pure Rust advanced audio synthesis.

## Spatial Audio (SA)

* [spaudiopy](https://spaudiopy.readthedocs.io/en/latest/index.html)  Spatial Audio Python Package. The focus (so far) is on spatial audio encoders and decoders. The package includes e.g. spherical harmonics processing and (binaural renderings of) loudspeaker decoders, such as VBAP and AllRAD.
* [Spatial_Audio_Framework (SAF)](https://leomccormack.github.io/Spatial_Audio_Framework/)  The Spatial_Audio_Framework (SAF) is an open-source and cross-platform framework for developing spatial audio related algorithms and software in C/C++. Originally intended as a resource for researchers in the field, the framework has gradually grown into a rather large and well-documented codebase comprising a number of distinct [**modules**](https://github.com/leomccormack/Spatial_Audio_Framework/blob/master/framework/modules); with each module targeting a specific sub-field of spatial audio (e.g. Ambisonics encoding/decoding, spherical array processing, amplitude-panning, HRIR processing, room simulation, etc.).
* [HO-SIRR](https://github.com/leomccormack/HO-SIRR)  Higher-order Spatial Impulse Response Rendering (HO-SIRR) is a rendering method, which can synthesise output loudspeaker array room impulse responses (RIRs) using input spherical harmonic (Ambisonic/B-Format) RIRs of arbitrary order. A MATLAB implementation of the Higher-order Spatial Impulse Response Rendering (HO-SIRR) algorithm; an alternative approach for reproducing Ambisonic RIRs over loudspeakers.
* [SpatGRIS](https://github.com/GRIS-UdeM/SpatGRIS)  SpatGRIS is a sound spatialization software that frees composers and sound designers from the constraints of real-world speaker setups. With the ControlGRIS plugin distributed with SpatGRIS, rich spatial trajectories can be composed directly in your DAW and reproduced in real-time on any speaker layout. It is fast, stable, cross-platform, easy to learn and works with the tools you already know. SpatGRIS supports any speaker setup, including 2D layouts like quad, 5.1 or octophonic rings, and 3D layouts like speaker domes, concert halls, theatres, etc. Projects can also be mixed down to stereo using a binaural head-related transfer function or simple stereo panning.
* [libmysofa](https://github.com/hoene/libmysofa)  Reader for AES SOFA files to get better HRTFs.

## Web Audio Processing (WAP)

* [WebRTC Audio Processing](https://github.com/xiongyihui/python-webrtc-audio-processing)  Python binding of WebRTC Audio Processing.
* [MIDI.js](https://galactic.ink/midi-js/)  🎹 Making life easy to create a MIDI-app on the web. Includes a library to program synesthesia into your app for memory recognition or for creating trippy effects. Convert soundfonts for Guitar, Bass, Drums, ect. into code that can be read by the browser. **[MIDI.js](https://github.com/mudcube/MIDI.js)** ties together, and builds upon frameworks that bring MIDI to the browser. Combine it with [jasmid](https://github.com/gasman/jasmid) to create a web-radio MIDI stream similar to this demo, or with [Three.js](https://github.com/mrdoob/three.js/), [Sparks.js](https://github.com/zz85/sparks.js/), or [GLSL](http://glslsandbox.com/) to create Audio/visual experiments.

## Music Information Retrieval (MIR)

* [Madmom](https://madmom.readthedocs.io/en/latest/index.html)  Madmom is an audio signal processing library written in Python with a strong focus on music information retrieval (MIR) tasks.

## Music Generation (MG)

* [isobar](https://github.com/ideoforms/isobar)  isobar is a Python library for creating and manipulating musical patterns, designed for use in algorithmic composition, generative music and sonification. It makes it quick and easy to express complex musical ideas, and can send and receive events from various different sources including MIDI, MIDI files, and OSC.
* [MusPy](https://salu133445.github.io/muspy/)  MusPy is an open source Python library for symbolic music generation. It provides essential tools for developing a music generation system, including dataset management, data I/O, data preprocessing and model evaluation.
* [music21](https://web.mit.edu/music21/)  music21 is a Toolkit for Computational Musicology.
* [Mozart](https://github.com/aashrafh/Mozart)  An optical music recognition (OMR) system. Converts sheet music to a machine-readable version. The aim of this project is to develop a sheet music reader. This is called Optical Music Recognition (OMR). Its objective is to convert sheet music to a machine-readable version. We take a simplified version where we convert an image of sheet music to a textual representation that can be further processed to produce midi files or audio files like wav or mp3.
* [MidiTok](https://github.com/Natooz/MidiTok)  A convenient MIDI / symbolic music tokenizer for Deep Learning networks, with multiple strategies .🎶
* [SCAMP](http://scamp.marcevanstein.com/#)  SCAMP is an computer-assisted composition framework in Python designed to act as a hub, flexibly connecting the composer-programmer to a wide variety of resources for playback and notation. SCAMP allows the user to manage the flow of musical time, play notes either using [FluidSynth](http://www.fluidsynth.org/) or via MIDI or OSC messages to an external synthesizer, and ultimately quantize and export the result to music notation in the form of MusicXML or Lilypond. Overall, the framework aims to address pervasive technical challenges while imposing as little as possible on the aesthetic choices of the composer-programmer.

## Speech Recognition (ASR)

## Speech Synthesis (TTS)

## And more
