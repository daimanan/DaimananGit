# DaimananGit｜代码南途

[简体中文](#zh-cn) · [繁體中文](#zh-tw) · [English](#en) · [Русский](#ru) · [한국어](#ko) · [日本語](#ja)

> 本仓库只发布官方安装包与说明，**不含源代码**。使用许可见 [LICENSE](./LICENSE)。

<a id="zh-cn"></a>

## 简体中文

代码旅途，不再迷路。

DaimananGit 是桌面 Git 客户端。它帮你看清分支和提交，让日常的提交、拉取和冲突更好懂。

简体中文、繁體中文、English、Русский、한국어、日本語都在同一个程序里。任选一个安装包即可，不用按语言分别下载。

### 下载

任选一处打开最新发布，按你的系统点对应文件。`<版本>` 是发布号，例如 `0.8.2`。文件名请保持英文，按后缀选择。

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest)（国际）
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases)（国内镜像，同一套安装包）

**Windows（x64）**

| 类型 | 文件名 |
|------|--------|
| 安装版（推荐，支持应用内更新） | `DaimananGit_<版本>_x64-setup.exe` |
| 解压即用 | `DaimananGit-<版本>-windows-x64-portable.zip` |

**Linux（x64）**

| 类型 | 文件名 |
|------|--------|
| Debian / Ubuntu（推荐） | `DaimananGit_<版本>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<版本>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<版本>-linux-x86_64.pkg.tar.zst` |
| AppImage（通用、免安装） | `DaimananGit_<版本>_amd64.AppImage` |
| 解压即用 | `DaimananGit-<版本>-linux-x64-portable.tar.gz` |

**macOS**

| 类型 | 文件名 |
|------|--------|
| 安装映像 | `DaimananGit_<版本>_*.dmg`（`aarch64` 或 `x64`，按芯片选择） |
| 解压即用 | `DaimananGit-<版本>-macos-aarch64-portable.zip` 或 `…-macos-x64-portable.zip` |

### 装好之后

1. **Windows**：运行安装程序；或把绿色版解压后打开 `DaimananGit.exe`。  
   **Linux**：优先用 deb / rpm / Arch 包安装；或给 AppImage 加上可执行权限后运行；或解压绿色版后执行 `./DaimananGit.sh`。  
   **macOS**：打开 DMG 安装；或解压绿色版后打开其中的 `.app`。
2. 打开 DaimananGit。
3. 确认本机已经安装 `git`。没有的话请先安装，才能打开仓库。

### 运行前需要

- 本机已安装 [Git](https://git-scm.com/)。
- **Windows**：需要 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)。Windows 10 / 11 多数已经自带。
- **Linux**：需要 WebKitGTK 4.1（用 deb / rpm / Arch 包安装时，一般会一并装上）。
  - Debian / Ubuntu：`sudo apt install libwebkit2gtk-4.1-0`
  - Fedora：`sudo dnf install webkit2gtk4.1`
  - openSUSE：`sudo zypper install webkit2gtk3`
  - Arch / Manjaro：`sudo pacman -S webkit2gtk-4.1`

### 切换语言

打开软件后，点顶栏右侧当前的语言名称。可选：简体中文、繁體中文、English、Русский、한국어、日本語。切换立刻生效，下次打开仍然保持。某个词还没有译文时，会显示英文。

### 自动更新

- **Windows 安装版**支持应用内检查更新（签名校验）。有新版本时按提示即可。
- **绿色版**、**Linux**、**macOS** 目前请到上面的 Releases 手动下载替换。
- 更新失败时，可到 GitHub 或 Gitee 手动下载同一版本的安装包。

### 常见问题

| 问题 | 处理 |
|------|------|
| 打不开仓库 / 提示找不到 git | 安装 Git，并确认终端里执行 `git --version` 有输出 |
| Windows 白屏或无法启动 | 安装或修复 WebView2 运行时 |
| Linux AppImage 无法运行 | `chmod +x DaimananGit_*.AppImage`，并安装 WebKitGTK 4.1 |
| 想确认是否官方包 | 只从本页列出的 GitHub / Gitee 官方 Releases 下载；见 [LICENSE](./LICENSE) |

