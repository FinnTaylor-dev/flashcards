Q: What does RISC stand for?
A: Reduced Instruction Set Computer.

---

Q: What does CISC stand for?
A: Complex Instruction Set Computer.

---

Q: What is a RISC processor?
A: A processor that uses a small instruction set, with each instruction typically taking one clock cycle to execute.

---

Q: What is a CISC processor?
A: A processor that uses a large instruction set containing complex instructions designed to accomplish tasks in as few lines of assembly code as possible.

---

Q: What is the main characteristic of a RISC instruction set?
A: It contains a small number of simple instructions.

---

Q: What is the main characteristic of a CISC instruction set?
A: It contains a large number of complex instructions.

---

Q: How many lines of machine code does a typical RISC instruction represent?
A: Approximately one line.

---

Q: How long does a typical RISC instruction take to execute?
A: One clock cycle.

---

Q: What is the main aim of CISC processors when designing instructions?
A: To accomplish tasks using as few lines of assembly code as possible.

---

Q: Where are CISC instructions built?
A: Directly into the processor hardware.

---

Q: Which type of processor generally requires more instructions to complete a task, RISC or CISC?
A: RISC.

---

Q: Which type of processor generally requires fewer lines of assembly code to complete a task?
A: CISC.

---

Q: What instructions are needed to multiply two numbers X and Y using the example RISC processor?
A: LDA R1, X LDA R2, Y MULT R1, R2 STO R1, X

---

Q: What does `LDA R1, X` do in the RISC multiplication example?
A: Loads the value of X into register R1.

---

Q: What does `LDA R2, Y` do in the RISC multiplication example?
A: Loads the value of Y into register R2.

---

Q: What does `MULT R1, R2` do in the RISC multiplication example?
A: Multiplies the values stored in registers R1 and R2.

---

Q: What does `STO R1, X` do in the RISC multiplication example?
A: Stores the result from register R1 in memory location X.

---

Q: How many instructions are used to multiply two numbers in the given RISC example?
A: Four instructions.

---

Q: How is the multiplication of two numbers represented in the given CISC example?
A: `MULT A, B`

---

Q: How many instructions are used to multiply two numbers in the given CISC example?
A: One instruction.

---

Q: Why can CISC processors perform a task using fewer lines of assembly code than RISC processors?
A: They have complex, specialised instructions that can perform multiple operations.

---

Q: Which processor type requires the compiler to do more work when translating high-level code into machine code?
A: RISC.

---

Q: Why does a RISC processor require more work from the compiler?
A: Its small instruction set means the compiler must combine multiple simple instructions to perform complex tasks.

---

Q: Which processor type requires less work from the compiler when translating high-level code into machine code?
A: CISC.

---

Q: Why does a CISC processor require less work from the compiler?
A: Its large instruction set contains complex instructions that can perform tasks with fewer instructions.

---

Q: Which processor type generally requires more RAM to store program code?
A: RISC.

---

Q: Why does RISC generally require more RAM to store program code?
A: More instructions are needed to complete tasks, resulting in longer programs.

---

Q: Which processor type generally requires less RAM to store program code?
A: CISC.

---

Q: Why does CISC generally require less RAM to store program code?
A: Fewer instructions are needed to complete tasks, resulting in shorter programs.

---

Q: Which processor type supports pipelining because its instructions take one clock cycle?
A: RISC.

---

Q: Why is pipelining possible with RISC processors?
A: Each instruction takes approximately one clock cycle, making instruction execution easier to organise into overlapping stages.

---

Q: What is pipelining?
A: A technique where multiple instructions are processed at different stages of execution simultaneously.

---

Q: Why are RISC instructions particularly suitable for pipelining?
A: They are simple and have a consistent execution time of approximately one clock cycle.

---

Q: What is one disadvantage of CISC processors regarding their instruction sets?
A: They contain many specialised instructions, even though only a small number may actually be used.

---

Q: Which processor type has many specialised instructions, some of which may rarely be used?
A: CISC.

---

Q: Which processor type was originally the standard processor design?
A: CISC.

---

Q: Which processor design gradually replaced CISC as the standard design?
A: RISC.

---

Q: Where are CISC processors now more commonly used?
A: Microcontrollers and embedded systems.

---

Q: What are the main differences between RISC and CISC processors?
A: RISC uses a small set of simple instructions, requires more compiler work and RAM, and supports pipelining. CISC uses a large set of complex instructions, requires less compiler work and RAM, and contains many specialised instructions that may rarely be used.

---

Q: What is a multicore CPU?
A: A CPU containing multiple independent processing cores that can execute instructions separately.

---

Q: What is a core in a CPU?
A: An independent processing unit capable of executing instructions.

---

Q: How do multiple cores improve CPU performance?
A: They allow multiple instructions or tasks to be processed independently at the same time.

---

Q: What is the main advantage of a multicore CPU?
A: Higher performance through multiple independent cores working simultaneously.

---

Q: What is a parallel system?
A: A system that completes tasks simultaneously using threading, even with a single processor core.

---

Q: How can a parallel system complete multiple tasks using a single core?
A: By using threading.

