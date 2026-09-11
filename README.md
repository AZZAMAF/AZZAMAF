# Azzam

**CS Student → Cloud Engineering / DevOps** · Jakarta, Indonesia

Self-directed toward Cloud/DevOps because my degree program doesn't cover it explicitly. I learn by breaking things and fixing them — the project below is the clearest proof of that so far.

---

## Featured Project

### 🖥️ Fedora + Sway — macOS-inspired Linux Desktop
A hand-built tiling WM setup, not a dotfiles clone. Some of the harder problems I actually diagnosed and fixed:

- **Root-caused a CPU throttling bug** on T2 MacBook hardware: `thermald` was forcing `powersave` governor despite safe temps (60–70°C) — fixed by disabling the daemon and manually setting `no_turbo=0` + `performance` governor across all 12 cores.
- **Fixed a GPU rendering crash** in a Flatpak app (Sober/Roblox) that was silently falling back to `llvmpipe` software rendering — forced it onto the discrete AMD Radeon GPU via `MESA_VK_DEVICE_SELECT`, confirmed with `btop` usage before/after.
- Built a custom **Waybar + EWW control panel**, screenshot pipeline (`grim` + `slurp` + `dunst`), and an Alt+Tab switcher (`swayr`) from scratch.

**[→ github.com/YOUR_USERNAME/dotfiles]** *(push it and link it here — this is your strongest proof of work right now)*

---

## Current Focus

Building toward Cloud Engineering with DevOps as the entry point:

| Area | Status |
|---|---|
| Linux administration & networking | Ongoing (daily driver, not just theory) |
| AWS (Cloud Practitioner → SAA) | In progress |
| Docker | Learning |
| Terraform | Learning |
| CI/CD | Not started |

I'd rather show a half-finished project with real bugs I solved than a polished tutorial clone.

---

## Stack

`Linux` `Bash` `AWS` `Docker` `Terraform` `Git`

---

## Contact

- Email: YOUR_EMAIL
- LinkedIn: YOUR_LINKEDIN

*Open to internship / junior Cloud-DevOps opportunities.*
