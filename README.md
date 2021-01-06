# Welcome!

I'm Luke Myers, a second year Computer Science student at UC San Diego.

## Experience

### Robotics

Previously, I was lead programmer and team co-captain of [FRC Team 980 ThunderBots](https://github.com/team980/).

![Picture of me](/robotics.jpg)

> That's me! This was taken at FIRST Championship Houston 2018.

### Android

While with FRC Team 980, I developed **ThunderScout**, a FRC scouting application that follows Google's Material Design principles.

## Extracurricular

### Minecraft

I've also been running Minecraft servers off and on since 2013. My latest one, **TheVortex SMP,** launched on December 15th.

![Minecraft server screenshot](/minecraft.jpg)

> This was the spawn of my old server. Ah, good times...

## Fun Facts

- My favorite Doctor is Peter Capaldi, of course.
- I own *Celeste* on three platforms - Switch, Epic Games, and Stadia.
- I use automatic light/dark mode in my text editors and IDEs.

## Contact

Questions? Comments? Reach out to me on Twitter [@CharAhNalaar](https://twitter.com/CharAhNalaar).

For professional inquiries, you can [contact me on LinkedIn](https://www.linkedin.com/in/luke-myers-55373a1b8/).

## Other

### Java 11

Java 11 is great. Here's a few snippets:

```
event.getRecipients()
    .forEach(p -> {
        if (player != p) {
            checkForMentions(p, event.getMessage());
        }
        p.spigot().sendMessage(message.create());
    });
```

```
return Transformations.map(database.dataDao().getByTeamNumber(eventId, teamNumber),
        list -> list.stream().map(ModelTransformations::fromDataModel).collect(Collectors.toList()));
    
```

```
ViewCompat.setOnApplyWindowInsetsListener(binding.buttonMatchScout, (v, insets) -> {
    CoordinatorLayout.LayoutParams params = (CoordinatorLayout.LayoutParams) v.getLayoutParams();
    params.bottomMargin = InsetUtils.dpToPixel(16, getContext()) + insets.getSystemWindowInsetBottom();
    return insets;
});
```

`var` deserves a shoutout in its own right, it makes reading Java so much nicer!

### TODO

- [x] Create this READMe
- [X] Submit it for my assignment
- [ ] Update wtih ThunderScout 3 repository
- [ ] Remove the extraneous sections