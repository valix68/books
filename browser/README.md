# Browser Internals Learning Resources

## Books

### 1. Web Browser Engineering
**Authors:** Pavel Panchekha, Chris Harrelson

Nội dung:

- Browser architecture
- Networking
- HTML parser
- CSS parser
- JavaScript runtime
- DOM
- Layout
- Painting
- Compositing
- GPU rendering
- Event loop
- Security
- Tự xây dựng một browser đơn giản bằng Python

---

### 2. The Tangled Web
**Author:** Michal Zalewski

Nội dung:

- Same-Origin Policy
- Cookies
- CORS
- DOM Security
- XSS
- Clickjacking
- Browser Security Model

---

## Web Articles & Official Documentation

### 1. How Browsers Work

Tác giả:

- Tali Garsiel
- Paul Irish

Link:

https://web.dev/articles/howbrowserswork

Nội dung:

- Browser architecture
- HTML parsing
- CSS parsing
- DOM
- CSSOM
- Render Tree
- Layout
- Painting
- Compositing

---

### 2. Inside look at modern web browser

Google Chrome Developers

Link:

https://developer.chrome.com/blog/inside-browser-part1/

Series gồm:

- Part 1 – CPU, GPU, Memory và Multi-process Architecture
- Part 2 – Navigation
- Part 3 – Rendering Process
- Part 4 – Compositor
- Part 5 – RenderingNG (tham khảo thêm)

---

### 3. Chromium Architecture

Link:

https://www.chromium.org/developers/design-documents/

Nội dung:

- Browser Process
- Renderer Process
- GPU Process
- Network Service
- Mojo IPC
- Content Layer
- Sandbox
- Site Isolation

---

### 4. Blink Design Documents

Link:

https://chromium.googlesource.com/chromium/src/+/main/third_party/blink/renderer/README.md

Nội dung:

- DOM
- HTML Parser
- CSS Engine
- LayoutNG
- Paint
- Compositor

---

### 5. Chromium Source

Link:

https://chromium.googlesource.com/chromium/src

Thư mục quan trọng:

```
src/
├── base/
├── chrome/
├── components/
├── content/
├── gpu/
├── media/
├── net/
├── services/
├── third_party/
│   └── blink/
├── ui/
├── v8/
└── cc/
```

---

### 6. Chromium Code Search

Link:

https://source.chromium.org/chromium/chromium/src

Cho phép tra cứu source code trực tiếp trên trình duyệt.

---

### 7. V8 Documentation

Link:

https://v8.dev/docs

Bao gồm:

- Ignition
- TurboFan
- Sparkplug
- Garbage Collection
- Hidden Classes
- Inline Cache
- Pointer Compression

---

### 8. V8 Blog

Link:

https://v8.dev/blog

Nơi công bố các thay đổi kiến trúc và tối ưu hóa của V8.

---

### 9. RenderingNG Documentation

Link:

https://developer.chrome.com/docs/chromium/renderingng

Nội dung:

- Rendering pipeline
- LayoutNG
- PaintNG
- Compositor
- GPU Rendering
- Scheduling

---

### 10. Chrome DevTools Protocol

Link:

https://chromedevtools.github.io/devtools-protocol/

Nội dung:

- Debugging
- Network
- DOM
- Runtime
- Page
- Target
- Browser
- Input
- Emulation

---

### 11. Blink API Documentation

Link:

https://chromium.googlesource.com/chromium/src/+/main/third_party/blink/

---

### 12. Chromium Security

Link:

https://www.chromium.org/Home/chromium-security/

Bao gồm:

- Sandbox
- Site Isolation
- Process Isolation
- Safe Browsing
- Security Architecture

---

## Suggested Reading Order

1. Web Browser Engineering
2. How Browsers Work
3. Inside look at modern web browser
4. Chromium Architecture
5. RenderingNG
6. Blink Design Docs
7. V8 Documentation
8. Chromium Security
9. Chrome DevTools Protocol
10. Chromium Source Code
11. Chromium Code Search
