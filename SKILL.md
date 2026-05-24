# SKILL: Viết Luận Văn / Bài Báo Khoa Học — Phong Cách Chuẩn (Tiếng Việt)
> Học từ: Báo cáo Logistics VN 2024, bài báo VRP tiếng Việt (UNETI), luận văn thạc sĩ tiếng Anh (Ontario Tech), và các paper quốc tế trong vr-research/references.
> **Mục tiêu cuối: viết bằng tiếng Việt học thuật chuẩn, không bị detect là AI.**

---

## 1. CẤU TRÚC LUẬN VĂN / BÀI BÁO CHUẨN

### 1.1 Bài báo đăng tạp chí (Journal Paper)
```
Tóm tắt (150–250 từ)
  └─ Bối cảnh → Vấn đề → Phương pháp → Kết quả chính → Ý nghĩa

1. Giới thiệu (Introduction)
  ├─ Đoạn 1: Bối cảnh thực tế (tại sao chủ đề này quan trọng)
  ├─ Đoạn 2: Tổng quan bài toán & các biến thể liên quan
  ├─ Đoạn 3: Khoảng trống nghiên cứu (những gì chưa ai làm)
  ├─ Đoạn 4: Đóng góp của bài báo (liệt kê rõ ràng)
  └─ Đoạn cuối: Cấu trúc bài ("Phần còn lại của bài được tổ chức như sau...")

2. Tổng quan tài liệu (Literature Review)
  ├─ Phân nhóm theo chủ đề
  ├─ Mỗi nhóm: tổng quan → ví dụ tiêu biểu → hạn chế → chỉ ra gap
  └─ Bảng tổng hợp tài liệu (thường ở cuối phần)

3. Mô tả bài toán / Mô hình toán học
  ├─ Mô tả bài toán bằng lời văn
  ├─ Bảng ký hiệu (Tập hợp, Tham số, Biến)
  └─ Hàm mục tiêu → Các ràng buộc (đánh số, giải thích từng ràng buộc)

4. Phương pháp giải / Thuật toán
  ├─ Sơ đồ khối tổng quan (Flowchart)
  └─ Mô tả chi tiết từng thành phần

5. Thực nghiệm tính toán
  ├─ Bộ dữ liệu kiểm thử (benchmark hoặc thực tế)
  ├─ So sánh với các phương pháp khác
  ├─ Phân tích độ nhạy (Sensitivity Analysis)
  └─ Thảo luận

6. Kết luận
  ├─ Tóm tắt đóng góp
  ├─ Hạn chế
  └─ Hướng nghiên cứu tiếp theo

Tài liệu tham khảo
```

### 1.2 Báo cáo khoa học / Báo cáo thực tiễn (như BCLVN 2024)
```
Lời nói đầu
  └─ Bối cảnh ra đời → Mục tiêu báo cáo → Cấu trúc 7 chương

Danh mục chữ viết tắt

Các chương nội dung:
  ├─ Mỗi chương có tiêu đề lớn + tiêu đề nhỏ theo số thứ tự (1.1, 1.1.1)
  ├─ Kết hợp số liệu thống kê + hình ảnh + bảng + phân tích
  └─ Kết luận/Đánh giá chung ở cuối mỗi mục lớn

Kết luận chung
Phụ lục + Tài liệu tham khảo
```

---

## 2. THUẬT NGỮ KỸ THUẬT CHUẨN (Tiếng Việt)

### 2.1 Bài toán cơ bản VRP
| Tiếng Anh | Viết tắt | Tiếng Việt |
|---|---|---|
| Vehicle Routing Problem | VRP | Bài toán định tuyến xe |
| Capacitated VRP | CVRP | VRP có ràng buộc tải trọng |
| VRP with Time Windows | VRPTW | VRP với cửa sổ thời gian |
| Multi-Depot VRP | MDVRP | VRP đa kho hàng |
| Pickup and Delivery Problem | PDP | Bài toán lấy hàng và giao hàng |
| Dynamic VRP | DVRP | VRP động |
| Electric VRP | EVRP | VRP xe điện |
| Location Routing Problem | LRP | Bài toán định vị - định tuyến |
| Split Delivery VRP | SDVRP | VRP giao hàng phân tách |

