# Ragnarok Origin Korea
## Translation File for RO Origins KR

Each line must be translated properly with all backslash/escapes (`\` symbol), curly braces (`{}`) or new lines (`\n`) to be included.

Examples:

1. This line `"AGI 10마다 ASPD+1%"` to be translated into `"ASPD+1% for every 10 AGI."`
2. This line `"\n퀘스트를 클리어 해야 합니다"` to be translated into `"\nClear the required quest."`
3. This line `"<color=#fff94b>Lv.{0}</color> {1} 오픈"` to be translated to `"<color=#fff94b>Lv.{0}</color> {1} Open"`
4. This line `"<color=$$Blue$$>[던전]</color>": "",` to be translated to `"<color=$$Blue$$>[Dungeon]</color>"`

## Files:

* `ro-origin-en.json` - All translated texts will be put here. **This will be the file to be modified**. 
* `data.json` - default KR translation file.
* `merged.json` - An auto-generated file. Combination of `data.json` and `ro-origin-en.kson` file (Mix or KR and EN translated texts)

## How to contribute:

1. Fork the project.
2. Create a topic branch from `master`.
3. Make some changes on the `ro-origin-en.json` file and `commit` to improve the project.
4. Push this branch to your GitHub project.
5. Open a `Pull Request` on GitHub.
6. Discuss, and optionally continue committing.
7. We, the project owner merges or closes the Pull Request.
8. Sync the updated master back to your fork.
