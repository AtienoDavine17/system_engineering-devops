# 0x05. Processes and Signals

## Description
This project covers:
- Listing processes
- Sending and handling signals
- Killing processes with `kill`, `killall`, and `pkill`
- Trapping signals in scripts
- Managing infinite loops

## Scripts

| File Name                 | Description                                      |
|--------------------------|--------------------------------------------------|
| `0-what-is-my-pid`       | Prints the PID of the current shell              |
| `1-list_your_processes`  | Lists all current processes                      |
| `2-show_your_bash_pid`   | Filters processes to show only bash              |
| `4-to_infinity_and_beyond` | Infinite loop with `sleep` and a message      |
| `5-dont_stop_me_now`     | Kills the infinite loop script                   |
| `6-stop_me_if_you_can`   | Stops the infinite loop without `kill` or `killall` |
| `7-highlander`           | Infinite loop that traps `SIGTERM`              |
| `67-stop_me_if_you_can`  | Tries to stop the invincible script              |
| `8-beheaded_process`     | Forcefully kills `7-highlander` with `SIGKILL`  |
