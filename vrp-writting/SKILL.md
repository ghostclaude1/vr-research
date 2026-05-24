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

## 10. COLLABORATIVE VRP — KIẾN THỨC CHUYÊN SÂU (từ file #13)

> Học từ: WangEtAl2018_CMCVRPSDP-HNSGA2-CGA.pdf (Knowledge-Based Systems, Elsevier 2018)

### 10.1 Khái niệm cốt lõi — Collaborative VRP

**Horizontal vs Vertical synergy:**
- **Horizontal synergy**: hợp tác giữa các cơ sở cùng cấp (DC với DC, PC với PC)
- **Vertical synergy**: hợp tác giữa các cấp khác nhau trong chuỗi cung ứng
- **Coalition**: liên minh giữa các logistics facility để chia sẻ xe + khách hàng

**Bài toán CMCVRPSDP:**
- DC (Distribution Center): giao hàng và có thể nhận hàng đồng thời
- PC (Pickup Center): chỉ nhận hàng
- Sau khi hợp tác: DC + PC chia sẻ xe, tái phân bổ khách hàng theo khoảng cách + tải trọng
- Bi-objective: min chi phí vận hành + min số lượng xe

### 10.2 Kỹ thuật viết — Paper này là mẫu xuất sắc

**Cấu trúc Introduction (pattern Wang et al. 2018):**
1. Đoạn 1: bối cảnh supply chain → giảm chi phí, cải thiện chất lượng, ý thức môi trường
2. Đoạn 2: tổng quan VRP + biến thể giao/nhận đồng thời
3. Đoạn 3: collaborative logistics + cooperative game theory
4. Đoạn 4: review MDVRP + clustering
5. **Table 1 (comparison table)** — so sánh 10 nghiên cứu với paper hiện tại → đây là cách "show the gap" rất thuyết phục
6. Đoạn cuối: liệt kê 4 đóng góp rõ ràng bằng (1)(2)(3)(4)

**Cách viết đóng góp (pattern chuẩn tiếng Anh — áp dụng được cả tiếng Việt):**
> "This article contributes in the following aspects: (1) We introduce...; (2) A bi-objective model...; (3) A hybrid...is proposed...; (4) We conducted empirical analyses..."

**Cách mô tả mathematical model:**
- Chia cost thành các thành phần TC1, TC2, TC3, AC → giải thích bằng lời trước khi viết công thức
- Sau mỗi nhóm ràng buộc: một câu giải thích nhóm đó ("Constraints (3)–(5) define semitrailer truck and vehicle capacities")
- Assumptions được liệt kê tường minh: (a), (b)

**Cách viết phần thực nghiệm (2 cấp — học thuật chuẩn):**
1. **Case study thực tế** (Chongqing city): chứng minh tính ứng dụng
2. **Benchmark dataset** (Modified Solomon): chứng minh hiệu quả thuật toán
→ Hai cấp này bổ trợ nhau: case study = thực tiễn, benchmark = học thuật

**Cách viết kết quả thuật toán trung thực (không "mỹ hóa"):**
> "HNSGA-II yields the minimum cost for every run **except the third one** where NSGA-II comes first."
→ Thừa nhận ngoại lệ → tăng tính tin cậy

**Pattern Discussion section:**
- Không chỉ tóm tắt kết quả — mở rộng sang tình huống thực tế khác (grand coalition vs sub-coalitions)
- Đặt vấn đề ổn định liên minh: "PC1 might take the number of its initial customers as a claim for profit allocation reconsideration, and threaten the stability"
→ Cách phân tích hàm ý thực tiễn rất sâu

### 10.3 Thuật ngữ mới — Cooperative Game Theory trong Logistics

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Cooperative game theory | Lý thuyết trò chơi hợp tác |
| Coalition / Grand coalition | Liên minh / Liên minh đầy đủ |
| Sub-coalition | Liên minh con |
| Profit allocation | Phân bổ lợi nhuận |
| Cost Gap Allocation (CGA) | Phương pháp phân bổ khoảng cách chi phí |
| Shapley value | Giá trị Shapley |
| MCRS (Minimum Cost-Remaining Savings) | Tiết kiệm còn lại chi phí tối thiểu |
| Core (of a coalition) | Lõi liên minh (tập nghiệm ổn định) |
| Coalition stability | Ổn định liên minh |
| Strictly Monotonic Path (SMP) | Nguyên lý đường đơn điệu tuyệt đối |
| Synergy requirement (ρ) | Yêu cầu hiệp lực (tỷ lệ % LSP lấy từ lợi nhuận chung) |
| Marginal cost | Chi phí biên |
| Cost gap | Khoảng cách chi phí |
| LSP (Logistics Service Provider) | Nhà cung cấp dịch vụ logistics bên thứ ba |
| NSGA-II | Giải thuật di truyền đa mục tiêu phi trội nhanh thế hệ II |
| MOPSO | Tối ưu bầy hạt đa mục tiêu |
| k-means clustering | Thuật toán phân cụm k-means |
| PMX (Partial Mapped Crossover) | Toán tử lai ghép ánh xạ từng phần |
| Swap mutation | Toán tử đột biến hoán vị |

### 10.4 Mẫu câu tiếng Việt học thuật — Chủ đề Collaborative VRP

**Giới thiệu hợp tác logistics:**
> "Trong môi trường cạnh tranh ngày càng khốc liệt, các cơ sở logistics ngày càng có xu hướng hình thành liên minh để chia sẻ nguồn lực vận tải nhằm giảm chi phí vận hành và tối ưu hóa mạng lưới phân phối."

**Đặt vấn đề phân bổ lợi nhuận:**
> "Tuy nhiên, việc phân bổ lợi nhuận một cách công bằng và đảm bảo tính ổn định của liên minh là thách thức cốt lõi mà các bên điều phối cần giải quyết để duy trì hợp tác bền vững."

**So sánh phương pháp phân bổ:**
> "Trong số các phương pháp phân bổ lợi nhuận được xem xét — bao gồm CGA, Shapley, MCRS và GQP — phương pháp CGA cho kết quả gần nhất với tâm lõi liên minh, qua đó đảm bảo tính ổn định và công bằng cao nhất cho các thành viên."

**Kết luận về grand coalition:**
> "Kết quả phân tích theo nguyên lý SMP cho thấy việc thành lập liên minh đầy đủ mang lại lợi ích vượt trội so với các kịch bản liên minh con, với mức giảm chi phí đạt tới X% đối với mỗi thành viên khi tham gia liên minh."

### 10.5 Cấu trúc bài báo mô hình hóa + game theory (pattern 2 tầng)

```
1. Introduction
   └─ Bối cảnh → MDVRP review → Collaborative logistics review
      → Table so sánh literature → 4 đóng góp

2. Problem Statement & Mathematical Model
   ├─ Definition (mô tả bài toán bằng lời + hình minh họa before/after)
   └─ Mathematical model (tham số → biến → TC1/TC2/TC3/AC → min F1, F2 → constraints)

3. Research Methodology
   ├─ 3.1 Algorithm (HNSGA-II: pseudo-code + giải thích từng bước)
   └─ 3.2 Profit allocation (CGA + SMP principle)

4. Empirical Analyses
   ├─ 4.1 Routing optimization (case study)
   ├─ 4.2 Algorithm comparison (benchmark Solomon)
   └─ 4.3 Profit allocation (grand coalition analysis)

5. Discussion
   └─ Grand coalition vs sub-coalitions + hàm ý thực tiễn

6. Conclusion
   └─ Số liệu cụ thể + future work (4 hướng)
```

---

## 11. SPLIT LOADS & 3D CLUSTERING — KIẾN THỨC CHUYÊN SÂU (từ file #14)

> Học từ: WangEtAl2021_CMDPDLN-SplitLoads-HGA-TS.pdf (Knowledge-Based Systems 231, Elsevier 2021)

### 11.1 Khái niệm cốt lõi — Split Loads trong VRP

**Tại sao cần split loads?**
- Nhu cầu một khách hàng vượt tải trọng xe → buộc phải chia nhiều chuyến
- Khách hàng nằm vùng ranh giới nhiều kho → chia tải để mỗi kho phục vụ một phần
- Kết quả: tăng **loading rate** (tỷ lệ lấp đầy xe), giảm số lượng tuyến, giảm quãng đường

**Min-max split strategy:**
- `h_i = ⌈d_i / Q⌉` → số lần thăm tối thiểu
- Nhu cầu bị chia theo lũy thừa 2: 1, 2, 4, ... → dễ phân bổ đều cho nhiều kho
- Với mạng n kho: mỗi phần được giao cho một kho khác nhau

**3D Customer Clustering:**
- 3 chiều: longitude, latitude, **time windows** (không gian + thời gian)
- Khách hàng ở vùng ranh giới (overlapping boundary) → ứng viên split
- Modified Manhattan distance thay vì Euclidean → phù hợp mạng lưới đô thị thực tế

### 11.2 Kỹ thuật viết — Điểm đặc sắc của paper này

**Cách dùng hình ảnh "trước/sau" (before/after figures):**
> Paper dùng Fig. 2 (initial network) và Fig. 3 (optimized network) + Table 2 so sánh số liệu cụ thể ngay trong phần Problem Statement — trước cả khi trình bày model.
→ **Kỹ thuật**: dùng ví dụ minh họa nhỏ (13 khách hàng) để "preview" kết quả, tạo motivation cho model phức tạp phía sau.

**Cách tổ chức Literature Review theo 4 nhánh song song:**
```
2.1 Problems with PDP (tổng quan PDP cơ bản)
2.2 PDP with split loads (nhánh split)
2.3 Multi-depot VRPPD with split loads + TW (nhánh kết hợp → gap)
2.4 Collaboration and resource configuration (nhánh collab)
2.5 Solution methodologies (nhánh thuật toán)
```
→ Mỗi nhánh dẫn đến **một limitation cụ thể** → ghép lại thành 4 gaps → 4 contributions.

**Cách liệt kê limitation trực tiếp (không hoa mỹ):**
> "(1) Sustainable service strategies... have not been sufficiently studied...
> (2) Collaboration and resource configuration... have not been fully accounted for.
> (3) The mathematical model... is lacking.
> (4) Traditional approaches are inefficient..."
→ Thẳng thắn, không hedge quá nhiều → phong cách paper kỹ thuật Q1 Elsevier

**Cách viết Section "Management Insights" (thay vì Discussion):**
- Tách riêng một mục "Management insights" cuối phần case study
- 2 đoạn: (1) ý nghĩa với nhà quản lý logistics; (2) bối cảnh e-commerce → hàm ý tương lai
→ Cách "đóng gói" hàm ý thực tiễn gọn, chuyên nghiệp, không lẫn vào kết quả thuật toán

**Cách báo cáo kết quả t-test trong bảng so sánh thuật toán:**
> Table 8 có hàng "t-test" và "p-value" ngay dưới kết quả → chứng minh sự khác biệt có ý nghĩa thống kê mà không cần một đoạn văn dài.

**Cách so sánh clustering algorithm (Table 14):**
- So sánh 3D clustering với MSC và DBSCAN
- Không chỉ so cost mà còn so computation time
→ Thể hiện sự toàn diện: tốt hơn cả về chất lượng lẫn tốc độ

### 11.3 Thuật ngữ mới — Split Loads & Clustering

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Split loads / Split delivery | Giao hàng phân tách / Tải trọng phân tách |
| Min-max split strategy | Chiến lược phân tách min-max |
| 3D customer clustering | Phân cụm khách hàng 3 chiều (không gian-thời gian) |
| Overlapping boundary | Vùng ranh giới chồng lấp |
| Loading rate | Tỷ lệ lấp đầy xe / Tỷ lệ tải trọng |
| Vehicle utilization | Hiệu suất sử dụng xe |
| Collaborative logistics network (CLN) | Mạng lưới logistics hợp tác |
| Non-collaborative network | Mạng lưới không hợp tác |
| Customer service sharing | Chia sẻ dịch vụ khách hàng |
| HGA-TS | Giải thuật di truyền lai ghép với tìm kiếm Tabu |
| Tabu list | Danh sách cấm (Tabu) |
| Aspiration criterion | Tiêu chí ngoại lệ (cho phép bỏ qua danh sách cấm) |
| Roulette wheel selection | Chọn lọc bánh xe roulette |
| Relocate / Swap / Reverse / Insert / Slide / SPS / SRPS | 7 toán tử tìm kiếm lân cận cục bộ |
| DBSCAN | Phân cụm dựa trên mật độ |
| MSC (Mean Shift Clustering) | Phân cụm dịch chuyển trung bình |
| ALNS | Tìm kiếm lân cận rộng thích nghi |

