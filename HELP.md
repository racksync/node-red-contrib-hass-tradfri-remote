<script type="text/markdown" data-help-name="node-type">
### Input

Set tradfri remote node as input entity from Home Assistant.

### Output

Use "TRADFRI Remote" node instead of switch node as output selection, Now you can use the output as `msg.payload` for each action/click  as following.

| Output | Click/Action |
|---------------|---------------|
| `OUTPUT 1`    | toggle |
| `OUTPUT 2`       | toggle hold |
| `OUTPUT 3`   | arrow left click |
| `OUTPUT 4`         | arrow right click |
| `OUTPUT 5`        | brightness up click |
| `OUTPUT 6`   | brightness down click |
| `OUTPUT 7`   | arrow right hold |
| `OUTPUT 8` | arrow left hold |
| `OUTPUT 9`        | brightness up hold |
| `OUTPUT 10`        | brightness down hold |
| `OUTPUT 11`    | arrow left release |
| `OUTPUT 12`    | arrow right release  |
| `OUTPUT 13`    | brightness down release  |
| `OUTPUT 14`    | brightness up release |

### Tips

- It is recommended to always do a full deploy when you changed some of the nodes of this library to prevent unexpected behavior.
- Always use debug node to test message payload before using in Production.

### Automation Training

- [Product & Services](http://racksync.com)
- [Training & Course](https://facebook.com/racksync)

</script>