### 2.2 Phương pháp giải
| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Exact method | Phương pháp chính xác |
| Heuristic | Thuật toán heuristic (heuristic cổ điển) |
| Metaheuristic | Thuật toán metaheuristic (siêu heuristic) |
| NP-hard | Thuộc lớp NP-khó / NP-đầy đủ |
| Branch and Bound | Thuật toán nhánh cận |
| Column Generation | Phương pháp sinh cột |
| Local Search | Tìm kiếm lân cận cục bộ |
| Variable Neighborhood Search | Tìm kiếm lân cận biến đổi (VNS) |
| Ant Colony Optimization | Thuật toán đàn kiến (ACO) |
| Genetic Algorithm | Giải thuật di truyền (GA) |
| Tabu Search | Thuật toán tìm kiếm Tabu |
| Adaptive Large Neighborhood Search | Tìm kiếm lân cận rộng thích nghi (ALNS) |
| Simulated Annealing | Thuật toán luyện kim mô phỏng |

### 2.3 Khái niệm chuyên ngành Logistics (theo BCLVN 2024)
| Thuật ngữ tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Depot | Kho hàng / Trung tâm phân phối / Điểm xuất phát |
| Fleet | Đội xe / Đội phương tiện |
| Route | Tuyến đường / Hành trình |
| Time window [a, b] | Cửa sổ thời gian [a, b] |
| Degree of dynamism | Mức độ động / Độ động của bài toán |
| LIFO constraint | Ràng buộc "vào sau - ra trước" |
| Workload fairness | Công bằng khối lượng công việc |
| Pareto front | Mặt trận Pareto (tập nghiệm không bị trội) |
| Simultaneous pickup & delivery | Giao nhận hàng đồng thời |
| Cold chain logistics | Logistics dây chuyền lạnh |
| Last-mile delivery | Giao hàng chặng cuối |
| 3PL | Dịch vụ logistics bên thứ ba |
| ICD | Cảng cạn / Điểm thông quan nội địa |
| LPI | Chỉ số hiệu quả logistics |

### 2.4 Cụm từ thống kê hay dùng trong báo cáo VN
- "tăng X% so với cùng kỳ năm trước"
- "chiếm tỷ trọng X% tổng..."
- "đạt mức tăng trưởng X%"
- "ước đạt X tỷ USD / nghìn tỷ đồng"
- "tốc độ tăng trưởng kép hàng năm (CAGR) đạt X%"
- "giai đoạn 2021 – 2030, tầm nhìn đến năm 2050"

---

## 3. CÁC MẪU LẬP LUẬN CHUẨN TIẾNG VIỆT

### 3.1 Mở đầu đoạn văn

**Giới thiệu bài toán (theo phong cách UNETI):**
> "Có thể phát biểu bài toán [tên bài toán] cơ bản một cách đơn giản như sau: [mô tả]."
> "Mục tiêu chính của nghiên cứu này là tìm ra giải pháp cho [vấn đề] bằng cách sử dụng [phương pháp]."

**Giới thiệu bối cảnh (theo phong cách BCLVN 2024):**
> "Trong bối cảnh [tình hình], [lĩnh vực] đang đối mặt với [thách thức]."
> "Năm [X], [chỉ tiêu] đạt [giá trị], [tăng/giảm] so với [mốc so sánh], cho thấy [nhận xét]."
> "Những năm gần đây, [xu hướng] đang định hình lại [lĩnh vực], đặt ra yêu cầu [giải pháp]."

**Chỉ ra khoảng trống nghiên cứu:**
> "Tuy nhiên, các nghiên cứu trước đây chủ yếu tập trung vào [phạm vi hẹp], trong khi [vấn đề rộng hơn] vẫn chưa được giải quyết đầy đủ."
> "Mặc dù đã có nhiều công trình nghiên cứu về [chủ đề], song việc [gap cụ thể] vẫn còn là khoảng trống cần được tiếp tục nghiên cứu."
> "Hầu hết các nghiên cứu hiện có chỉ xem xét [A], trong khi [B] – yếu tố có tác động đáng kể đến thực tiễn – lại ít được chú ý."