### 11.4 Cấu trúc paper "model + 2-stage algorithm" (pattern Wang et al. 2021)

```
1. Introduction
   └─ Bối cảnh e-commerce → split loads → collaboration → gap

2. Literature Review (5 nhánh → 4 limitations → 4 contributions)

3. Problem Statement
   ├─ Ví dụ minh họa nhỏ (before/after hình + bảng so sánh)  ← ĐIỂM ĐẶC SẮC
   └─ Mô tả bài toán MDPDVRPST

4. Model Formulation
   ├─ Table ký hiệu (Notations & Variables)
   ├─ Objective: Min C = TC + PC
   ├─ Route constraints (4)–(14)
   ├─ Capacity constraints (15)–(25)
   └─ Time constraints (26)–(37) + Binary (38)–(43)

5. Solution Methodology
   ├─ 5.1 3D clustering + split strategy (Algorithm 1 + min-max strategy)
   ├─ 5.2 HGA-TS (encoding/decoding → evaluation → genetic operators → TS)
   └─ 5.3 Algorithm comparison (small-scale CPLEX validation + large-scale benchmark)

6. Case Study (Chongqing, 5 depots, 150 customers)
   ├─ 6.1 Data source
   ├─ 6.2 Clustering results
   ├─ 6.3 Route optimization with split loads
   └─ 6.4 Management insights  ← ĐIỂM ĐẶC SẮC

7. Conclusions (số liệu cụ thể + 5 future directions)
```

### 11.5 Mẫu câu tiếng Việt — Chủ đề Split Loads

**Giới thiệu nhu cầu split:**
> "Trong thực tế, nhu cầu của một số khách hàng có thể vượt tải trọng của một xe hoặc nằm trong vùng ranh giới phục vụ của nhiều kho hàng. Khi đó, chiến lược phân tách tải trọng cho phép nhu cầu được chia thành nhiều phần nhỏ và phục vụ bởi nhiều xe hoặc nhiều kho khác nhau, qua đó nâng cao tỷ lệ lấp đầy xe và giảm thiểu chi phí vận chuyển tổng thể."

**Mô tả kết quả loading rate:**
> "Kết quả so sánh cho thấy tỷ lệ lấp đầy xe trung bình tăng từ X% lên Y% sau khi áp dụng chiến lược phân tách tải trọng, đồng thời số lượng tuyến đường giảm từ A xuống B, phản ánh hiệu quả tối ưu hóa sử dụng nguồn lực phương tiện."

**Chuyển tiếp từ clustering sang routing:**
> "Trên cơ sở kết quả phân cụm 3 chiều, các khách hàng đã được tái phân bổ về kho phù hợp nhất. Những khách hàng nằm trong vùng ranh giới chồng lấp của nhiều kho được xác định là ứng viên phân tách tải trọng, tạo tiền đề cho bước tối ưu hóa tuyến đường tiếp theo."

---

## 12. EVRP — TỔNG QUAN & PHÂN LOẠI (từ file #18)

> Học từ: Xu2024_EVRP-Review.pdf (Studia UBB Informatica, Vol. LXIX No.2, 2024)

### 12.1 Bức tranh toàn cảnh EVRP (2022–2024)

**Ba chiều phân loại EVRP:**
| Chiều | Các loại |
|---|---|
| **Mô hình tiêu thụ năng lượng** | Linear (khoảng cách/thời gian) vs Nonlinear (lực cản không khí, lực cản lăn, trọng lực, tải trọng, địa hình) |
| **Chiến lược sạc pin** | Full charging / Partial charging / Battery swapping / Wireless charging / Mobile charging |
| **Ràng buộc mở rộng** | Time windows (hard/soft/mixed/prioritized) / Pickup & Delivery / Multi-depot / Open/Closed/Half-open |

**13 hàm mục tiêu phổ biến trong EVRP:**
1. Tổng quãng đường | 2. Tổng thời gian | 3. Số xe | 4. Tiêu thụ năng lượng
5. Chi phí cố định | 6. Chi phí phạt | 7. Chi phí/thời gian sạc hoặc đổi pin
8. Thời gian chờ tại trạm sạc | 9. Chi phí giao hàng | 10. Chi phí suy hao pin
11. Chi phí phát thải carbon | 12. Chi phí dịch vụ khách hàng | 13. Khác

**Phân bố thuật toán EVRP (2022–2024):**
- LNS/ALNS: 29.2% → **phổ biến nhất**
- VNS: 16.7%
- Branch-and-Price: 12.5%
- ACO: 8.3% | SA: 8.3% | GA: 6.2% | TS: 4.2% | Other: 14.6%

### 12.2 Kỹ thuật viết — Paper Review/Survey

**Cấu trúc bài review chuẩn (pattern Xu 2024):**
```
1. Introduction
   ├─ Bối cảnh (carbon emission, EU Climate Act)
   ├─ Khoảng trống: review hiện có chỉ đến 2022 → paper này bù khoảng 2022–2024
   └─ Phạm vi: 42 papers, impact factor > 4

2. EVRP Formulation (model MIP cơ bản — "nền tảng chung")

3. Classifications (phân loại theo 3 chiều: energy / charging / constraints)
   ├─ 3.1 Objective functions → Table 1 (matrix paper × objectives)
   ├─ 3.2 Energy consumption calculation
   ├─ 3.3 Charging strategy
   └─ 3.4 Constraints (TW / PD / Multi-depot / Open-Close)

4. Solution Approaches (phân tích từng nhóm thuật toán)

5. Discussion
   ├─ 5.1 So sánh ưu/nhược các thuật toán
   └─ 5.2 Open issues (multi-objective, hybrid AI, ML prediction)

6. Conclusions
```

**Kỹ thuật đặc trưng của paper review:**

*Table matrix (paper × features):*
> Table 1 liệt kê 42 paper × 13 objective functions → đánh dấu ✓ → đọc ngay pattern nào phổ biến, gap nào chưa ai làm
→ **Học được**: đây là cách "show the landscape" toàn diện nhất trong review paper

*Xác định khoảng trống thời gian:*
> "Existing review studies primarily focus on research published before 2022... Therefore, the present study conducts an in-depth review of recent EVRP research from 2022."
→ **Pattern gap theo thời gian** — đơn giản nhưng rất thuyết phục khi lĩnh vực phát triển nhanh

*Cách so sánh thuật toán trong Discussion (không chỉ khen):*
> "BP needs to be combined with heuristic acceleration strategies to balance efficiency and accuracy"
> "GA typically requires more iterations to converge... leading to higher computational costs"
> "ACO in large-scale EVRP... increased computation time"
→ **Học được**: mỗi thuật toán có 1 điểm mạnh + 1 hạn chế thực tế → trung thực, không PR

*Future directions 3 hướng rõ ràng:*
> (1) Multi-objective trade-offs → cần thuật toán hiệu quả hơn
> (2) Hybrid heuristic + reinforcement learning
> (3) Machine learning dự báo năng lượng, nhu cầu sạc, lưu lượng giao thông

### 12.3 Thuật ngữ mới — EVRP

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Electric Vehicle Routing Problem (EVRP) | Bài toán định tuyến xe điện |
| State of Charge (SoC) | Trạng thái sạc pin |
| State of Health (SoH) | Trạng thái sức khỏe pin |
| Battery degradation | Suy hao pin |
| Full charging strategy | Chiến lược sạc đầy |
| Partial charging strategy | Chiến lược sạc một phần |
| Battery swapping | Đổi pin |
| Wireless charging | Sạc không dây |
| Mobile charging/swapping | Sạc/đổi pin di động |
| Charging station | Trạm sạc |
| Hard time window | Cửa sổ thời gian cứng |
| Soft time window | Cửa sổ thời gian mềm |
| Mixed time window | Cửa sổ thời gian hỗn hợp |
| Prioritized time window | Cửa sổ thời gian ưu tiên |
| Half-open model | Mô hình nửa mở (xe về kho gần nhất) |
| Branch-and-Price (BP) | Thuật toán nhánh và giá |
| Q-learning (QL) | Học tăng cường Q-learning |
| Memetic Algorithm (MA) | Thuật toán ký ức (hybrid GA + local search) |
| LNS-QL | LNS kết hợp Q-learning |
| Time-Dependent EVRP | EVRP phụ thuộc thời gian |
| Energy consumption model | Mô hình tiêu thụ năng lượng |

### 12.4 Mẫu câu tiếng Việt — Chủ đề EVRP & Review Paper

**Mở đầu bài review bằng bối cảnh chính sách:**
> "Trước áp lực ngày càng tăng về giảm phát thải khí nhà kính, nhiều quốc gia đã ban hành các chính sách thúc đẩy chuyển đổi sang phương tiện điện trong lĩnh vực vận tải. Trong bối cảnh đó, bài toán định tuyến xe điện (EVRP) nổi lên như một hướng nghiên cứu trọng tâm, mở rộng từ VRP truyền thống với các ràng buộc đặc thù về dung lượng pin và chiến lược sạc."

**Xác định khoảng trống theo thời gian:**
> "Mặc dù đã có một số công trình tổng quan về EVRP, phần lớn tập trung vào các nghiên cứu trước năm [X]. Do lĩnh vực này phát triển nhanh chóng trong những năm gần đây, một đánh giá có hệ thống về các tiến bộ mới nhất là cần thiết để cung cấp bức tranh cập nhật cho cộng đồng nghiên cứu."

**So sánh thuật toán trung thực (review style):**
> "LNS và biến thể ALNS chiếm ưu thế trong giải EVRP nhờ khả năng xử lý bài toán quy mô lớn và dễ dàng tích hợp với các thuật toán khác. Tuy nhiên, hiệu quả của LNS phụ thuộc đáng kể vào thiết kế các toán tử phá hủy và sửa chữa, đòi hỏi điều chỉnh cẩn thận cho từng biến thể bài toán cụ thể."

**Định hướng tương lai (future work) kiểu review:**
> "Nhìn về tương lai, ba hướng nghiên cứu tiềm năng được xác định: (i) phát triển các thuật toán đa mục tiêu hiệu quả hơn để cân bằng các mục tiêu xung đột trong EVRP; (ii) khám phá sự kết hợp giữa heuristic và học tăng cường để thích nghi với môi trường động; và (iii) tích hợp mô hình học máy dự báo nhu cầu sạc pin và lưu lượng giao thông vào quá trình định tuyến."

---

## 13. STOCHASTIC DYNAMIC VRP & PRESCRIPTIVE ANALYTICS (từ file #19/#24)

> Học từ: SoeffkerEtAl2022_SDVRP-PrescriptiveAnalytics-Review.pdf (EJOR 298, 2022) — Invited Review
> ⚠️ Lưu ý: file PDF này bị đặt nhầm tên là "Failure-specific cooperative recourse strategy..." nhưng nội dung thực là bài review SDVRP.

### 13.1 Framework Prescriptive Analytics cho SDVRP

**Ba tầng business analytics:**
- **Descriptive analytics** → rút insights từ dữ liệu quá khứ
- **Predictive analytics** → xây dựng information model dự báo tương lai
- **Prescriptive analytics (PA)** → tích hợp information model vào decision making

**Ba nguồn bất định trong SDVRP:**
| Nguồn | Ví dụ |
|---|---|
| **Uncertain demand** | Khách hàng mới xuất hiện trong ngày, nhu cầu thực tế chỉ biết khi xe đến nơi, thời gian phục vụ biến động |
| **Uncertain environment** | Tắc đường, đóng đường, phí cầu đường thay đổi |
| **Uncertain resources** | Xe hỏng, tài xế nghỉ đột xuất, tài xế crowdsourced, phạm vi xe điện |

