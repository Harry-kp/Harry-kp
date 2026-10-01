<p align="center">
  <img src="assets/terminal.svg" alt="A terminal session: whoami prints 'harshit, backend engineer at BrowserStack, I teach LLMs to spot accessibility bugs'" width="100%"/>
</p>

### Things I built because something annoyed me

| The annoyance | What I did about it |
|---|---|
| My VPN client was a black box. Connected? Leaking DNS? No idea. | [**Vortix**](https://github.com/Harry-kp/vortix): a terminal UI that shows everything, live. Now in Homebrew core, which still surprises me. |
| Every Kafka UI wants a broker string and a JAAS file. AWS MSK just wants IAM. | [**kitz**](https://github.com/Harry-kp/kitz): your Kafka desk clerk. Reads `~/.aws`, skips the paperwork. |
| Postman takes longer to open than my request takes to run. | [**Mercury**](https://github.com/Harry-kp/mercury): a 5 MB API client that opens in 50 ms. Requests are plain files, so git just works. |
| Every approval flow starts as `approved: true` and ends with an auditor asking questions. | [**approval_engine**](https://github.com/Harry-kp/approval_engine): a Rails gem with a ledger that never forgets who said yes. |
| My electricity bill was a mystery and the official app wasn't helping. | [**UPPCL Pro**](https://github.com/Harry-kp/uppcl-pro-app): reverse-engineered the meter's API, built the app I wanted. English and हिन्दी. |
| I forget to blink. | [**AFK**](https://github.com/Harry-kp/afk): takes over the screen every 20 minutes. You can skip it. You shouldn't. |

<details>
<summary><b>Bugs I fixed in other people's code</b></summary>
<br>

- **[Grafana Tempo](https://github.com/grafana/tempo/pull/6532)**: the block builder ignored the storage config you gave it.
- **[Lima](https://github.com/lima-vm/lima/pull/4628)**: `limactl create --name` ignored `--name`.
- **[CocoIndex](https://github.com/cocoindex-io/cocoindex/pull/1704)**: LMDB limits were hardcoded; now you pick.
- **[Maybe Finance](https://github.com/maybe-finance/maybe/pulls?q=author%3AHarry-kp+is%3Amerged)** and **[Ruby for Good](https://github.com/rubyforgood/homeward-tails/pulls?q=author%3AHarry-kp+is%3Amerged)**: six small fixes, from currency formats to letting fosterers actually apply for pets.

</details>

<details>
<summary><b>Borrow my habits</b></summary>
<br>

How I work, packaged as [agent skills](https://github.com/Harry-kp/skills) for Claude Code, Codex, Cursor and friends:

```sh
npx skills add Harry-kp/skills
```

</details>

### Say hi

[blog](https://harrykp.vercel.app/blog) · [linkedin](https://www.linkedin.com/in/harshit-chaudhary-4ab0a01aa/) · [chaudharyharshit9@gmail.com](mailto:chaudharyharshit9@gmail.com)

Open an issue on anything here, or tell me what annoys *you*. That's usually how the next project starts.

<sub>No streak counters, view counters or language pie charts were harmed in the making of this README.</sub>
