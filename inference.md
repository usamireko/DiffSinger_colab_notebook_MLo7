### Diffsinger CLI Inference Notebook
----
This is simple notebook that aims to make CLI inference easier for everyone
----

### Parameters
-----
- DS_file = Path of the .ds file (You can generate one on OU by Export Project (Export Diffsinger Script v2)
- model_folder = Path of the acoustic model folder
- speaker_name = Name of the speaker to do inference
- lang = language
- custom_vocoder = Enables the usage of custom vocoders, ignoring the one present in your VB´s config.yaml
- vocoder_type = Changes vocoders, options being NSF-HiFiGAN or DDSP
- custom_vocoder_type = Path of your custom vocoder
- gender = Gender parameter from -1 to 1
- output_path = Path to where to drop the generated WAV
- output_filename = Name of the generated WAV
- seed = seed used when rendering, leave it to the default -1 unless you are doing several tests and consistency is important
- key = Key transition of pitch
- render_steps = How many steps to render, more isnt always better!
- playback = Do you want to listen the result? Click this