<a id="zh-tw"></a>

## 繁體中文

程式旅途，不再迷路。

DaimananGit 是桌面 Git 用戶端。它幫你看清分支與提交，讓日常的提交、拉取與衝突更好懂。

簡體中文、繁體中文、English、Русский、한국어、日本語都在同一個程式裡。任選一個安裝包即可，不必按語言分開下載。

### 下載

任選一處開啟最新發布，依你的系統點選對應檔案。`<版本>` 是發布號，例如 `0.8.2`。檔名請保持英文，依副檔名選擇。

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest)（國際）
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases)（國內鏡像，同一套安裝包）

**Windows（x64）**

| 類型 | 檔名 |
|------|------|
| 安裝版（建議，支援應用內更新） | `DaimananGit_<版本>_x64-setup.exe` |
| 解壓即用 | `DaimananGit-<版本>-windows-x64-portable.zip` |

**Linux（x64）**

| 類型 | 檔名 |
|------|------|
| Debian / Ubuntu（建議） | `DaimananGit_<版本>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<版本>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<版本>-linux-x86_64.pkg.tar.zst` |
| AppImage（通用、免安裝） | `DaimananGit_<版本>_amd64.AppImage` |
| 解壓即用 | `DaimananGit-<版本>-linux-x64-portable.tar.gz` |

**macOS**

| 類型 | 檔名 |
|------|------|
| 安裝映像 | `DaimananGit_<版本>_*.dmg`（`aarch64` 或 `x64`，依晶片選擇） |
| 解壓即用 | `DaimananGit-<版本>-macos-aarch64-portable.zip` 或 `…-macos-x64-portable.zip` |

### 裝好之後

1. **Windows**：執行安裝程式；或將免安裝版解壓後開啟 `DaimananGit.exe`。  
   **Linux**：優先用 deb / rpm / Arch 包安裝；或替 AppImage 加上執行權限後執行；或解壓免安裝版後執行 `./DaimananGit.sh`。  
   **macOS**：開啟 DMG 安裝；或解壓免安裝版後開啟其中的 `.app`。
2. 開啟 DaimananGit。
3. 確認電腦已安裝 `git`。若尚未安裝，請先安裝，才能開啟儲存庫。

### 執行前需要

- 電腦已安裝 [Git](https://git-scm.com/)。
- **Windows**：需要 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)。Windows 10 / 11 多半已經內建。
- **Linux**：需要 WebKitGTK 4.1（用 deb / rpm / Arch 包安裝時，通常會一併裝上）。
  - Debian / Ubuntu：`sudo apt install libwebkit2gtk-4.1-0`
  - Fedora：`sudo dnf install webkit2gtk4.1`
  - openSUSE：`sudo zypper install webkit2gtk3`
  - Arch / Manjaro：`sudo pacman -S webkit2gtk-4.1`

### 切換語言

開啟軟體後，點選頂端列右側目前的語言名稱。可選：简体中文、繁體中文、English、Русский、한국어、日本語。切換立即生效，下次開啟仍會保留。某個詞還沒有譯文時，會顯示英文。

### 自動更新

- **Windows 安裝版**支援應用內檢查更新（簽名驗證）。有新版本時依提示操作即可。
- **免安裝版**、**Linux**、**macOS** 目前請到上方 Releases 手動下載替換。
- 更新失敗時，可到 GitHub 或 Gitee 手動下載同一版本的安裝包。

### 常見問題

| 問題 | 處理 |
|------|------|
| 打不開儲存庫 / 提示找不到 git | 安裝 Git，並確認終端機執行 `git --version` 有輸出 |
| Windows 白畫面或無法啟動 | 安裝或修復 WebView2 執行階段 |
| Linux AppImage 無法執行 | `chmod +x DaimananGit_*.AppImage`，並安裝 WebKitGTK 4.1 |
| 想確認是否為官方包 | 只從本頁列出的 GitHub / Gitee 官方 Releases 下載；見 [LICENSE](./LICENSE) |

<a id="en"></a>

## English

Navigate your code journey.