**Sequential decision process (Bellman Equation):**
> Mọi SDVRP đều có thể mô hình hóa như một chuỗi quyết định: mỗi state sk → solve decision model → chọn xk → transition → state mới sk+1

### 13.2 Phân loại 4 nhóm phương pháp PA cho SDVRP

| Nhóm | Phương pháp | Dùng info model | Horizon |
|---|---|---|---|
| **Rolling Horizon** | Reoptimization | Descriptive (hiện tại) | Ngắn |
| **Cat. I** | Cost Function Approximation (CFA) | External, predictive | Ngắn-vừa |
| **Cat. I** | Policy Function Approximation (PFA) | External, predictive | Dài |
| **Cat. IIa** | Multiple Scenario Approach (MSA) | Internal, predictive | Vừa |
| **Cat. IIa** | Rollout Algorithm (RA) | Internal, predictive | Vừa-dài |
| **Cat. IIb** | Value Function Approximation (VFA) | Internal, prescriptive | Dài |

**Quy tắc chọn phương pháp:**
- Cần **detail** (dimensionality cao, heterogeneity, correlation, constraints phức tạp) → CFA hoặc MSA
- Cần **horizon dài** (future reward >> immediate reward, disruptivity cao) → PFA hoặc VFA
- Cần cả hai → Rollout Algorithm

### 13.3 Kỹ thuật viết — Paper Review cao cấp (Invited Review EJOR)

**Điểm khác biệt so với review thông thường:**

*Framework hóa toàn bộ lĩnh vực bằng một sơ đồ duy nhất:*
> Fig. 1 (Prescriptive Analytics) → Fig. 2 (Dimensions of VRP) → Fig. 3 (Sources of uncertainty) → Fig. 4 (Sequential decision process) → Fig. 5 (Methods visualization)
→ **Học được**: review paper đỉnh không chỉ liệt kê — mà xây dựng một **unified framework** để đặt mọi thứ vào đúng chỗ

*Dùng một ví dụ xuyên suốt (running example):*
> Dynamic VRP with stochastic customer requests → minh họa từng phần: information model, decision model, từng nhóm phương pháp
→ **Học được**: running example giúp người đọc follow được lý thuyết trừu tượng

*Table tổng hợp định tính (Table 2):*
> So sánh 6 phương pháp theo 4 tiêu chí (Detail/Horizon × Info/Decision model), dùng +/++/+++ thay vì số liệu
→ **Học được**: trong review, đôi khi đánh giá định tính còn thuyết phục hơn số liệu — miễn là rõ ràng và có luận điểm

*Anecdotal evidence trước generalization:*
> Section 5.1: thực nghiệm cụ thể (MSA vs VFA theo heterogeneity) → Section 5.2: khái quát hóa thành recommendation chung
→ **Học được**: đưa bằng chứng cụ thể TRƯỚC khi nói rule chung → đảm bảo credibility

*Outlook ≠ Future work:*
> Thay vì liệt kê "future directions" như paper thường, Invited Review này đặt ra **research agenda**: quantitative measures cần phát triển, validation của Table 2 cần community research
→ **Học được**: Outlook của Invited Review là lời kêu gọi cộng đồng, không phải checklist

### 13.4 Thuật ngữ mới — SDVRP & Prescriptive Analytics

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Stochastic Dynamic VRP (SDVRP) | Bài toán định tuyến xe ngẫu nhiên động |
| Prescriptive analytics (PA) | Phân tích quy định / Phân tích hỗ trợ ra quyết định |
| Sequential decision process | Quá trình quyết định tuần tự |
| Degree of dynamism (DOD) | Mức độ động của bài toán |
| Information model | Mô hình thông tin (mô tả bất định) |
| Decision model | Mô hình quyết định |
| Policy | Chính sách (hàm ánh xạ state → decision) |
| Bellman Equation | Phương trình Bellman |
| Post-decision state | Trạng thái sau quyết định |
| Value function approximation (VFA) | Xấp xỉ hàm giá trị |
| Policy function approximation (PFA) | Xấp xỉ hàm chính sách |
| Cost function approximation (CFA) | Xấp xỉ hàm chi phí |
| Multiple Scenario Approach (MSA) | Phương pháp đa kịch bản |
| Rollout Algorithm (RA) | Thuật toán rollout |
| Rolling horizon reoptimization | Tái tối ưu hóa theo khoảng lăn |
| Crowdsourced driver | Tài xế cộng đồng (gig economy) |
| Disruptivity | Tính gián đoạn / độ đột ngột của thay đổi |
| Heterogeneity (spatial/temporal) | Tính không đồng nhất (không gian/thời gian) |

### 13.5 Mẫu câu tiếng Việt — Chủ đề SDVRP

**Giới thiệu bài toán động:**
> "Trong thực tế vận hành logistics, thông tin về nhu cầu khách hàng, điều kiện giao thông và tình trạng phương tiện không phải lúc nào cũng được biết trước. Các thay đổi bất ngờ trong ba chiều này — nhu cầu, môi trường và nguồn lực — đặt ra yêu cầu ra quyết định động theo thời gian thực, vượt ra ngoài phạm vi của các bài toán VRP tĩnh truyền thống."

**Phân biệt descriptive / predictive / prescriptive:**
> "Trong khi phân tích mô tả (descriptive analytics) rút ra insights từ dữ liệu lịch sử và phân tích dự báo (predictive analytics) xây dựng mô hình thông tin về các diễn biến tương lai, phân tích quy định (prescriptive analytics) đi xa hơn bằng cách tích hợp trực tiếp mô hình thông tin vào quá trình ra quyết định — hướng tới các lời khuyên hành động tối ưu."

**Lập luận về framework thống nhất:**
> "Mặc dù các bài toán SDVRP rất đa dạng về lĩnh vực ứng dụng, chúng đều chia sẻ một cấu trúc chung: một chuỗi quyết định tuần tự trong đó mỗi quyết định được đưa ra dựa trên thực hiện hóa hiện tại của mô hình thông tin và mục tiêu tối đa hóa phần thưởng kỳ vọng tích lũy. Framework này, được hình thức hóa qua phương trình Bellman, cho phép phân loại và so sánh các phương pháp tính toán một cách có hệ thống."

---

## 14. CAPACITATED CLUSTERING & GRAMPS METAHEURISTIC (từ file #20)

> Học từ: AhmadiOsman2005_GRAMPS-CCP.pdf (EJOR 162, Elsevier 2005)

### 14.1 Bài toán CCP — Capacitated Clustering Problem

**Định nghĩa:**
- Cho n điểm có trọng số → phân thành p cluster
- Mỗi cluster có 1 tâm (center), tổng trọng số không vượt Q
- Mục tiêu: tối thiểu tổng scatter (tổng khoảng cách các điểm đến tâm cluster của chúng)
- NP-hard (dẫn từ NP-completeness của UCP với p=2)

**Ứng dụng thực tiễn của CCP:**
- Hợp nhất đơn hàng khách hàng thành lô vận tải (→ **liên quan trực tiếp đến VRP clustering**)
- Vị trí trung tâm chuyển mạch mạng viễn thông
- Thiết kế quỹ chỉ số tối ưu
- Thiết kế hệ thống thông tin, ứng dụng sản xuất và marketing

### 14.2 Framework GRAMPS — Học điểm cốt lõi

**GRAMPS = GRASP + AMP (Adaptive Memory Programming)**

So sánh 3 phương pháp Guided Construction Search:
| Đặc điểm | GRASP | ACO | GRAMPS |
|---|---|---|---|
| Bộ nhớ | Không có | Pheromone toàn bộ | Elite set (chọn lọc) |
| Học từ | - | Tất cả nghiệm | Nghiệm elite tốt nhất |
| Xử lý nghiệm yếu | - | Evaporation | Không chấp nhận vào elite |
| Chọn trung tâm | Greedy random | Probabilistic pheromone | Density + Intensity kết hợp |

**3 quá trình của GRAMPS mỗi iteration:**
1. **Construction** (RDSCM): chọn center từ RCL theo hàm hc = c·density + intensity
2. **Learning**: cập nhật elite set, tính intensity (tần suất × chất lượng của center trong elite)
3. **Local search**: restricted 1-interchange descent trên cặp l-adjacent clusters

**Cân bằng exploration/exploitation — điểm thông minh nhất của GRAMPS:**
> Tham số c điều khiển trọng số density vs intensity:
> - Đầu: c = 10r → ưu tiên density (problem-domain data) → exploration
> - Dần dần: c giảm → ưu tiên intensity (memory data) → exploitation
> - Tự điều chỉnh theo số distinct solutions tìm được trong 2r iteration gần nhất

### 14.3 Kỹ thuật viết — Paper thuật toán EJOR cổ điển (2005)

**Cấu trúc ngắn gọn, tập trung vào algorithm:**
```
1. Introduction: CCP definition → ứng dụng → review ngắn các phương pháp → gap → đóng góp
2. GRAMPS Metaheuristic (tổng quát)
3. GRAMPS Implementation (cho CCP cụ thể)
   ├─ 3.1 Construction (DSCM/RDSCM)
   ├─ 3.2 Learning (elite set management + intensity measure)
   ├─ 3.3 Local search (restricted 1-interchange)
   └─ 3.4 GRAMPS algorithm (pseudocode)
4. Computational Experience
   ├─ 4.1 Test instances (40 benchmarks, 4 sets)
   ├─ 4.2 Effect of learning (V1 vs V2)
   └─ 4.3 Comparison with literature
5. Conclusion
```

**Kỹ thuật phân tích ablation (V1 vs V2):**
> Thay vì chỉ so sánh GRAMPS với các thuật toán khác, paper tách ra:
> - V1 = GRAMPS không có learning (= GRASP thuần)
> - V2 = GRAMPS đầy đủ
> → Chứng minh được đúng thành phần nào tạo ra improvement
→ **Học được**: ablation study — phương pháp chứng minh đóng góp của từng component

**Vấn đề so sánh CPU time giữa các máy khác nhau — giải pháp chuẩn:**
> Table 5: convert CPU time của tất cả thuật toán về cùng một nền tảng (Sun SPARC 1000) dùng Mflop/s
> + Đề xuất **MIC** (Marginal Improvement per CPU unit) = ARPI / ACPU → ranking tổng hợp
→ **Học được**: khi phần cứng khác nhau, phải normalize CPU time + dùng chỉ số tổng hợp

**Cách viết Conclusion ngắn + hướng tương lai có giá trị:**
> 3 hướng mở rộng cụ thể:
> (1) Học thêm từ assignment (không chỉ centers)
> (2) Maintain large elite set từ nhiều metaheuristics → unified framework
> (3) Kết hợp GRAMPS với path relinking

### 14.4 Thuật ngữ mới — Clustering & Metaheuristics

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Capacitated Clustering Problem (CCP) | Bài toán phân cụm có ràng buộc tải trọng |
| p-median problem | Bài toán p-trung vị |
| Scatter (objective) | Tổng phân tán (tổng khoảng cách điểm → tâm) |
| Cluster tightness (s) | Độ chặt của cluster (tỷ lệ tổng nhu cầu / tổng capacity) |
| Greedy Random Adaptive Search (GRASP) | Tìm kiếm thích nghi ngẫu nhiên tham lam |
| Adaptive Memory Programming (AMP) | Lập trình bộ nhớ thích nghi |
| Elite set | Tập nghiệm ưu tú |
| Intensity measure | Thước đo cường độ (tần suất × chất lượng) |
| Strongly determined variable | Biến được xác định mạnh |
| Consistent variable | Biến nhất quán (tần suất cao trong elite) |
| Restricted Candidate List (RCL) | Danh sách ứng viên giới hạn |
| Density Search Construction Method (DSCM) | Phương pháp xây dựng tìm kiếm mật độ |
| k-interchange neighborhood | Lân cận hoán đổi k điểm |
| l-adjacent clusters | Các cluster l-kề nhau |
| Aspiration criterion | Tiêu chí ngoại lệ (chấp nhận nghiệm bị cấm nếu đủ tốt) |
| MIC (Marginal Improvement per CPU) | Cải thiện biên trên mỗi đơn vị CPU |
| ARPD (Average Relative % Deviation) | Độ lệch phần trăm tương đối trung bình |
| Ablation study | Nghiên cứu loại bỏ thành phần |

