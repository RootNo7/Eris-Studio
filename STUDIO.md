# ERIS Studio

ERIS Studio is the central interface for ERIS.

## Main dashboard

The dashboard provides access to:

- Models
- Training
- Experiments
- Datasets
- Evaluation
- Hardware
- Environments
- Deployment
- Assistants
- Research

## Specialized interfaces

Each training system should have an interface appropriate to its task.

### Language model

Show useful information such as:

- loss
- learning rate
- tokens/sec
- evaluation
- resource usage
- checkpoints

### Vision

Potentially:

- images
- detections
- predictions
- datasets
- visual evaluation
- training metrics

### Gaming/environment

Potentially:

- live world
- agent view
- actions
- rewards
- environment state
- replay
- server status
- training metrics

### Speech/audio

Potentially:

- waveform
- spectrogram
- transcription
- generated audio
- latency
- evaluation

## UX

The interface should be understandable to beginners while allowing deeper technical inspection.

Long-running operations must run asynchronously.

The UI should remain responsive rather than freezing during training.