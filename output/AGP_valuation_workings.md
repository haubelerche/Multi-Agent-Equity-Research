# Diễn giải định giá — AGP

> Tài liệu nội bộ để kiểm định. Trình bày đầy đủ công thức, dữ liệu đầu vào và bước trung gian của từng phép tính định giá. KHÔNG phải báo cáo khách hàng.

## 1. Thông tin chung

| Thành phần | Giá trị |
| --- | ---: |
| Mã cổ phiếu | AGP |
| Công ty | AGP |
| Sàn | — |
| Ngành | — |
| Mã lần chạy | missing_run_id |
| Ngày định giá | 2026-07-01 |
| Mã ảnh chụp dữ liệu | v2snap_44d75472a76131ba9a25 |
| Năm gốc | 2025 |
| Mã băm tái lập | — |

## 2. Tóm tắt kết quả định giá

| Thành phần | Giá trị |
| --- | ---: |
| Giá hiện tại (VND) | 35,600 |
| Giá mục tiêu kết hợp (VND) | 23,486 |
| Tiềm năng tăng/giảm | -34.0% |
| Khuyến nghị | Chưa công bố - cần phê duyệt của chuyên viên phân tích |

**Luật xếp hạng** (tổng tỷ suất sinh lời = mức tăng/giảm giá + lợi suất cổ tức): > 20% → Mua; < −10% → Bán; còn lại → Giữ.

## 3. Bảng giả định

| Thành phần | Giá trị |
| --- | ---: |
| WACC | 9.5% |
| Chi phí vốn chủ sở hữu (Re) | 13.8% |
| Tăng trưởng dài hạn (g) | 3.0% |
| Số năm dự phóng | 5 |
| Thuế suất | — |
| P/E mục tiêu | 18.3x |
| Mức cộng/trừ định giá | — |

> Các giả định hiện là giá trị mặc định và phải được rà soát, phê duyệt trước khi sử dụng trong báo cáo chính thức.

## 4. Dự phóng theo yếu tố dẫn dắt

| Chỉ tiêu | 2026F | 2027F | 2028F | 2029F | 2030F |
| --- | ---: | ---: | ---: | ---: | ---: |
| Doanh thu thuần | 905 | 969 | 1,038 | 1,112 | 1,192 |
| Giá vốn hàng bán (COGS) | -639 | -685 | -733 | -786 | -842 |
| Lợi nhuận gộp | 266 | 285 | 305 | 327 | 350 |
| Chi phí SG&A | -237 | -254 | -272 | -292 | -312 |
| EBIT | 28 | 31 | 33 | 35 | 38 |
| Chi phí lãi vay | -24 | -26 | -28 | -30 | -32 |
| Lợi nhuận trước thuế | 5 | 5 | 5 | 6 | 6 |
| Chi phí thuế | -1 | -1 | -1 | -1 | -1 |
| LNST cổ đông mẹ | 4 | 4 | 4 | 5 | 5 |
| Khấu hao (D&A) | 37 | 40 | 43 | 46 | 49 |
| CAPEX | -100 | -91 | -79 | -65 | -49 |
| EPS (VND) | 141 | 151 | 162 | 173 | 186 |
| Vay ròng (phát hành nợ − trả nợ) | 45 | 48 | 52 | 55 | 59 |
| Dư nợ vay cuối kỳ | 677 | 726 | 777 | 833 | 892 |
| Cổ tức tiền mặt | 1 | 1 | 1 | 1 | 1 |
| Tỷ lệ chi trả cổ tức | 22.8% | 22.8% | 22.8% | 22.8% | 22.8% |

_Logic yếu tố dẫn dắt: doanh thu theo tăng trưởng giả định; biên lợi nhuận dẫn xuất EBIT/LNST; lịch nợ vay chuyển tiếp với `vay ròng = phát hành nợ − trả nợ`; cổ tức theo tỷ lệ chi trả._

## 5. Chỉ số tài chính

