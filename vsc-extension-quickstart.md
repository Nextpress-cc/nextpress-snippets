# Nextpress Snippets 🚀

**The Ultimate React & Next.js Code Snippets Extension for VS Code**

Boost your productivity with professional, time-saving snippets for React and Next.js development. Perfect for both JavaScript and TypeScript developers.

## ✨ Why Choose Nextpress Snippets?

- **Lightning-Fast Development**: Create components, pages, and layouts in seconds
- **Full TypeScript Support**: Built-in type definitions and proper TypeScript syntax
- **Next.js App Router Ready**: Optimized for the latest Next.js 13+ architecture
- **Developer-Focused Design**: Created by developers for real-world React workflows

## 🎯 Key Features

- **Dual-Language Compatibility**: Seamlessly work with **JavaScript** (`js`, `jsx`) and **TypeScript** (`ts`, `tsx`)
- **Modern React Patterns**: Follow best practices with functional components and proper exports
- **Intuitive Shortcut System**: Easy-to-remember prefixes for different component types:
  - `jsc`/`tsc`: React Components
  - `jsp`/`tsp`: Next.js Pages
  - `jsl`/`tsl`: Next.js Layouts
  - `js0`/`ts0`: Default Exports
  - `js1`/`ts1`: Named Exports

## 🛠️ Installation

1. Launch **VS Code**
2. Open **Extensions Marketplace** (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for **"Nextpress Snippets"**
4. Click **Install** → **Reload** your editor

## 🚀 Usage Guide

### 📂 **JavaScript/JSX Snippets**

| Prefix | Description | Shortcut |
|--------|-------------|----------|
| `jsc`  | React Component | JavaScript Component |
| `jsp`  | Next.js Page | JavaScript Page Component |
| `jsl`  | Next.js Layout | JavaScript Layout Component |
| `js0`  | Default Export Function | JavaScript Default Export |
| `js1`  | Named Arrow Function | JavaScript Named Export |

### 📄 **TypeScript/TSX Snippets**

| Prefix | Description | Shortcut |
|--------|-------------|----------|
| `tsc`  | TypeScript Component | TypeScript Component with Props |
| `tsp`  | TypeScript Next.js Page | TypeScript Page Component |
| `tsl`  | TypeScript Layout | TypeScript Layout Component |
| `ts0`  | TypeScript Default Export | TypeScript Default Export |
| `ts1`  | TypeScript Named Export | TypeScript Named Export |

## 📝 Detailed Examples

### JavaScript Snippets

#### `jsc` - JavaScript Component
```javascript
export const Button = () => {
  return (
    <div>Button</div>
  )
}
```

#### `jsp` - JavaScript Page
```javascript
export default function ProductPage() {
  return (
    <div>ProductPage</div>
  )
}
```

#### `jsl` - JavaScript Layout
```javascript
export default function AppLayout({ children }) {
  return (
    <div>
      {children}
    </div>
  )
}
```

#### `js0` - JavaScript Default Export
```javascript
export default function Navbar() {
  return (
    <div>Navbar</div>
  )
}
```

#### `js1` - JavaScript Named Export
```javascript
export const ProductCard = () => {
  return (
    <div>ProductCard</div>
  )
}
```

### TypeScript Snippets

#### `tsc` - TypeScript Component with Props
```typescript
type Props = {}

export const SearchBar = ({}: Props) => {
  return (
    <div>SearchBar</div>
  )
}
```

#### `tsp` - TypeScript Page Component
```typescript
export default function DashboardPage() {
  return (
    <div>DashboardPage</div>
  )
}
```

#### `tsl` - TypeScript Layout Component
```typescript
type Props = {
  children: React.ReactNode
}

export default function AdminLayout({ children }: Props) {
  return (
    <div>
      {children}
    </div>
  )
}
```

#### `ts0` - TypeScript Default Export
```typescript
export default function UserProfile() {
  return (
    <div>UserProfile</div>
  )
}
```

#### `ts1` - TypeScript Named Export
```typescript
export const Pagination = () => {
  return (
    <div>Pagination</div>
  )
}
```

## 💡 Usage Tips

1. **Tab Completion**: After typing the snippet prefix, press `Tab` to trigger the snippet
2. **Tab Navigation**: Use `Tab` to navigate between placeholder variables in the generated code
3. **Auto-Renaming**: When you change a component name in one place, all instances update automatically
4. **Works Everywhere**: Snippets work in `.js`, `.jsx`, `.ts`, and `.tsx` files

## ⚙️ Recommended Configuration

For the best experience, add these settings to your VS Code `settings.json`:

```json
{
  "editor.snippetSuggestions": "top",
  "editor.tabCompletion": "on",
  "nextpress.snippets.priority": "high"
}
```

## 📚 Documentation & Support

* **GitHub Repository**: [nextpress-cc/nextpress-snippets](https://github.com/nextpress-cc/nextpress-snippets)
* **Issue Reporting**: [Issue Tracker](https://github.com/nextpress-cc/nextpress-snippets/issues)
* **Feature Requests**: Feel free to suggest new snippets via GitHub issues

## 📜 License

Released under the **MIT License** • Crafted with ❤️ by the Nextpress Team.

---

**💡 Pro Tip**: Combine with the official Next.js extension for the ultimate React development environment!
