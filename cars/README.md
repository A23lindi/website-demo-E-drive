# Car Images

Website uses these local image files from `client/public/cars`.

To change a car photo, replace the matching `.jpg` file with a new image using the same filename. If the filename stays the same, you do not need to change code or run the database seed again.

Current files:

- `tesla-model-3.jpg` - Tesla Model 3
- `tesla-model-y.jpg` - Tesla Model Y
- `bmw-i4.jpg` - BMW i4
- `bmw-ix.jpg` - BMW iX
- `mercedes-eqc.jpg` - Mercedes EQC
- `volkswagen-id4.jpg` - Volkswagen ID.4
- `hyundai-ioniq-5.jpg` - Hyundai Ioniq 5
- `kia-ev6.jpg` - Kia EV6
- `nissan-leaf.jpg` - Nissan Leaf
- `porsche-taycan.jpg` - Porsche Taycan

If you rename files or add different filenames, update `server/seed/carSeeder.js`, then run this from the `server` folder:

```powershell
npm run seed
```
