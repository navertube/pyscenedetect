PySceneDetect Documentation
#######################################################################

This documentation covers the PySceneDetect command-line interface (the `scenedetect` command) and Python API (the `scenedetect` module).  The latest release of PySceneDetect can be installed via `pip install scenedetect[opencv]`. Windows builds and source releases can be found at `scenedetect.com/download <http://www.scenedetect.com/download/>`_. Note that PySceneDetect requires `ffmpeg` or `mkvmerge` for video splitting support.

.. note::

     If you see any errors in the documentation, or want to suggest improvements, feel free to raise an issue on `the PySceneDetect issue tracker <https://github.com/Breakthrough/PySceneDetect/issues>`_.

The latest source code for PySceneDetect can be found on Github at `github.com/Breakthrough/PySceneDetect <http://github.com/Breakthrough/PySceneDetect>`_.


***********************************************************************
Table of Contents
***********************************************************************

=======================================================================
``scenedetect`` Command Reference 🖥️
=======================================================================

.. toctree::
    :maxdepth: 2
    :caption: Command-Line Interface [CLI]:
    :name: clitoc

    cli
    cli/config_file
    cli/backends


=======================================================================
``scenedetect`` Python Module 🐍
=======================================================================

.. toctree::
    :maxdepth: 2
    :caption: Python API Documentation:
    :name: apitoc

    api
    api/detectors
    api/backends
    api/scene_manager
    api/video_splitter
    api/stats_manager
    api/frame_timecode
    api/scene_detector
    api/video_stream
    api/platform
    api/migration_guide

=======================================================================
Indices and Tables
=======================================================================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Text-to-Speech (TTS)
======================

Definition
----------
Text-to-speech (TTS) is a form of assistive technology that converts written text into audible speech. This conversion is widely employed to aid those with visual impairments, reading disabilities, and in applications such as GPS, e-learning, and content creation.

How Text-to-Speech Works
------------------------

1. **Text Processing**
   
   - The input text is processed initially. This conversion incorporates punctuation, capitalization, and numbers, which can influence the intonation and rhythm of the resulting speech.
   - Tokenization occurs, breaking down extensive text into smaller units like sentences or words.

2. **Linguistic Analysis**

   - A linguistic examination determines the pronunciation of each word. Homographs, words that are spelled the same but pronounced differently based on their context, are managed using rules to deduce the correct pronunciation.

3. **Speech Synthesis**

   - The speech is synthesized once the system identifies the sounds to produce. Historically, two main methods were employed:
     
     a. **Concatenative TTS:** Utilizes vast databases of pre-recorded speech. Each word or phoneme is recorded multiple times, then assembled to produce fluid speech.
     
     b. **Formant TTS:** Synthesizes speech by generating the vocal tract shapes and sounds characteristic of human speech, though it may sound more robotic.

4. **Deep Learning and Neural Networks**

   - Modern TTS systems often use deep learning. Neural networks, especially recurrent neural networks (RNNs) and transformers, are trained on large datasets to produce incredibly lifelike speech.
   - Models like Google's Tacotron and WaveNet exemplify this, synthesizing realistic speech using neural networks.

5. **Output**

   - The synthesized speech is either broadcasted through a speaker or stored as an audio file.

With continual advancements in AI and deep learning, TTS technology is becoming more realistic and adaptable in its applications. See more: `Sound of text <https://www.voiceoftext.com/p/sound-of-text-wa.html>`_

Countries Frequently Using Text-to-Speech
---------------------------------------------

The adoption of text-to-speech (TTS) technology can be determined by various factors, including technological advancement, educational initiatives, and accessibility requirements. Based on these criteria, here are five countries that have been prominent in the use and development of TTS:

1. **United States**
   - The vast tech industry and an emphasis on accessibility, driven by regulations like the Americans with Disabilities Act, have made the U.S. a significant player in TTS technology. Resource:

2. **Japan**
   - With its technological prowess and an aging demographic that can benefit from assistive tech, Japan has a keen interest in TTS. Please visit `Japanese Text to speech <https://karinov.co.id/japanese-text-to-speech-%e3%83%86%e3%82%ad%e3%82%b9%e3%83%88%e8%aa%ad%e3%81%bf%e4%b8%8a%e3%81%92/>`_ for more information.

3. **United Kingdom**
   - Digital accessibility is a priority in the UK. Regulations ensure that web content is made accessible, often employing TTS where necessary.

4. **Germany**
   - Being a European leader in tech and innovation, Germany uses TTS extensively, especially in sectors like automotive and education. Related tool: `German Text to Speech <https://karinov.co.id/text-in-sprache-umwandeln-german-text-to-speech/>`_

5. **South Korea**
   - `South Korea Text to speech <https://karinov.co.id/korean-text-to-speech-%ed%85%8d%ec%8a%a4%ed%8a%b8%eb%a5%bc-%ec%9d%8c%ec%84%b1%ec%9c%bc%eb%a1%9c-%eb%b3%80%ed%99%98%ed%95%98%ec%84%b8%ec%9a%94/>`_, with its advanced tech landscape and emphasis on education, has integrated TTS into many applications and platforms.

.. note::
   TTS usage is widespread and not limited to technologically advanced nations. The technology holds promise for regions in development, especially in contexts like education. For the most recent data, it's advisable to consult industry reports or contemporary surveys.