### 14.5 Liên hệ với VRP Clustering

CCP là **bài toán nền tảng** cho các bước clustering trong nhiều VRP paper:
- File #13 (HNSGA-II): k-means clustering để phân cụm khách hàng trước khi route
- File #14 (HGA-TS): 3D customer clustering (lon/lat/TW)
- **CCP cung cấp foundation lý thuyết**: tại sao clustering NP-hard, cách đo scatter, tại sao cần metaheuristic thay vì exact solver

---

## 15. HMCVRP & BENDERS DECOMPOSITION (từ file #21)

> Học từ: ZhangEtAl2022_HMCVRP-Benders-BBC.pdf (Transportation Research Part B 160, Elsevier 2022)

### 15.1 Bài toán HMCVRP — Điểm mới so với các paper trước

**Heterogeneous multi-depot collaborative VRP:**
- Các kho hàng (depot) mang **sản phẩm khác nhau** → không thể exchange request trực tiếp
- Giải pháp: **transshipment** — xe của depot A chở sản phẩm B bằng cách ghé **transfer point (TP)**
- TP có thể là: depot của B hoặc customer của B (xe B phải đến unload trước xe A đến load)
- **3 thách thức cốt lõi**: (1) chọn TP tối ưu, (2) phối hợp arrival time, (3) theo dõi product flow

