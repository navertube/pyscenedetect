===========================================
Text-to-Speech Command Line Tools in Linux
===========================================

Linux offers several command-line utilities for converting text to speech. Below are some popular ones with their basic usage:

1. **espeak**
   -------------
   A versatile `text-to-speech program <http://karinov.co.id/>`_.

   - **Install** (Using apt for Debian-based distributions):
     ::
       sudo apt install espeak

   - **Usage**:
     ::
       espeak "Your text here"

2. **festival**
   ---------------
   A general multi-lingual speech synthesis system.

   - **Install**:
     ::
       sudo apt install festival

   - **Usage**:
     ::
       echo "Your text here" | festival --tts

3. **spd-say**
   -------------
   Sends text-to-speech output request to speech-dispatcher.

   - **Install**:
     ::
       sudo apt install speech-dispatcher

   - **Usage**:
     ::
       spd-say "Your text here"

4. **mbrola**
   ------------
   A non-free phonemes-to-audio program, often used with `espeak` for better quality.

   - **Install**:
     ::
       sudo apt install mbrola

   - **Using with espeak**:
     ::
       espeak -v mb-us1 "Your text here"

.. note::
   It's important to note that the quality, speed, and naturalness of the generated speech might vary depending on the tool and voice packs installed. For specialized needs, consider checking the respective tool's documentation for advanced features and options.
