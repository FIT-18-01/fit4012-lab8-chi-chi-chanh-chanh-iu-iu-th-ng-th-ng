# Lab 8 - Peer review response

## Nhóm được review

- Tên nhóm: Chi Chi / Chanh Chanh
- Người review: Reviewer FIT4012

## Góp ý nhận được

1. Cần có log minh chứng cho Sender và Receiver.
2. Cần kiểm tra trường hợp packet bị can thiệp.
3. Cần cập nhật README với thông tin nhóm và hướng dẫn chạy.

## Phản hồi và chỉnh sửa

| Góp ý | Phản hồi của nhóm | File/commit đã sửa |
|---|---|---|
| Cần có log minh chứng cho Sender và Receiver. | Đã thêm log `logs/sender_success.log` và `logs/receiver_success.log`. | N/A |
| Cần kiểm tra trường hợp packet bị can thiệp. | Đã thêm test tampered hash và tampered ciphertext trong `tests/`. | N/A |
| Cần cập nhật README với thông tin nhóm và hướng dẫn chạy. | Đã cập nhật README với tên nhóm, nhiệm vụ và hướng dẫn demo. | N/A |

## Tự đánh giá sau chỉnh sửa

- Chương trình chạy được demo Sender/Receiver: Có
- Có kiểm tra SHA-256: Có
- Có mã hóa DES key bằng RSA-OAEP: Có
- Có test cho packet/tamper: Có
- Có log minh chứng: Có
