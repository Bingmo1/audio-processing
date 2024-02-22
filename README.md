class AudioProcessor:
    def __init__(self, audio_file):
        self.audio_file = audio_file

    def process_high_frequency(self):
        print("Processing high-frequency part of audio:", self.audio_file)

# Example usage
processor = AudioProcessor("example_audio.wav")
processor.process_high_frequency()