| Chỉ số | Công thức | 2026F | 2027F | 2028F | 2029F | 2030F |
| --- | --- | ---: | ---: | ---: | ---: | ---: |
| Biên lợi nhuận gộp | lợi nhuận gộp / doanh thu | 29.4% | 29.4% | 29.4% | 29.4% | 29.4% |
| Biên EBIT | EBIT / doanh thu | 3.1% | 3.2% | 3.2% | 3.2% | 3.2% |
| Biên lợi nhuận ròng | lợi nhuận sau thuế / doanh thu | 0.4% | 0.4% | 0.4% | 0.4% | 0.4% |
| ROE | lợi nhuận sau thuế / vốn chủ sở hữu | 0.8% | 0.9% | 0.9% | 1.0% | 1.0% |

## 6. Định giá FCFF

**Công thức:** `FCFF = EBIT×(1−t) + D&A − CAPEX − ΔNWC`

- WACC = **9.5%**; tăng trưởng dài hạn g = **3.0%**

| Khoản mục | 2026F | 2027F | 2028F | 2029F | 2030F |
| --- | ---: | ---: | ---: | ---: | ---: |
| EBIT | 28 | 31 | 33 | 35 | 38 |
| Thuế suất | — | — | — | — | — |
| D&A | 37 | 40 | 43 | 46 | 49 |
| CAPEX | 100 | 91 | 79 | 65 | 49 |
| ΔNWC | -213 | 14 | 14 | 16 | 17 |
| FCFF | 173 | -40 | -24 | -7 | 14 |
| Hệ số chiết khấu | 91.3% | 83.4% | 76.2% | 69.6% | 63.5% |
| PV(FCFF) | 158 | -33 | -19 | -5 | 9 |

| Thành phần | Giá trị |
| --- | ---: |
| PV dòng tiền dự phóng (Σ PV FCFF) | 110 |
| Giá trị cuối kỳ (Gordon: FCFFₙ×(1+g)/(WACC−g)) | 218 |
| Giá trị hiện tại của giá trị cuối kỳ | 138 |
| Tỷ trọng giá trị cuối kỳ / giá trị doanh nghiệp | — |
| = Giá trị doanh nghiệp (EV) | 249 |
| − Nợ ròng | 455 |
| = Giá trị vốn chủ sở hữu | -206 |
| ÷ Số cổ phiếu (triệu) | 27 |
| = Giá/cổ phiếu (FCFF, VND) | — |

_Giá/cổ phiếu theo FCFF hiển thị `—` vì giá trị vốn chủ sở hữu âm (-206): dòng tiền tự do âm kéo giá trị doanh nghiệp và phần vốn chủ sở hữu xuống dưới 0, nên không thể quy ra giá dương. Đây là kết quả kinh tế của mô hình, không phải thiếu dữ liệu._

## 7. Định giá FCFE

**Công thức:** `FCFE = lợi nhuận sau thuế + khấu hao − CAPEX − ΔNWC + vay ròng`, chiết khấu theo chi phí vốn chủ sở hữu.

| Thành phần | Giá trị |
| --- | ---: |
| Chi phí vốn chủ sở hữu (Re) | 13.8% |
| Tăng trưởng dài hạn (g) | 3.0% |
| Giá trị vốn chủ sở hữu | 625 |
| ÷ Số cổ phiếu (triệu) | 27 |
| = Giá/cổ phiếu (FCFE, VND) | 23,486 |

## 8. Kết hợp phương pháp FCFF và FCFE

**Công thức:** `Giá mục tiêu = 0.60 × Giá_FCFF + 0.40 × Giá_FCFE`

**Diễn giải:** Chưa thể kết hợp theo trọng số 60/40 vì giá FCFF chưa có giá trị hợp lệ. Bảng giữ nguyên từng cấu phần để người đọc thấy rõ ô nào không thể tính.

| Thành phần | Giá trị |
| --- | ---: |
| Giá theo FCFF (VND) | — |
| Giá theo FCFE (VND) | 23,486 |
| Trọng số FCFF / FCFE | 0.60 / 0.40 |
| = Giá mục tiêu kết hợp (VND) | 23,486 |
| Chênh lệch FCFF/FCFE | — |
| Chỉ ở dạng nháp | Có |

## 9. P/E dự phóng để đối chiếu

