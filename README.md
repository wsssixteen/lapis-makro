# Lapis Makro

Kalkulator sasaran kalori dan makro dalam BM dan English, selapis demi selapis.
Calorie and macro targets in Bahasa Melayu and English, one layer at a time.

Live: https://wsssixteen.github.io/lapis-makro/

Four quick layers, each with its own result, then a reward:

1. **Asas / Basics**: calories you burn, protein, BMI
2. **Matlamat / Goal**: daily calorie target and an estimated date range to reach it (lose, keep or gain)
3. **Makro / Macros**: protein, fat and carbs on a plate, with everyday food examples
4. **Hidangan / Meals**: protein per meal and a sleep tip
5. **Kek anda / Your cake**: a one-of-a-kind kek lapis Sarawak pattern, baked for each visitor. People can change the pattern (12) and colours (16), or bake another version. Underneath: portions for each meal. **Simpan gambar / Save image** makes a 1080 × 1350 picture with the cake and the portions.

## Put it online with GitHub Pages

1. Create a **public** repository named `lapis-makro` under `wsssixteen`.
2. Upload these files to it: `index.html`, `og-image.png`, `favicon.svg`, `apple-touch-icon.png`, `README.md`.
3. Open **Settings → Pages**. Under **Build and deployment → Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute or two, the site is live at https://wsssixteen.github.io/lapis-makro/

When you share that link on WhatsApp, Telegram or Facebook, `og-image.png` shows as the preview picture.

## Privacy

Everything runs in the visitor's browser. Numbers and the cake code are saved only on their own device (browser storage). There is no sign-up, no server and no tracking.

## Method and sources (checked October 2026)

- Resting burn: Mifflin-St Jeor equation (1990). It predicts within ±10% for about 7 to 8 in 10 adults; it hasn't been tested in healthy Malaysian adults, so the app tells people to adjust after 4 weeks.
- Activity levels: 1.4 / 1.6 / 1.8 / 2.0, the physical activity levels in Malaysia's Recommended Nutrient Intakes (RNI 2017).
- Weight loss: 10%, 20% or 25% below the daily burn, at most 750 kcal a day, never below 1,200 kcal (women) or 1,500 kcal (men). Malaysian CPG Management of Obesity 2023: eat 500–750 kcal/day less for 0.5–1 kg a week; low-calorie diets 1,200–1,500 (women) and 1,500–1,800 kcal (men).
- Weight gain: 5%, 10% or 15% above the daily burn, at most 500 kcal a day, with strength training.
- Goal date: a weekly simulation (7,700 kcal ≈ 1 kg, burn recalculated each week). The later date adds the slowdown from Hall et al. (Lancet 2011), about 14% of the calorie change.
- Protein: 1.2 g/kg (rarely lifts), 1.6 (1–2× a week), 2.0 (3+ a week), using the goal weight and never more than the weight at BMI 25.
- Fat: 25%, 30% or 35% of calories (RNI 2017: 25–30%; AMDR 20–35%). Carbs fill the rest and stay at 130 g or more where the day allows.
- Portions follow KKM sizes: 1 cawan nasi = 2 senduk = 150 g ≈ 200 kcal; 1 sudu teh minyak = 5 g; a palm-size piece of chicken or fish ≈ 25 g protein. Roti canai + teh tarik = 420 kcal (KKM).
- BMI for Malaysian adults: 18.5–22.9 normal, 23–27.4 pre-obese, 27.5 and above obese (CPG 2023). No weight-loss target is set below BMI 18.5.
- Women: one target all month (the cycle shifts resting burn by only about 3–5%); the app explains that weight can rise 0.5–1 kg of water around a period.

Estimates for healthy adults, not medical advice. Not designed for use during pregnancy.

## Credits

Fonts: Libre Franklin and Atkinson Hyperlegible (SIL Open Font License), loaded from Google Fonts.
