class VideoEditor:
    def __init__(self, video_file):
        self.video_file = video_file

    def add_clip(self, clip):
        print(f"Added clip: {clip}")

    def remove_clip(self, clip):
        print(f"Removed clip: {clip}")

    def export_video(self, output_file):
        print(f"Exported edited video to: {output_file}")

# Example usage
editor = VideoEditor("my_video.mp4")
editor.add_clip("Clip 1")
editor.add_clip("Clip 2")
editor.add_clip("Clip 3")

editor.remove_clip("Clip 2")

editor.export_video("edited_video.mp4")
