# 📦 Backup Automático

## 🕐 Último Backup
**Data e Hora:** 14/05/2026, 08:45:39  
**Timestamp UTC:** 2026-05-14T11:45:39.616Z

---

## ✅ Status do Backup

### 🗄️ Banco de Dados
- **Database:** `teste`
- **Tamanho do dump:** 0.83 MB
- **Status:** ✅ Backup realizado com sucesso

### 📁 Uploads
- Total de arquivos: 27.106
- Tamanho total: 13.61 GB
- ⚠️ Nenhuma parte foi criada


---

## 📊 Resumo

| Item | Valor |
|------|-------|
| Banco de Dados | ✅ Exportado |
| Uploads | 0 parte(s) |
| Data do Backup | 14/05/2026, 08:45:39 |

---

## 🔧 Como restaurar

### Restaurar Banco de Dados:
```bash
mysql -u root -p teste < backup.sql
```

### Restaurar Uploads:
1. Baixe todas as partes `uploads.zip.001`, `uploads.zip.002`, etc.
2. Junte as partes:
   ```bash
   copy /B uploads.zip.* uploads_completo.zip
   ```
3. Extraia o ZIP completo

---

*Gerado automaticamente em 14/05/2026, 08:45:39*
