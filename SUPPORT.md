# MediaRoam Support / 支援

MediaRoam is a free personal media browser for iPhone, iPad, and Apple TV. It connects to storage selected by the user, including SMB, pCloud, WebDAV, Jellyfin, Files, and secure HTTPS links added by the user.

MediaRoam 是免費的 iPhone、iPad 與 Apple TV 個人媒體瀏覽器，可連接使用者自行選擇的 SMB、pCloud、WebDAV、Jellyfin、「檔案」及使用者加入的安全 HTTPS 連結。

## Contact support / 聯絡支援

Use one of the public, guided forms below. Routine triage and replies are handled by the MediaRoam AI maintenance assistant, and every AI reply clearly identifies itself.

請使用下方公開表單。例行分類與回覆由 MediaRoam 的 AI 維護助理處理，且每一則 AI 回覆都會清楚標示身分。

- [Report a bug / 回報問題](https://github.com/jiajie1982-png/MediaRoam-Feedback/issues/new?template=bug_report.yml)
- [Request a feature / 提出功能願望](https://github.com/jiajie1982-png/MediaRoam-Feedback/issues/new?template=feature_request.yml)
- [Browse existing feedback / 查看所有回饋](https://github.com/jiajie1982-png/MediaRoam-Feedback/issues)

A free GitHub account is required to post. Reports are public. Never include passwords, verification codes, access tokens, API keys, IP addresses, full file paths, private media, or personal documents.

留言需要免費 GitHub 帳號，而且內容是公開的。請勿張貼密碼、驗證碼、Token、API Key、IP、完整檔案路徑、私人媒體或個人文件。

## Common checks / 常見檢查

### SMB

Confirm that the Apple device is on the same local network as the computer or NAS. On Windows, enable Network Discovery and File and Printer Sharing. If discovery does not find the computer, enter its local address manually.

請確認 Apple 裝置與電腦或 NAS 位於同一個區域網路。Windows 請開啟「網路探索」與「檔案及印表機共用」。若自動搜尋不到，可手動輸入區域網路位址。

### pCloud

Choose the account's correct region. US accounts use `api.pcloud.com`; EU accounts use `eapi.pcloud.com`.

請選擇帳號的正確區域：美國帳號使用 `api.pcloud.com`，歐洲帳號使用 `eapi.pcloud.com`。

### Playback

Start with Automatic VLC-compatible playback. For an unstable network, choose a more stable buffer level in Settings. Offline download remains available for supported sources.

建議先使用自動 VLC 相容播放；網路不穩時可在設定中選擇較穩定的緩衝。支援的來源也可下載成離線副本。

### HTTPS links / HTTPS 連結

Use a directly accessible HTTPS media or file URL. MediaRoam rejects plain HTTP, URLs containing embedded credentials, insecure redirects, and HTML or sign-in pages. Saved URLs remain in this device's Keychain. Never post a private or token-bearing URL in a public support report.

請使用可直接存取媒體或檔案的 HTTPS 網址。MediaRoam 會拒絕 HTTP、內嵌帳號密碼、不安全轉址、HTML 網頁及登入頁。儲存的網址只保留在這台裝置的 Keychain；請勿在公開回報中張貼私人或含權杖的網址。

## Local data / 本機資料

Settings can clear caches and offline copies or sign out of a source. These actions do not delete remote files. A remote rename, overwrite, or delete happens only after the user explicitly chooses that command and confirms it.

設定可清除快取、離線副本或登出來源，不會刪除遠端檔案。只有使用者主動選擇並確認遠端改名、覆寫或刪除時，才會更動遠端資料。

See the [MediaRoam Privacy Policy](PRIVACY.md).
