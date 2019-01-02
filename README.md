# Robot Moniker
## Generating new robot names in PyTorch!

### Overview
In this project we'll create new robot names using a Character level RNN model, trained on over 700 robot names from pop-culture over the last century.

The model uses an Encoder-Decoder architecture, where the Encoder works to create character representations for use by the RNN and decoding (output) layers.

The purpose of this project is to help create new robot pet or project names using a fun and novel way.
Feel free to use it, improve and modify it as you wish.  And, if YOUR model comes up with a cool name for a robot you're working on, tweet it to us at @R4Robotics.

**Usage:**
```
python generate.py --names <n>
```
*Where <n> is the number of names to generate*
