---
layout: page
title: Rules
---

## Send

You can send your vulnerable machine to our email `vulnyx@protonmail.com` by filling in the following information:

```
VM Name: <machine name>

Level: <machine difficulty (easy, medium & hard)

Creator Name: <name or alias of the creator>

URL: <url where you share your machine with us>

Writeup: <explain to us step by step the solution of the machine (this will only be seen by our team of testers)>

example:
- low user: shellshock (CVE-2014-6271)
- privilege escalation: abuse permissions sudo binary awk (GTFOBins)
```

If you prefer you can also send us the solution in `.pdf` or `video` format (hidden to avoid spoilers).

## Rules

- Do `not` use `content` on the VM that may `offend` other `people`.
- Do `not` use `external URLs` to resolve the VM.
- The VM does `not` have to have a `graphical interface "GUI"` (Unless it is necessary to solve the VM)
- `Delete` or `redirect` any `history` files to `/dev/null` (Unless it is necessary to solve the VM)
- The VM has to have a logic from the beginning to the end.
- The creator has to test the VM to avoid possible bugs.
- The VM has to work correctly in `VirtualBox`.
- The VM must have the `flags`: (`user.txt` & `root.txt`) located in `/home/[user]/user.txt` & `/root/root.txt`
- If the VM requires a `brute force attack`, put a `password` that does `not exceed 5000 lines` of `rockyou.txt`.
- If the VM requires a `domain`/`subdomain` it has to be `.nyx` (example: `domain.nyx`/`subdomain.domain.nyx`)
- We do `not accept VM` that are on `other platforms` (The only reason is because we want to have our own machines)

The VM that does not comply with the rules will be rejected.

## Pull request process (Optional)

After acceptance of your machine, if you want to appear as a <a href="https://github.com/vulnyx/vulnyx.github.io/graphs/contributors" target="_blank">`collaborator`</a> in the official <a href="https://github.com/VulNyx/vulnyx.github.io" target="_blank">`repository`</a> you can do it as follows:

1. Go to <a href="https://github.com/VulNyx/vulnyx.github.io/tree/main/_vms" target="_blank">`_vms/`</a>
2. Click "`Add File`"
3. Click "`Create New File`" create a file with the `name` of your `machine` with extension `.md` (example: `Blog.md`)

Edit this template with your data:

```
---
level:
  Easy:
    -
creator:
  d4t4s3c:
    -
tested:
  VirtualBox:
    -
---
```

The other missing information (`ID`, `URL` & `MD5`) will be filled in by us.

<a href="#" class="bttop">⬆️</a>