**Trình bày đóng góp:**
> "Bài báo này đóng góp vào lĩnh vực nghiên cứu theo ba hướng chính sau:"
> "Những đóng góp chính của nghiên cứu bao gồm: (i) [đóng góp 1]; (ii) [đóng góp 2]; (iii) [đóng góp 3]."

### 3.2 Kết thúc đoạn / Chuyển đoạn

**Tóm kết một ý:**
> "Tóm lại, [tổng kết ngắn gọn ý vừa trình bày]."
> "Như vậy, có thể thấy rằng [nhận định khái quát]."
> "Từ phân tích trên, [kết luận dẫn sang ý tiếp theo]."

**Chuyển sang phần tiếp:**
> "Phần tiếp theo trình bày [nội dung phần sau]."
> "Trên cơ sở đó, phần [X] sẽ đề xuất [hướng tiếp cận]."
> "Phần còn lại của bài được tổ chức như sau: Phần 2 trình bày tổng quan tài liệu... Cuối cùng, Phần [n] đưa ra kết luận và hướng nghiên cứu tiếp theo."

**Nhận xét sau khi trình bày kết quả:**
> "Kết quả thực nghiệm cho thấy [phương pháp đề xuất] cho kết quả tốt hơn [phương pháp so sánh] ở [X]% các trường hợp kiểm thử."
> "Điều này chứng tỏ rằng [lý giải kết quả]."
> "Điều đáng chú ý là [nhận xét bổ sung]."

### 3.3 Trích dẫn và dẫn nguồn (tiếng Việt)

**Đề cập tên tác giả:**
> "[Tác giả] ([năm]) đã đề xuất [phương pháp]..."
> "Theo [Tác giả] và cộng sự ([năm]), [kết quả/nhận định]."
> "Kết quả này phù hợp với các phát hiện của [Tác giả] ([năm])."
> "Kế thừa từ nghiên cứu của [Tác giả] ([năm]), bài báo này mở rộng..."

**Khi so sánh phương pháp:**
> "So với phương pháp của [Tác giả] ([năm]), cách tiếp cận của chúng tôi [ưu điểm cụ thể]."
> "Khác với [Tác giả] ([năm]) chỉ xét trường hợp [A], nghiên cứu này xem xét cả [B] và [C]."

---

## 4. PHONG CÁCH VIẾT TIẾNG VIỆT HỌC THUẬT — CHỐNG DETECT AI

### 4.1 Nguyên tắc chung

**Câu văn cần:**
- Đan xen câu ngắn và câu dài, tránh đồng đều
- Dùng mệnh đề quan hệ: "trong đó", "theo đó", "bên cạnh đó", "đặc biệt là"
- Kết hợp chủ động và bị động: "được thực hiện", "được đề xuất", "đã chứng minh rằng"
- Dùng số liệu cụ thể thay vì nói chung chung

**Tránh:**
- Không bắt đầu nhiều câu liên tiếp bằng "Đây là", "Điều này", "Việc này"
- Không dùng liên tiếp cấu trúc "Thứ nhất... Thứ hai... Thứ ba..." quá máy móc
- Không lặp từ "quan trọng", "đáng chú ý", "hiệu quả" liên tục
- Tránh câu quá hoàn hảo, không có chút do dự hay thừa nhận hạn chế

**Nên dùng:**
- Hedge words: "nhìn chung", "về cơ bản", "có thể thấy", "trong hầu hết các trường hợp", "phần lớn"
- Từ nối tự nhiên: "tuy nhiên", "bên cạnh đó", "ngoài ra", "đồng thời", "thậm chí", "trái lại"
- Thừa nhận hạn chế thực: "vẫn còn tồn tại", "chưa đáp ứng đủ", "cần tiếp tục hoàn thiện"

### 4.2 Phong cách Giới thiệu tự nhiên (học từ UNETI papers)

**Pattern 1 — Xuất phát từ định nghĩa:**
> "Bài toán [tên] bắt nguồn từ năm [X] khi [tác giả gốc] thiết lập công thức toán học và phương pháp tiếp cận bằng thuật toán để giải quyết [bài toán thực tế]. Năm [Y], [tác giả sau] đã cải tiến cách giải bằng cách sử dụng [phương pháp mới], từ đó sự quan tâm đến [bài toán] được mở rộng từ [nhóm ban đầu] sang [phạm vi rộng hơn]."

