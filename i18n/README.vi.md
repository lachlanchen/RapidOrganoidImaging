[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# Rapid Organoid Imaging

![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Project Type](https://img.shields.io/badge/Type-Paper%20Companion-informational)
![Status](https://img.shields.io/badge/Status-Scaffolded-lightgrey)
![Docs](https://img.shields.io/badge/Docs-README-brightgreen)
![i18n](https://img.shields.io/badge/i18n-Enabled-00A86B)

> Kho lưu trữ của bài báo Event-based Rapid Organoid Imaging.

## Tổng quan

Kho lưu trữ này hiện đóng vai trò là kho đi kèm cho bài báo **Event-based Rapid Organoid Imaging**.

Tại thời điểm của bản nháp này, kho đã có giấy phép, quy tắc bỏ qua và khung tài liệu, nhưng vẫn chưa có mã nguồn được theo dõi, gói, script hoặc tài nguyên thí nghiệm.

| Ảnh chụp trạng thái | Trạng thái hiện tại |
|---|---|
| Phạm vi | Kho lưu trữ đi kèm bài báo |
| Thành phần chính | Khung tài liệu |
| Tình trạng mã nguồn | Chưa có tệp triển khai nào được theo dõi |
| Mức sẵn sàng đa ngôn ngữ | Thư mục `i18n/` đã tồn tại |

## Tính năng

- Khung dự án chuẩn cho bài báo: *Event-based Rapid Organoid Imaging*.
- Đã bao gồm giấy phép Apache 2.0.
- Mẫu `.gitignore` theo định hướng Python, cho thấy khả năng sẽ dùng công cụ Python trong tương lai.
- Có sẵn thư mục `i18n/` cho các biến thể README đa ngôn ngữ.

## Cấu trúc dự án

```text
RapidOrganoidImaging/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

Ghi chú:
- `.auto-readme-work/` là không gian làm việc của pipeline và có thể chứa các tạo tác trợ giúp được sinh ra.
- Các tệp hiện đang được theo dõi ở thư mục gốc là `README.md`, `LICENSE` và `.gitignore`.
- `i18n/` đã tồn tại, nhưng các README theo từng ngôn ngữ có thể vẫn đang chờ được tạo.

## Điều kiện tiên quyết

Các điều kiện tối thiểu hiện tại:

- `git` (để clone và theo dõi cập nhật)
- Tùy chọn: công cụ Python (`python`, `pip`, môi trường ảo) nếu/khi mã nguồn được thêm vào

Hiện chưa có phụ thuộc runtime bắt buộc nào được khai báo trong các manifest đang được theo dõi.

## Cài đặt

```bash
git clone <your-repository-url>
cd RapidOrganoidImaging
```

Nếu/khi mã Python được thêm vào, một thiết lập môi trường điển hình có thể là:

```bash
python -m venv .venv
source .venv/bin/activate
```

Ghi chú giả định: các lệnh cài phụ thuộc chưa được định nghĩa vì hiện chưa có manifest phụ thuộc nào được theo dõi.

## Cách sử dụng

Hiện tại cách sử dụng ưu tiên tài liệu:

- Đọc phạm vi dự án và các cập nhật trong `README.md`.
- Tham chiếu tiêu đề bài báo liên quan: **Event-based Rapid Organoid Imaging**.
- Theo dõi các commit sắp tới bổ sung script tái lập, bộ dữ liệu hoặc mã model/inference.

Vì chưa có entrypoint thực thi nào được theo dõi, hiện chưa có lệnh chạy để cung cấp ở giai đoạn này.

## Cấu hình

Hiện chưa có tệp cấu hình nào được định nghĩa (ví dụ chưa có `.env.example`, `config.yaml`, hoặc schema đối số CLI trong mã được theo dõi).

Khi cấu hình được đưa vào, mục này nên mô tả:

- Các biến môi trường bắt buộc
- Đường dẫn dataset/đầu vào
- Vị trí đầu ra
- Tùy chọn phần cứng/runtime

## Ví dụ

Hiện chưa có ví dụ thực thi nào được thêm vào kho.

Các nhóm ví dụ dự kiến (sẽ được bổ sung khi có mã):

- Chuẩn bị / nạp dữ liệu
- Xử lý luồng sự kiện
- Quy trình suy luận hoặc phân tích ảnh organoid
- Trực quan hóa/xuất kết quả

## Ghi chú phát triển

- `.gitignore` hiện có là mẫu Python tương đối đầy đủ và đã bỏ qua các tạo tác virtualenv/build/test phổ biến.
- Chưa có workflow CI, cấu hình formatter, hoặc bộ test nào được theo dõi.
- `i18n/` đã tồn tại và sẵn sàng cho các README theo từng ngôn ngữ.

## Khắc phục sự cố

### Tôi đã clone repo nhưng không có mã nguồn

Đây là trạng thái dự kiến ở hiện tại. Kho lưu trữ hiện đang hoạt động như một khung đi kèm bài báo.

### Liên kết ngôn ngữ trỏ tới tệp có thể chưa tồn tại

Điều này có thể xảy ra trước khi các README đa ngôn ngữ được tạo. Dòng điều hướng ngôn ngữ được giữ lại có chủ đích để đảm bảo cấu trúc i18n nhất quán.

### Tôi không tìm thấy yêu cầu cài đặt

Hiện chưa có manifest phụ thuộc nào được theo dõi (ví dụ `requirements.txt`, `pyproject.toml`, hoặc `environment.yml`).

## Lộ trình

Các cải tiến tăng dần được lên kế hoạch:

- Bổ sung metadata bài báo (tác giả, venue, liên kết DOI/arXiv) khi có sẵn
- Bổ sung hướng dẫn tái lập và các tệp khóa môi trường
- Bổ sung script/notebook có thể chạy cho quy trình imaging
- Bổ sung chỉ dẫn dữ liệu mẫu và quy ước thư mục dự kiến
- Bổ sung kiểm thử/kiểm định và CI
- Xuất bản README đa ngôn ngữ trong `i18n/`

## Trích dẫn

Metadata trích dẫn hiện chưa được đưa vào kho lưu trữ.

Khi có sẵn, hãy thêm khối BibTeX ở đây và giữ đồng bộ với phiên bản bài báo.

## Đóng góp

Rất hoan nghênh đóng góp sau khi các tệp triển khai và quy trình phát triển được công bố.

Luồng đóng góp được khuyến nghị (mức best-effort hiện tại):

1. Fork kho lưu trữ.
2. Tạo nhánh tính năng.
3. Thực hiện thay đổi có phạm vi rõ ràng với thông điệp commit minh bạch.
4. Mở pull request mô tả động lực, cách tiếp cận và xác thực.

Nếu sau này có hướng dẫn đóng góp (ví dụ `CONTRIBUTING.md`), hãy tuân theo đó như nguồn sự thật.

## Giấy phép

Dự án này được cấp phép theo Apache License 2.0. Xem [LICENSE](../LICENSE).

## Lời cảm ơn

- Tuyên bố mục đích kho lưu trữ từ README chuẩn: "Repo of paper Event-based Rapid Organoid Imaging"
