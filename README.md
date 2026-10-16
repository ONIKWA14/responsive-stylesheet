Search Tools

Find files matching `.vscode/**`

Find files matching `package.json`

There’s no existing run task or package setup in this folder, so I’ll serve the static site locally and verify it responds before sharing the URL.

Ran terminal command: python -m http.server 8000

Ran terminal command: try { $r = Invoke-WebRequest -Uri 'http://localhost:8000/' -TimeoutSec 5; Write-Output "HTTP $([int]$r.StatusCode)"; Write-Output $r.Content.Substring(0, [Math]::Min(200, $r.Content.Length)) } catch { Write-Error $_; exit 1 }
Tool execution failed with exit code 1

Read Terminal
Completed with input: {
  "shellId": "0",
  "delay": 5
}

Ran terminal command: curl.exe --silent --show-error --fail --max-time 5 http://localhost:8000/

Search Tools

Search Tools

Opened `Browser`

The site is live locally at [http://localhost:8000/](http://localhost:8000/), and I opened it in the browser. It’s served from your computer, not published to the public internet.