**Pattern 2 — Xuất phát từ thực tế (học từ BCLVN 2024):**
> "Trong bối cảnh [xu hướng thực tế], [lĩnh vực] ngày càng đóng vai trò quan trọng đối với [đối tượng]. Theo [nguồn số liệu], [chỉ tiêu] đạt [giá trị] vào năm [X], phản ánh [nhận xét]. Tuy nhiên, [vấn đề nổi lên] đặt ra yêu cầu cấp thiết phải [giải pháp tối ưu hóa]."

### 4.3 Phong cách Tổng quan tài liệu tự nhiên (học từ UNETI papers)

**Cấu trúc đoạn lit review chuẩn (3-4 câu):**
1. Câu chủ đề: giới thiệu nhóm nghiên cứu hoặc hướng tiếp cận
2. Ví dụ cụ thể: 1-2 công trình tiêu biểu + kết quả / hạn chế
3. Nhận xét chung: đánh giá xu hướng hoặc điểm thiếu sót
4. Chuyển tiếp: dẫn sang vấn đề cần giải quyết trong bài

**Ví dụ (phong cách tiếng Việt học thuật):**
> "Các phương pháp giải chính xác đảm bảo lời giải tối ưu sẽ được tìm thấy trong một khoảng thời gian hữu hạn. Tuy nhiên, thời gian chạy của chúng trong trường hợp tồi nhất là rất lớn, do đó lớp thuật toán này chỉ giải được những bài toán có kích thước nhỏ hoặc vừa như thuật toán nhánh cận, thuật toán sinh cột,... Các phương pháp gần đúng gồm các giải thuật cho chất lượng lời giải gần với lời giải tối ưu như nhóm các giải thuật heuristic cổ điển, nhóm các giải thuật tìm kiếm cục bộ và nhóm các giải thuật metaheuristic."

---

## 5. TRÌNH BÀY MÔ HÌNH TOÁN HỌC CHUẨN TIẾNG VIỆT

### 5.1 Cấu trúc chuẩn
```
1. Mô tả bài toán (1-2 đoạn văn xuôi)
2. Định nghĩa đồ thị G = (V, A) hoặc G = (N, E)
3. Bảng tập hợp (Sets)
4. Bảng tham số (Parameters)
5. Bảng biến quyết định (Decision Variables)
6. Hàm mục tiêu: đánh số (1), (2),...
7. Các ràng buộc: đánh số (3), (4),... kèm giải thích
```

### 5.2 Cách giải thích ràng buộc (tiếng Việt)

**Pattern chuẩn:**
> "Ràng buộc (X) đảm bảo [ý nghĩa]. [Giải thích thêm nếu cần]."
> "Ràng buộc (X) [ngăn chặn / yêu cầu / đảm bảo] [điều kiện]. Cụ thể, [giải thích vế trái và vế phải]."

**Ví dụ (phong cách UNETI):**
> "(1) biểu diễn mối liên hệ giữa x và y."
> "(2), (3): đảm bảo mỗi khách được một xe phục vụ."
> "(4) đảm bảo sức chứa một xe."
> "(5), (6), (7), (8) đảm bảo mọi lộ trình đều bắt đầu và kết thúc tại kho."

### 5.3 Ký hiệu biến thường dùng
- n: tổng số khách hàng cần phục vụ
- K: tổng số chuyến xe / tập xe
- N = {0, 1, ..., n+1}: tập các đỉnh của đồ thị
- C = {1, 2, ..., n}: tập các khách hàng
- cij: chi phí đi từ i đến j
- q: sức chứa của một xe
- di: nhu cầu tại nút i
- xijk ∈ {0,1}: biến nhị phân, bằng 1 nếu xe k đi từ i đến j

---

## 6. TRÌNH BÀY KẾT QUẢ THỰC NGHIỆM CHUẨN TIẾNG VIỆT

