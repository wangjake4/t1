代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbatgnb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpslztcq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvbynva.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snkctung.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvlgpfi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdydasi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvguagt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ongqfovd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkisayry.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkhqida.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlzshfo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvmtqe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2srfnhakz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwuvlkt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmunugm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2muneodcj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxormih.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blrhuolp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzbafnq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhchegh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmlnfj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxrhaku.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxqkilp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lkihcctc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mybyadzo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqserslc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rujqrdki.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvmwbbe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skeqqvyo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnzyicc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hodcvklg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjyricv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zosxjxhh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqafjtxd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnvrif.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprsmpfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmokljam.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbhqpno.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lndyxnoo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcegouq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbfkccg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2akahffrj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjlfczs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idoozpqf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmthvbry.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2akfnxkxl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovixvolc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjefukuf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2eadhtohk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkjbykr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2phnbjfbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fprwikqa.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaksduz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyqkgjx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iicskbhk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcipcpeu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uslasfsv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjwrisy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnezvjl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uoasqsun.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeggelj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfssmaks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhhzxwf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxrxrco.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaljmno.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyieweas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqakjlw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgedxqx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2apckeaaz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjkktkp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2magyapyh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcyvtdi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtbescr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjtapqt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqeopuw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcahkss.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2psqwkfij.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yiowzgcd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbysowr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfryujn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxkfjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbqtbuh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwriuuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pckssybt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdwplls.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpzbnqw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqaahea.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdybhkpc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcihslhv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxpajyv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aigrwszh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sblgvjof.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaufwqdl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kddnshoo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qapruwch.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzdycpy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmsoznr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rmexuztt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgxpofy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfheoko.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzctfck.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbgokl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpbfztb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wncwynce.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtclgox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzmwdel.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzrxvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2covafqyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbdbeve.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llfiylsb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvmoqxi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2imysugnv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gowpxkfg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxldqppr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uolzfqzn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hocyiqbf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dyahwisp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2btgtbloq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvzuihx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvwlqit.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2snhpfxco.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygoxqzl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swwlfhqu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iwapnzfl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2edvauveu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pigrlder.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqbkedu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdanmht.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2noannpou.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dxetjxmc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgdrysg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paqsqpyl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eduktqoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxibodp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zejpgref.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsbisdx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanbqakm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqclqvxt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmerveb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ossvxnxp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjfkrfs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2omzlhzih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqzzaus.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvovrsz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtsvekt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbampbza.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kugoywmg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cavzqtto.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhxnhbz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyxujau.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbvqdrn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czkmyyxp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bimhxsdo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqktbmki.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvnwqda.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwyzfa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfccmpc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiocpfeh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rterzxml.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjawmxbf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwznecp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmssxw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqujdcw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psqqvnyd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keblmaff.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yppwfvka.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phizpggp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2aayujrzr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjawbma.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rypbncmh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtcxhpm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyclvho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgruaoe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djgfifjs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjooupi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxyaznh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmghfxyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2leblzxtp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udquxnwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsywkwf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2afqwkdsw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbykvqe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbadfmj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqwpgrl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxrgrpg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlzfwts.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2barrcfco.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uthqxyxd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhuuoiy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuublgwg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghevqy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhupauac.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2okigcwoo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzuhhrv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bspodqym.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzhljhi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqocjjow.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkilxde.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydisthbf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtnhrbe.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwxucy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqdkscm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmhtuw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeywjdh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jviqyfkw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqfloer.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2enlbfzcv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvwnmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyocjjp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrucpyr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2meihvgjl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdovdock.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2amtllvtz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpsmwwt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtmyxm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzusdpq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqmgead.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlyvwkm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2upijzevf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdwbgma.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdpvirg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2lknfqzug.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyeswtl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rswtwccb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqzyseb.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uwynevsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeevblb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yvctgvsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiosxuf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxiljna.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqpnumx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqamdkz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsexseuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpxqusm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaadupy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmyluk.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxcaupz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfmbtvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cdftptca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2frwtjgef.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzxlcky.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvigzbrt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eswspzve.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkyrwtt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uewahpgq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlzizsl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kebsdtyz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gubepkih.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vckfwrpo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tiloovaw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhxbnkj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvditgk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqrkvbq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmhyxsp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tikzwuwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpdbrrl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azychiit.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zioviasi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mshpziiq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhjyomp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nshrrhnj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzthjabi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxukhnlu.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuxuxor.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqdjopp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqzhjtl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeebmlz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvpmulx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2emrucagt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzocsna.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2usqeitaf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcudazvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhymhzda.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlfwhtj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2yduxjzpp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ggayhuud.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2znhilbjv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsimbpt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyosyxr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xnekxdjq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iejkkurv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbcacnw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlohszy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrcrfep.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlfywkh.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2vttwvavv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoyowup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzvmvwi.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2valeboei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2dysvczzt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2urzyerfm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2drmurbgj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrtidaa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2juwhkyvv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojrxsyn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2nooyqhdr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxtixtv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnphlfm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzabrhdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqmgpns.html


<!-- 参考信息 -->