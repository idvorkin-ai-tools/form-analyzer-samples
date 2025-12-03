# Form Analyzer Samples

Sample videos for [FormAnalyzer](https://github.com/idvorkin/swing-analyzer) exercise analysis.

## Structure

```
exercises/
├── kettlebell-swing/
│   ├── good/     # Examples of proper form
│   └── bad/      # Examples of form issues
├── pull-up/
│   ├── good/
│   └── bad/
└── pistol-squat/
    ├── good/
    └── bad/
```

## Usage

Videos can be fetched directly from GitHub raw URLs:

```
https://raw.githubusercontent.com/idvorkin-ai-tools/form-analyzer-samples/main/exercises/kettlebell-swing/good/swing-sample.webm
```

Or use the `index.json` manifest to discover available samples programmatically.

## Contributing

To add new samples:
1. Place video in appropriate `exercises/<type>/good/` or `exercises/<type>/bad/` folder
2. Update `index.json` manifest
3. Create PR
