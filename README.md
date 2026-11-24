<h1 align="center"> langdon </h1>

<p align="center"> A filetype to record the messy, but <i>human</i> writing process. </p>

<img src="https://media1.tenor.com/m/iIq6J-tP28AAAAAd/laputa-castle-in-the-sky.gif" width="2000">

### TLDR; What is <b>langdon</b>?
langdon records how a document was written. A **sitting** stores each insertion, deletion, paste, undo, and the time between them. The sealed file is a `.tr` trace. A decoder replays the sitting and reads the process.

## What it is for

The trace is a local provenance log. It shows whether characters arrived one keystroke at a time, in a paste, or through undo. That is evidence about the mechanical process of one sitting.

It is not a detector of who thought of the words. Text typed by hand can still have been read from a model. Software that controls the recorder can synthesize a trace. Readings in the report use process names: incremental composition, mixed entry, block insertion. They do not say "human" or "AI."

