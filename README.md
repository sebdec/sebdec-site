# sebdec.com

Sébastien Decrême's personal website for product and technology writing, selected projects and outdoor interests.

## Requirements

- Node.js 22.12 or later
- pnpm 11.20.0

## Commands

| Command             | Purpose                                                |
| ------------------- | ------------------------------------------------------ |
| `pnpm install`      | Install dependencies                                   |
| `pnpm dev`          | Start the local development server                     |
| `pnpm check`        | Run Astro and TypeScript diagnostics                   |
| `pnpm format`       | Format project files                                   |
| `pnpm format:check` | Verify formatting without changing files               |
| `pnpm build`        | Run diagnostics and create the static production build |
| `pnpm preview`      | Preview the production build locally                   |

## Architecture

- Astro with static output
- Astro components and global CSS
- Markdown content for technical articles
- No client-side UI framework
- Vercel deployment