| Thành phần | Giá trị |
| --- | ---: |
| EPS dự phóng (VND) | 141 |
| P/E trung vị nhóm so sánh | 18.3x |
| Mức cộng/trừ định giá | — |
| P/E mục tiêu | 18.3x |
| Giá mục tiêu (VND) | 2,582 |

## 10. Phân tích độ nhạy

**Độ nhạy FCFF theo WACC và tăng trưởng dài hạn**

_Không có ô định giá hợp lệ để hiển thị; mô hình giữ dấu gạch ngang thay vì tự suy diễn số._
- Biên chi phí bán hàng và quản lý lịch sử không khớp trực tiếp với EBIT hoạt động; mô hình dùng biên EBIT hoạt động thuần được suy ra từ lợi nhuận hoạt động sau khi loại phần tài chính.
- Tỷ lệ CAPEX/doanh thu dự phóng bắt đầu từ 11.1% thay vì 12.9%; sau đó giảm dần về mức đầu tư duy trì theo khấu hao.
- Lịch nợ vay dự phóng dùng lộ trình đòn bẩy đã đối chiếu với báo cáo lưu chuyển tiền tệ; dư nợ được giữ quanh 74.8% doanh thu, còn vay ròng đi theo quy mô tăng trưởng kinh doanh.
- Không suy ra được chi phí nợ trực tiếp từ lịch nợ do thiếu cặp dữ liệu lãi vay/dư nợ lịch sử; mô hình tạm dùng tỷ lệ chi phí lãi vay trên doanh thu làm biến đại diện, với độ tin cậy thấp.
- Thiếu dữ liệu tồn kho lịch sử để dự phóng vốn lưu động; mô hình giữ tồn kho dự phóng bằng 0, nên cần đọc kết quả dòng tiền với mức thận trọng cao hơn.
- Thiếu dữ liệu phải trả người bán lịch sử để dự phóng vốn lưu động; phần thay đổi vốn lưu động có thể bị ước tính cao hơn thực tế.
- Chưa có số dư tiền cuối kỳ được báo cáo để đối chiếu cơ chế điều tiết tiền mặt; khả năng hòa giải dòng tiền vẫn cần được kiểm tra thêm.
- Giá trị vốn chủ sở hữu âm nên không tính được giá mục tiêu theo phương pháp này.

**Độ nhạy FCFE theo chi phí vốn chủ sở hữu và tăng trưởng dài hạn**

| Độ nhạy FCFE theo chi phí vốn chủ sở hữu và tăng trưởng dài hạn | 2.0% | 2.5% | 3.0% | 3.5% | 4.0% |
| --- | --- | --- | --- | --- | --- |
| 11.8% | 25,453 | 26,082 | 26,784 | 27,569 | 28,456 |
| 12.8% | 23,918 | 24,416 | 24,965 | 25,572 | 26,249 |
| 13.8% | 22,647 | 23,048 | 23,486 | 23,967 | 24,497 |
| 14.8% | 21,578 | 21,906 | 22,262 | 22,649 | 23,072 |
| 15.8% | 20,666 | 20,938 | 21,231 | 21,547 | 21,891 |

**Độ nhạy P/E dự phóng** — `EPS năm dự phóng thứ nhất × P/E mục tiêu`

| Độ nhạy P/E dự phóng | 10 | 12 | 14 | 16 | 18 |
| --- | --- | --- | --- | --- | --- |
| 120 | 1,200 | 1,440 | 1,680 | 1,920 | 2,160 |
| 130 | 1,300 | 1,560 | 1,820 | 2,080 | 2,340 |
| 141 | 1,410 | 1,692 | 1,974 | 2,256 | 2,538 |
| 152 | 1,520 | 1,824 | 2,128 | 2,432 | 2,736 |
| 162 | 1,620 | 1,944 | 2,268 | 2,592 | 2,916 |

**Độ nhạy EV/EBITDA** — `Giá = (EBITDA × Hệ số − Nợ ròng − Lợi ích cổ đông không kiểm soát + Tài sản ngoài hoạt động) / Số cổ phiếu × 1000`

