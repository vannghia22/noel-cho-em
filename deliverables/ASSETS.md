# Tài nguyên đã dùng

1. Footage: file người dùng b (2).mp4, sao nguyên vẹn thành assets/source.mp4. Giữ quyền và phạm vi sử dụng theo nguồn người dùng.
2. Proxy hình: assets/presenter-edit.mp4, sinh từ footage bằng FFmpeg, H.264 CRF18, GOP30, không audio; dùng để seek ổn định. Không kéo giãn ảnh.
3. Thoại: assets/dialogue.wav, giữ giọng thật; high-pass70Hz và loudness normalization. Đo file thoại: −15,8 LUFS, peak −1,5 dBFS.
4. Nhạc: assets/music-final.wav, nhạc mallet/pad thủ tục tạo riêng cho bản dựng, không dùng sample nhạc ngoài; các file music-original/music-bed/music-ducked là bản trung gian. Mức nền thấp, duck theo thoại và fade cuối.
5. SFX: pop.mp3, whoosh-short.mp3 từ thư viện offline đi kèm HyperFrames0.8.185. Package license Apache-2.0; nguồn https://github.com/heygen-com/hyperframes . Không tải SFX từ nguồn không rõ.
6. Font: Be Vietnam Pro800, Latin/Vietnamese, @fontsource/be-vietnam-pro5.3.0. SIL Open Font License lưu ở assets/fonts/LICENSE.
7. GSAP3.14.2: assets/gsap.min.js, official npm distribution qua jsDelivr; license https://gsap.com/standard-license/ .
8. Nhận dạng: whisper.cpp, small đa ngôn ngữ và large-v3-turbo-q5_0, tiếng Việt. Model tải từ ggerganov/whisper.cpp revision5359861c739e955e79d9a303bcbc70fb988958b1, kiểm tra SHA256 theo metadata chính thức trước khi chạy. Không đóng gói model lớn vào project.

Không dùng stock video, hình sản phẩm không xác minh, voice clone hoặc lời chứng thực dựng thêm. Âm thanh được đo bằng công cụ; agent không nghe trực tiếp được audio trong phiên này.
