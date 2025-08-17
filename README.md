# set-mouse-config

A simple `ratbagctl` wrapper to quickly switch libratbag mouse profiles.

---

## Installation

### Arch Linux (AUR)

```bash
yay -S set-mouse-config-git
```

### Manual Installation

Clone the repository and copy the script somewhere in your `$PATH` (e.g. `/usr/local/bin`):

```bash
git clone https://github.com/JonPC4/set-mouse-config.git
cd set-mouse-config
chmod +x smc
sudo cp smc /usr/local/bin/
```

Now `smc` is available system-wide.

---

## Usage

```bash
smc <profile-number>
```

**Example:**

```bash
smc 1
```

This activates profile **1** for the first detected ratbag device.

---

## Requirements

- [libratbag](https://github.com/libratbag/libratbag) (provides `ratbagctl`)
- `bash`
