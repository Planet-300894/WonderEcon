# WonderEcon

**WonderEcon** is an interactive LLM-multi-agent economic simulation system in which households, firms, commercial banks, a central bank, and a government interact across five markets, forming a self-consistent macroeconomic loop. Every agent decides through a four-step natural-language *observation–belief–price–action* pipeline, and a player mode lets a human take over one agent as a human-in-the-loop counterfactual.

## Downloads

All related files are distributed through the [**Releases**](../../releases) page. Download the packages you need from there.

| File | Description |
| --- | --- |
| `WonderEcon-v0.0.1.zip` | Source code of the underlying algorithm engine. |
| `06_JSON_house_fix_work1.zip` | Interactive-platform data/assets (required to run the demo). |
| `EWM_Run_Windows1.zip` | Interactive-platform Windows runtime (required to run the demo). |
| `start_observer_mode.bat` | Launcher script for the interactive platform. |

## Running the Interactive Platform

> **Requirements:** Windows only. Python must be installed (Python **3.11 or later** is recommended).

1. From the [Releases](../../releases) page, download all three of the following:
   - `06_JSON_house_fix_work1.zip`
   - `EWM_Run_Windows1.zip`
   - `start_observer_mode.bat`
2. Extract the two `.zip` files into the **same folder**. That folder should then contain:
   ```
   <your-folder>/
   ├── 06_JSON_house_fix_work1/      (extracted)
   ├── EWM_Run_Windows1/             (extracted)
   └── start_observer_mode.bat
   ```
   Make sure `start_observer_mode.bat` sits alongside the two extracted folders (not inside either of them).
3. Double-click **`start_observer_mode.bat`** to launch the system.

## Algorithm Engine

If you only want the underlying simulation engine (without the interactive front end), download and unzip `WonderEcon-v0.0.1.zip` from the [Releases](../../releases) page.