### 6.1 Cấu trúc phần kết quả
```
5.1 Cấu hình thực nghiệm
  - Bộ dữ liệu kiểm thử (benchmark / thực tế)
  - Cấu hình máy tính (CPU, RAM, ngôn ngữ lập trình)
  - Tham số thuật toán

5.2 Kết quả và so sánh
  - Bảng so sánh với baseline / trạng thái hiện tại
  - Nhận xét từng trường hợp

5.3 Phân tích độ nhạy
  - Thay đổi từng tham số và quan sát ảnh hưởng
```

### 6.2 Cách mô tả kết quả (tiếng Việt)

**So sánh tốt hơn:**
> "Thuật toán [X] cho kết quả tốt hơn [Y] ở [Z]% các trường hợp kiểm thử, như thể hiện trong Bảng [số]."
> "Với bộ dữ liệu có [n] khách hàng, phương án đề xuất đạt tổng quãng đường [giá trị], tiết kiệm khoảng [X]% so với phương án hiện tại."

**Kết quả hỗn hợp (trung thực hơn):**
> "Kết quả nhìn chung là khả quan, tuy nhiên với các trường hợp có [đặc điểm đặc biệt], hiệu quả cải thiện không đáng kể."
> "Mặc dù [chỉ tiêu A] được cải thiện đáng kể, song [chỉ tiêu B] lại tăng nhẹ, phản ánh sự đánh đổi [trade-off] vốn có trong bài toán."

**Nhận xét hàm ý thực tiễn:**
> "Kết quả này gợi mở rằng các nhà quản lý logistics nên [khuyến nghị cụ thể]."
> "Về mặt thực tiễn, điều này có nghĩa là [hàm ý ứng dụng]."

---

## 7. VĂN PHONG TIẾNG VIỆT HỌC THUẬT — KHO TỪ

### 7.1 Từ/cụm từ học thuật thường dùng (tiếng Việt)
- "theo đó" → liên kết nguyên nhân - kết quả
- "bên cạnh đó" → bổ sung ý
- "tuy nhiên" / "song" / "nhưng" → đối lập
- "ngoài ra" → thêm ý phụ
- "đặc biệt là" → nhấn mạnh
- "đáng chú ý là" → điểm nổi bật
- "nhìn chung" / "về cơ bản" → tổng kết
- "cụ thể là" / "cụ thể" → chi tiết hóa
- "có thể thấy rằng" → rút ra nhận định
- "điều này cho thấy" → giải thích kết quả
- "trên cơ sở đó" → dẫn vào hành động tiếp theo
- "trong khuôn khổ nghiên cứu này" → giới hạn phạm vi
- "vượt ra ngoài phạm vi của bài báo này" → thừa nhận giới hạn
- "cần tiếp tục nghiên cứu" → đề xuất hướng tương lai

### 7.2 Cấu trúc câu hay gặp trong văn học thuật VN
- "Với [điều kiện], [phương pháp] [hành động]."
- "Mặc dù [A], [B] vẫn [kết quả]."
- "Do [nguyên nhân], [hệ quả]."
- "Từ [căn cứ/phân tích], có thể rút ra [kết luận]."
- "[Kết quả], qua đó [hàm ý/ứng dụng]."
- "Không chỉ [A] mà còn [B], điều này [kết luận]."
- "[Tác giả] đã [hành động], đồng thời [hành động phụ]."
- "Theo [nguồn], [thực trạng/số liệu], [nhận xét]."

### 7.3 Từ/cụm từ chuyên ngành Logistics VN (từ BCLVN 2024)
- "hạ tầng logistics" (không nói "cơ sở hạ tầng logistics" khi đã rõ ngữ cảnh)
- "chi phí logistics" (không "cost logistics")
- "dịch vụ logistics tích hợp" = integrated logistics services
- "giao thông đa phương thức" = multimodal transport
- "thị phần vận tải" = transport market share
- "kết nối vùng miền" = regional connectivity
- "tuyến đường thủy nội địa" = inland waterway route
- "cảng cạn / ICD" = inland container depot
- "chặng cuối / giao hàng chặng cuối" = last-mile delivery
- "chuỗi lạnh / logistics dây chuyền lạnh" = cold chain logistics
- "trung tâm logistics" = logistics center/hub
- "điểm thông quan" = customs clearance point
- "tuyến liên vận quốc tế" = international multimodal route

