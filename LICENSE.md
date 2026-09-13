# Notchpoint licence

Copyright (c) 2026 JKC. All rights reserved.

Notchpoint is free to use, for personal and commercial purposes alike.
It is not open source: the source code is not published, and this licence grants no rights to it.

## You may

- Install and use Notchpoint on any number of machines you own or administer.
- Share the installer, unmodified, as published at <https://github.com/iamprincejkc/Notchpoint/releases>.

## You may not

- Sell Notchpoint, bundle it into a paid product, or charge for access to it.
- Modify, decompile, disassemble or reverse engineer it, except to the extent that right cannot be excluded by law.
- Redistribute a modified copy, or present it as your own work.

## What it does with your data

Notchpoint reads usage figures using credentials that other tools have already written on your machine.
It reads those files and never writes them, and it never refreshes or rotates a token that another tool owns.

Nothing is sent anywhere except to each provider's own usage endpoint, using that provider's own credential.
Gemini usage is read over loopback from a process already running locally, and involves no credential at all.

There is no telemetry, no analytics and no update check.

## No warranty

Notchpoint is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and non-infringement.

In no event shall the author be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from or in connection with the software or its use.
