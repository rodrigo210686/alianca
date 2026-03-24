# Rsync Sync Report - Aliança (Administrative - 18h)

## 📋 Resumo Executivo

- **Status**: ✅ SUCESSO
- **Data/Hora**: 23 de março de 2026 @ 18:00:01
- **Log**: `rsync_2026-03-23_18-00-01-adm.log`

## 📊 Estatísticas Gerais

| Métrica | Valor |
|---------|-------|
| Total de Arquivos | 23.840 |
| Arquivos Regulares | 21.349 |
| Diretórios | 2.491 |
| Tamanho Total | 19,32 GB |
| Dados Transferidos | 8,78 MB |
| Posição da Origem | `mnt/trabadm-origem/` |

## 🔄 Dados da Transferência

- **Bytes Enviados**: 9,84 MB
- **Bytes Recebidos**: 3,00 KB
- **Velocidade Média**: 480,05 KB/seg
- **Taxa de Compressão (Speedup)**: 1.962,86x

## 📁 Estrutura de Diretórios

**Origem**: `mnt/trabadm-origem/`

**Diretórios Principais**:
- `Administrativo/` (Senhas, sistemas diversos)
- `Contabilidade/` (Custos escritório, Fundo Fixo)

## 📈 Análise

### ✅ Sucesso da Sincronização

A operação completou com sucesso. Todos os 23.840 arquivos foram verificados.

### ⚡ Eficiência

- **Speedup de 1.962,86x** indica que aproximadamente **99,95%** dos dados já estavam sincronizados
- Apenas **8,78 MB** de **19,32 GB** necessitaram re-transmissão
- Economia de banda: **99,95%** de dados economizados

### 🚀 Performance

- Velocidade de transferência: **480,05 KB/seg** (consistente e estável)
- Tempo estimado total: Aproximadamente 18 segundos para a transferência de 8,78 MB
- Transferência eficiente com mínima utilização de largura de banda

### 🔐 Dados Administrativos

Este sync sincroniza dados da pasta administrativa, incluindo:
- Credentials e senhas de sistemas
- Documentação de contabilidade
- Configurações administrativas

## 💡 Recomendações

1. **Sincronizações Periódicas**: Manter o cronograma de sincronizações regulares, considerando o baixo volume de delta
2. **Monitoramento**: Continuar monitorando a velocidade de transferência que permanece consistente
3. **Backup Administrativo**: Validar que dados sensíveis estão sendo sincronizados corretamente em backup
4. **Verificação de Integridade**: Considerar checksum verification para dados administrativos críticos

## 🔧 Informações Técnicas

- **Tipo de Operação**: Sincronização com checksum
- **Método**: rsync com transmissão eficiente
- **Protocolo**: SSH/RSync (inferido)
- **Duração**: Sincronização rápida com alta eficiência

---

**Última Atualização**: 23 de março de 2026
**Status**: Pronto para produção
