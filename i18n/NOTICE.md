291  npm install -g pm2
295  pm2 list  
296  pm2 start npm --name flowise -- run start
pm2 start pnpm --name flowise -- start

303  pm2 restart flowise
306  pm2 restart flowise



pm2 stop <id>


## 不支持npm node20 18以下 用yarn
npm install -g yarn
yarn install

npm install -g pnpm  # 推荐
pnpm install
pnpm store prune
pnpm install --frozen-lockfile

DEBUG=* pnpm run dev
export NODE_OPTIONS="--max_old_space_size=4096"
pnpm run dev





