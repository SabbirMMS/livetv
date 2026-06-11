# MMS Studio TV (Live M3U Player)

A modern, high-performance web-based M3U / HLS live television player and playlist analyzer. Designed with a premium, sleek dark-themed interface, it allows users to import custom streams, audit connection health in real time, and enjoy smooth playback.

Official Public Repository: [GitHub - SabbirMMS/livetv](https://github.com/SabbirMMS/livetv)
> [Watch Live](https://sabbirmms.github.io/livetv)

---

## 🚀 Key Features

* **Premium Floating Player**: Enjoy live streams inside a floating picture-in-picture (PiP) style player that supports volume controls, native full-screen mode, and layout minimization/expansion.
* **Intelligent Auto-Checks**: Channels visible on your active page automatically audit their connectivity and latency. Stale or dead links are flagged instantly.
* **Concurrent Health Analyzer**: Multi-threaded checker runs up to `10` simultaneous check requests to scan entire playlists or showing selections at lightning speeds.
* **Smart Filter & Debounced Search**: Type-ahead search is debounced by `300ms` with active loading states to prevent input lag on playlists containing thousands of channels.
* **Advanced Pagination**: Clean pagination control supporting configurable page sizes (`10`, `20`, `50`, `100` channels per page) and responsive navigation.
* **Command Palette (`Ctrl+K` / `Cmd+K`)**: Access shortcuts, search channels, clear database, export M3U, or toggle between Dark and Light mode.
* **Import & Export Playlists**: Easily paste a public M3U/M3U8 link, drag & drop a playlist file, or choose from our preloaded IPTV sources. Export your favorite or clean lists back to standard M3U.

---

## 🛠️ Built With

* **Vite + React (TypeScript)**: For building a fast, modern single-page application.
* **HLS.js**: Native-like HTTP Live Streaming (HLS) decoding for custom media feeds.
* **Tailwind CSS**: A beautiful, custom fluid utility styling system.
* **Lucide Icons**: Crisp, modern, responsive iconography.
