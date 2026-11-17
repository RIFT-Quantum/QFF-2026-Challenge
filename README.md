<div align="center">

# Quantum Computing Hackathon Challenge

**RIFT Labs** (Research in Future Technologies)
**The Catholic University of America**, College of Engineering, Physics, and Computing

Qiskit Fall Fest 2026

</div>

---

## Submit here

**[Submission form](https://forms.gle/XzEeSVtTvWzWVVxBA)**

**Deadline: Friday, November 20, 2026, 12:00 noon (Eastern).**

Open the form early so you know what it asks for before you are ready to submit.

---

## The challenge

Two Jupyter notebooks of quantum computing problems. Pick a track, work through the
problems, submit your notebook.

Each problem gives you the background you need, a function to write, and a cell that
checks your answer. No prior quantum experience is needed for Track 1. You do need to
be comfortable writing Python.

### Track 1, eight problems

1. Your first qubit, and loading a probability into it
2. The Bloch sphere, and reading a qubit three ways
3. Entanglement and the four Bell states
4. GHZ states and parity
5. Quantum teleportation
6. Deutsch and Jozsa: one query instead of many
7. Grover search
8. The quantum Fourier transform, and reading a phase out of a gate

### Track 2, four problems

1. **VQE for H₂**, finding a molecule's ground state energy
2. **QAOA for MaxCut**, splitting a graph to cut as many edges as possible
3. **Order finding**, the quantum part of Shor's factoring algorithm
4. **The Steane [[7,1,3]] code**, correcting errors on an encoded qubit

Track 2 assumes what Track 1 covers. Start there if any of it is unfamiliar.

You may submit to both tracks as separate entries.

---

## Files

```
quantum_hackathon_track1_participant.ipynb    Track 1    <- start here
quantum_hackathon_track2_participant.ipynb    Track 2    <- or here
README.md                                     this file
```

The answer keys are published after the deadline.

---

## Setup

```bash
pip install qiskit numpy scipy notebook      # scipy is Track 2 only
jupyter notebook
```

Open your track's notebook and run the cells from the top.

Built against Qiskit 2.6, Python 3.11 or newer.

Everything runs on your own machine. You do not need an IBM Quantum account, an API
token, or any cloud backend, and there is no queue to wait in. Running something on real
hardware as an extension is welcome but not required.

A full run takes about 3 seconds for Track 1 and about 60 seconds for Track 2. If either
one hangs for minutes, something is wrong, so ask an organiser.

---

## How the notebooks work

Each problem has three parts:

1. **Background.** The physics and the maths you need.
2. **Your task.** A function to fill in. Running the empty version is harmless, it just
   defines a stub that does nothing.
3. **Check.** A cell that tests your answer and prints `[ PASS ]` or `[ FAIL ]`. It never
   raises, so a wrong answer does not stop the notebook.

At the bottom of each notebook, `scoreboard()` shows every check at once. A complete
Track 1 passes 20 of 20. A complete Track 2 passes 36 of 36.

**One convention worth knowing up front.** Qiskit puts qubit 0 as the rightmost bit of a
bitstring, so in `|011>` qubit 0 is 1, qubit 1 is 1, and qubit 2 is 0. If an answer comes
out looking mirrored, check this first.

---

## What to submit

Your completed `.ipynb` file with the outputs saved. Run all cells, save, then upload.

Please also:

- Put your name, your team name if you have one, and your track in a markdown cell at
  the top.
- Leave your working visible. Partial credit is real, and a problem you got part way
  through with your reasoning written out counts for more than a blank cell.
- Note anything extra you did in a cell at the bottom and we will look at it.

You do not have to finish everything. Submit what you have by noon on November 20.

**On AI assistants:** allowed, and we would rather you said so than not. If one wrote a
substantial part of a solution, add a short note in that cell. What matters is that you
can explain what you submitted.

---
<div align="center">

**[Submit by Friday, November 20, 2026, 12:00 noon ET](https://forms.gle/XzEeSVtTvWzWVVxBA)**

<br>

<b>RIFT Labs</b> (Research in Future Technologies)<br>
<b>The Catholic University of America</b>, College of Engineering, Physics, and Computing

</div>
