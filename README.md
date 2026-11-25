# R11 CyberGym Cloud Preflight

Temporary research runner for the R11 real-vulnerability verification pilot.

This repository intentionally contains no vulnerability payloads, secrets, private data, or agent credentials. The first workflow only checks the GitHub-hosted Ubuntu runner's Docker support, disk, memory, and Docker internal-network isolation. It does **not** pull or execute any vulnerable target image or PoC.

After the preflight, a separate, reviewed workflow will be needed for a single CyberGym task. The benchmark must remain local to the ephemeral runner; no service is exposed publicly.