DaimananGit is a desktop Git client. It helps you see branches and commits clearly, and makes everyday commits, pulls, and conflicts easier to follow.

简体中文, 繁體中文, English, Русский, 한국어, and 日本語 ship in the same app. Download any package — there is no separate build per language.

### Download

Open the latest release from either host and pick the file for your system. `<version>` is the release number, for example `0.8.2`. Keep the English file names and match the suffix.

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest) (global)
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases) (China mirror, same packages)

**Windows (x64)**

| Type | File name |
|------|-----------|
| Installer (recommended; in-app updates) | `DaimananGit_<version>_x64-setup.exe` |
| Portable | `DaimananGit-<version>-windows-x64-portable.zip` |

**Linux (x64)**

| Type | File name |
|------|-----------|
| Debian / Ubuntu (recommended) | `DaimananGit_<version>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<version>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<version>-linux-x86_64.pkg.tar.zst` |
| AppImage (no install) | `DaimananGit_<version>_amd64.AppImage` |
| Portable | `DaimananGit-<version>-linux-x64-portable.tar.gz` |

**macOS**

| Type | File name |
|------|-----------|
| Disk image | `DaimananGit_<version>_*.dmg` (`aarch64` or `x64`, match your chip) |
| Portable | `DaimananGit-<version>-macos-aarch64-portable.zip` or `…-macos-x64-portable.zip` |

### After you install

1. **Windows**: run the installer, or unzip the portable build and open `DaimananGit.exe`.  
   **Linux**: prefer the deb / rpm / Arch package; or mark the AppImage executable and run it; or unpack the portable archive and run `./DaimananGit.sh`.  
   **macOS**: open the DMG, or unpack the portable zip and open the `.app`.
2. Open DaimananGit.
3. Make sure `git` is installed. The app needs it before it can open a repository.

### Before you run it

- [Git](https://git-scm.com/) is installed.
- **Windows**: [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) is required. Most Windows 10 and 11 systems already have it.
- **Linux**: WebKitGTK 4.1 is required (usually pulled in by deb / rpm / Arch packages).
  - Debian / Ubuntu: `sudo apt install libwebkit2gtk-4.1-0`
  - Fedora: `sudo dnf install webkit2gtk4.1`
  - openSUSE: `sudo zypper install webkit2gtk3`
  - Arch / Manjaro: `sudo pacman -S webkit2gtk-4.1`

### Change language

After the app opens, click the language name on the right side of the top bar. Choices: 简体中文, 繁體中文, English, Русский, 한국어, 日本語. The switch is instant and is remembered next time. If a phrase has no translation yet, it falls back to English.

### Auto-update

- The **Windows installer** can check for updates in-app (signature verified). Follow the prompts when a new version is available.
- **Portable**, **Linux**, and **macOS** builds: download a newer package from Releases and replace manually for now.
- If an update fails, download the same version’s installer from GitHub or Gitee.

### FAQ

| Issue | What to try |
|-------|-------------|
| Cannot open a repo / git not found | Install Git and confirm `git --version` works in a terminal |
| Windows blank window or won’t start | Install or repair the WebView2 runtime |
| Linux AppImage won’t run | `chmod +x DaimananGit_*.AppImage` and install WebKitGTK 4.1 |
| Is this an official build? | Download only from the GitHub / Gitee Releases linked above; see [LICENSE](./LICENSE) |

<a id="ru"></a>

## Русский

Путь по коду — без блужданий.

DaimananGit — настольный клиент Git. Он показывает ветки и коммиты, а обычные коммиты, получение изменений и конфликты становятся понятнее.

简体中文, 繁體中文, English, Русский, 한국어 и 日本語 уже внутри одной программы. Скачайте любой пакет — отдельной сборки для языка нет.

### Скачать

Откройте последний выпуск на любом из сайтов и выберите файл для своей системы. `<версия>` — номер выпуска, например `0.8.2`. Имена файлов оставляйте на английском и сверяйте окончание.

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest) (международный)
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases) (зеркало в Китае, те же пакеты)

**Windows (x64)**

