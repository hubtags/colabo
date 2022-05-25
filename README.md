Type: Object
All animation settings. The only required property is effect.
effect
Type: String
A string indicating which effect to use for the transition.
easing (default: "swing")
Type: String
A string indicating which easing function to use for the transition.
duration (default: 400)
Type: Number or String
A string or number determining how long the animation will run.
complete
Type: Function()
A function to call once the animation is complete, called once per matched element.
queue (default: true)
Type: Boolean or String
A Boolean indicating whether to place the animation in the effects queue. If false, the animation will begin immediately. A string can also be provided, in which case the animation is added to the queue represented by that string.
