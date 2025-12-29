---
layout: default
title: Debian Packaging Mentor
---

<img src="{{ site.baseurl }}/assets/banner.png" alt="Debian Packaging Mentor banner" style="width:100%; border-radius:10px;" />

# Debian Packaging Mentor

Debian Packaging Mentor is an interactive AI assistant that helps developers create, review, and improve Debian packages
following Debian Policy and maintainer best practices.

It acts like a friendly Debian mentor—guiding you from the first `debian/` directory to a package that is suitable for sponsorship review.

<p>
  <a href="https://chatgpt.com/g/g-695266414e1081918bfbaca955bc975c-debian-packaging-mentor"
     style="display:inline-block;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;color:#fff;background:#d70751;">
     Open in ChatGPT
  </a>
  <a href="https://github.com/aleff-github/debian-packaging-mentor"
     style="display:inline-block;margin-left:10px;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;color:#111;background:#eaeaea;">
     View GitHub Repository
  </a>
</p>

---

## Quick Start

Try one of these prompts:

- “Help me create a Debian package for my project. Here is my upstream repo and build system.”
- “Review my `debian/control` and `debian/rules` for Policy compliance.”
- “Here is my `lintian` output. What should I fix first?”
- “I received sponsor feedback on this bug report. Help me understand and apply it.”

---

## What to Share for Best Results

To get accurate, actionable help, paste or attach:

- The full `debian/` directory (all files)
- Clean build logs (preferably from `sbuild` or `pbuilder`)
- Full `lintian` output
- Upstream license files (COPYING/LICENSE) and relevant file headers

---

## Key Features

- Creates and reviews Debian `debian/` packaging files
- Explains Debian Policy in practical terms
- Helps interpret and resolve `lintian` messages
- Suggests sponsor-style improvements
- Supports multiple build systems (CMake, Meson, Autotools, Python, Go, Rust, etc.)

---

## Related Resources

See: [Resources](resources.md)

---

## Disclaimer

Debian is a registered trademark of Software in the Public Interest, Inc.
This project is not affiliated with or endorsed by the Debian Project.

This is **not an official Debian project** and does **not replace** sponsor/mentor review. Debian Policy remains the final authority.

