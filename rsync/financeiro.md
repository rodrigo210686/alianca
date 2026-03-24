# Rsync Sync Report - Aliança

## 📋 Resumo Executivo

Log de sincronização via rsync entre dois servidores do diretório financeiro da empresa Aliança.

**Data/Hora:** 23 de março de 2026 às 19:00:03  
**Status:** ✅ Sincronização Concluída com Sucesso

---

## 📊 Estatísticas Gerais

| Métrica | Valor |
|---------|-------|
| **Total de Arquivos** | 89.431 |
| **Arquivos Regulares** | 76.900 |
| **Diretórios** | 12.531 |
| **Tamanho Total** | 34.46 GB |
| **Tamanho Transferido** | 4.28 MB |
| **Velocidade Média** | 118.63 KB/s |
| **Taxa de Compressão (Speedup)** | 4.179,86x |

---

## 🔄 Dados da Transferência

- **Bytes Enviados:** 8.23 MB
- **Bytes Recebidos:** 14.08 KB
- **Bytes Totais Enviados:** 8.23 MB
- **Tamanho Total no Destino:** 34.46 GB

---

## 📁 Diretório Sincronizado

**Origem:** `mnt/financeiro-origem/`

Estrutura de pastas sincronizadas:
- Extrato de contas bancárias (PDFs)
- Pasta COBRANÇA
  - Subpasta: ANALISE DE RECEBIMENTO - 2026

---

## ✅ Pontos Importantes

### ✔️ Sucesso da Sincronização
- Todas as 89.431 entidades foram verificadas
- Somente 4.28 MB foram transferidos (arquivos novos ou modificados)
- A maioria dos dados já estava sincronizada (89.99% dos dados não foi retransferido)

### 🔍 Eficiência
- **Speedup de 4.179,86x:** Significa que o rsync economizou transferência de ~360 GB
- O protocolo rsync identificou arquivos já existentes e apenas sincronizou diferenciais
- Uso eficiente de banda de rede

### ⚡ Performance
- Velocidade média de **118.63 KB/s**
- Velocidade inicial da transferência chegou a **87.25 MB/s**
- Velocidade variou entre 3.09 KB/s e 112 KB/s (oscilações de rede comum)

---

## 🎯 Conclusão

A sincronização do diretório `mnt/financeiro-origem/` foi **bem-sucedida**. 
- O tamanho reduzido de dados transferidos (4.28 MB) indica que a maioria dos arquivos já estava sincronizada
- A taxa de speedup elevada comprova a eficiência do algoritmo RSYnc na detecção de arquivos duplicados
- Nenhum erro foi registrado no processamento

**Recomendações:** Continue com as sincronizações periódicas para manter os servidores sempre atualizados.

---

**Data do Relatório:** 24 de março de 2026  
**Arquivo de Log:** `rsync_2026-03-23_19-00-01.log`
