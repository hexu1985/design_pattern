## 中间者模式 mediator

在中间者模式，对象间不是直接互相通信，而是间接地通过中间者。中间者收到信息后，再通知所有相关的对象。这样减少了对象之间相互依赖的情况，对象仅依赖于中间者。

---

### 类图

![类图](doc/mediator_class.png)

---

### 时序图

![时序图](doc/mediator_sequence.png)
