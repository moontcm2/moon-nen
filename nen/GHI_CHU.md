# Nến BTCUSDT (Bybit) cho Moon Bot

Dữ liệu tự cập nhật mỗi giờ từ VPS (dịch vụ `moon-nen`), nguồn Bybit v5 `/v5/market/kline`,
`category=linear`, `symbol=BTCUSDT` — đúng nguồn nến bot dùng. Chỉ có nến đã đóng.

- `H1/BTCUSDT_H1_<năm>-<tháng>.csv`: mỗi tháng một file.
- `H4/`, `H12/`, `D/`, `W/`: mỗi năm một file `BTCUSDT_<khung>_<năm>.csv`.
- Cột: `t_ms,mo_utc,open,high,low,close,volume` (giờ mở nến, UTC).
- `TRANG_THAI.json`: lần ghi cuối và nến cuối của từng khung.

Không có key, số dư, lệnh hay cấu hình bot nào trong repo này.
