# Bootstrap 5 Portfolio Template

### TEMPLATE SCREENSHOT

### WEBSITE PREVIEW 

## 🎮 Frontend Development Guide

### Tech Stack
- React 18 with TypeScript
- Vite for bundling
- TailwindCSS for styling
- wagmi + viem for Web3

### Component Library
```typescript
// Available components
import { 
  GameCard,
  Leaderboard,
  WalletButton,
  ScoreDisplay 
} from '@/components';
```

### State Management
- React Query for server state
- Zustand for client state
- Optimistic updates for UX

### Building for Production
```bash
npm run build
npm run preview  # Test production build
```

### Environment Variables
- `VITE_API_URL` - Backend API endpoint
- `VITE_CHAIN_ID` - Target blockchain
