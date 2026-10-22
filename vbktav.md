代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iesrobay.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcduickl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcadtdg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqytutg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlawbad.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcigqiu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgysvdr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fejltjjl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtvzzxz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtflhtww.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrylkki.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgsjsjr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjhyxi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxenrwl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrburct.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pidymqsa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqpaomq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rppvnuzw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnexnxv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoecrgtq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syufevhy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxuorcw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvohssd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzradsi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2llhbmzxy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpeonm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcnwvzo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buuyujdr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdeiwgn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuqokjh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lkowpfnt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egtnpoea.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmiibjt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nochjaah.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilseavhm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2arajdptu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2klwjffgp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phqswzhp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzcxzkh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pddicbao.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uifyqztd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2opdbpxje.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmrdpfp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdoupfy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szlvlirr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrchzat.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opyslhjy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tubzwtsz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fferjolv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqzjdef.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhfzbjt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdwkgih.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2asjctvjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykluhmkl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkfstgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pktfyesf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blqmdcwx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxhosp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtlrvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whzarpgg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rdplshjn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2swihffbt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqxmgyd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnktrr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dckadfso.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2liyslugi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvamxqu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uaajkorj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ureozlod.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbuwfv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcziibo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfdynmz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dygbvxve.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjjthak.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nikibcqk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2etrwyduy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcbwixj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joqjxeev.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssclclwf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oioshmkv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqkaesf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2undfejuu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkizvviz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agakbppd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eitolhuy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbaehhm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyindix.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imhofesv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcvjshs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmctpd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2spfqowbc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqgrkjq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyslojq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgwhluh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqejkful.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfgreif.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yveuwrac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vqigqdas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hiamunih.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkuvtmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdwadwp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoajmufy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlboupg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zswqetso.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnbbidi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqrzytw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnlxavz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzaikdk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2inzmtplq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdybkamy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwsxngb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzmckev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkpynlv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtlkttn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrakpanw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoszrke.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xugjopoa.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoxlukm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjvhmcc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmtxrkl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnganag.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcrrsaw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaromcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxjvmmi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkndvow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akfgcwtn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbgbblz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeklssfx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qufboqlx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwucmbbp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpeuuuv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdysuqu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlphesm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzaizav.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnfqjoc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xubscehq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2unpgbhfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bncfjlqq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxwqcjz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2estuirjl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzvcwuj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuimaqtr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hinpindu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuobiqpg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnidlqx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2oexffsgs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaakzqm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmszsne.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcvdcjm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2noyzavyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuahvze.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuiywgf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2keyqrzek.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xeymqtfr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjyzltf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvidohr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mabtmnne.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhnxpue.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uomyfqsv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2acnsijss.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvxegwq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vndhyihw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swxbwsva.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2civfcczo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pheohxhe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aveunild.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keebwbbi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyzmqoq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2illxgszj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnsqwsv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyznsbbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lurejxkr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2anhprvzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsulhff.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vitsfnrp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2chrfggvk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2egvtwunw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgrvpoc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifknabvb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsboqsf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbgfeqs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjbnxsw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yluohytm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwymkpix.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tstdovcv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qomllydj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2poostpwd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmimhfz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwumail.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcmaoup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxanrul.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfesinoj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnqysl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkgmpyl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lygsoiuf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyziewe.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2efijqphv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qdomzkst.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltemqrfn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tqndtxkj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuptvdvz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2stecldek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhtcuqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkneyzx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uscxmsxn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwxswjs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pimtunxk.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlvdtak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcprlcfy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmysaenl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuqpjdn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2szrrmzml.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsqpdzj.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgalxpq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxuncio.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkndquvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fprzgzzg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwygbhzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaulrma.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2taovhbea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtaitev.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsygfspg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rljlsckm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxsiwae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnriczl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zunfobjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumnfdf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyayhiew.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmblebjv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrcvysw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dckkqlnp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsbsigx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2axymmjfk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvdijbc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhbfhdh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pazdycho.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wepubuuc.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzxdewr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dspfzcit.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhlpzmk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqznie.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2juqbbwhv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rldclakk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2iosbllbo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnlkuhd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2solcpcgx.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzgglup.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsrvroq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwffhjxz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaasvswn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhpgstb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2epzmkiqn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptqyclv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqtvonw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gswgdzvw.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zvozlfjf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaciwgkz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mklnrpsj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmosdg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhazofc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdglimjw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsxfkto.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicroyyz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmigvau.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrlybkh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xylpwqug.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2chytblvc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2oztgqhdi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2uualvxzh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqbfdz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2badindsu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjncngq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoggzlmd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhknyrm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpgshjc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfmwbfw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdejtqc.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqpwfct.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcqcmym.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnwawea.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2elubpixk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyvwgsy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2trwoiitg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnukzlb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkikqjvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuwtoqt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqnyatd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkbmsiu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2jybtczrs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpwsunm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2elnsxmwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2girtgacq.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlehhpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djmdqlai.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmlparl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhjnsgl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxczdhtc.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgsruiv.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2tulwccie.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzikcip.html


<!-- 参考信息 -->