**So sánh với file #13 (CMCVRPSDP):**
| Đặc điểm | CMCVRPSDP (#13) | HMCVRP (#21) |
|---|---|---|
| Sản phẩm | Giống nhau | Khác nhau |
| Hợp tác | Chia sẻ xe + khách hàng | Transshipment tại TP |
| Phương pháp | HNSGA-II (heuristic) | Benders-based B&C (exact) |
| Quy mô | Vừa-lớn | Nhỏ-vừa |

### 15.2 Kỹ thuật Benders-based Branch-and-Cut (EBBC)

**Decomposition 3 phần:**
- **MASTER**: tìm routes + TP tối ưu (không xét arrival time hay product flow)
- **SP1**: kiểm tra feasibility của arrival time → generate Benders' cuts (32)
- **SP2**: kiểm tra feasibility của product flow → generate Benders' cuts (46)

**Tại sao Benders tốt hơn big-M?**
> Big-M constraints trở nên "lỏng" trong LP relaxation → không tạo được tight lower bound → branch-and-bound tree rất lớn
> Combinatorial Benders' cuts cắt trực tiếp vào infeasible combinations → tighter LP relaxation

**4 enhancement strategies của EBBC:**
1. **Multiple cuts từ DP3/DP4**: giải dual problems nhiều lần với weights khác nhau → nhiều cuts hơn
2. **Subtour elimination** (Stoer-Wagner min-cut algorithm): loại subtour trước khi pass sang SP1/SP2
3. **Single vehicle subproblem (SP3)**: tạo cuts riêng cho từng xe → nhiều cuts hơn SP2
4. **Additional cuts (73)-(76)**: symmetry-breaking + logic cuts từ domain knowledge

**Kết quả thực nghiệm (EBBC vs CPLEX/SVR):**
- Group 1 (2 depot, 20 KH): EBBC 10.91s vs SVR 300s → **27× nhanh hơn**
- Group 3 (3 depot, 20 KH): EBBC 29s vs SVR 7200s (timeout, 0/20 optimal)
- Group 4 (3 depot, 30 KH): EBBC 659s vs SVR 7200s (timeout, 0/20 optimal)

### 15.3 Insight thực tiễn quan trọng

**Khoảng cách depot ảnh hưởng đến cost savings:**
> Khi depots càng xa nhau → cost savings giảm dần (từ 28.7% xuống 22.1%)
> Depots gần → depot TP phổ biến hơn; Depots xa → customer TP phổ biến hơn
→ **Hàm ý quản lý**: công ty nên cân nhắc vị trí depot khi triển khai collaborative routing

**Ổn định liên minh — kết quả đáng chú ý:**
> Chỉ 5/20 instances có non-empty core
> Cả 3 phương pháp phân bổ đơn giản (no allocation, equal division, Shapley) đều thất bại → chỉ 1 instance Shapley thuộc core
→ **Kết luận**: grand coalition **không phải lúc nào cũng ổn định** — cần cơ chế phân bổ được thiết kế cẩn thận

### 15.4 Kỹ thuật viết — Paper thuật toán chính xác (TRB Q1)

**Cấu trúc paper exact algorithm chuẩn TRB:**
```
1. Introduction
   ├─ Bối cảnh logistics China (JD, Alibaba Rookie Station) → last-mile delivery
   ├─ Literature review: collaborative VRP (homogeneous) → gap (heterogeneous)
   └─ 3 đóng góp: (1) model HMCVRP, (2) EBBC algorithm, (3) operational insights

2. HMCVRP Formulation
   ├─ Problem description + assumptions
   ├─ MIP với conditional constraints (P1)
   └─ Big-M transformation → tại sao cần Benders

3. Algorithm (EBBC)
   ├─ 3.1 Benders-based B&C framework (MASTER + SP1 + SP2)
   ├─ 3.2 Combinatorial Benders' cuts (từ dual DP1, DP2)
   └─ 3.3 Enhancement strategies (4 loại)

4. Computational Study
   ├─ 4.1 Algorithm efficacy (BBC vs BBC+ vs ... vs EBBC vs SVR)
   ├─ 4.2 Depot locations → cost savings
   └─ 4.3 Cost savings allocation → coalition stability

5. Conclusions + future work
```

**Điểm đặc sắc:**
- **Table 2**: so sánh paper này với 7 CBC papers trước theo 4 chiều đặc điểm → cách "position" contribution rõ nhất
- **Ablation theo cấp**: BBC → BBC+ → BBC+SEC → BBC+SVC → EBBC → mỗi enhancement được kiểm chứng độc lập
- **Insights chính sách (Section 4.2, 4.3)**: không chỉ nói "algorithm tốt hơn" mà còn rút ra hàm ý vận hành

### 15.5 Thuật ngữ mới — Exact Methods & Transshipment

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Heterogeneous multi-depot VRP (HMCVRP) | VRP đa kho hàng không đồng nhất |
| Transfer point (TP) | Điểm trung chuyển |
| Transshipment | Trung chuyển hàng hóa |
| Benders' decomposition | Phân rã Benders |
| Benders-based branch-and-cut (BBC) | Thuật toán nhánh cắt dựa trên Benders |
| Combinatorial Benders' cuts (CBC) | Cắt Benders tổ hợp |
| Conditional constraints | Ràng buộc có điều kiện |
| Big-M transformation | Biến đổi big-M |
| Master problem | Bài toán master |
| Subproblem (SP) | Bài toán con |
| Dual problem (DP) | Bài toán đối ngẫu |
| Minimal Infeasible Subsystem (MIS) | Hệ con bất khả thi tối thiểu |
| Subtour elimination | Loại bỏ vòng con |
| Stoer-Wagner algorithm | Thuật toán min-cut Stoer-Wagner |
| Symmetry-breaking constraint | Ràng buộc phá đối xứng |
| Horizontal collaboration | Hợp tác ngang hàng |
| Core (of cooperative game) | Lõi (trò chơi hợp tác) |

### 15.6 Mẫu câu tiếng Việt — Chủ đề Exact Method & Collaboration

**Giới thiệu tại sao cần exact method:**
> "Trong khi các phương pháp heuristic và metaheuristic được ưa chuộng cho bài toán quy mô lớn, việc phát triển thuật toán chính xác vẫn có giá trị thiết yếu, đặc biệt khi cần đảm bảo tính tối ưu của nghiệm hoặc khi quy mô bài toán vừa phải cho phép điều này trong thời gian tính toán chấp nhận được."

**Giải thích Benders decomposition:**
> "Phân rã Benders cho phép tách bài toán gốc thành bài toán master và các bài toán con. Bài toán master tối ưu hóa các biến định tuyến, trong khi các bài toán con kiểm tra tính khả thi của nghiệm master đối với các ràng buộc phức tạp hơn. Khi nghiệm master bất khả thi, các cắt Benders được sinh ra và bổ sung vào master để loại bỏ vùng không khả thi."

**Kết quả depot location:**
> "Kết quả thực nghiệm cho thấy mức tiết kiệm chi phí giảm dần khi khoảng cách giữa các kho hàng tăng lên, gợi ý rằng lợi ích biên của hợp tác trở nên kém đáng kể hơn khi các kho hàng nằm xa nhau. Do đó, doanh nghiệp nên xem xét vị trí địa lý của các kho hàng như một yếu tố quyết định trong việc triển khai chiến lược định tuyến hợp tác."

---

## 16. COLD-CHAIN VRP + TIME-DEPENDENT ROADS (từ file #23)

> Học từ: HouEtAl2025_ColdChain-MDSO-FALNS.pdf (Int J Comput Intell Syst 18:289, Springer 2025)

### 16.1 Bài toán — Multi-depot Semi-open Cold-Chain VRP

**4 đặc điểm kết hợp độc đáo:**
| Đặc điểm | Nội dung |
|---|---|
| **Multi-depot** | Nhiều kho hàng, xe xuất phát từ kho gần nhất |
| **Semi-open** | Xe **không** cần quay về kho xuất phát, trả hàng tại kho **gần nhất** |
| **Time-dependent** | Vận tốc xe thay đổi theo thời gian: v(t) = α·sin(βt) + γ |
| **Simultaneous pickup & delivery** | Xe phục vụ cả giao và lấy hàng trong cùng một hành trình |

**Cấu trúc chi phí tổng (4 thành phần):**
```
Min C = C1 + C2 + C3 + C4
├─ C1: Chi phí cố định (số xe sử dụng)
├─ C2: Chi phí lạnh = C21 (vận chuyển) + C22 (chờ đợi) + C23 (mở cửa xe)
├─ C3: Chi phí hư hỏng hàng = C31 (giao) + C32 (lấy) + C33 (nhiệt độ mở cửa)
│      Dùng hàm suy giảm: D(t) = D₀·e^(-δt)
└─ C4: Chi phí nhiên liệu (theo mô hình CMEM — phụ thuộc tải trọng, vận tốc, gradient)
```

### 16.2 Algorithm FA-LNS

**Firefly Algorithm (FA) → biến đổi cho bài toán rời rạc:**
- Luminous intensity: Iᵢ = 1/f(xᵢ) → cá thể tốt hơn sáng hơn
- **Discrete distance**: rᵢⱼ = số vị trí khác nhau trong 2 chuỗi chromosome → thay Euclidean
- **Crossover thay vì "di chuyển"**: lᵢⱼ = ceil(rᵢⱼ·γ^gen) → độ dài đoạn crossover tăng dần theo học
- Greedy acceptance: chỉ cập nhật nếu nghiệm mới tốt hơn

**LNS (Large Neighborhood Search):**
- **Relevance removal**: chọn khách hàng liên quan theo R(i,j) = 1/(dᵢⱼ + vᵢⱼ)
- **Regret insertion**: ưu tiên tái chèn khách hàng có "regret value" cao nhất

**Departure time optimization strategy:**
> tbest = ES nếu ES ≤ T1 hoặc ES ≥ T2 (tránh kẹt xe)
> → Giảm thời gian di chuyển → giảm chi phí hư hỏng hàng đáng kể

### 16.3 Kết quả thực nghiệm

**FA-LNS vs Gurobi (Solomon benchmark):**
- N ≤ 10 KH: cả hai tối ưu, FA-LNS nhanh hơn nhẹ
- N = 25 KH: Gurobi mất 711-813s, FA-LNS chỉ 11-14s — **khi RC201 N=25**: Gurobi timeout, FA-LNS tốt hơn 8.2%

**FA-LNS vs PSO/LNS/GALNS (50–100 KH):**
- AVG GAP: FA-LNS 1.55% vs GALNS 6.26% vs LNS 9.32% vs PSO 16.34%

**Sensitivity Analysis — 3 loại:**
| SA | Kết quả chính |
|---|---|
| Departure time (SAME vs DIFF) | DIFF giảm total cost từ 2499 → 1296 (giảm 48%), giảm damage cost từ 1206 → 14 |
| Vehicle speed (V1/V2/V3) | V1 (ổn định) tốt nhất về tổng chi phí; V2 (đề xuất) tốt nhất về damage cost |
| Return strategy (non-open vs semi-open) | Semi-open: quãng đường giảm 7546 vs 8631, total cost 1312 vs 1321 |

### 16.4 Kỹ thuật viết — Paper ứng dụng thực tiễn (case study)

**Cấu trúc 8 sections (mô hình mở rộng):**
```
1. Introduction (bối cảnh → gap 2 chiều: TDVRP + MDVRP chưa kết hợp cold-chain)
2. Literature Review (2.1 TDVRP + 2.2 MDVRPTW → 2.3 Research Analysis: gap)
3. Problem Formulation (mô tả + symbols + travel time + 4 cost components + model)
4. Algorithm Design (FA-LNS: encoding → FA discrete → LNS → time optimization)
5. Parameter Sensitivity + Algorithm Comparison (Gurobi + heuristics)
6. Case Study + 3 Sensitivity Analyses
7. Managerial Insights (5 insights cho nhà quản lý)
8. Conclusion (Discovery + Limitations + Future)
```

**Điểm đặc sắc:**

*Section "Managerial Insights" riêng (Section 7):*
> 5 actionable insights cho nhà quản lý, mỗi insight map trực tiếp vào 1 sensitivity analysis
→ **Học được**: đây là cách "close the loop" từ kết quả kỹ thuật → hàm ý vận hành rõ ràng nhất

*Tách "Discovery" và "Limitations" trong Conclusion:*
> Section 8.1 Discovery vs 8.2 Limitations and Future Research Directions
→ **Học được**: structure conclusion 2 phần → rõ ràng hơn 1 đoạn gộp chung

*3 sensitivity analyses tiếp nối nhau trong Case Study:*
> 6.3.1 Departure time → 6.3.2 Vehicle speed → 6.3.3 Return strategy
→ Mỗi SA trả lời một câu hỏi "what if?" → thuyết phục về tính thực tiễn của mô hình

### 16.5 Thuật ngữ mới — Cold-chain & Time-dependent VRP

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Cold-chain logistics | Logistics dây chuyền lạnh |
| Semi-open VRP | VRP nửa mở (xe về kho gần nhất) |
| Time-dependent VRP (TDVRP) | VRP phụ thuộc thời gian |
| Triangular speed function v(t) | Hàm tốc độ hình sin (mô phỏng ùn tắc) |
| Refrigeration cost | Chi phí lạnh / Chi phí duy trì nhiệt độ |
| Cargo damage/deterioration cost | Chi phí hư hỏng hàng / Chi phí suy giảm chất lượng |
| Product decay function D(t) = D₀e^(-δt) | Hàm suy giảm chất lượng sản phẩm |
| CMEM (Comprehensive Emission Model) | Mô hình phát thải toàn diện (tính nhiên liệu) |
| Firefly Algorithm (FA) | Thuật toán đom đóm |
| Luminous intensity | Cường độ sáng (đánh giá chất lượng cá thể) |
| Light absorption coefficient (γ) | Hệ số hấp thụ ánh sáng |
| Relevance removal | Phép phá hủy dựa trên liên quan |
| Regret insertion | Phép sửa chữa dựa trên giá trị hối tiếc |
| Departure time optimization | Tối ưu hóa thời điểm xuất phát |
| Semi-open return strategy | Chiến lược quay về nửa mở |
| Broken chain risk | Rủi ro đứt gãy dây chuyền lạnh |

### 16.6 Mẫu câu tiếng Việt — Cold-chain & Managerial Insights

**Giới thiệu bài toán cold-chain:**
> "Khác với logistics truyền thống, logistics dây chuyền lạnh đòi hỏi kiểm soát nhiệt độ liên tục và chặt chẽ trong suốt quá trình vận chuyển. Bất kỳ sự gián đoạn nào trong chuỗi lạnh đều có thể dẫn đến suy giảm chất lượng sản phẩm, gây thiệt hại kinh tế và ảnh hưởng đến sức khỏe người tiêu dùng."

**Giới thiệu mô hình time-dependent:**
> "Để phản ánh thực tế giao thông đô thị, nghiên cứu này áp dụng hàm tốc độ dạng sin v(t) = α·sin(βt) + γ để mô phỏng sự biến động tốc độ xe theo thời gian trong ngày, trong đó các tham số α, β, γ đặc trưng cho biên độ, chu kỳ và tốc độ trung bình của dòng giao thông tương ứng."

**Trình bày managerial insight:**
> "Từ kết quả phân tích độ nhạy, có thể rút ra khuyến nghị thực tiễn sau cho các nhà quản lý logistics dây chuyền lạnh: [insight]. Cụ thể, [số liệu chứng minh], cho thấy rằng [kết luận hành động]."

---

## 17. MDHFVRPB & VNS-GRAMPS (từ file #25)

> Học từ: KocaturkEtAl2021_MDHFVRPB-VNS-GRAMPS.pdf (Annals of Operations Research, Springer 2021)
> 🔗 **Liên kết trực tiếp với file #20**: Paper này chính thức áp dụng GRAMPS (của Ahmadi & Osman 2005) vào một bài toán VRP phức hợp mới.

### 17.1 Bài toán MDHFVRPB — Tổ hợp 3 bài toán

**Multi-Depot + Heterogeneous Fleet + Backhauls:**
- **Multi-depot**: nhiều kho, xe xuất phát và quay về cùng kho
- **Heterogeneous fleet**: nhiều loại xe với chi phí cố định và biến đổi khác nhau
- **Backhauls (DFPS — Deliver First Pickup Second)**: xe phải phục vụ hết tất cả linehaul customers trước khi ghé bất kỳ backhaul customer nào

**Phân loại VRPDP:**
| Loại | Giải thích |
|---|---|
| SPD (Simultaneous P&D) | Mỗi khách vừa nhận vừa giao trong một lần ghé |
| MPD (Mixed P&D) | Mỗi khách chỉ giao hoặc chỉ lấy |
| DFPS (Deliver First Pickup Second) | Giao hết rồi mới lấy — gọi là VRP with Backhauls |

**Tại sao MDHFVRPB là mới?**
> "To the best of our knowledge, this is the first study that integrates the MDVRPB and heterogeneous vehicle fleet."
→ Contribution rõ ràng: kết hợp 3 bài toán đã có thành 1 bài toán tích hợp chưa ai nghiên cứu

### 17.2 Model Tightening — Kỹ thuật quan trọng

**4 nhóm tightening của mô hình restricted:**
1. Chia constraint (2) thành (2a) linehaul + (2b) backhaul → loại bỏ biến zero
2. Chia constraint (3) thành (3a) + (3b) tương tự
3. Chia constraint (4) thành (4a) linehaul + (4b) backhaul + (4c) depot
4. Chia constraint (9) thành (9a)-(9d) → tight capacity theo từng loại cung

**Kết quả**: Restricted model giảm O(Km² + n² - mn²) constraints và O(m² + n² + mn) biến → **LB tighter, CPU time ngắn hơn hoặc bằng**

### 17.3 VNS-GRAMPS — Học cách hybrid 2 metaheuristics

**Cấu trúc 2 giai đoạn:**
```
Stage 1: Reactive GRASP (RGRASP)
  ├─ ISSCA → Initial seed solution (vehicle fleet composition per depot)
  ├─ REDSA → Full initial solution (insert unrouted customers)
  ├─ VNS (local search)
  └─ Lưu: best solution + best RCL size + best neighborhood size

Stage 2: GRASP với parameters từ Stage 1
  ├─ SIA → tạo initial seed từ best solution của Stage 1
  ├─ REDSA → rebuild routes
  └─ VNS (local search với params tối ưu từ Stage 1)
```

**5 neighborhood structures (theo thứ tự hiệu quả giảm dần):**
1. Two-shift Type 2 (EIR: 1.52%) — best
2. Two-shift Type 1 (0.63%)
3. Two-one node interchange (0.23%)
4. One-node interchange (0.12%)
5. Two-node interchange (0.10%)

**Thứ tự này được xác định bằng Effective Improvement Ratio (EIR):**
> EIR = Average_Improvement / Success_Ratio
→ **Học được**: đây là cách data-driven ordering of neighborhood structures — không hardcode, không guess

**ISSCA — thuật toán tạo initial seed thông minh:**
- Dùng 2 rules để xác định borderline customers (có thể thuộc 2 depot)
- Thử 3 thứ tự depot (tăng dần, giảm dần, random demand) → chọn tốt nhất
- Cluster first, route second với vehicle type assignment

### 17.4 Kết quả — Hiệu quả của hybridization

| So sánh | Scenario 1 gap vs LB | Nhận xét |
|---|---|---|
| CPLEX (UB) | 39.05% | Baseline tệ nhất |
| VNS (basic) | 18.44% | Tốt hơn CPLEX nhưng kém |
| **VNS-GRAMPS** | **13.01%** | Tốt nhất |

→ Hybridization GRAMPS + VNS giảm gap từ 18.44% → 13.01% (**5.4 percentage points**)

**Trade-off**: VNS-GRAMPS mất 4.34 phút vs VNS 1.54 phút → **gần 3× chậm hơn** nhưng đổi lại solution tốt hơn đáng kể

### 17.5 Kỹ thuật viết — Paper thuật toán hybrid AOR

**Đặc điểm nổi bật:**

*4-fold contributions được liệt kê với (i)(ii)(iii)(iv):*
> "(i) The MDHFVRPB is studied, (ii) A new formulation is proposed, (iii) A novel hybridisation of VNS and GRAMPS is developed, (iv) New data sets are generated..."
→ **Học được**: contributions đủ 4 chiều — bài toán mới, model mới, algorithm mới, data mới

*Tạo benchmark instances khi chưa có sẵn:*
> 3 scenarios được tạo bằng cách kết hợp data từ các bài toán liên quan (MDHFVRP + FSMVRPB + MDVRP)
→ **Học được**: đây là cách "bootstrapping" benchmark cho bài toán mới — tận dụng datasets có sẵn

*Đặt câu hỏi "tại sao thứ tự neighbourhood quan trọng" rồi trả lời bằng thực nghiệm (Table 1):*
> Chạy trên 12 instances, tính EIR cho 5 operators, rồi dùng kết quả để sắp xếp
→ Không dùng intuition, dùng data

*Supplement material strategy:*
> Paper chính (~26 trang) chứa ideas + results tóm tắt; chi tiết bảng số liệu đặt trong file supplement online
→ **Học được**: journal papers dài có thể dùng supplement để giữ paper chính gọn gàng, readable

### 17.6 Thuật ngữ mới — MDHFVRPB

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| Backhaul customer | Khách hàng lấy hàng (backhaul) |
| Linehaul customer | Khách hàng giao hàng (linehaul) |
| DFPS (Deliver First Pickup Second) | Giao trước lấy sau |
| Heterogeneous fleet | Đội xe dị loại |
| Fixed fleet (HFFVRP) | Đội xe cố định (số lượng mỗi loại xe cố định) |
| Fleet mix (HVFVRP) | Kết hợp đội xe (tối ưu số lượng từng loại xe) |
| Variable cost | Chi phí biến đổi (theo km) |
| Fixed cost | Chi phí cố định (theo xe sử dụng) |
| Tightening | Siết chặt mô hình (giảm biến/ràng buộc dư thừa) |
| Lower bound (LB) | Cận dưới |
| Upper bound (UB) | Cận trên |
| Gap vs LB (%) | Khoảng cách so với cận dưới (%) |
| Reactive GRASP (RGRASP) | GRASP phản ứng (tự điều chỉnh tham số) |
| Effective Improvement Ratio (EIR) | Tỷ lệ cải thiện hiệu quả |
| Borderline customer | Khách hàng biên giới (có thể thuộc 2 depot) |
| Cluster first route second | Phân cụm trước, xây tuyến sau |

### 17.7 Mẫu câu tiếng Việt — Bài toán tổ hợp (hybrid problem)

**Giới thiệu bài toán kết hợp:**
> "Bài toán [tên] được đề xuất trong nghiên cứu này là sự tổ hợp của ba bài toán định tuyến xe có liên quan: [A], [B] và [C]. Mặc dù mỗi bài toán thành phần đã được nghiên cứu rộng rãi trong tài liệu, sự kết hợp đồng thời của cả ba đặc điểm này chưa được nghiên cứu một cách hệ thống."

**Biện minh tightening:**
> "Mô hình ban đầu có O(...) ràng buộc và O(...) biến. Bằng cách tái định nghĩa các nhóm ràng buộc [X] thành các ràng buộc con riêng biệt cho từng loại khách hàng, chúng tôi giảm được đáng kể số lượng biến và ràng buộc, qua đó tạo ra một mô hình chặt hơn với cận dưới LP tốt hơn."

**Kết luận hybridization:**
> "Kết quả thực nghiệm cho thấy thuật toán VNS-GRAMPS đạt mức gap trung bình X% so với cận dưới, vượt trội so với X% của VNS thuần và X% của CPLEX. Điều này chứng tỏ rằng việc tích hợp cơ chế học thích nghi của GRAMPS vào khung tìm kiếm lân cận biến đổi VNS tạo ra sự bổ sung cộng hưởng đáng kể."

---

## 18. STOCHASTIC SPDP & FAILURE-SPECIFIC COOPERATIVE RECOURSE (file #19 — đúng)

> Học từ: ZhuSheu2018_FSC-SPDPSD-ALNS.pdf (EJOR, Elsevier 2018)
> ✅ Đây là file đúng của slot #19 trong danh sách (thay thế file bị nhầm tên trước đó)

### 18.1 Bài toán SPDPSD — Điểm mới

**VRPSPD với Stochastic Demands (SPDPSD):**
- Xe giao **và** lấy hàng đồng thời, nhưng nhu cầu chỉ biết khi xe **đến nơi**
- Hai loại failure:
  - **Complete Failure (C-failure)**: xe đầy hàng lấy về **và** hết hàng giao → phải quay depot
  - **Semi-failure (S-failure)**: chỉ hỏng một chiều (còn hàng giao hoặc còn chỗ để lấy) → tiếp tục tuyến

**FSC Strategy (Failure-Specific Cooperative):**
- Mỗi cặp xe: **lead vehicle (type A)** + **partner vehicle (type B)**
- Type A: C-failure → quay depot; S-failure → bỏ qua, tiếp tục
- Type B (extend-and-skip): phục vụ các khách hàng bị bỏ qua bởi type A

### 18.2 Framework Toán Học — A Priori Routing với Stochastic Demands

**Expected cost của type A route:**
> G(VA) = Len(τA) + Σᵢ P_CF(i) · Drecs(i)
> Trong đó Drecs(i) = 3d(i,0) + d(0,i+1) - d(i,i+1) → chi phí 2 chuyến vòng khi C-failure

**Tính P_CF(i) — xác suất C-failure tại điểm i:**
- State (zᵢ, rᵢ): tồn kho hàng giao + chỗ trống để lấy sau khi ghé khách i
- Markov chain: transition probabilities qua Eq. (11) — 4 cases dựa trên (z>0/≤0, r>0/≤0)
- Recursion: PCF(k)(i) từ PCF(k-1)(l) và PCF(1)(i-l) → PCF(i) = Σₖ PCF(k)(i)

**Expected cost của type B route:**
- **Extend-and-skip**: chèn tất cả khách của route A vào route B → skip nếu demand đã được đáp ứng
- Markov Decision Process (MDP) cho recourse action: 1 trip hay 2 trips tới depot

### 18.3 Kỹ thuật viết — Paper phương pháp phân tích xác suất (EJOR)

**Cấu trúc đặc trưng:**
```
1. Introduction: VRPSPD + stochastic demands → gap (chưa ai làm a priori routes cho cả 2 loại nhu cầu stochastic)
2. Problem description and notations
3. FSC strategy (mô tả bằng lời + hình minh họa Fig.1)
4. Expected cost (4.1 type A + 4.2 type B — chi tiết toán học)
5. ALNS algorithm
6. Computational study (800 instances × 5 demand patterns)
7. Conclusions
```

**Điểm đặc sắc:**

*Định nghĩa 2 loại failure trước khi vào toán học:*
> C-failure (zi ≤ 0 AND ri ≤ 0) vs S-failure (zi > 0, ri ≤ 0) OR (zi ≤ 0, ri > 0)
→ **Học được**: phân loại failure rõ ràng bằng điều kiện toán học → làm nền cho toàn bộ phân tích sau

*Hình minh họa đơn giản hóa phức tạp:*
> Fig. 1(a)(b)(c): a priori routes → type A travels → type B travels → giải thích FSC bằng 3 hình liên tiếp
> Fig. 4: possible skips khi VB phục vụ khách hàng — minh họa extend-and-skip

*Phân tích 5 demand patterns:*
> eD-eP / hD-lP / lD-hP / lD-lP / hD-hP → 800 instances = 8 kích cỡ × 2 vị trí depot × 5 patterns × 10 instances
→ **Học được**: thiết kế thực nghiệm **factorial** — kiểm tra tất cả combinations quan trọng

*Table 2 — kết quả giản dị nhưng mạnh:*
> FSC giảm chi phí 3.8% – 33.2% (midpoint depot) và 8% – 39.2% (corner depot)
> Corner depot → lợi ích lớn hơn → **insight**: FSC đặc biệt hiệu quả khi depot xa

*Table 3 — đo nhiều chiều kết quả:*
> Không chỉ cost mà còn: số routes, số detours, Imp.(%) → đánh giá toàn diện hơn

### 18.4 Thuật ngữ mới — Stochastic VRP

| Tiếng Anh | Tiếng Việt chuẩn |
|---|---|
| A priori route | Tuyến đường lập trước (trước khi biết demand thực) |
| Stochastic demands | Nhu cầu ngẫu nhiên |
| Complete Failure (C-failure) | Hỏng hoàn toàn (không thể phục vụ bất kỳ chiều nào) |
| Semi-failure (S-failure) | Hỏng một phần (còn khả năng phục vụ một chiều) |
| Recourse action | Hành động xử lý sự cố |
| A priori route optimization | Tối ưu hóa tuyến đường lập trước |
| Failure-specific cooperative (FSC) | Hợp tác theo loại sự cố |
| Lead vehicle (type A) | Xe dẫn đầu |
| Partner vehicle (type B) | Xe đối tác |
| Extend-and-skip | Mở rộng và bỏ qua (strategy phục vụ của xe B) |
| Stochastic programming with recourse (SPR) | Lập trình ngẫu nhiên có xử lý sự cố |
| Risk pooling | Phân tán rủi ro |
| Markov Decision Process (MDP) | Quá trình quyết định Markov |
| Detour trip | Chuyến vòng (về depot và quay lại) |
| ISM (Independent Service Method) | Phương pháp phục vụ độc lập (không hợp tác) |
| Degree of dynamism | Mức độ động của bài toán |

### 18.5 Mẫu câu tiếng Việt — Stochastic Routing

**Giới thiệu bài toán stochastic:**
> "Trong thực tế, nhu cầu của khách hàng không phải lúc nào cũng được biết trước tại thời điểm lập kế hoạch. Khi nhu cầu chỉ được tiết lộ khi xe đến nơi, các tuyến đường tối ưu trong điều kiện tất định có thể không còn khả thi hoặc hiệu quả, đặt ra yêu cầu phát triển các chiến lược định tuyến và xử lý sự cố phù hợp với môi trường ngẫu nhiên."

**Mô tả recourse strategy:**
> "Khi xảy ra hỏng hoàn toàn (C-failure) tại một điểm khách, xe không còn khả năng phục vụ bất kỳ yêu cầu nào và buộc phải quay về kho để giải phóng hàng lấy và nạp thêm hàng giao. Trong khi đó, khi xảy ra hỏng một phần (S-failure), xe vẫn có thể tiếp tục phục vụ khách hàng tiếp theo theo một chiều, và phần nhu cầu chưa được đáp ứng sẽ được chuyển cho xe đối tác."

---

## 19. BIỂU ĐỒ, HÌNH MINH HỌA & XỬ LÝ DỮ LIỆU TRONG VRP PAPER

> Tổng hợp từ: mainPaper (WangEtAl2025_MDPDTWDD-EAAI) + tất cả 17 sections reference papers đã học
> **Mục tiêu**: biết dùng loại hình/biểu đồ nào, khi nào, để làm gì — và cách xử lý data chuẩn học thuật.

---

### 19.1 BẢNG TỔNG HỢP: LOẠI HÌNH & MỤC ĐÍCH

| Loại hình | Tên tiếng Anh | Dùng ở đâu trong bài | Mục đích cụ thể |
|---|---|---|---|
| **Sơ đồ mạng lưới** | Network map / Route visualization | Problem statement, Case study | Hiển thị tuyến đường trước/sau tối ưu, vị trí kho + khách hàng, open-closed routes |
| **Sơ đồ khối thuật toán** | Algorithm flowchart | Solution methodology | Mô tả luồng thuật toán tổng quan — input → process → output |
| **Hình minh họa từng bước** | Step-by-step illustration | Solution methodology | PMX crossover, destroy-repair, insertion strategy — giải thích bằng ví dụ trực quan |
| **Hình trước/sau** | Before-after figure | Problem statement | Chứng minh tính cần thiết của phương pháp đề xuất (motivating example) |
| **Biểu đồ hội tụ** | Convergence curve | Algorithm performance | Theo dõi cost/fitness theo iteration — chứng minh thuật toán hội tụ tốt |
| **Mặt trận Pareto** | Pareto front | Multi-objective results | Biểu diễn tập nghiệm Pareto trong không gian 2 mục tiêu (cost vs NV) |
| **Bản đồ phân cụm** | Clustering result map | Case study | Kết quả phân cụm khách hàng theo kho — vị trí địa lý thực |
| **Biểu đồ thanh so sánh** | Grouped bar chart | Analysis & Discussion | So sánh thuật toán/kịch bản theo nhiều chỉ số — grouped by instance size |
| **Biểu đồ phân tích độ nhạy** | Sensitivity analysis chart | Analysis & Discussion | Thay đổi 1 tham số → quan sát ảnh hưởng lên TOC, NV, CT |
| **Sơ đồ R/A matrix** | Message-passing diagram | Algorithm detail | AP clustering — minh họa R(i,j) và A(i,j) |
| **Hình crowding distance** | Crowding distance illustration | NSGA-II detail | Giải thích cách tính crowding distance trong Pareto selection |
| **Sơ đồ insertion strategy** | Insertion scenario diagram | Dynamic demand section | 3 kịch bản chèn nhu cầu động — scenario a/b/c/d |

---

### 19.2 HƯỚNG DẪN CHI TIẾT — TỪNG LOẠI HÌNH

#### 19.2.1 Sơ đồ mạng lưới trước/sau (Network before-after)

**Dùng khi:** Problem statement (Section 3) hoặc Case study (Section 5)

**Cấu trúc chuẩn (học từ mainPaper Fig. 1 và file #14 Fig. 2-3):**
```
Fig. X(a): Trạng thái ban đầu (non-collaborative / không tối ưu)
  - Kho hàng: ký hiệu ■ hoặc ★ (phân biệt DD và PD)
  - Khách hàng: ký hiệu ● với màu khác nhau theo loại (delivery/pickup/dynamic)
  - Tuyến đường: mũi tên/đường kẻ — màu khác nhau mỗi xe
  - Chú thích vi phạm: ghi rõ "C12: TW violation", "V7: long-distance service"

Fig. X(b): Sau tối ưu (collaborative, không có dynamic insertion)
Fig. X(c): Sau tối ưu (collaborative + insertion strategy)
```

**Bảng so sánh đi kèm (Table 3 trong mainPaper):**
> Luôn có table ngay sau hình → so sánh các chỉ số (TTT, TC, PC, MC, NV, TOC, Gap)
→ **Quy tắc**: Figure = thấy được trực quan; Table = số liệu chứng minh

**Nội dung cần thể hiện trên hình:**
- Vị trí địa lý: dùng tọa độ thực (Chongqing) hoặc chuẩn hóa (Solomon benchmark)
- Depot: hình vuông ■ hoặc tam giác ▲ — phân biệt loại depot
- Khách hàng delivery: ● màu xanh
- Khách hàng pickup: ● màu đỏ
- Khách hàng dynamic: ● màu vàng/cam
- Mỗi tuyến: màu riêng + số thứ tự xe (V1, V2...)
- Arrows: hướng di chuyển (từ depot → khách → ... → depot)

#### 19.2.2 Sơ đồ khối thuật toán (Flowchart)

**Dùng khi:** Section 4 (Solution Methodology)

**Cấu trúc (học từ mainPaper Fig. 2 — 3DAPANSGA-II):**
```
Start
│
├─ Stage 1: 3D AP Clustering
│   ├─ Input: DD, PD, customers
│   ├─ Calculate space-time distance matrix
│   ├─ While m ≤ M: Update R, A matrices
│   └─ Output: Customer clusters
│
├─ Stage 2: ANSGA-II
│   ├─ Initialize population
│   ├─ While gen ≤ M_gen:
│   │   ├─ Genetic operations (selection, crossover, mutation)
│   │   ├─ Evaluate fitness (TOC, NV)
│   │   ├─ Nondominated + crowding distance sorting
│   │   ├─ If stagnation: execute local search
│   │   └─ Update gbest
│   └─ Output: Pareto optimal solutions
│
├─ Insertion Strategy (for dynamic demands)
│   ├─ For each dynamic demand:
│   │   ├─ Check working vehicles' capacity
│   │   ├─ Scenario 1: direct insertion
│   │   ├─ Scenario 2: goods transfer + insertion
│   │   └─ Scenario 3: new vehicle
│   └─ Update gbest
│
End
```

**Quy tắc vẽ flowchart chuẩn học thuật:**
- Hình chữ nhật: process (tính toán, cập nhật)
- Hình thoi: decision (if/while)
- Hình oval: start/end
- Màu sắc: dùng shading nhẹ để phân biệt giai đoạn
- Không quá phức tạp: nếu có pseudocode riêng thì flowchart chỉ cần level cao

#### 19.2.3 Biểu đồ hội tụ (Convergence curve)

**Dùng khi:** Algorithm performance test (Section 5.1)

**Trục:**
- Trục X: số iteration (gen) hoặc computation time (s)
- Trục Y: TOC ($) hoặc fitness value
- Mỗi thuật toán: một đường — dùng style khác nhau (solid, dashed, dotted) + màu khác nhau

**Pattern chuẩn:**
```
Iteration 1→50: giảm nhanh (exploration phase)
Iteration 50→100: giảm chậm hơn (exploitation phase)
Iteration 100→150: plateau (converge)
```

**Nhận xét chuẩn đi kèm:**
> "As shown in Fig. X, the proposed algorithm converges to a stable solution within approximately [n] iterations, which is faster than [competing algorithms]. This demonstrates the effectiveness of the elite iteration mechanism in improving convergence performance."

**Khi có nhiều instances:** vẽ average convergence curve across instances, hoặc chọn 3-4 representative instances

#### 19.2.4 Mặt trận Pareto (Pareto front)

**Dùng khi:** Multi-objective optimization results (Section 5.3)

**Trục:**
- Trục X: Objective 1 (TOC hoặc cost)
- Trục Y: Objective 2 (NV hoặc emissions hoặc time)
- Mỗi thuật toán: scatter plot với marker style khác nhau

**Cách so sánh Pareto fronts:**
- Thuật toán tốt hơn: Pareto front nằm **gần gốc tọa độ hơn** (dominated the other)
- Metrics đánh giá Pareto front (học từ mainPaper Table 17):
  - **HV (Hyper-volume)**: lớn hơn = tốt hơn (bao phủ không gian nhiều hơn)
  - **MID (Mean Ideal Distance)**: nhỏ hơn = tốt hơn (gần ideal point hơn)
  - **NOP (Number of Pareto solutions)**: nhiều hơn = đa dạng hơn
  - **DI (Diversity)**: lớn hơn = phân tán đều hơn trên mặt trận

**Quy tắc nhận xét HV:**
> "The proposed algorithm achieves the highest average HV of [X], indicating that its Pareto front covers a larger portion of the objective space compared to competing algorithms."

#### 19.2.5 Bảng kết quả thuật toán chuẩn (Algorithm comparison table)

**Cột tiêu chuẩn (học từ mainPaper Table 12, 13, 16):**

| Instances | Thuật toán đề xuất | | | Thuật toán A | | | | Thuật toán B | | | |
|---|---|---|---|---|---|---|---|---|---|---|---|
| | TOC | NV | CT(s) | TOC | NV | CT(s) | TOC gap | TOC | NV | CT(s) | TOC gap |

**Hàng bắt buộc ở cuối:**
- **Average**: trung bình tất cả instances
- **t-test**: kiểm định thống kê (âm = thuật toán đề xuất tốt hơn)
- **p-value**: <0.05 = có ý nghĩa thống kê

**TOC gap = (TOC_alg - TOC_best) / TOC_best × 100%**

**Cách viết nhận xét chuẩn:**
> "The t-test results (t = [value], p = [value] < 0.05) confirm that the difference between the proposed algorithm and [competitor] is statistically significant, further validating the superiority of [proposed]."

#### 19.2.6 Biểu đồ sensitivity analysis

**Dùng khi:** Analysis & Discussion (Section 5.4)

**3 loại sensitivity analysis chuẩn (học từ mainPaper 5.4 + HouEtAl2025 Section 6.3):**

**Loại 1 — So sánh kịch bản (Scenario comparison):**
> mainPaper 5.4.3: "non-collaborative vs collaboration only vs collaboration+insertion"
- Dùng: **grouped bar chart** với 3 bars cho mỗi chỉ số (TOC, NV, CT)
- Trục X: các chỉ số (hoặc instances)
- Trục Y: giá trị (cost hoặc tỷ lệ cải thiện %)

**Loại 2 — Thay đổi tham số (Parameter sensitivity):**
> HouEtAl2025: vehicle speed V1/V2/V3; mainPaper 5.4.2: vehicle capacity
- Dùng: **line chart** (x-axis = tham số, y-axis = TOC hoặc gap %)
- Mỗi chỉ số đánh giá: một đường

**Loại 3 — So sánh chiến lược/loại (Type comparison):**
> mainPaper 5.4.1: hard/soft/mixed time windows; mainPaper 5.4.4: insertion strategies
- Dùng: **bar chart** hoặc **table** với improvement %

---

### 19.3 XỬ LÝ DỮ LIỆU CHUẨN TRONG VRP PAPER

#### 19.3.1 Cấu trúc Data section (Section 5.2)

**Mô tả data chuẩn (học từ mainPaper Section 5.2):**
```
5.2. Data description
  ├─ Nguồn data: "A real-world case study in [location]"
  ├─ Quy mô: số depot (DDs, PDs), số khách hàng (R, S, D)
  ├─ Thời gian làm việc: [time window của depot]
  ├─ Tham số vận tải: tốc độ xe, tải trọng, chi phí nhiên liệu
  └─ Cách thu thập: GIS data / survey / công ty logistics thực tế
```

**Table mô tả data chuẩn (học từ mainPaper Table 14):**
| Instance | DDs | PDs | Customers | Static delivery | Static pickup | Dynamic pickup |
|---|---|---|---|---|---|---|

→ **Học được**: phân rõ thành phần customers theo loại → reviewer hiểu ngay

#### 19.3.2 Hai loại dataset trong VRP paper

**Loại 1 — Benchmark instances:**
> Dùng để kiểm chứng thuật toán với cộng đồng nghiên cứu

| Benchmark | Bài toán | Nguồn |
|---|---|---|
| Solomon C1/C2/R1/R2/RC1/RC2 | VRPTW | Solomon (1987) |
| Cordeau Pr/p instances | MDVRPTW | Cordeau et al. (2001) |
| NEO instances (PDVRPTW) | PDVRPTW | neo.lcc.uma.es |
| Li & Lim instances | PDPTW | Li & Lim (2003) |

**Cách tạo custom benchmark từ available data (học từ mainPaper Section 5.1.2 + KocaturkEtAl2021):**
> "30 instances are constructed based on MDVRPTWs and PDVRPTWs benchmark instances provided on NEO. Given the differences between the MDPDTWDD and the instances provided on NEO, some adjustments such as merging and swapping on benchmark instances are necessary."
- **Merging**: kết hợp 2 benchmark có cùng format
- **Swapping**: đổi loại demand (delivery ↔ pickup)
- **Random assignment**: gán loại customer ngẫu nhiên (static delivery / static pickup / dynamic pickup)

**Loại 2 — Real-world case study:**
> Dùng để chứng minh tính ứng dụng thực tiễn

**Cách mô tả (học từ mainPaper + WangEtAl2018 + HouEtAl2025):**
1. Tên địa điểm + quy mô: "Chongqing city, China — 3 DDs, 4 PDs, 200 customers"
2. Cách thu thập: "GPS coordinates from GIS database"
3. Thời gian: "one working day (8:00–20:00)"
4. Tham số thực tế: fuel price, maintenance cost, speed

#### 19.3.3 Cách chia nhóm instances để thực nghiệm

**Pattern chuẩn (học từ mainPaper + các reference papers):**

**Chiến lược 1 — Chia theo quy mô (Scale):**
> mainPaper: Group 1 (20 KH), Group 2 (30 KH), Group 3 (40 KH)
> → small / medium-large instances

**Chiến lược 2 — Chia theo cấu hình depot:**
> mainPaper Table 14: (1DD,1PD) / (1DD,2PD) / (2DD,1PD) / (2DD,2PD) / (1DD,3PD) / (3DD,1PD)
> → 6 loại cấu hình × 5 quy mô khách hàng = 30 instances

**Chiến lược 3 — Chia theo đặc trưng demand:**
> ZhuSheu2018: eD-eP / hD-lP / lD-hP / lD-lP / hD-hP (5 demand patterns)
> → Factorial design: kiểm tra tất cả combinations quan trọng

**Nguyên tắc thiết kế:**
- Ít nhất 2 cấp độ quy mô (small + medium-large)
- Cover các biến thể cấu hình chính của bài toán đề xuất
- Mỗi instance chạy tối thiểu 10–20 runs → lấy best/average/std

#### 19.3.4 Chỉ số đánh giá (Evaluation metrics)

**Nhóm 1 — Cost metrics:**
| Chỉ số | Ký hiệu | Công thức/Ý nghĩa |
|---|---|---|
| Total Operating Cost | TOC | TC + PC + MC + IC + FC |
| TOC gap vs CPLEX | TOC gap (%) | (TOC_alg - TOC_CPLEX)/TOC_CPLEX × 100 |
| Travel Cost | TC | f·p·Σd_ij |
| Penalty Cost | PC | ε·TAE + ω·TAL |
| Maintenance Cost | MC | M_v/T × NV |
| Insertion Cost | IC | γ·Σ demand_dynamic |
| Fixed Cost | FC | β_depot + δ·delivery + χ·pickup |

**Nhóm 2 — Vehicle metrics:**
| Chỉ số | Ý nghĩa |
|---|---|
| NV (Number of Vehicles) | Số xe sử dụng |
| TTT (Total Travel Time) | Tổng thời gian di chuyển |
| TAE (Total Arriving Early) | Tổng thời gian đến sớm |
| TAL (Total Arriving Late) | Tổng thời gian đến muộn |

**Nhóm 3 — Algorithm performance metrics:**
| Chỉ số | Ý nghĩa | Tốt khi |
|---|---|---|
| CT (Computation Time) | Thời gian tính toán (s) | Nhỏ hơn |
| ARPD / Gap (%) | Average Relative % Deviation | Nhỏ hơn |
| t-test + p-value | Kiểm định thống kê | p < 0.05 |

**Nhóm 4 — Multi-objective metrics (khi dùng NSGA-II/Pareto):**
| Chỉ số | Ý nghĩa | Tốt khi |
|---|---|---|
| HV (Hyper-volume) | Thể tích vùng bị dominate bởi Pareto front | Lớn hơn |
| MID (Mean Ideal Distance) | Khoảng cách trung bình đến điểm lý tưởng | Nhỏ hơn |
| NOP (Number of Pareto solutions) | Số nghiệm Pareto tìm được | Nhiều hơn |
| DI (Diversity) | Mức độ phân tán của Pareto front | Lớn hơn |

**Nhóm 5 — Clustering quality (khi dùng AP/k-means clustering):**
| Chỉ số | Ý nghĩa |
|---|---|
| Silhouette coefficient | Đánh giá chất lượng phân cụm (−1 đến 1) |
| Davies-Bouldin index | Nhỏ hơn = tốt hơn |
| Number of clusters | Số cụm được tạo ra |

#### 19.3.5 Validation flow — Quy trình kiểm chứng đầy đủ

**3 tầng validation (học từ mainPaper Section 5 + WangEtAl2021):**

```
Tầng 1 — Correctness (small-scale vs CPLEX):
  ├─ 15 instances nhỏ (n ≤ 40 KH)
  ├─ So sánh với CPLEX solver (exact)
  ├─ Tính TOC gap (%) → chứng minh gần tối ưu
  └─ Mục tiêu: gap < 3% là chấp nhận được

Tầng 2 — Performance (medium-large vs other heuristics):
  ├─ 30 instances (n = 48–150 KH)
  ├─ So sánh với 5–6 thuật toán cùng loại
  ├─ Chỉ số: TOC, NV, CT + t-test + p-value
  └─ Mục tiêu: tốt nhất hoặc competitive

Tầng 3 — Applicability (real-world case study):
  ├─ 1 case study thực tế (Chongqing / TP.HCM / ...)
  ├─ So sánh trước/sau optimization + kịch bản
  ├─ Management insights (5–7 insights cho nhà quản lý)
  └─ Mục tiêu: chứng minh tính ứng dụng
```

#### 19.3.6 Cách xử lý dynamic demands trong data

**Dynamic demand data (học từ mainPaper Assumptions 4-5):**
- **Tỷ lệ**: thường 5–15% tổng số khách hàng là dynamic
  > mainPaper: dynamic = 5 hoặc 10 KH / tổng 48–150 KH ≈ 3–10%
- **Thời điểm xuất hiện**: ngẫu nhiên trong working hours, sau khi xe đã xuất phát
- **Phân phối**: Poisson distribution (arrival rate λ) — như trong Theorem proof
- **Xử lý**: insertion strategy (3 scenarios) hoặc new vehicle

**Cách mô tả phân phối demand:**
> "Dynamic pickup demands follow a Poisson distribution with arrival rate λ, where the arrival time is uniformly distributed within [t_start, t_end] of the working day."

**Cách tạo dynamic demand data khi không có data thực:**
1. Generate random arrival times ∈ [departure_time + buffer, depot_closing - buffer]
2. Demand quantities ~ Uniform[q_min, q_max] hoặc ~ Normal(μ, σ)
3. Locations: chọn ngẫu nhiên từ tập địa điểm có sẵn hoặc generate trong vùng địa lý

---

### 19.4 CẤU TRÚC SECTION 5 CHUẨN — mainPaper Pattern

**Pattern đầy đủ nhất (học từ mainPaper 2025, EAAI):**

```
5. Implementation and Analysis

5.1. Algorithm performance test
  5.1.1. Small-scale instances
    - Benchmark dataset: Cordeau Pr10 (15 instances, n=20/30/40)
    - Compare: CPLEX vs 3DAPANSGA-II vs 5 algorithms
    - Table 12-13: TOC, NV, CT, TOC gap
    - Nhận xét: "3DAPANSGA-II achieves the lowest average TOC gap of 0.53%"

  5.1.2. Medium-large scale instances
    - Custom instances: 30 instances từ NEO benchmark (n=48-150)
    - Compare: 6 algorithms
    - Table 14: Instance characteristics (DD, PD, customers by type)
    - Table 15: Parameter settings of all algorithms
    - Table 16: TOC, NV, CT + t-test + p-value (30 × 6 algorithms)
    - Table 17: HV, MID, NOP, DI (multi-objective metrics)
    - Fig convergence curve: algorithm convergence comparison

5.2. Data description (real-world case)
  - Location + scale
  - Data source
  - Parameter values

5.3. Optimization results
  5.3.1. Customer clustering result analysis
    - Fig clustering map: kết quả 3D AP clustering
    - So sánh 3D AP vs 2D AP vs k-means
  5.3.2. Stability analysis for parameter selection
    - Fig convergence: stability of algorithm parameters
  5.3.3. MDPDTWDD optimization results
    - Fig route map: before/after
    - Table: comparison of all scenarios

5.4. Analysis and discussion
  5.4.1. Comparison of different time window types
  5.4.2. Comparison of different vehicle capacities
  5.4.3. Comparison of different cases for resource sharing
  5.4.4. Result comparison of insertion strategies

5.5. Management insights (5-7 actionable insights)
```

---

### 19.5 FIGURE LIST — CHECKLIST ĐẦY ĐỦ CÁC HÌNH TRONG VRP PAPER

| STT | Hình | Vị trí | Bắt buộc? |
|---|---|---|---|
| Fig 1 | Motivating example (before/after network) | Section 3.1 | ✅ Bắt buộc |
| Fig 2 | Algorithm flowchart | Section 4.1 | ✅ Bắt buộc |
| Fig 3 | Algorithm detail (clustering / crossover / insertion) | Section 4.x | ✅ Bắt buộc |
| Fig 4 | PMX / crossover step-by-step | Section 4.3.1 | Nếu dùng GA |
| Fig 5 | Destroy-repair illustration | Section 4.3.2 | Nếu dùng LNS |
| Fig 6 | Crowding distance in NSGA-II | Section 4.3.3 | Nếu multi-objective |
| Fig 7 | Insertion strategy scenarios | Section 4.4 | Nếu có dynamic |
| Fig 8 | Convergence curves | Section 5.1 | ✅ Bắt buộc |
| Fig 9 | Pareto front comparison | Section 5.1/5.3 | Nếu bi-objective |
| Fig 10 | Clustering result map (case study) | Section 5.3.1 | Nếu có clustering |
| Fig 11 | Route visualization (case study before) | Section 5.3.3 | ✅ Bắt buộc |
| Fig 12 | Route visualization (case study after) | Section 5.3.3 | ✅ Bắt buộc |
| Fig 13 | Sensitivity analysis chart | Section 5.4 | ✅ Bắt buộc |

**Ghi chú quan trọng:**
- **Minimum**: Fig 1 (motivating), Fig 2 (flowchart), convergence curve, route maps (before/after), sensitivity chart
- **Recommended cho paper Q1**: tất cả hình trên + Pareto front + clustering map
- **Caption chuẩn**: "Fig. X. [Tên hình]. (a) [mô tả a]; (b) [mô tả b]."
- **Font size trong hình**: ≥ 8pt (đọc được khi in A4)
- **Màu sắc**: dùng màu cơ bản rõ ràng; nếu in đen trắng thì dùng line style khác nhau (solid/dashed/dotted)

---

### 19.6 MẪU CÂU TIẾNG VIỆT — MÔ TẢ HÌNH & DỮ LIỆU

**Giới thiệu hình mạng lưới:**
> "Hình X minh họa quá trình tối ưu hóa mạng lưới logistics MDPDTWDD qua ba giai đoạn. Trong Hình X(a), mỗi kho hàng hoạt động độc lập với các tuyến đường khép kín, dẫn đến vi phạm cửa sổ thời gian tại nhiều điểm khách hàng (ví dụ: C12 và C25). Sau khi áp dụng chiến lược hợp tác và chia sẻ tài nguyên, như thể hiện trong Hình X(b), các xe có thể thực hiện tuyến đường mở-đóng hỗn hợp, giảm đáng kể số phương tiện cần thiết và chi phí vận hành."

**Mô tả dataset:**
> "Để kiểm chứng hiệu quả của thuật toán đề xuất, 30 instances kiểm thử được xây dựng dựa trên bộ dữ liệu chuẩn MDVRPTW và PDVRPTW từ cơ sở dữ liệu NEO. Mỗi instance bao gồm [n_DD] kho giao hàng, [n_PD] kho lấy hàng và [n] khách hàng, trong đó khách hàng được phân loại ngẫu nhiên thành ba nhóm: nhu cầu giao hàng tĩnh, nhu cầu lấy hàng tĩnh và nhu cầu lấy hàng động."

**Mô tả case study data:**
> "Nghiên cứu điển hình được thực hiện trên mạng lưới logistics tại thành phố [tên], bao gồm [n_DD] kho giao hàng, [n_PD] kho lấy hàng và [n] điểm khách hàng. Tọa độ địa lý của các điểm được thu thập từ cơ sở dữ liệu GIS, và dữ liệu nhu cầu được tổng hợp từ khảo sát thực tế tại [doanh nghiệp/khu vực]. Các tham số vận hành, bao gồm chi phí nhiên liệu, tốc độ xe và chi phí bảo dưỡng, được xác định dựa trên mức giá thực tế tại thời điểm nghiên cứu."

**Nhận xét kết quả hội tụ:**
> "Như minh họa trong Hình X, thuật toán đề xuất hội tụ ổn định sau khoảng [n] vòng lặp, trong khi các thuật toán so sánh cần nhiều vòng lặp hơn để đạt cùng mức chất lượng nghiệm. Điều này chứng tỏ rằng cơ chế lặp ưu tú với tìm kiếm cục bộ có tác dụng tăng tốc độ hội tụ và tránh được tình trạng kẹt tại nghiệm cục bộ."

**Nhận xét Pareto front:**
> "Hình X so sánh mặt trận Pareto của sáu thuật toán trên instance [n]. Mặt trận Pareto của thuật toán đề xuất nằm gần góc gốc tọa độ nhất, phản ánh khả năng tìm được tập nghiệm không bị trội vượt trội so với các thuật toán còn lại. Điều này được xác nhận bởi giá trị HV trung bình cao nhất ([giá trị]) và giá trị MID trung bình thấp nhất ([giá trị]) trong số tất cả thuật toán được so sánh."

**Mô tả sensitivity analysis:**
> "Phần này phân tích ảnh hưởng của [tham số/kịch bản] đến hiệu quả của mô hình đề xuất. Kết quả trong Hình X cho thấy rằng [nhận xét chính]. Cụ thể, khi [điều kiện thay đổi], TOC [tăng/giảm] trung bình [X]%, trong khi số lượng xe [thay đổi như thế nào]. Điều này gợi ý rằng [khuyến nghị quản lý]."

---

### 19.7 TỔNG HỢP NHANH — "PAPER NÀO DÙNG GÌ"

| Paper | Figures đặc trưng | Data đặc trưng |
|---|---|---|
| **mainPaper (Wang 2025)** | Fig1 before/after 3-state, flowchart, PMX, destroy-repair, crowding dist, insertion scenarios, convergence, Pareto, clustering map | Cordeau Pr10 + 30 custom instances từ NEO + Chongqing case |
| **WangEtAl2018 (#13)** | Table 1 comparison, before/after network, Pareto front | Chongqing case + modified Solomon |
| **WangEtAl2021 (#14)** | Before/after 3D clustering, t-test in table, loading rate comparison | Chongqing case (5 depots, 150 KH) |
| **ZhangEtAl2022 (#21)** | Depot location sensitivity (scatter), ablation enhancement table | Custom instances 2-3 depots, 20-30 KH |
| **HouEtAl2025 (#23)** | Convergence curves, 3 sensitivity charts, route maps | Solomon + custom cold-chain case |
| **KocaturkEtAl2021 (#25)** | EIR neighborhood table, gap comparison table | MDHFVRPB custom benchmark |
| **ZhuSheu2018 (#19)** | Fig1 FSC 3-panel, Fig4 skip illustration, Table 2-3 results | 800 instances × 5 demand patterns (factorial) |
| **AhmadiOsman2005 (#20)** | Ablation V1 vs V2 table, MIC ranking | 40 benchmarks, 4 sets |

---

*Cập nhật lần cuối: Sau khi đọc mainPaper (WangEtAl2025_MDPDTWDD-EAAI) + tổng hợp từ 17 sections reference papers*
*Tổng số file đã học: 21/27 (bao gồm BCLVN 2024)*