---

Q: What is threading?
A: The use of separate threads of execution to allow tasks to be managed and processed concurrently.

---

Q: What is the main similarity between multicore systems and parallel systems?
A: Both aim to improve performance by allowing multiple tasks to be processed concurrently.

---

Q: What is the main difference between multicore systems and parallel systems?
A: Multicore systems use multiple independent CPU cores, whereas parallel systems can achieve concurrent task execution on a single core using threading.

---

Q: Which generally performs better for larger projects: multicore systems or parallel systems?
A: Multicore systems.

---

Q: Why do multicore systems generally perform better than parallel systems on larger projects?
A: Multiple independent cores can execute instructions simultaneously, providing greater processing capacity than relying on threading on a single core.

---

Q: What is a GPU?
A: A Graphics Processing Unit, a processor designed to carry out many operations in parallel.

---

Q: What does GPU stand for?
A: Graphics Processing Unit.

---

Q: How does a GPU differ from a CPU in terms of processor organisation?
A: A GPU has lots of independent processors that work in parallel, whereas a CPU generally has fewer processing cores designed for a wider variety of tasks.

---

Q: Why are GPUs efficient at repetitive tasks?
A: They contain many independent processors that can perform similar operations simultaneously.

---

Q: What type of processing is a GPU particularly efficient at?
A: Parallel processing of repetitive tasks.

---

Q: What are two common uses of GPUs?
A: Image processing and machine learning.

---

Q: Why are GPUs useful for image processing?
A: They can process many image-related operations simultaneously using their multiple independent processors.

---

Q: Why are GPUs useful for machine learning?
A: They can perform large numbers of repetitive calculations in parallel.

---

Q: What is a co-processor?
A: A secondary processor designed to supplement the activities of the primary processor.

---

Q: Why is a GPU classified as a co-processor?
A: It supplements the CPU by handling specialised tasks such as image processing and machine learning.

---

Q: What is the difference between a CPU and a GPU?
A: A CPU is designed to handle a wide variety of general-purpose tasks, whereas a GPU contains many independent processors designed to carry out repetitive tasks in parallel.

---

Q: What is the relationship between GPUs and parallel processing?
A: GPUs use many independent processors working simultaneously, making them highly efficient at parallel processing.

---

Q: How are GPUs, multicore CPUs and parallel systems connected?
A: All can improve performance through concurrent processing. Multicore CPUs use multiple independent cores, parallel systems can use threading on a single core, and GPUs use many independent processors to perform repetitive operations simultaneously.

---

Q: Which processor is particularly suited to image processing and machine learning?
A: A GPU.

---

Q: Which processor design uses a small instruction set and supports pipelining?
A: RISC.

---

Q: Which processor design uses a large instruction set with complex, specialised instructions?
A: CISC.

---

C: RISC stands for [Reduced Instruction Set Computer].

---

C: CISC stands for [Complex Instruction Set Computer].

---

C: RISC processors use a [small] instruction set, whereas CISC processors use a [large] instruction set.

---

C: Each RISC instruction takes approximately [one clock cycle] to execute.

---

C: A typical RISC instruction represents approximately [one line of machine code].

---

C: CISC processors aim to accomplish tasks using as few lines of [assembly code] as possible.

---

C: CISC instructions are built directly into the processor [hardware].

---

C: RISC processors require [more] compiler work than CISC processors when translating high-level code into machine code.

---

C: CISC processors require [less] compiler work than RISC processors when translating high-level code into machine code.

---

C: RISC processors generally require [more RAM] because programs contain more instructions.

---

C: CISC processors generally require [less RAM] because programs contain fewer instructions.

---

C: [Pipelining] is possible with RISC processors because each instruction takes approximately one clock cycle.

---

C: CISC processors contain many [specialised instructions], even though only a few may actually be used.

---

C: CISC processors were originally the [standard] processor design, but were gradually replaced by [RISC] designs.

---

C: CISC processors are now more commonly used in [microcontrollers] and [embedded systems].

---

C: A multicore CPU contains multiple [independent cores] that can execute instructions separately.

---

C: Multicore CPUs improve performance by allowing multiple [instructions or tasks] to be processed independently at the same time.

---

C: Parallel systems can complete tasks using a single core through [threading].

---

C: [Threading] allows a parallel system to manage concurrent tasks using a single core.

---

C: Multicore systems generally perform better than parallel systems on [larger projects].

---

C: A GPU stands for [Graphics Processing Unit].

---

C: A GPU contains lots of [independent processors] that work in [parallel].

---

C: GPUs are particularly efficient at completing [repetitive tasks].

---

C: Two common uses of GPUs are [image processing] and [machine learning].

---

C: A GPU is a type of [co-processor], meaning a secondary processor designed to supplement the activities of the [primary processor].

---

C: GPUs are efficient at parallel processing because they contain [many independent processors] that can perform operations simultaneously.

---

C: A CPU is generally designed for [general-purpose processing], whereas a GPU is particularly suited to [parallel processing of repetitive tasks].

---

C: The three main processor topics in this section are [RISC and CISC], [GPUs] and [multicore and parallel systems].
