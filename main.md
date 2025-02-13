### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Launch the Agent Home

## Step 1
Navigate the Agent to the launch pad by using the ``||johnsonBuildChallenge:agent move||`` block and then use the ``||johnsonBuildChallenge:agent launch||`` block to send it home. Avoid any obstacles along the way.

#### ~ tutorialhint
Don't launch the Agent too early. If you launch it from anywhere besides the launch pad the Agent will miss it's mark.


```ghost
    johnsonBuildChallenge.agent_move()
    johnsonBuildChallenge.launch_agent()
```
```template
    johnsonBuildChallenge.agent_move(Four_Axis.Forward, 2)
    johnsonBuildChallenge.agent_move(Four_Axis.Right, 3)
    johnsonBuildChallenge.launch_agent()
```

```package
johnson_build_challenge_ts=github:ReWrite-Media/johnson_build_challenge_ts
```