| Тип | Имя файла |
|-----|-----------|
| Установщик (рекомендуется; обновления в приложении) | `DaimananGit_<версия>_x64-setup.exe` |
| Портативная сборка | `DaimananGit-<версия>-windows-x64-portable.zip` |

**Linux (x64)**

| Тип | Имя файла |
|-----|-----------|
| Debian / Ubuntu (рекомендуется) | `DaimananGit_<версия>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<версия>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<версия>-linux-x86_64.pkg.tar.zst` |
| AppImage (без установки) | `DaimananGit_<версия>_amd64.AppImage` |
| Портативная сборка | `DaimananGit-<версия>-linux-x64-portable.tar.gz` |

**macOS**

| Тип | Имя файла |
|-----|-----------|
| Образ диска | `DaimananGit_<версия>_*.dmg` (`aarch64` или `x64`, по чипу) |
| Портативная сборка | `DaimananGit-<версия>-macos-aarch64-portable.zip` или `…-macos-x64-portable.zip` |

### После установки

1. **Windows**: запустите установщик или распакуйте портативную сборку и откройте `DaimananGit.exe`.  
   **Linux**: предпочтительно deb / rpm / Arch; либо сделайте AppImage исполняемым; либо распакуйте архив и выполните `./DaimananGit.sh`.  
   **macOS**: откройте DMG или распакуйте zip и откройте `.app`.
2. Откройте DaimananGit.
3. Убедитесь, что установлен `git`. Без него программа не откроет репозиторий.

### Что нужно заранее

- Установленный [Git](https://git-scm.com/).
- **Windows**: нужен [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/). В большинстве систем Windows 10 и 11 он уже есть.
- **Linux**: нужен WebKitGTK 4.1 (обычно ставится вместе с deb / rpm / Arch).
  - Debian / Ubuntu: `sudo apt install libwebkit2gtk-4.1-0`
  - Fedora: `sudo dnf install webkit2gtk4.1`
  - openSUSE: `sudo zypper install webkit2gtk3`
  - Arch / Manjaro: `sudo pacman -S webkit2gtk-4.1`

### Смена языка

После запуска нажмите название языка справа на верхней панели. Варианты: 简体中文, 繁體中文, English, Русский, 한국어, 日本語. Смена сразу вступает в силу и запоминается. Если для фразы ещё нет перевода, показывается английский текст.

### Автообновление

- **Установщик Windows** может проверять обновления в приложении (с проверкой подписи). Следуйте подсказкам при новой версии.
- **Портативные**, **Linux** и **macOS** сборки: пока скачивайте новый пакет из Releases вручную.
- Если обновление не удалось — скачайте тот же установщик с GitHub или Gitee.

### Частые вопросы

| Проблема | Что сделать |
|----------|-------------|
| Не открывается репозиторий / нет git | Установите Git и проверьте `git --version` в терминале |
| Белый экран или не запускается в Windows | Установите или восстановите WebView2 |
| AppImage в Linux не запускается | `chmod +x DaimananGit_*.AppImage` и установите WebKitGTK 4.1 |
| Это официальная сборка? | Скачивайте только с указанных GitHub / Gitee Releases; см. [LICENSE](./LICENSE) |

<a id="ko"></a>

## 한국어

코드 여정에서 길을 잃지 마세요.

DaimananGit은 데스크톱 Git 클라이언트입니다. 브랜치와 커밋을 분명히 보여주고, 평소의 커밋, 가져오기, 충돌을 더 쉽게 따라가게 합니다.

简体中文, 繁體中文, English, Русский, 한국어, 日本語가 같은 프로그램 안에 있습니다. 꾸러미는 하나만 받으면 됩니다. 언어별로 따로 받지 않습니다.

### 다운로드

아래 중 한곳에서 최신 릴리스를 열고 시스템에 맞는 파일을 고르세요. `<버전>`은 릴리스 번호입니다. 예: `0.8.2`. 파일 이름은 영어 그대로 두고, 끝부분으로 맞는 꾸러미를 고르세요.

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest) (해외)
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases) (국내 미러, 동일 패키지)

**Windows (x64)**

