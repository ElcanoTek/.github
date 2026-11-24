<p align="center">
  Self-hosted AI agent infrastructure, client dashboards, inventory intelligence, and supporting tools you run yourself.
  <br>
  <a href="https://elcanotek.com">elcanotek.com</a> · <a href="https://elcanotek.com/fleet">Fleet</a> · <a href="https://flag.elcanotek.com">Flag Design System</a>
</p>

## Platform

<p align="center">
  <a href="https://github.com/ElcanoTek/fleet">
    <img src="https://raw.githubusercontent.com/ElcanoTek/fleet/main/docs/screenshots/web/chat.png" width="100%" alt="Fleet chat UI — a six-week customer kickoff plan with owners and revenue calculation">
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/fleet"><b>fleet</b></a>
  is a general-purpose agent fleet you run yourself — any model, in a sandbox, on a budget, connected to your data.
  <a href="https://elcanotek.com/fleet">elcanotek.com/fleet</a>
</p>

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/ElcanoTek/fleet">
        <img src="https://raw.githubusercontent.com/ElcanoTek/fleet/main/docs/screenshots/web/patrols.png" width="100%" alt="Fleet Patrols — an in-chat recurring patrol checking deal pacing and spend on a weekday schedule">
      </a>
      <br>
      <b>Patrols</b> · recurring scheduled checks in chat
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/ElcanoTek/fleet">
        <img src="https://raw.githubusercontent.com/ElcanoTek/fleet/main/docs/screenshots/web/orchestrator.png" width="100%" alt="Fleet Background tasks — agent slots, task counts, sleeping timers, and scheduled runs">
      </a>
      <br>
      <b>Orchestrator</b> · background tasks, slots, and timers
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/ElcanoTek/pages">
    <img src="https://raw.githubusercontent.com/ElcanoTek/pages/main/docs/images/admin-dashboard.png" width="100%" alt="Pages admin dashboard listing client dashboards with live, draft, and approval-gated status alongside a workspace sidebar">
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/pages"><b>pages</b></a>
  is a self-hosted platform for versioned, access-controlled client dashboards. Agents and humans publish HTML over REST or MCP; every version is reviewable, gated, and reversible.
</p>

<p align="center">
  <a href="https://github.com/ElcanoTek/lens">
    <img src="https://raw.githubusercontent.com/ElcanoTek/lens/main/docs/images/dashboard.png" width="100%" alt="Lens dashboard classifying websites, apps, and CTV channels into quality tiers and IAB content categories">
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/lens"><b>lens</b></a>
  classifies advertising inventory — websites, iOS and Android apps, and CTV channels — into quality tiers with IAB content categories using an escalating crawl ladder and LLM classification.
</p>

<p align="center">
  <a href="https://github.com/ElcanoTek/explorer">
    <img src="https://raw.githubusercontent.com/ElcanoTek/explorer/main/docs/images/explorer-search-results.png" width="100%" alt="Explorer targeted email search view with date range, sender/recipient/subject filters, and message results">
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/explorer"><b>explorer</b></a>
  is a self-hosted web UI for searching raw MIME email archives in Amazon S3, with date-scoped search, message rendering, and attachment downloads.
</p>

<p align="center">
  <a href="https://github.com/ElcanoTek/auth">
    <img src="https://raw.githubusercontent.com/ElcanoTek/auth/main/docs/screenshots/admin.png" width="100%" alt="Auth administrator portal showing account management and application access for Elcano microservices">
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/auth"><b>auth</b></a>
  provides single sign-on, an application launcher, and account administration for Elcano microservices.
</p>

<p align="center">
  <a href="https://flag.elcanotek.com">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ElcanoTek/flag/main/docs/preview-light.png">
      <img src="https://raw.githubusercontent.com/ElcanoTek/flag/main/docs/preview-dark.png" width="100%" alt="Flag design system preview showing the Elcano app header, theme toggle, and color token swatches">
    </picture>
  </a>
  <br>
  <a href="https://github.com/ElcanoTek/flag"><b>flag</b></a>
  is the Elcano design system — shared tokens, icons, and light/dark UI components across every Elcano app.
  <a href="https://flag.elcanotek.com">flag.elcanotek.com</a>
</p>

## Starters &amp; Bridges

- [**example-config**](https://github.com/ElcanoTek/example-config) — Starter Fleet config bundle (personas, protocols, MCPs, and branding) for standing up a new client stack.
- [**example-kubernetes-config**](https://github.com/ElcanoTek/example-kubernetes-config) — Example Kubernetes / Helm deployment configuration for running Fleet on a cluster.
- [**fleet-buzz-bridge**](https://github.com/ElcanoTek/fleet-buzz-bridge) — ACP adapter connecting `fleet acp` to Buzz so agents can answer directly in Buzz threads.
