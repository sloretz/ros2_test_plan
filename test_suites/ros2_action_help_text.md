# Test Case: ros2 action help text

## Make sure there are no typos

1. Run `ros2 action -h`
1. Read the help text and make sure there are no typos

## Make sure only the expected commands are present

1. Run `ros2 action -h`
2. Make sure The help text only shows commands: `info`, `list`, `send_goal`, and `show`.
