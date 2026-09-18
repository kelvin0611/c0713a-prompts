# C0713A — Prompt 卡（香港交通到站 App）

中三 STEM 課堂用嘅 Prompt 卡。學生開個網頁，撳「複製」，貼落 Cursor 就得。

**網址**：https://kelvin0611.github.io/c0713a-prompts/

## 內容

| Step | 做咩 |
|---|---|
| 1 | 出路線掣（792 條九巴路線）|
| 2 | 撳路線見站名 |
| 3 | 幾多分鐘到站 |
| 4 | 加港鐵下一班車 |
| 5 | 自動更新 ＋ 斷線唔爛 |
| ? | 壞咗點算（把錯誤交畀 AI）|

每個 step 都有：可複製嘅 prompt、應該見到咩、常見錯。

## 給導師

- 學生**唔需要打 code**，只係貼 prompt
- 貼完一定要撳 Cursor 嘅 **Keep All**，再回瀏覽器重新整理
- 出錯唔好自己修 —— 叫學生 copy Console 紅字，貼落 AI（呢個就係教 Debug）

## 資料來源

政府開放數據（data.gov.hk）：
- 九巴 ETA：`https://data.etabus.gov.hk/v1/transport/kmb/`
- 港鐵下一班車：`https://rt.data.gov.hk/v1/transport/mtr/getSchedule.php`

全部免 API key、免後端。本頁只用官方開放數據，冇使用任何巴士／港鐵公司商標。

## 本地預覽

```bash
python3 -m http.server 8000
# 開 http://localhost:8000
```

## 授權

教學用途。香港交通到站 App 課堂教材，2026。
