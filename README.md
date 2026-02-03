# pi-mono issue evidence

This repo hosts binary artifacts referenced from issue reports.

- `pi-tui-widthchange-clear.gif`: demonstrates a minimal pi-tui repro where a width-change-triggered full re-render emits CSI 3 J (clear scrollback) + clear screen, causing visible flicker and wiping scrollback in many terminals.