---

## 8. MẪU ĐOẠN VĂN HOÀN CHỈNH

### 8.1 Mẫu mở bài (tiếng Việt học thuật)

**Kiểu 1 — Khởi đầu từ bối cảnh thực tế:**
> "Trong những năm gần đây, sự phát triển mạnh mẽ của thương mại điện tử đã tạo ra áp lực ngày càng lớn đối với hệ thống phân phối hàng hóa đô thị. Theo Báo cáo Logistics Việt Nam 2024, thị trường logistics toàn cầu ước đạt 8,96 nghìn tỷ USD năm 2023 và dự kiến tăng lên 21,91 nghìn tỷ USD vào năm 2033, với tốc độ tăng trưởng kép hàng năm đạt 9,35%. Trong bối cảnh đó, bài toán định tuyến xe (Vehicle Routing Problem – VRP) và các biến thể của nó ngày càng thu hút sự quan tâm của cả giới nghiên cứu lẫn các doanh nghiệp logistics, do tiềm năng tiết kiệm chi phí vận hành đáng kể mà chúng mang lại."

**Kiểu 2 — Khởi đầu từ bài toán:**
> "Có thể phát biểu bài toán VRP cơ bản một cách đơn giản như sau: Có một tập hợp M xe giống nhau cùng xuất phát tại một kho hàng đi làm nhiệm vụ giao hàng cho N khách hàng, mỗi khách hàng đòi hỏi cung cấp một lượng hàng nhất định. Yêu cầu đặt ra của bài toán là tìm đường đi ngắn nhất cho M xe đáp ứng được tất cả các đòi hỏi của khách hàng. Bài toán VRP bắt nguồn từ năm 1959 khi Dantzig và Ramser thiết lập công thức toán học để giải quyết vấn đề cung cấp xăng dầu cho các trạm dịch vụ; từ đó đến nay, sự quan tâm đến VRP đã mở rộng từ một nhóm các nhà toán học sang phạm vi rộng các nhà nghiên cứu và các nhà thực hành từ nhiều ngành khác nhau."

### 8.2 Mẫu đoạn kết luận (tiếng Việt)
> "Bài báo đã trình bày rõ thêm các kiến thức cơ bản về [bài toán], làm rõ [thuật toán đề xuất] và tiến hành thực nghiệm với bộ dữ liệu được phân loại cụ thể. Kết quả cho thấy [kết quả chính]. Việc [hướng mở rộng] là hướng nghiên cứu tiếp theo của bài báo."

---

## 9. GHI CHÚ VỀ PHONG CÁCH THEO TỪNG LOẠI VĂN BẢN

### 9.1 Bài báo tạp chí tiếng Việt (UNETI style)
- Tóm tắt ngắn gọn, thẳng vào vấn đề
- Từ khóa bao gồm cả tiếng Việt và tiếng Anh
- Công thức toán học đánh số, giải thích ký hiệu ngay dưới công thức
- Kết luận ngắn (3-5 câu), tập trung vào đóng góp và hướng tiếp theo

### 9.2 Báo cáo thực tiễn (BCLVN style)
- Kết hợp hình ảnh, bảng, biểu đồ dày đặc
- Trích dẫn nguồn ngay dưới mỗi hình/bảng: "Nguồn: [Tổ chức], [năm]"
- Dùng gạch đầu dòng nhiều để liệt kê chính sách, giải pháp
- Đánh giá cuối mỗi mục: ưu điểm trước, hạn chế sau, khuyến nghị cuối

### 9.3 Luận văn thạc sĩ
- Formal hơn bài báo, giải thích chi tiết hơn
- Mọi ký hiệu mới cần định nghĩa ngay lần đầu xuất hiện
- Mỗi chương có phần giới thiệu và phần kết luận chương riêng
- Thừa nhận hạn chế rõ ràng ở chương Kết luận

---

*Cập nhật lần cuối: Sau khi đọc Báo cáo Logistics Việt Nam 2024 (file #26) và các paper tiếng Việt UNETI (file #3, #4)*
*Tổng số file đã học: 12/27 (bao gồm BCLVN 2024)*
