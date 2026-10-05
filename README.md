I make things.

<p>
  <a href="https://github.com/Unjuno/profile-doom/issues/1">
    <picture>
      <source media="(prefers-reduced-motion: reduce) and (max-width: 1011px) and (prefers-color-scheme: dark)" srcset="https://unjuno.github.io/profile-doom/panel-v4-mobile-dark.png">
      <source media="(prefers-reduced-motion: reduce) and (max-width: 1011px) and (prefers-color-scheme: light)" srcset="https://unjuno.github.io/profile-doom/panel-v4-mobile-light.png">
      <source media="(prefers-reduced-motion: reduce) and (prefers-color-scheme: dark)" srcset="https://unjuno.github.io/profile-doom/panel-v4-desktop-dark.png">
      <source media="(prefers-reduced-motion: reduce) and (prefers-color-scheme: light)" srcset="https://unjuno.github.io/profile-doom/panel-v4-desktop-light.png">
      <source media="(max-width: 1011px) and (prefers-color-scheme: dark)" srcset="https://unjuno.github.io/profile-doom/panel-v4-mobile-dark.gif">
      <source media="(max-width: 1011px) and (prefers-color-scheme: light)" srcset="https://unjuno.github.io/profile-doom/panel-v4-mobile-light.gif">
      <source media="(prefers-color-scheme: dark)" srcset="https://unjuno.github.io/profile-doom/panel-v4-desktop-dark.gif">
      <img src="https://unjuno.github.io/profile-doom/panel-v4-desktop-light.gif" width="800" alt="Runtime 01. A recorded Freedoom replay with the last saved input. One save, everyone plays. Take a turn: open the GitHub comment controller.">
    </picture>
  </a>
</p>

[**Take a turn →**](https://github.com/Unjuno/profile-doom/issues/1) · [Runs](https://github.com/Unjuno/profile-doom/actions) · [Save history](https://github.com/Unjuno/profile-doom/commits/main/state/game.json) · [Source](https://github.com/Unjuno/profile-doom)

<sub>Shared save. Comment-driven. Replayed here.</sub>

<details>
<summary><strong>Controls</strong></summary>

Open the [controller](https://github.com/Unjuno/profile-doom/issues/1), sign in, and post **one** command as a new comment. Each block has its own copy control.

Forward
```text
/forward
```
Back
```text
/back
```
Turn left
```text
/left
```
Turn right
```text
/right
```
Fire
```text
/fire
```
Use / open
```text
/use
```

Wait for the [run](https://github.com/Unjuno/profile-doom/actions) to finish, then reload this profile. Everyone affects the same session. Clicking the panel opens the controller; it does not send an immediate game input. Image caching may delay the next replay.

</details>

<details>
<summary><strong>How this runs</strong></summary>

| Surface | Job |
| :-- | :-- |
| This README | Display |
| [Issue comments](https://github.com/Unjuno/profile-doom/issues/1) | Input |
| [GitHub Actions](https://github.com/Unjuno/profile-doom/actions) | Compute |
| [Save slot 0](https://github.com/Unjuno/profile-doom/tree/main/state/save) | Memory |

[Read the current saved input](https://github.com/Unjuno/profile-doom/blob/main/state/game.json) · [Inspect the replay manifest](https://unjuno.github.io/profile-doom/panel-v4.json)

Chocolate Doom + Freedoom. The picture is a recorded replay, not a live stream. Its moving line is replay progress, not service health. The input label describes the last persisted command. The game and its snapshot metadata are composed into one image to avoid mixing two separately cached visual assets.

A personal experiment, not an official GitHub feature.

</details>

---

<sub>[Elsewhere](http://unjuno.org/) · [Repositories](https://github.com/Unjuno?tab=repositories) · Still a README.</sub>
