function copiarResumo() {
    const getV = id => document.getElementById(id).value || "N/I";
    const vEspera = document.getElementById('valEspera').innerText;
    const vEmpenho = document.getElementById('valEmpenho').innerText;

    const resumo = `REGISTRO DE HORÁRIOS DA OCORRÊNCIA:
- Hora da Ocorrência: ${getV('hOcorrencia')}
- Hora de Contato no Plantão Virtual: ${getV('hContato')}
- Hora do Retorno do Plantão da PC: ${getV('hRetorno')}
- Hora de Chegada na Depol: ${getV('hChegadaDepol')}
- Hora de Início do Atendimento na Depol: ${getV('hInicioAtendimento')}
- Hora de Liberação na Depol: ${getV('hLiberacao')}
- Hora de Chegada na Fração: ${getV('hFracao')}

CÁLCULOS DE TEMPO:
- TEMPO DE ESPERA TOTAL: ${vEspera}
- TEMPO TOTAL DE EMPENHO DA GURP: ${vEmpenho}`;

    // Compatibilidade com iOS / Safari para cópia de texto
    if (navigator.clipboard && window.isSecureContext) {
      navigator.clipboard.writeText(resumo).then(exibirToast);
    } else {
      const textArea = document.createElement("textarea");
      textArea.value = resumo;
      textArea.style.position = "fixed";
      textArea.style.left = "-999999px";
      document.body.appendChild(textArea);
      textArea.focus();
      textArea.select();
      try {
        document.execCommand('copy');
        exibirToast();
      } catch (err) {
        alert("Selecione o texto manualmente para copiar.");
      }
      document.body.removeChild(textArea);
    }
  }

  function exibirToast() {
    const toast = document.getElementById('toast');
    toast.classList.add('show');
    setTimeout(() => toast.classList.remove('show'), 2500);
  }
