# scroll_velocity_listener

Wrapper widget for attaining velocity from a scroll view as the scroll changes

## Usage
Wrap the target scroll view with a ScrollVelocityListener widget and you will receive velocity updates via the `onVelocity` callback. The unit returned is pixels per millisecond

```
ScrollVelocityListener(
  onVelocity: (velocity) {
    // Velocity is in pixels per millisecond
  },
  child: ListView(
    children: [
      Container(),
      Container(),
      Container(),
      Container(),
    ],
  ),
);
```
