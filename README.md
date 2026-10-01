# Aarya V

Bachelor of Science student at the University of Melbourne building systems software, data pipelines, and interactive mathematical tools.

[LinkedIn](https://www.linkedin.com/in/aarya-vivek) · [YouTube](https://www.youtube.com/@pihedron) · [Email](mailto:aarya.v.web@gmail.com)

![Databricks](https://forthebadge.com/api/badges/generate?panels=2&primaryLabel=Databricks&secondaryLabel=Gen+AI&primaryBGColor=%23ff3622&primaryTextColor=%23FFFFFF&secondaryBGColor=%238acaff&secondaryTextColor=%231b3139&primaryFontSize=12&primaryFontWeight=600&primaryLetterSpacing=2&primaryFontFamily=Roboto&primaryTextTransform=uppercase&secondaryFontSize=12&secondaryFontWeight=900&secondaryLetterSpacing=2&secondaryFontFamily=Montserrat&secondaryTextTransform=uppercase&primaryIcon=databricks&primaryIconColor=%23FFFFFF&primaryIconSize=16&primaryIconPosition=left)
![Power BI](https://forthebadge.com/api/badges/generate?panels=2&primaryLabel=Microsoft&secondaryLabel=Power+BI&primaryBGColor=%23251d20&primaryTextColor=%23FFFFFF&secondaryBGColor=%23f1c911&secondaryTextColor=%23232021&primaryFontSize=12&primaryFontWeight=600&primaryLetterSpacing=2&primaryFontFamily=Roboto&primaryTextTransform=uppercase&secondaryFontSize=12&secondaryFontWeight=900&secondaryLetterSpacing=2&secondaryFontFamily=Montserrat&secondaryTextTransform=uppercase)

## Featured Engineering

### [energy-forecasting](https://github.com/hshmp/energy-forecasting)

End-to-end Databricks lakehouse pipeline forecasting regional electricity grid demand.

- automated ingestion of 5-min interval AEMO price and demand data for Victoria into Unity Catalog Bronze volumes
- silver layer deduplication and filtering into managed Delta tables
- feature engineering in gold with cyclic trigonometric encodings, demand lag steps, and rolling averages
- trained XGBoost model on full-year 2024 data
- export pipeline feeding an interactive Power BI dashboard tracking grid load

### [ascii_stream](https://github.com/hshmp/ascii_stream)

Real-time terminal video player written in Rust for the Windows console.

- child process pipeline streaming raw RGB video frames from ffmpeg over standard output
- real-time luminance mapping to ASCII characters with 24-bit ANSI truecolor escape sequences
- interactive playback engine with frame pacing, runtime speed adjustment, and throttled non-blocking scrubbing
- win32 console buffer manipulation with automated window sizing and vertical font squish correction

### [fib](https://github.com/pihedron/fib)

Arbitrary-precision Fibonacci number calculator in Rust computing the twenty-millionth term in under 1 second.

- custom fast doubling implementation tracking Fibonacci and Lucas number state pairs
- avoids matrix squaring overhead by exploiting Lucas number duality for large-integer arithmetic
- handles negative indices and arbitrary-precision bigints without precision loss
- paired with an algorithmic explainer video reaching over 50k views on YouTube

### Interactive STEM Education [IGCSE Kit](https://github.com/hshmp/igcsekit) & [IGCSE Pages](https://github.com/pihedron/igcse)

Education tools for the Cambridge syllabus built with SvelteKit and TypeScript.

- [set theory visualizer](https://igcse.pages.dev/exams/cie/0580/1) parsing boolean algebra expressions into dynamic SVG Venn diagram region highlights
- reactive number theory engine computing prime factor decomposition ladders, factor combinations, and divisor relationships
- in-browser [pseudocode compiler](https://igcsekit.vercel.app/igcse/computer_science) for Cambridge IGCSE Computer Science with Monaco editor integration
- interactive logic gate truth table generators and biology Punnett square simulators

## Technical Focus

- systems programming and video processing in Rust, C++, Python
- cloud data pipelines on Databricks using Delta Lake, PySpark, and Unity Catalog
- explorable explanations and reactive UI built with SvelteKit and TypeScript
- data analysis in Python, R, SQL, Power BI
- algorithmic optimisation in C, C++, Dart

---

## Achievements

- Databricks Certified Generative AI Engineer Associate
- Microsoft Certified Power BI Data Analyst Associate PL-300 with 900+ score
- #11 nationally in the New Zealand Informatics Competition 2024
- Education Officer at the University of Melbourne Competitive Programming Club
