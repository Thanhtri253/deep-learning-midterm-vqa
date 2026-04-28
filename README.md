## Deep Learning — VQA Project

> Project | Deep Learning | Ton Duc Thang University | 2026

## Thành viên
| MSSV | Họ tên |
|------|--------|
| 523H0159 | Nguyen Thai Khanh Nam |
| 523H0174 | Tran Van Qui |
| 523H0186 | Le Khac Thanh Tri |

---

##  Nội dung

### Task 1 — Deep Belief Network (DBN)
- Dataset: MNIST (tự động tải qua torchvision)
- Notebook: `task1_deep_belief_network/deep_belief_network_mnist.ipynb`

### Task 2 — Visual Question Answering (VQA)
**Classification:**
| Notebook | Mô tả |
|----------|-------|
| `vqa_pretrained_attention.ipynb` | Pretrained model + Attention |
| `vqa_pretrained_no_attention.ipynb` | Pretrained model, không Attention |
| `vqa_scratch_attention.ipynb` | Train từ đầu + Attention |
| `vqa_scratch_no_attention.ipynb` | Train từ đầu, không Attention |

**Seq2Seq:**
| Notebook | Mô tả |
|----------|-------|
| `vqa_e_pretrained_attention.ipynb` | VQA-E Pretrained + Attention |
| `vqa_e_pretrained_no_attention.ipynb` | VQA-E Pretrained, không Attention |
| `vqa_e_scratch_attention.ipynb` | VQA-E Train từ đầu + Attention |
| `vqa_e_scratch_no_attention.ipynb` | VQA-E Train từ đầu, không Attention |

---

##  Hướng dẫn chạy

Chạy trên **Google Colab** (khuyến nghị):
1. Mở notebook muốn chạy
2. Upload lên Colab hoặc mount Google Drive
3. Dataset MNIST sẽ tự tải khi chạy
4. Dataset VQA-E: tải thủ công từ [VQA Website](https://visualqa.org/)

## 📄 Báo cáo
Xem file `Report/report.pdf`
