# Suno Soundforge

A centralized repository for storing AI-generated music from [Suno](https://suno.com), designed to serve as a reliable CDN/URL source for external applications.

## 🎯 Purpose

- **Storage**: Archive and version control for Suno-generated audio tracks.
- **Hosting**: Provide direct access URLs for use in other applications, websites, or media players.
- **Organization**: Maintain a structured library of AI music assets.

## 📂 Recommended Structure

Organize your music files to make them easy to find and reference:

```text
/
├── tracks/
│   ├── [genre]/           # e.g., lo-fi, electronic, classical
│   │   ├── track-name.mp3
│   │   └── ...
│   └── [playlist]/        # e.g., background-music, intro-themes
└── README.md
```

## 🚀 How to Use

### 1. Adding Music
1. Create a directory (e.g., `tracks/`) if it doesn't exist.
2. Upload your `.mp3` or `.wav` files.
3. Commit and push the changes to the repository.

### 2. Getting Direct URLs for Apps

To use the hosted music in another app, use the **Raw** link. 

**Format:**
```
https://raw.githubusercontent.com/[YOUR_GITHUB_USERNAME]/suno-soundforge/main/tracks/[PATH_TO_FILE]
```

**Example:**
If you upload `cyber-dream.mp3` to a `tracks/electronic` folder, the URL would be:
`https://raw.githubusercontent.com/[YOUR_GITHUB_USERNAME]/suno-soundforge/main/tracks/electronic/cyber-dream.mp3`

> **Tip:** You can also use [jsDelivr](https://www.jsdelivr.com/) for a fast CDN link:
> `https://cdn.jsdelivr.net/gh/[YOUR_GITHUB_USERNAME]/suno-soundforge@main/tracks/electronic/cyber-dream.mp3`

## 📄 Metadata

Consider adding a `catalog.json` file if your external app needs to index the available music dynamically.

## 📜 License

Please review [Suno's Terms of Service](https://suno.com/terms) regarding ownership and commercial use of generated audio.
