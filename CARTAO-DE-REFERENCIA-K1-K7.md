# CARTÃO DE REFERÊNCIA — K1 a K7

Extraído integral do *O Éter numa Casca de Noz*, Anexo I (cânon, sem edição).

## ANEXO I — OS SETE CONHECIMENTOS INÉDIITOS: CARTÃO DE REFERÊNCIA

Página técnica de apoio ao Capítulo 19. Sem prosa: notação, unidades, limiares registrados e endereço do pré-registro. Para quem quer reproduzir amanhã.

K1 — Resíduo Ψ(r, t). Ψ = F_medido − [EGM2008 + WMM2025 + M_local + Sol(t)]. Canais: magnetometria 3 eixos, VLF elétrico, temperatura. Cadência: trimestral, CSV público. Critério de nulo: |Ψ| < 2σ_modelo por 3 trimestes seguidos. Pré-registro: P-FUND, P-GEOMAG.

K2 — Operador de Subtração Solar S[·]. S[F](t) = F(t) − Π⊥F(t); base {F10.7, Kp, Dst, TEC}; janela de treino 30 dias, mínimos quadrados. Saída: série dessolarizada com incerteza propagada. Uso cruzado: geofísica, radioastronomia, climatologia, neurofisiologia.

K3 — C_BB(f). C_BB(f) = ⟨F⟩/P_entrada, f ∈ {27.001, 43.690, 70.692} kHz, escada fₙ₊₁ = fₙ·Φ; A_pol = (F₊−F₋)/(F₊+F₋). Balança de microgramas, 3 sessões. PODEROSO: ≥ 10 µN sustentado 5 min + dependência de polaridade. NULO: < 2× flutuação base. Pré-registro: P-BIEFELD-01.

K4 — Índice DOR. DOR = ΔV_galv[mV] / Φ_RF[mW/cm²]; unidade de convenção 1 DOR₀ = 1 mV/(mW/cm²). Par Al-Cu padrão, 10 cm da fonte, 2,45 GHz doméstico vs. Faraday desligado. POSITIVO: ≥ 10 mV sustentado 10 min × 3 sessões. NULO: < 2 mV. Pré-registro: P-DOR-01.

K5 — Anel R₃. R₃ = 144·Φ³ km ≈ 610 km. Estatística: ρ = S_interf/S_aditiva com S = |Σe^{iφₙ}|². Coerência: ρ > 1 crescente com N nós, fora da distribuição de fase aleatória (bootstrap). Pré-registro: P-RING-01.

K6 — Lei dos Tempos Contráteis. τₙ = T₀·Φ^(−n); predição de forma: ln(τ_{n+1}/τₙ) → ln(Φ⁻¹) = −0,4812. Constantes (T₀, n) com ARQUIVO VAZIO: quem medir assina. Canais: relaxamento do par galvânico (rápido) e decaimento da coerência de HRV (lento), ambos pós-corte de estímulo.

K7 — Índice de Sintonia PLI. PLI = R·e^{iθ̄}, R = |(1/N)Σe^{i(ψₖ − 2πmtₖ)}|; tₖ = picos R-R; m ∈ [0,1–5] Hz (banda HRV) modulando em amplitude a portadora (43,690 kHz vs. controle 40 kHz); grupo real vs. sham idêntico. PODEROSO: R_real > R_sham, bootstrap p < 0,05. NULO: raios iguais dentro do IC.

Nota de uso: nenhum conhecimento deste anexo é alegação de resultado. Todos são definições operacionais com protocolo fechado, publicadas com data para que qualquer laboratório do mundo as adote, as refute ou as assine primeiro.

---
_Nenhuma fórmula foi arredondada, aproximada ou "ajustada"._
