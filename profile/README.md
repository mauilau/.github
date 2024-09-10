# Mauilau - Minimalist Smart Wallet
Un smart wallet minimalista con funcionalidad super limitada para una experiencia de usuario super sencilla.

## Inspiración:
La inspiración detrás de Mauilau nace de la necesidad de simplificar y democratizar el uso de wallets en aplicaciones descentralizadas, eliminando las barreras técnicas y de usabilidad para usuarios nuevos en el mundo de Web3. Observamos que muchos usuarios, especialmente en eventos y aplicaciones específicas, se sienten abrumados por la complejidad de la tecnología blockchain y la gestión de wallets. Queremos proporcionar una solución sencilla, accesible y funcional, permitiendo que cualquier persona pueda interactuar con una smart wallet sin la necesidad de conocimientos técnicos profundos ni tener que gestionar palabras semilla. El proyecto toma inspiración de la simplicidad que se requiere en eventos como torneos de póker, donde se necesita una funcionalidad clara y directa: contar y enviar tokens de manera controlada.

## ¿Qué hace?
Mauilau es una smart wallet minimalista diseñada para ser utilizada en un navegador, donde los usuarios pueden crear una wallet con solo un correo electrónico gracias a la tecnología de Account Abstraction. La wallet permite dos funciones simples:

- Mostrar tokens predefinidos: La wallet solo despliega los tokens de un contrato predefinido que se configura con antelación. En este caso, se asignan tres tokens que representan las "vidas" de los jugadores en un torneo de póker.
- Enviar tokens: Con un solo clic, los usuarios pueden aprobar una transacción para enviar uno de esos tokens a una dirección predefinida, como parte de las reglas del torneo.
No hay necesidad de interacción compleja con el blockchain, ni de manejar ether para gas, ya que el administrador de la plataforma proporciona el éter necesario para las transacciones.

## ¿Cómo lo vamos a construir?
El proyecto se desarrollará utilizando Account Abstraction (AA) para gestionar la creación de wallets sin necesidad de palabras semilla, lo que mejora la experiencia de usuario.

- Front-end: Será una aplicación descentralizada (dApp) simple y ligera que correrá en el navegador. Utilizaremos React para la interfaz de usuario. Back-end: El sistema se conectará con contratos inteligentes predefinidos que manejarán la asignación de tokens.
- Smart Contracts: Los contratos estarán escritos en Solidity y desplegados en la red de XXX (Layer 2 de Ethrereum) de bajo costo para asegurar transacciones rápidas y económicas. Se asignará ether de gas a las wallets cuando se confirme el pago de entrada al torneo, y los tokens se distribuirán automáticamente.
- Infraestructura: Usaremos tecnologías como IPFS para almacenamiento descentralizado, y Alchemy o Infura para las llamadas a la blockchain.

## Retos enfrentados:
Al desarrollar Mauilau, nos encontramos con varios desafíos que debimos resolver:

- Simplificación extrema: Crear una wallet con funcionalidad extremadamente limitada sin comprometer la seguridad ni la integridad del sistema fue un desafío. Solucionamos esto al restringir la dapp a solo dos funciones muy específicas.
- Account Abstraction: Integrar Account Abstraction para eliminar la necesidad de una frase semilla presentó algunas complejidades, especialmente en cómo gestionar las firmas y la seguridad sin exponer al usuario a demasiada fricción.
- Asignación de gas: Lograr que los usuarios no tengan que gestionar el gas fue un reto técnico y de diseño. Optamos por que los administradores carguen ether a las wallets para cubrir las transacciones.
- Interfaz amigable: Diseñar una interfaz lo suficientemente intuitiva para que los usuarios no se sientan abrumados por los procesos técnicos, pero que siga cumpliendo con los estándares de seguridad y funcionalidad.

## ¿Qué hemos aprendido?
A lo largo del desarrollo de Mauilau, aprendimos la importancia de balancear simplicidad con funcionalidad en aplicaciones Web3. Nos dimos cuenta de que es posible ofrecer una experiencia de usuario sin fricción en el mundo de las criptomonedas y blockchain, pero requiere un alto nivel de atención en los detalles técnicos para garantizar que los usuarios no tengan que preocuparse por el backend del sistema. También hemos aprendido cómo Account Abstraction puede abrir muchas oportunidades para hacer más accesibles las aplicaciones descentralizadas.

## Qué sigue para Mauilau?
Después del hackathon, planeamos expandir las capacidades de Mauilau y explorar su uso en diferentes industrias:

- Desarrollo del Dashboard: Crear una plataforma donde los usuarios puedan personalizar qué tokens quieren visualizar y definir qué hacen los botones dentro de su wallet, manteniendo siempre la simplicidad en el diseño.
- Explorar otros casos de uso: Creemos que esta smart wallet minimalista tiene aplicaciones en sectores como la hotelería (para programas de puntos), la industria del entretenimiento (para eventos), y sistemas de fidelización de clientes.
- Modelo de negocio: Nuestra próxima fase será explorar posibles modelos de negocio que hagan sustentable este proyecto, como la personalización de wallets para diferentes empresas o eventos, o la integración con sistemas de pago corporativos.
En conclusión, Mauilau busca revolucionar la forma en que las personas interactúan con sus activos digitales, haciendo que la tecnología sea accesible para todos, eliminando barreras y mejorando la experiencia del usuario en el ecosistema Web3.

## Built With
astar hardhat react solidity

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
