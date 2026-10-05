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
      <img src="https://unjuno.github.io/profile-doom/panel-v4-desktop-light.gif" width="800" alt="Runtime 01. A recorded Freedoom replay with the last saved input. One save, everyone plays.">
    </picture>
  </a>
</p>

<table>
  <tr>
    <td align="center"><a aria-label="Move forward" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20forward&amp;body=%2Fforward"><kbd>&nbsp;▲ FORWARD&nbsp;</kbd></a></td>
    <td align="center"><a aria-label="Fire" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20fire&amp;body=%2Ffire"><kbd>&nbsp;FIRE&nbsp;</kbd></a></td>
  </tr>
  <tr>
    <td align="center"><a aria-label="Turn left" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20left&amp;body=%2Fleft"><kbd>&nbsp;◀ LEFT&nbsp;</kbd></a></td>
    <td align="center"><a aria-label="Turn right" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20right&amp;body=%2Fright"><kbd>&nbsp;RIGHT ▶&nbsp;</kbd></a></td>
  </tr>
  <tr>
    <td align="center"><a aria-label="Move back" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20back&amp;body=%2Fback"><kbd>&nbsp;▼ BACK&nbsp;</kbd></a></td>
    <td align="center"><a aria-label="Use or open" href="https://github.com/Unjuno/profile-doom/issues/new?title=runtime%2Finput%3A%20use&amp;body=%2Fuse"><kbd>&nbsp;USE / OPEN&nbsp;</kbd></a></td>
  </tr>
</table>

<p align="center"><sub>Choose an input. GitHub opens a prefilled turn; press <strong>Submit new issue</strong> once to send it.</sub></p>

[Controller](https://github.com/Unjuno/profile-doom/issues/1) · [Runs](https://github.com/Unjuno/profile-doom/actions) · [Save history](https://github.com/Unjuno/profile-doom/commits/main/state/game.json) · [Source](https://github.com/Unjuno/profile-doom)

<sub>One save. Everyone's turn. The replay updates after the Action finishes.</sub>

<details>
<summary><strong>Manual input / fallback</strong></summary>

You can also use the [shared controller](https://github.com/Unjuno/profile-doom/issues/1) and post exactly one command as a comment:

```text
/forward
/back
/left
/right
/fire
/use
```

The profile buttons create one-shot input issues. Valid turns are processed by GitHub Actions and closed automatically after a successful deploy.

</details>

<details>
<summary><strong>How this runs</strong></summary>

| Surface | Job |
| :-- | :-- |
| This README | Display + controller |
| [Issues](https://github.com/Unjuno/profile-doom/issues) | Input queue |
| [GitHub Actions](https://github.com/Unjuno/profile-doom/actions) | Compute |
| [Save slot 0](https://github.com/Unjuno/profile-doom/tree/main/state/save) | Memory |

[Read the current saved input](https://github.com/Unjuno/profile-doom/blob/main/state/game.json) · [Inspect the replay manifest](https://unjuno.github.io/profile-doom/panel-v4.json)

Chocolate Doom + Freedoom. The picture is a recorded replay, not a live stream. GitHub asks for one confirmation before a prefilled input issue is created. Snapshot metadata describes the last persisted command.

A personal experiment, not an official GitHub feature.

</details>

---

<sub>[Elsewhere](http://unjuno.org/) · [Repositories](https://github.com/Unjuno?tab=repositories) · Still a README.</sub>
