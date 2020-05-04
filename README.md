# tmux-airpods

Shows individual power levels for AirPods and case when connected over bluetooth.

## Installation

Add the following to your `~/.tmux.conf`

```
set -g status-right "#{airpods_battery}"

set -g @plugin 'KernelPanicAUS/tmux-airpods'
```
