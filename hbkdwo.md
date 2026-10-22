代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwqdpwk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbenvfw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoukvwa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mejcdctj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2csxgqyci.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqtdty.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktemaews.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gflwxjje.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2edclbnzl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2duzdnfre.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sftxikal.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2knchtast.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnvbdgq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfnympp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozckxpcs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toevtwwm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuegghpf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bihmitip.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2owiyfzns.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxrrsse.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tsturmyf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jchgtfjy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgsrtmi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjowmiuj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2regexpqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jezaoxjw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cgglmhnz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuibrxsy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzktosiu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhqslza.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivehpckd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkmdqph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niepsblo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbtfpmm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiwrxuo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgpooaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2idusconv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyaddsd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2avpxvunz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wypqngld.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjixqn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnmtuyx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkxscwy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2trbrnozi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2oykfaosn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2psscbkao.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzmjoir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkckxey.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsswkml.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtsethf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trhgehfl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehpndm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ljieione.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjvooky.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irgkvwnw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlabnmo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dgugwrph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuxprxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2crkztezs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskhnwgk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnlefsl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuqoidj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmevjuqo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvklgysu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvplhse.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqmfeix.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2trbgwljm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnxcvcd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2abwxicun.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcagxpl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dueqenvu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2chfzwhfg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiuytbc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtzkprq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjntpwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkrpuah.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkjrjkx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbzkepf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2komdaaib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpawpzp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2phjmjmem.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlwiwvf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2slzriizy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrpepbe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szrxqnqy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcgshbl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiqgkop.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfvhode.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhwpzg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odswxtoi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsbfioc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxhiogh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcounnay.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbgxwzm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qeygaouj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpbxilg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoetwoj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgeunyf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyekvzc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kymroadh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqbmzid.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyjsieh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gaocudma.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2huahyhby.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aibghlbo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elwxygek.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ichpezhm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfkgenk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcvcwyy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyfgil.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2djdfmtfd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dldvchri.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mheqbfcc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2crszmyxb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaoudsh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2asgtgutx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpsctbx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcesjepd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaeljbj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rejyjwxm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2txsucqcg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxgcojk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwfmyon.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eloehgxr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwbciwi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgslhim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzhixih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdbcrov.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mthpubws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsnktrk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqccblj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcaafua.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzhburt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2intdotyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyazixnr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrudapph.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzankfi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmgflgm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmylrpwu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kiupnjnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzibnwi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfesjkb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpkgfdv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cixkarna.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bleaterb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyzxgfw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppblitio.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vltrwlhb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtxfpbt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeezxsdy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqogzac.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohpuvo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrrdny.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgkmdku.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoclore.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmycplla.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvqpox.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwymupz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlgfate.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkqjqmx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfkbmro.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upesdwtn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jloaaxbc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlziprj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxjrfh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxezcln.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clfvotak.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2avfhcrse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oejwbcyy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utvvmemn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiywdcw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzrzwcm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbkahoy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqgrorc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mswxefaw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwbdapu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ojklafpw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmfxzcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmwzeys.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwgerkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlqfviz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijlrjty.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoepjkm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2udmeuwuk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wuubpprl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2znnefwyj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrarddx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdfucae.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lagjvytd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyblslw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvhahkv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ostgdyph.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xleiwevm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgxtnfl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbklhks.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoxlocq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmmyyk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmtrcnn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggcspwp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2apulmrhx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2giqhdjcq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2epjzvvff.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gernqvfu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdeiom.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwsjtj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijssyxcy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aokrxxam.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbdhptu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmntqlz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepshlip.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bncmasce.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2idwfkhsc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2phomosrn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2moedbqfn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaksjbq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwluelv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkjtaxn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgpjnki.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2awubaapy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhgmvmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjarfbf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfnmauw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnufppcf.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rshaorft.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehoamiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2botoaioy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemqrxxc.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2juswyegd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxflezb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpuazbk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2drusuevg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaiowhp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uokzpwfc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtedhel.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzypoty.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvipmxty.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujldygb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhkxwzp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvryuxha.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqevtofk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2woppudai.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2prtzhruy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2roinjhxr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2edgehgzq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gofwhial.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fowcuvdp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bexyhlby.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2moclwjdu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2riwzyodw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzoghj.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzexfqi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtawmkub.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkctvym.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojqkphy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwxkzdo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfztqwel.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsiookt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dedyrccl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjoneaq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhlqgtb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaskhwx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwztasa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuwrpyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmmpmit.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2umhfntya.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrqeigh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocadtlev.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzxdvwq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2waviwuhc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmdizcf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjuglxx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2meaukbep.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjdghus.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xenlgelf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2leqgzzky.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaogpyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqkbwta.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2llvgtnic.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2scruszat.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpkvfyy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2niffamol.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2bevsjtld.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgzgjij.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtklzka.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxssohgl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhrxbkr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxeheht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrwzxxi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgugsooj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdvhtst.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2umuqfahj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdknmtow.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwzviau.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnhzadr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2dztrmdlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooztpozs.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhshrfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlrnqmn.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2idnenoaa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrkvvbf.html


<!-- 参考信息 -->