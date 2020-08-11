# Test Case: ros2 action info

## Make sure there are no typos

1. Run `ros2 action info -h`
1. Read the help text and make sure there are no typos

## Make sure it can show an action server

1. In one terminal, run `ros2 run examples_rclcpp_minimal_action_server action_server_member_functions`
2. Run `ros2 action info /fibonacci` and make sure it shows 0 clients and 1 server

## Make sure it can show an action client

1. In one terminal, run `ros2 run examples_rclcpp_minimal_action_client action_client_member_functions`
2. Run `ros2 action info /fibonacci` and make sure it shows 1 client and 0 servers
