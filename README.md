<h1 align="center">My VSCode settings</h1>

<p align="center">
    <a href="#features">Features</a> |
    <a href="#settings">Settings</a> 
</p>

# Features
- [x] Minimalist
- [x] Productive
- [x] Responsive 

# Settings

```bash 
{
    // editor config
      "editor.fontFamily": "JetBrains Mono",
      "editor.fontSize": 15,
      "editor.fontLigatures": true,
      "editor.fontWeight": "bold",
      "editor.fastScrollSensitivity": 5,
      "editor.padding.top": 30,
      "editor.padding.bottom": 30,
      "editor.wordWrap": "on",
      "editor.linkedEditing": true,
      "editor.lineHeight": 26,
      "editor.semanticHighlighting.enabled": false,
      "editor.rulers": [
        80,
        120
      ],
      "editor.parameterHints.enabled": false,
      "editor.acceptSuggestionOnCommitCharacter": false,
      "editor.renderLineHighlight": "gutter",
      "editor.suggestSelection": "first",
      "editor.inlineSuggest.enabled": true,
      "editor.inlineSuggest.showToolbar": "never",
      "editor.tabSize": 4,
      "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.addMissingImports": "explicit"
      },
    // workbench config
      "workbench.colorTheme": "Min Dark",
      "workbench.iconTheme": "vs-seti",
      "workbench.productIconTheme": "fluent-icons",
      "workbench.layoutControl.enabled": false,
      "workbench.editor.enablePreview": false,
      "workbench.statusBar.visible": true,
      "workbench.editor.empty.hint": "hidden",
    // window config
      "window.menuBarVisibility": "compact",
      "window.titleBarStyle": "custom",
      "window.commandCenter": false,
      "window.zoomLevel": -1,
    // explorer config
      "explorer.sortOrder": "foldersNestsFiles",
      "explorer.compactFolders": false,
      "explorer.fileNesting.enabled": true,
      "explorer.fileNesting.patterns": {
        "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-lock*, bun.lockb, nest*",
        "tailwind.config.js": "tailwind.config*, postcss.config*",
        ".env.local": ".env*",
        ".env": ".env*"
      },
    // files config
      "files.autoSave": "afterDelay",
      "files.exclude": {
        "**/.svn": true,
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true
      },
      "files.associations": {
        ".sequelizerc": "javascript",
        ".stylelintrc": "json",
        "*.tsx": "typescriptreact",
        ".env.*": "dotenv",
        ".prettierrc": "json"
      },
    // terminal config
      "terminal.integrated.profiles.windows": {
        "Windows Terminal": {
          "path": "C:\\Users\\GR\\AppData\\Local\\Microsoft\\WindowsApps\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\wt.exe",
          "args": [
            "-p",
            "Windows Terminal"
          ],
          "icon": "terminal-powershell"
        }
      },
      "terminal.integrated.defaultProfile.windows": "Windows Terminal",
    // discord presence
      "discord.detailsEditing": "📝 {file_name}({file_size}) ・ ln {current_line}, col {current_column}",
      "discord.lowerDetailsEditing": "📂 {workspace}/{dir_name}",
      // listen coding:
      // "discord.lowerDetailsEditing": "🎶 listen/{dir_name}",
      "discord.detailsIdling": "zzz",
      "discord.idleTimeout": 300,
      "discord.largeImageIdling": "🌙",
      "discord.lowerDetailsIdling": "Idling",
      "discord.largeImage": "Coding in {lang}",
    // liveshare config    
      "liveshare.keepAliveInterval": 200,
      "liveshare.showReadOnlyUsersInEditor": "always",
      "liveshare.anonymousGuestApproval": "accept",
    // syntax config
      "emmet.syntaxProfiles": {
        "javascript": "jsx",
        "javascriptreact": "jsx",
        "typescript": "tsx",
        "typescriptreact": "tsx"
      },
      "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "typescript": "typescriptreact"
      },
    // cspell checker
      "cSpell.language": "pt_BR, en-US",
      "cSpell.userWords": [
        "autofetch",
        "bootcamp",
        "bmewburn",
        "Cascadia",
        "chakra",
        "checkin",
        "checkins",
        "clsx",
        "Codegen",
        "datadog",
        "Datetime",
        "dayjs",
        "Dotenv",
        "esbuild",
        "fastify",
        "Fastify",
        "feedbackwidget",
        "ffprobe",
        "Hono",
        "IUGU",
        "intelephense",
        "jamjuree",
        "jupiter",
        "liveblocks",
        "lockb",
        "LIVEBLOCKS",
        "liveshare",
        "middlewares",
        "mixpanel",
        "monaco",
        "nestjs",
        "omni",
        "Omni",
        "Onboarded",
        "pallas",
        "postgres",
        "postgresql",
        "prefetch",
        "programfiles",
        "reactflow",
        "roboto",
        "rocketseat",
        "rotion",
        "rsxp",
        "Sandpack",
        "Sysnative",
        "sequelizerc",
        "shiki",
        "skylab",
        "stylelintrc",
        "sqlite",
        "supergraph",
        "svgr",
        "sympla",
        "textblock",
        "tiptap",
        "trpc",
        "TRPC",
        "tsup",
        "unfollow",
        "Unfollow",
        "unform",
        "Unform",
        "unmark",
        "upsert",
        "Usuario",
        "WEBPUSH",
        "windir"
      ],
      "cSpell.enableFiletypes": [
        "!asciidoc",
        "!c",
        "!cpp",
        "!csharp",
        "!go",
        "!handlebars",
        "!haskell",
        "!jade",
        "!java",
        "!latex",
        "!php",
        "!pug",
        "!python",
        "!restructuredtext",
        "!rust",
        "!scala",
        "!scss"
      ],
    // javascript config
      "[javascript]": {
        "editor.formatOnSave": false,
        "editor.codeActionsOnSave": {
          "source.fixAll.eslint": "explicit"
        }
      },
      "javascript.suggest.autoImports": true,
      "javascript.updateImportsOnFileMove.enabled": "always",
    // typescript config
      "[typescript]": {
        "editor.formatOnSave": false,
        "editor.codeActionsOnSave": {
          "source.fixAll.eslint": "explicit"
        }
      },
      "typescript.tsserver.log": "off",
      "typescript.suggest.autoImports": true,
      "typescript.updateImportsOnFileMove.enabled": "always",
    // js and ts config
      "[javascript][typescript]": {
        "editor.codeActionsOnSave": {
          "source.fixAll.eslint": "explicit"
        }
      },
    // langs and techs config
      "[prisma]": {
        "editor.formatOnSave": true
      },
      "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
      },
      "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
      },
    // git and github config
      "git.autofetch": true,
      "git.confirmSync": false,
      "git.enableSmartCommit": true,
      "git.ignoreMissingGitWarning": true,
      "git.openRepositoryInParentFolders": "never",
      "githubPullRequests.pullBranch": "never",
      "githubPullRequests.createOnPublishBranch": "never",
      "github.copilot.enable": {
        "*": true,
        "yaml": true,
        "plaintext": false,
        "markdown": true
      },
    // symbols config
      "symbols.hidesExplorerArrows": false,
      "symbols.files.associations": {
        "*.module.ts": "nest",
        "*.guard.ts": "typescript",
        "*.spec.ts": "ts-test",
        "*.e2e-spec.ts": "ts-test",
        "vitest.config.e2e.ts": "vite",
        ".env.example": "gear"
      },
    // tailwind config
      "tailwindCSS.includeLanguages": {
        "plaintext": "html"
      },
      "tailwindCSS.emmetCompletions": true,
      "tailwindCSS.colorDecorators": true,
      "tailwindCSS.validate": true,
      "tailwindCSS.experimental.classRegex": [
        [
          "tv\\(([^)]*)\\)",
          "[\"'`]([^\"'`]*).*?[\"'`]"
        ]
      ],
    // general config
      "update.mode": "start",
      "update.enableWindowsBackgroundUpdates": true,
      "update.showReleaseNotes": false,
      "security.workspace.trust.untrustedFiles": "newWindow",
      "security.promptForLocalFileProtocolHandling": false,
      "extensions.ignoreRecommendations": true,
  }
```

Made with 💜 by Vítor Conceição ▶ [See my LinkdIn](https://www.linkedin.com/in/v%C3%ADtor-concei%C3%A7%C3%A3o-707404227/)

