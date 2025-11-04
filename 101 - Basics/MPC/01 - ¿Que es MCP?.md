# ¿Qué es MCP y porque es el futuro de la programación con Inteligencia Artificial?

---

### ¿Qué es Model Context Protocol (MCP)?

![Image](https://portkey.ai/blog/content/images/2024/12/whatismcp.png)

![Image](https://substackcdn.com/image/fetch/%24s_%215Qxi%21%2Cw_1200%2Ch_600%2Cc_fill%2Cf_jpg%2Cq_auto%3Agood%2Cfl_progressive%3Asteep%2Cg_auto/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fdc01797d-9996-4b83-a00f-6771b8071d97_900x500.png)

![Image](https://miro.medium.com/1%2AzN71LjNRbJqD6SyNaxKr2g.png)

“MCP” significa **Model Context Protocol**. Es un estándar abierto (open-source) desarrollado por Anthropic en noviembre de 2024 para facilitar que los modelos de lenguaje grande (LLMs) y otras aplicaciones de IA puedan conectarse a **fuentes externas de datos, herramientas, servicios y sistemas** de forma estandarizada. ([redhat.com][1])

### Cómo funciona – en términos simples

* Una aplicación de IA actúa como **cliente MCP** que quiere “algo” (datos, ejecutar una acción, etc.).
* Un **servidor MCP** es una pieza de software que expone recursos, herramientas o servicios que el cliente puede usar (por ejemplo: base de datos, API, sistema interno). 
* Todo se comunica mediante un protocolo (por ejemplo JSON-RPC 2.0) y sigue un “handshake” inicial donde se intercambian capacidades (qué puede ofrecer el servidor, qué entiende el cliente). ([redhat.com][1])
* De este modo, el modelo de IA no queda “aislado” sólo con su entrenamiento, sino que puede acceder dinámicamente a contexto, herramientas y datos actualizados. ([CIO][2])

### ¿Por qué se considera “el futuro de la programación con IA”?

Varios aspectos lo hacen relevante para ver cómo evoluciona la programación y los sistemas de IA:

1. **Escalabilidad e integración simplificada**
   Antes de MCP, cada par “modelo de IA ↔ herramienta o base de datos” requería una integración personalizada (“N × M” problema: N modelos, M herramientas). Con MCP, se reduce a “N + M”: los modelos usan un estándar único para conectarse a múltiples herramientas. ([Medium][3])

2. **Contexto más rico para IA**
   Los modelos ya no sólo dependen de lo que aprendieron en entrenamiento, sino que pueden **acceder al estado actual de sistemas, historiales, bases de datos, APIs**, lo que mejora su pertinencia, precisión y utilidad en aplicaciones reales. ([CIO][2])

3. **Permite a la IA “hacer cosas” además de responder**
   No sólo “preguntar y responder”, sino ejecutar acciones reales: actualizar registros, disparar workflows, conectarse a sistemas internos, etc. Esto transforma la programación: cada vez más el desarrollador define “qué capacidad tiene la IA” y los sistemas lo exponen vía MCP. ([zapier.com][4])

4. **Interoperabilidad y estándar común**
   Al ser estándar abierto, permite que diferentes proveedores, modelos, herramientas y plataformas se comuniquen bajo el mismo lenguaje. Esto facilita que el ecosistema de IA crezca sin estar bloqueado por integraciones propietarias. ([redhat.com][1])

### ¿Y cómo impacto tendría para quienes programan IA o construyen aplicaciones?

* Los desarrolladores de IA pueden centrarse menos en escribir *adaptadores* personalizados para cada sistema externo, y más en **definir las “capabilities”** de su IA.
* Las aplicaciones pueden estar más interconectadas: la IA se vuelve un “agente” que opera dentro de la infraestructura de software, no solo una caja negra de respuestas.
* La programación se vuelve más “orientada a agentes” o “sistemas contextuales”, donde definirás herramientas, recursos y conexiones más que sólo lógica algorítmica tradicional.
* En tu campo (por ejemplo, automatización, actualización de tablas, scripting…), podría significar que los flujos que creas con IA ganan acceso dinámico a bases de datos, APIs y sistemas internos sin tanto “código de integración”.

### Algunas advertencias

No todo es “mágico” y sin riesgos:

* La seguridad: al exponer herramientas para que la IA actúe, surgen riesgos de ejecución de código, fuga de datos, privilegios mal gestionados. ([arXiv][5])
* Estándar aún emergente: aunque ya adoptado por varios actores, todavía hay que ver prácticas maduras, gobernanza, y cómo se gestiona la complejidad en producción.
* No sustituye lógica de negocio ni arquitectura buena: sigue siendo clave definir bien qué hace cada “tool”, qué datos se permiten, cómo se controla el flujo.

---

Si querés **profundizar en cómo tú podrías usar MCP** en tus scripts o entornos (por ejemplo en Python, integrando con bases de datos, automatización, etc.), puedo buscar algunos ejemplos concretos o librerías SDK que ya lo soporten. ¿Te parece que lo haga?

[1]: https://www.redhat.com/en/topics/ai/what-is-model-context-protocol-mcp?utm_source=chatgpt.com "What is Model Context Protocol (MCP)?"
[2]: https://www.cio.com/article/4035003/mcp-explained-the-ai-gamechanger.html?utm_source=chatgpt.com "MCP explained: The AI gamechanger | CIO"
[3]: https://medium.com/ai-essentials/model-context-protocol-mcp-what-it-is-and-why-it-matters-12f2e12449c0?utm_source=chatgpt.com "Model Context Protocol (MCP): What It Is and Why It Matters | by Tobi Plumpter | AI Essentials | Medium"
[4]: https://zapier.com/blog/mcp?utm_source=chatgpt.com "What is MCP (Model Context Protocol)? | Zapier"
[5]: https://arxiv.org/abs/2504.03767?utm_source=chatgpt.com "MCP Safety Audit: LLMs with the Model Context Protocol Allow Major Security Exploits"
