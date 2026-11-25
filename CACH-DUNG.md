# Cách dùng kho mochi-skills

## 1. Lấy repo về

```bash
git clone https://github.com/Nien7979/mochi-skills.git
cd mochi-skills
```

## 2. Dùng skill với Claude Code / Free Claude Code (FCC)

Skill là thư mục chứa `SKILL.md` — Claude tự đọc khi công việc khớp với
mô tả trong file đó.

```bash
# Cài 1 skill (ví dụ: skill "tdd" của mattpocock-skills)
cp -r skills/claude-skills/mattpocock-skills/engineering/tdd ~/.claude/skills/

# Cài hết skill của một repo (ví dụ toàn bộ mattpocock-skills)
cp -r skills/claude-skills/mattpocock-skills/* ~/.claude/skills/

# Cài hết skill một danh mục
cp -r skills/claude-skills/* ~/.claude/skills/
```

Khởi động lại Claude Code sau khi copy để skill được nhận.

## 3. Dùng với Codex / Gemini CLI

Các CLI này cũng đọc skill dạng thư mục `SKILL.md` (xem tài liệu của từng
CLI để biết thư mục skill của nó, thường `~/.codex/skills/` hoặc
`~/.gemini/skills/`). Copy thư mục skill vào đó theo cùng cách trên.

## 4. Dùng trực tiếp file SKILL.md

Mở file `SKILL.md` của skill cần dùng và làm theo hướng dẫn trong đó —
skill chỉ là văn bản hướng dẫn, không cần cài đặt gì thêm.

## Lưu ý an toàn

- **Không chạy mù bất kỳ script nào** trong thư mục skill (`.py`/`.js`/`.sh`):
  đọc qua trước khi chạy, chỉ chạy khi hiểu nó làm gì.
- Mỗi thư mục skill kèm file LICENSE của repo gốc — tuân theo giấy phép đó
  khi dùng lại, phân phối lại hay sửa đổi.
- Skill lấy từ repo gốc tại thời điểm 25/11/2026; muốn bản mới nhất, lấy
  tại link repo gốc ghi trong [NGUON.md](NGUON.md).
- Repo này chỉ chứa file text UTF-8. File nhị phân (ảnh, font, gói nén…)
  của skill gốc không có ở đây — lấy tại repo gốc nếu cần.
