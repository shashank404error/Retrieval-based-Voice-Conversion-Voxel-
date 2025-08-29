# Retrieval-based-Voice-Conversion-WebUI for Voxel

This project is a part of a bigger project called Voxel, which converts images into talking videos with voice conversion in real-time. This model is used to convert the input voice into a target voice.

## Quick Start with Docker

To ensure a consistent and reliable setup, the tried and tested way to run this project is by using Docker.

1.  **Build the Docker image:**

    ```bash
    docker build -t rvc-app .
    ```

2.  **Run the Docker container:**

    ```bash
    docker run -p 7860:7860 rvc-app
    ```

This will start the WebUI, which will be accessible at `http://localhost:7860`.

## Using Other RVC Models

You can easily extend the voice conversion capabilities by downloading other pre-trained RVC models.

1.  Download additional RVC models from the Hugging Face repository: [`https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main`](https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main)
2.  Extract the downloaded files.
3.  Replace the entire /assest directory in this project with the downloaded files.
5.  Restart the docker application to use the new model.

## Reference Projects

*   [ContentVec](https://github.com/auspicious3000/contentvec/)
*   [VITS](https://github.com/jaywalnut310/vits)
*   [HIFIGAN](https://github.com/jik876/hifi-gan)
*   [Gradio](https://github.com/gradio-app/gradio)
*   [FFmpeg](https://github.com/FFmpeg/FFmpeg)
*   [Ultimate Vocal Remover](https://github.com/Anjok07/ultimatevocalremovergui)
*   [audio-slicer](https://github.com/openvpi/audio-slicer)
*   [Vocal pitch extraction:RMVPE](https://github.com/Dream-High/RMVPE)
    *   The pretrained model is trained and tested by [yxlllc](https://github.com/yxlllc/RMVPE) and [RVC-Boss](https://github.com/RVC-Boss).

## Acknowledgements

I would like to thank the contributors to the original Retrieval-based-Voice-Conversion-WebUI and all the reference projects that made this work possible.