| 종류 | 파일 이름 |
|------|-----------|
| 설치판 (권장, 앱 내 업데이트) | `DaimananGit_<버전>_x64-setup.exe` |
| 압축 풀기 판 | `DaimananGit-<버전>-windows-x64-portable.zip` |

**Linux (x64)**

| 종류 | 파일 이름 |
|------|-----------|
| Debian / Ubuntu (권장) | `DaimananGit_<버전>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<버전>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<버전>-linux-x86_64.pkg.tar.zst` |
| AppImage (설치 없음) | `DaimananGit_<버전>_amd64.AppImage` |
| 압축 풀기 판 | `DaimananGit-<버전>-linux-x64-portable.tar.gz` |

**macOS**

| 종류 | 파일 이름 |
|------|-----------|
| 디스크 이미지 | `DaimananGit_<버전>_*.dmg` (`aarch64` 또는 `x64`, 칩에 맞게) |
| 압축 풀기 판 | `DaimananGit-<버전>-macos-aarch64-portable.zip` 또는 `…-macos-x64-portable.zip` |

### 설치한 다음

1. **Windows**: 설치 프로그램을 실행하거나, 압축 풀기 판을 푼 뒤 `DaimananGit.exe`를 여세요.  
   **Linux**: deb / rpm / Arch 패키지를 우선 사용하거나, AppImage에 실행 권한을 주거나, 압축을 푼 뒤 `./DaimananGit.sh`를 실행하세요.  
   **macOS**: DMG를 열거나, 압축을 푼 뒤 `.app`을 여세요.
2. DaimananGit을 엽니다.
3. 컴퓨터에 `git`이 있는지 확인하세요. 없으면 먼저 설치해야 저장소를 열 수 있습니다.

### 실행 전에 필요한 것

