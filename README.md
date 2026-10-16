# Vivado Report Tool

Scans a Vivado project folder and generates combined reports (timing, utilization, power, DRC, logs) in one place.

## Download

1. Go to the [Releases page](../../releases/latest).
2. Under **Assets**, download:
   - `vivado-report-widget.exe`: floating bubble, stays on top while you use Vivado
   - `vivado-report.exe`: command-line version
3. Double-click to run. No Python or install needed.

> Windows may show "Windows protected your PC". Click **More info**, then **Run anyway**.

## Usage

**Widget:** click the bubble, pick your Vivado project folder, choose scan options, and start the scan. Right-click the bubble to quit.

**Command line:** double-click `vivado-report.exe`, or drag your project folder onto it.

## Output

Files are written into the scanned project folder:

- `combined_vivado_report.md`
- `combined_report.json`
- `knowledge_graph.md`
- `build_trend.md` and `build_comparison.md` (after 2 or more scans of the same project)

## Requirements

- Windows 10/11

## Issues

Found a bug? Open an issue on this repo or contact the author.
