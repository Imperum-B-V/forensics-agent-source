IMPERUM FORENSICS AGENT - CORRESPONDING SOURCE
=============================================

This repository publishes the complete corresponding source of each version of the
Imperum Forensics Agent, as required by the GNU Affero General Public License
version 3 (AGPL-3.0) under which the agent is distributed.

The agent is a modified version of Velociraptor (https://github.com/Velocidex/
velociraptor), Copyright (C) Rapid 7 Inc, licensed under AGPL-3.0. IMPERUM B.V
rebrands and re-signs the Windows program, re-signs and joins the macOS programs
into one universal application, and ships the Linux program unmodified. Each
release's MODIFICATIONS.md states exactly what was changed and how.

WHERE TO FIND A VERSION
  Every agent version has one GitHub release here, tagged agent-v<version>, with
  one archive attached:
    imperum-agent-<version>-source.tar.gz
  The licence notice shipped with every agent package names the release of its
  own version. The archive holds:
    upstream/          the upstream source at the exact tags used, and the Go
                       modules it links (go mod vendor)
    imperum/           every script and build file IMPERUM B.V uses to build,
                       brand, sign and package the agent
    MODIFICATIONS.md   what was changed, per platform
    LICENSE            the AGPL-3.0 text
    NOTICE             the agent's licence notice
    SOURCES.txt        where each part comes from, with sha256 checksums

VERSIONS
  Agent version   Released     Release          Archive sha256
  -------------   ----------   --------------   ----------------------------------------------------------------
  (one row per agent version, added when its release is published)

WHAT IS NOT HERE
  The Imperum Agent Status tray and the Imperum platform are separate programs of
  IMPERUM B.V, only aggregated with the agent; they are not covered by the
  agent's licence. Signing keys are not part of the source: builds you make run
  unsigned or under your own signature.

CONTACT
  IMPERUM B.V - https://imperum.io
