# PomodoroSlack

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `pomodoro_slack` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:pomodoro_slack, "~> 0.1.0"}]
    end
    ```

  2. Ensure `pomodoro_slack` is started before your application:

    ```elixir
    def application do
      [applications: [:pomodoro_slack]]
    end
    ```

# pomodoro-slack
Slack bot pomodoro

# Useful commands
These are the bot commands:

### /pomodoro start
- Set you as away for 25 minutes
- Fire hooks
- After 25 minutos
- Set you as available
- After for 5 minutes
- Fire hooks
- Set you as away
- After 4 repetition
- Set you as available for 30 minutes
- Fire hooks
- After 30 minutes
- repeat

### /pomodoro stop
- Set you as available
- Fire "stop" hooks

### /pomodoro interrupt "Description of interruption, and can mark users with @"
- Set you available
- Fire custom hook

### /pomodoro continue
- Set you away
- continue last pomodoro

### /pomodoro work
- Set yourselft as away for 25 minutes
- Fire hooks
- After 25 minutes
- set you as available
- Fire hooks

### /pomodoro break
- Set you as available for 5 minutes
- Fire hooks
- After 5 minutes
- set you as unavailable
- Ask if you want to start work
- Fire hooks

### /pomodoro notify #channel
- Set channel to receive a notification when pomodoro start

### /pomodoro notify
- List channels that will be notified when you start pomodoro

# References

* [Slack API](https://api.slack.com/)
  * [User presence](https://api.slack.com/docs/presence)
  * [RTM](https://api.slack.com/rtm)

<a href="https://slack.com/oauth/authorize?scope=incoming-webhook,commands,bot&client_id=17018323921.26424356498"><img alt="Add to Slack" height="40" width="139" src="https://platform.slack-edge.com/img/add_to_slack.png" srcset="https://platform.slack-edge.com/img/add_to_slack.png 1x, https://platform.slack-edge.com/img/add_to_slack@2x.png 2x" /></a>
