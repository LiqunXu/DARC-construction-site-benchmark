# DARC Construction Site Benchmark

Static academic project website for the DARC Construction Site Benchmark, an Isaac Sim and Isaac Lab virtual construction site environment for robot training, testing, simulation, and benchmark evaluation.

## Local Preview

```bash
python3 -m http.server 8765
```

Then open `http://localhost:8765/`.

## GitHub Pages Deployment

This repository is ready to publish with GitHub Pages from the `main` branch root.

1. Create an empty GitHub repository, for example `darc-construction-site-benchmark`.
2. Push this local repository:

```bash
git remote add origin https://github.com/LiqunXu/darc-construction-site-benchmark.git
git push -u origin main
```

3. In GitHub, open `Settings -> Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/root`.

The website URL will be:

```text
https://liqunxu.github.io/darc-construction-site-benchmark/
```

Original slides and source demo videos are intentionally ignored because GitHub has a 100 MB file limit. The site uses compressed web-ready videos in `assets/videos/`.