| Độ nhạy EV/EBITDA | 7 | 8 | 9 | 10 | 11 |
| --- | --- | --- | --- | --- | --- |
| 56 | — | — | 1,856 | 3,960 | 6,064 |
| 61 | — | 1,135 | 3,412 | 5,688 | 7,965 |
| 66 | 225 | 2,698 | 5,170 | 7,642 | 10,114 |
| 71 | 1,619 | 4,291 | 6,962 | 9,634 | 12,305 |
| 76 | 2,829 | 5,673 | 8,518 | 11,362 | 14,206 |

**Độ nhạy DCF giản lược**

_Không có ô định giá hợp lệ để hiển thị; mô hình giữ dấu gạch ngang thay vì tự suy diễn số._
- DCF giản lược theo dòng tiền từ hoạt động kinh doanh trừ CAPEX chỉ là phép kiểm tra tham khảo; định giá chính nên dựa trên FCFF/FCFE và phần kết hợp phương pháp.
- Dòng tiền tự do lịch sử âm trong các năm 2022FY và 2024FY; vì vậy cách ngoại suy tăng trưởng dòng tiền bằng tốc độ tăng trưởng kép không đủ tin cậy và chỉ nên dùng như kiểm tra tham khảo.
- Không tính được tốc độ tăng trưởng kép của dòng tiền tự do vì giá trị đầu kỳ hoặc cuối kỳ không dương; mô hình đang dùng giả định tăng trưởng dòng tiền tự do 5% để tham khảo.
- Giá trị cuối kỳ chiếm khoảng 71.1% đến 83.1% giá trị doanh nghiệp trong các kịch bản DCF giản lược, cao hơn ngưỡng 70%; kết quả định giá rất nhạy với giả định tăng trưởng dài hạn và tỷ lệ chiết khấu.

## 11. Đối chiếu & cảnh báo

**Đối chiếu nhất quán số:**

- Chưa thể đối chiếu giá FCFF trong phần kết hợp vì một trong hai giá trị đầu vào chưa có kết quả hợp lệ; người đọc cần ưu tiên phần cảnh báo phương pháp khi diễn giải giá mục tiêu.

**Cảnh báo từ mô hình tính toán:**

- Price_FCFF không có — dùng 100% FCFE. Không đúng trọng số 60/40; kết quả cần phê duyệt thủ công.
- Biên chi phí bán hàng và quản lý lịch sử không khớp trực tiếp với EBIT hoạt động; mô hình dùng biên EBIT hoạt động thuần được suy ra từ lợi nhuận hoạt động sau khi loại phần tài chính.
- Tỷ lệ CAPEX/doanh thu dự phóng bắt đầu từ 11.1% thay vì 12.9%; sau đó giảm dần về mức đầu tư duy trì theo khấu hao.
- Lịch nợ vay dự phóng dùng lộ trình đòn bẩy đã đối chiếu với báo cáo lưu chuyển tiền tệ; dư nợ được giữ quanh 74.8% doanh thu, còn vay ròng đi theo quy mô tăng trưởng kinh doanh.
- Không suy ra được chi phí nợ trực tiếp từ lịch nợ do thiếu cặp dữ liệu lãi vay/dư nợ lịch sử; mô hình tạm dùng tỷ lệ chi phí lãi vay trên doanh thu làm biến đại diện, với độ tin cậy thấp.
- Thiếu dữ liệu tồn kho lịch sử để dự phóng vốn lưu động; mô hình giữ tồn kho dự phóng bằng 0, nên cần đọc kết quả dòng tiền với mức thận trọng cao hơn.
- Thiếu dữ liệu phải trả người bán lịch sử để dự phóng vốn lưu động; phần thay đổi vốn lưu động có thể bị ước tính cao hơn thực tế.
- Chưa có số dư tiền cuối kỳ được báo cáo để đối chiếu cơ chế điều tiết tiền mặt; khả năng hòa giải dòng tiền vẫn cần được kiểm tra thêm.
- Giá trị vốn chủ sở hữu âm nên không tính được giá mục tiêu theo phương pháp này.

**Mã băm tái lập:** `—`

_Nguồn gốc dữ liệu: mọi số định giá được dẫn xuất từ dữ liệu tài chính chuẩn hóa đã khóa và tệp kết quả định giá bằng Python; không có số liệu nào do mô hình ngôn ngữ sinh ra._