- [Git](https://git-scm.com/)이 설치되어 있어야 합니다.
- **Windows**: [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)가 필요합니다. Windows 10 / 11에는 대부분 이미 있습니다.
- **Linux**: WebKitGTK 4.1이 필요합니다(deb / rpm / Arch 패키지가 보통 함께 설치).
  - Debian / Ubuntu: `sudo apt install libwebkit2gtk-4.1-0`
  - Fedora: `sudo dnf install webkit2gtk4.1`
  - openSUSE: `sudo zypper install webkit2gtk3`
  - Arch / Manjaro: `sudo pacman -S webkit2gtk-4.1`

### 언어 바꾸기

프로그램을 연 뒤, 위쪽 막대 오른쪽에 있는 언어 이름을 누르세요. 선택: 简体中文, 繁體中文, English, Русский, 한국어, 日本語. 바로 바뀌고, 다음에 열어도 유지됩니다. 아직 번역이 없는 문구는 영어로 나옵니다.

### 자동 업데이트

- **Windows 설치판**은 앱에서 업데이트를 확인할 수 있습니다(서명 검증). 새 버전이 있으면 안내를 따르세요.
- **압축 풀기 판**, **Linux**, **macOS**는 당분간 Releases에서 수동으로 받아 교체하세요.
- 업데이트에 실패하면 GitHub 또는 Gitee에서 같은 버전 설치 파일을 받으세요.

### 자주 묻는 질문

| 문제 | 해결 |
|------|------|
| 저장소를 열 수 없음 / git 없음 | Git을 설치하고 터미널에서 `git --version`을 확인하세요 |
| Windows에서 흰 화면이거나 실행 안 됨 | WebView2 런타임을 설치하거나 복구하세요 |
| Linux AppImage가 실행되지 않음 | `chmod +x DaimananGit_*.AppImage` 후 WebKitGTK 4.1을 설치하세요 |
| 공식 패키지인지 확인 | 위에 링크된 GitHub / Gitee Releases에서만 받으세요. [LICENSE](./LICENSE) 참고 |

<a id="ja"></a>

## 日本語

コードの旅で、迷わない。

DaimananGit はデスクトップの Git クライアントです。ブランチとコミットを見渡し、日々のコミット、取得、衝突をわかりやすくします。

简体中文、繁體中文、English、Русский、한국어、日本語は同じプログラムに入っています。言語ごとの別パッケージはありません。どれか一つを入手してください。

### ダウンロード

どちらかの最新リリースを開き、お使いのシステムに合うファイルを選んでください。`<バージョン>` はリリース番号です。例: `0.8.2`。ファイル名は英語のまま、末尾で種類を見分けてください。

- [GitHub Releases](https://github.com/daimanan/DaimananGit/releases/latest)（海外）
- [Gitee Releases](https://gitee.com/daimanan/daimanangit/releases)（中国ミラー、同じパッケージ）

**Windows（x64）**

| 種類 | ファイル名 |
|------|------------|
| インストーラー（推奨・アプリ内更新対応） | `DaimananGit_<バージョン>_x64-setup.exe` |
| 展開してすぐ使う | `DaimananGit-<バージョン>-windows-x64-portable.zip` |

**Linux（x64）**

| 種類 | ファイル名 |
|------|------------|
| Debian / Ubuntu（推奨） | `DaimananGit_<バージョン>_amd64.deb` |
| Fedora / openSUSE | `DaimananGit-<バージョン>-*.x86_64.rpm` |
| Arch / Manjaro | `DaimananGit-<バージョン>-linux-x86_64.pkg.tar.zst` |
| AppImage（インストール不要） | `DaimananGit_<バージョン>_amd64.AppImage` |
| 展開してすぐ使う | `DaimananGit-<バージョン>-linux-x64-portable.tar.gz` |

**macOS**

| 種類 | ファイル名 |
|------|------------|
| ディスクイメージ | `DaimananGit_<バージョン>_*.dmg`（`aarch64` または `x64`、チップに合わせて） |
| 展開してすぐ使う | `DaimananGit-<バージョン>-macos-aarch64-portable.zip` または `…-macos-x64-portable.zip` |

### 入手したあと

1. **Windows**: インストーラーを実行するか、展開版を解凍して `DaimananGit.exe` を開きます。  
   **Linux**: まず deb / rpm / Arch を使うか、AppImage に実行権限を付けるか、展開版で `./DaimananGit.sh` を実行します。  
   **macOS**: DMG を開くか、展開版の `.app` を開きます。
2. DaimananGit を開きます。
3. パソコンに `git` があることを確認します。ない場合は先に入れてください。入っていないとリポジトリを開けません。

### 起動する前に必要なもの

- [Git](https://git-scm.com/) が入っていること。
- **Windows**: [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) が必要です。Windows 10 / 11 の多くには最初から入っています。
- **Linux**: WebKitGTK 4.1 が必要です（deb / rpm / Arch ならたいてい一緒に入ります）。
  - Debian / Ubuntu: `sudo apt install libwebkit2gtk-4.1-0`
  - Fedora: `sudo dnf install webkit2gtk4.1`
  - openSUSE: `sudo zypper install webkit2gtk3`
  - Arch / Manjaro: `sudo pacman -S webkit2gtk-4.1`

### 言語を切り替える

起動したら、画面上部の右にある言語名をクリックします。選べるのは 简体中文、繁體中文、English、Русский、한국어、日本語 です。切り替えるとすぐに反映され、次に開いたときも残ります。まだ訳がない語句は英語で表示されます。

### 自動更新

- **Windows インストーラー版**はアプリ内で更新を確認できます（署名検証あり）。新しいバージョンがあれば案内に従ってください。
- **展開版**、**Linux**、**macOS** は当面 Releases から手動で入手して置き換えてください。
- 更新に失敗した場合は、GitHub または Gitee から同じバージョンのインストーラーを入手してください。

### よくある質問

| 問題 | 対処 |
|------|------|
| リポジトリが開けない / git がない | Git を入れ、ターミナルで `git --version` を確認 |
| Windows で白画面・起動しない | WebView2 ランタイムを入れるか修復 |
| Linux の AppImage が動かない | `chmod +x DaimananGit_*.AppImage` のうえ WebKitGTK 4.1 を入れる |
| 公式パッケージかどうか | 上記の GitHub / Gitee Releases からのみ入手。[LICENSE](./LICENSE) も参照 |

---

使用条件见 [LICENSE](./LICENSE)。本仓库不接受源码贡献；问题反馈请通过发布页或官网渠道联系。
