# DESIGN PATTERNS

#### 1. Design Patterns là gì? <a href="#id-1.-design-patterns-la-gi" id="id-1.-design-patterns-la-gi"></a>

Design Pattern là một giải pháp chung để giải quyết các vấn đề phổ biến khi thiết kế phần mềm trong lập trình hướng đối tượng OOP.

#### 2. Design Patterns có tác dụng gì? <a href="#id-2.-design-patterns-co-tac-dung-gi" id="id-2.-design-patterns-co-tac-dung-gi"></a>

* **Tăng tốc độ phát triển phần mềm**: Sử dụng design patterns trong phát triển phần mềm cho phép các lập trình viên có một công cụ để giải quyết các vấn đề thông dụng trong thiết kế phần mềm. Kể cả khi không gặp phải những vấn đề đó, việc nắm vững design patterns cũng rất hữu ích khi nó giúp lập trình viên thấy được cách giải quyết vấn đề thông qua việc ứng dụng các nguyên tắc thiết kế hướng đối tượng.
* **Code tường minh, dễ dàng teamwork**: Design patterns giúp hỗ trợ lập trình viên giao tiếp hiệu quả hơn. Đơn cử như việc chỉ cần nêu tên một pattern, tất cả những thành viên trong nhóm đều sẽ hình dung được cấu trúc, ý tưởng và cách ứng dụng nó. Nhờ đó giúp lập trình viên dễ dàng làm việc nhóm và tối ưu thời gian hơn.
* **Tái sử dụng code**: Design patterns giúp lập trình viên thiết kế phần mềm có thể dễ dàng tái sử dụng và mở rộng code với các giải pháp tối ưu. Do đó, khi gặp vấn đề trong xây dựng phần mềm, lập trình viên có thể sử dụng design patterns như là kim chỉ nam để giúp họ giải quyết những vấn đề thay cho việc tự đi tìm kiếm giải pháp.
* **Hạn chế lỗi tiềm ẩn, dễ dàng nâng cấp**: Ngoài ra, việc sử dụng lại các design patterns còn giúp lập trình viên tránh các vấn đề tiềm ẩn có thể sẽ gây ra những lỗi lớn trong tương lai. Điều này cũng giúp dự án dễ nâng cấp và bảo trì hơn trong tương lai.

#### 3. Lợi ích khi sử dụng Design Patterns <a href="#id-3.-loi-ich-khi-su-dung-design-patterns" id="id-3.-loi-ich-khi-su-dung-design-patterns"></a>

* **Design pattern** cung cấp giải pháp ở dạng tổng quát
* **Design pattern** giúp dễ dàng mở rộng và tăng tốc độ phát triển phần mềm
* Dùng lại các **design pattern** giúp tránh được các vấn đề tiềm ẩn có thể gây ra những lỗi lớn, dễ dàng nâng cấp, bảo trì về sau
* Một lợi thế lớn để sử dụng một mẫu thiết kế là lập trình viên khác sẽ có thể dễ dàng nhận ra nó (đặc biệt là nếu bạn sử dụng quy ước đặt tên tốt).

#### 4. Phân loại Design Patterns <a href="#id-4.-phan-loai-design-patterns" id="id-4.-phan-loai-design-patterns"></a>

Về cơ bản thì **design pattern** sẽ được chia làm 3 nhóm chính:

1. [**Creational Patterns**](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802374) **(nhóm khởi tạo -** **5 mẫu):**
   * [Abstract Factory](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867495)
   * [Builder](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867508)
   * [Factory](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802401)
   * [Prototype](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59769099)
   * [Singleton](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802414)
2. [**Structural Patterns**](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867482) **(nhóm cấu trúc - 7 mẫu):**
   * [Adapter](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59769112)
   * [Bridge](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867535)
   * [Composite](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59900451)
   * [Decorator](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867548)
   * [Facade](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59900464)
   * [Flyweight](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59900477)
   * [Proxy](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867576)
3. [**Behavioral Patterns**](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59900396) **(nhóm tương tác/hành vi - 11 mẫu):**
   * [Chain of responsibility](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802497)
   * [Command](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867603)
   * [Interpreter](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59769153)
   * [Iterator](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802510)
   * [Mediator](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802523)
   * [Memento](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802536)
   * [Observer](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59900504)
   * [State](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802549)
   * [Strategy](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59802562)
   * [Template method](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59769208)
   * [Visitor](https://mikinycorporation.atlassian.net/wiki/spaces/DP/pages/59867644)

#### 5. Khi nào nên sử dụng Design Patterns <a href="#id-5.-khi-nao-nen-su-dung-design-patterns" id="id-5.-khi-nao-nen-su-dung-design-patterns"></a>

* Việc sử dụng các **design pattern** sẽ giúp chúng ta giảm được thời gian và công sức suy nghĩ ra các cách giải quyết cho những vấn đề đã có lời giải. Lợi ích của việc sử dụng các mô hình **Design Pattern** vào phần mềm đó chính là giúp chương trình chạy uyển chuyển hơn, dễ dàng quản lý tiến trình hoạt động, dễ nâng cấp bảo trì, …
* Tuy nhiên điểm bất cập của **design pattern** là nó luôn là một lĩnh vực khá khó nhằn và hơi trừu tượng. Khi bạn viết code mới từ đầu, khá dễ dàng để nhận ra sự cần thiết phải có mẫu thiết kế. Tuy nhiên, việc áp dụng mẫu thiết kế cho code cũ thì khó khăn hơn.
* Khi sử dụng những mẫu **design pattern** có sẵn thì chúng ta sẽ đối mặt với một vấn đề nữa là perfomance của product (code sẽ chạy chậm chẳng hạn). Cần phải chắc chắn là bạn đã hiểu toàn bộ mã nguồn làm việc như thế nào trước khi đụng vào nó. Việc này có thể là dễ dàng hoặc là đau thương, phụ thuộc vào độ phức tạp của code.
* Hiện nay chúng ta đang áp dụng rất nhiều **design pattern** vào công việc lập trình của mình. Nếu bạn thường tải và cài đặt các thư viện, packages hoặc module nào đó thì đó là lúc bạn thực thi một **design pattern** vào hệ thống.
