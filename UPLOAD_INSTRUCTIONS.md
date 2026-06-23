# Upload Instructions for Profile README

This folder is your GitHub profile README repository.

GitHub will show this on your profile only if:

1. The repository is public.
2. The repository name is exactly `back2om`.
3. `README.md` is in the root of that repository.

## Steps

1. Go to GitHub and create a public repository named:

```text
back2om
```

Do not initialize it with a README, license, or .gitignore.

2. From this folder, run:

```bash
cd /Projects/Git/back2om

git init
git add README.md UPLOAD_INSTRUCTIONS.md
git commit -m "Add profile README"

git branch -M main
git remote add origin https://github.com/back2om/back2om.git
git push -u origin main
```

3. Edit the placeholders in `README.md`:

- Replace `YOUR-LINKEDIN-SLUG` with your LinkedIn URL slug.
- Replace `YOUR_PUBLIC_EMAIL@example.com` or remove the email badge.

4. Pin your best repositories in this order:

1. ambient-multimodal-clinical-ai
2. birdclef-bioacoustic-soundscape-ai
3. deterministic-agentic-cx
4. agentic-pr-workflow-lab
5. edge-multimodal-inference-lab
6. spark-genomics-kmer-pipeline
