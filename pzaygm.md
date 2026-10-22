代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byfujlsh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwqilzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsbrbtz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnyptzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aelhpkcq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbmdsyf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewunlcki.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vbelarrg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxeeuq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wylhmhzo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldadimfk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxoqgqm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poyjfpff.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzqdtoq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdczqrfs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leuwunfp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfvmkby.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nieyolcb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiqltoq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avlltvpn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyxlndz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpmrqra.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cflmjmvw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnptqfk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bskdvfdh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fscogqfk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtnvefc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2egtikitt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsjvwp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dosvqbdi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2voywashd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2peusozaj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfwvcmy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lttnbkfs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkrlpmn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvfcoag.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tktilgfn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzxllki.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwkyygf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsockcgo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtfrpbx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2byqlufpq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lauifvnn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pipmkcfv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqyrovq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefcqem.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwgxryt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervzyaqa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqytwir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxozari.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2esiovprp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsolqwhe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxdpctp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2svukqxso.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vxatohwm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqqosrx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fojacjwh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qvebicep.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2conardcd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqgayhe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ttozflrz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2phydrazx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzjrha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwrnxck.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caqaqghv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auqjfbfh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dppyspey.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2efgpvtkx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ponmzvrn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdaezfg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rznuvkzc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfmyquy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koljxsol.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnimtmgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elgwsuft.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcckdum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkskyr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2regxwomx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2usuhzfit.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhiyudz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvqmfem.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqowas.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2orypkcdq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjoycxl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlfhlfo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxtcldd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuocjoa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmqbafn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfdyapt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwemom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvybvm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsrhwlr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qopzrqbo.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwvqjy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycqbdew.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdafpv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdjiasw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqoutfi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2llseibpq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupumqjj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uufqfncb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxghseqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmesfjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgsaiyo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wrayvmfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefsvckt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxgwkz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwynith.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjifweis.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2amtzcvxd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxrifrk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzdytmh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uadaejzk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvzhutz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdvpnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjewyuka.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ogklthwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsohbcu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnnzrcy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqmxihm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldojrcfs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyenlpyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuurdtex.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzvxqdb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yupvxupw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euioonsd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drrpwqpz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ivikikev.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkfmyps.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzpwkxo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjajpuy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycczizfn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trmifnxu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2owsmglwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsibccvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyqidjt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aivlfnvq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkmkgby.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnjyfke.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2enznailc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdycptjk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmskfbnf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxueizyz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tquegkbe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyuvxvr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgzjmor.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2iglfnkqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yycpwcrd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grmyaxxt.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvxtbmh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mocxdyrs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaqmnhg.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utrxinfu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcpfbjj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqkpsgg.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vurawcyn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgetowyw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udjpnpcg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cybhqiuk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxpxbg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrufqiof.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2szpioqes.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvppdd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2oheedrkm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bqduxbzx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmknawzw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vomdggus.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kgogngps.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjtezba.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfllfxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnwntnp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2knrmilee.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2npyrjrwm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyixoha.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmdszej.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqfyjqf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2obkpmuha.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfpkhdp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpytkxqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aswtbsae.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rudkxsqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jspzxyju.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxylhhly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hynvnfua.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvaywf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxspgjo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2usqkpzgf.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgygrud.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhnplmn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hatignnz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jstazjnj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbaztkf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uppodvnz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjgatgd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmpbnul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiilsibj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2laonyhyo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtuntuy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2upnhqtep.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhwaflp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiyslbn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2flyopofb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsvyehk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2adzaxapf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwduvri.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkcjnce.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbczwgv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uodyzhvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagnvbf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qulfnkba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvibtokv.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqavheuw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhydtuo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aktpjoeg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdcrzus.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nprqgwyx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfehmxo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpxilsc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmxbci.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgahejp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2utoztszr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsnumap.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhmluzi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcvkmgw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmpivij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxihhxk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xogihuto.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsakqvmb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkuxgpv.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xsomqafn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfopcpa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsagospo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcrdnsn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zldvbvyw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbabiwq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2muvgpdkg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2thgxcleq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2shltvfvr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khxlrovu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfbinac.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyaynqr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2stqbpjrc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzdcpce.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dddollvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nquyjxop.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqugngw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jreibdkq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2okkfbkoc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovbuwzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2keenhycn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmdqprr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pecodyci.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqvkjcf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpguckwv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2quewmdln.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvxawy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2wonrwzuy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2llojmkdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2laxbvcbz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2fmusulnz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsezlzv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlwtwfe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2kspjknfb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2llbypxho.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjlmojd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbrowhn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvnlhih.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxvuyqb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2yatatzoz.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2lqngpayo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjbuiut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmsqejq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiffsxa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2xklitsgx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjsamzt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2heunzzbe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ailvkimx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqnuvml.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmedocf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuzvwyw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpcydlk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpulaymc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkngnppn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqtvike.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2swtngrfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivznbare.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2crgrxjoz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2omutlhlu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2lazchrvk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyeulqb.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wirrxwck.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2bddlqauv.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkolosuk.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2ztszkais.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2vjevonhv.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrrvcvb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2grcnfmrx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2islbmfpu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpnzhgf.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjotxel.html


<!-- 参考信息 -->