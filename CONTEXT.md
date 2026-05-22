# NBB TACTICAL VISION — CONTEXT FILE
> Cole este arquivo inteiro no início de cada nova conversa com o Claude.

## 🎯 PROJETO
- Sistema de análise tática do NBB via computer vision
- Alvo: MIT Sloan Sports Analytics Conference 2027
- Stack: YOLO + ByteTrack + Homografia + GNN

## 👤 FELIPE
- SI — FT/Unicamp Limeira (3º semestre)
- f281413@dac.unicamp.br
- AWS Student Builder Group Leader

## 🖥️ AMBIENTE
- Google Colab (execução)
- NVIDIA RTX 3050 6GB (local, backup)
- Vídeo de trabalho: nbb_highlights_teste.mp4 (Corinthians x Pinheiros)

## ✅ STATUS ATUAL
Fase: Camada 1 concluída — YOLO funcionando
Próximo passo: Implementar ByteTrack (tracking com IDs)

## ⚙️ PARÂMETROS CALIBRADOS
roi_y_start = 0.15
roi_y_end   = 0.88
roi_x_start = 0.02
roi_x_end   = 0.98
MIN_HEIGHT  = 0.08
MAX_HEIGHT  = 0.55
conf        = 0.35
Modelo      = yolov8n.pt

## 🔄 LOG
| 22/05/2026 | YOLO + ROI calibrada, 15 detecções no highlights | Transmissão ao vivo inviável — câmera pan-tilt |

## 🔄 PRÓXIMA TAREFA
Bloco 11 — Integrar ByteTrack: cada jogador recebe ID fixo persistente entre frames
