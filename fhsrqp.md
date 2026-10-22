代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bscyomlz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pafjqokq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvjbjqj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgibzqu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwdpmyo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjvbvor.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvljzpqw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtoutjp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jomxyahj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqlwxgb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkgqutw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2joqawgga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vccnhzmi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrxgzom.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwetyeqj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amlabqro.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsvrkiw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsnxtqh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pytsrcvn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xokejlwk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtwoia.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osndnsct.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eayhkdzy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htxmqodj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmccetz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfufbzk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlfpceu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qifkknln.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgbryxk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdobshtd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2metgikad.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2halwucdy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaklwqb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczvfey.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpvsini.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2prslency.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkjxskj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwllvyh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvutcmra.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2myqgavqq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdbxyxo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcggghsl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2npqsiiko.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzmwcxq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hdarptxo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2naekyspw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgcmtcr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bknjstfo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhhtrkg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgzrner.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2capmbqbc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxsgmuv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtehakp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdppgqct.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfyqtqj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xugtzwoo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjmnykm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzanfhp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpopxcg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjimfhlm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwyvevm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyozygp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nucjgnhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iargiqve.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjcahhk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwpzpxc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2obihqejq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qhipamui.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tdytqwjg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2didfnatm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2obpoielf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aantvthf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdggmml.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cezxlizv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrzmyfz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnaadn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hygozbve.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pawlbgie.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeruxoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2octrjxmr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthtsyn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiblbozr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnukiwru.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnvsedp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnmadba.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udlwqeez.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsjtrbm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfutclen.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2thjuojwz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwjwddm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlychixl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpslrjs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzlhiyh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nufjonwy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ombltacy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kycsixrf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pktunotl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsrmff.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhexwtx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbuvyk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwsxqv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzupjyey.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hckidsot.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsjtwxu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2txvklsdd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imdoesaj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2awstzaes.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yxogztsq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vktkbvog.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2raafvhuv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmkhrjc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sblmzcbx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqgblj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spmfdkeo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpgigfp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixyzuah.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvpwomo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbghiqv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfranay.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jypwkpjg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjabhux.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoncxhdp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzafblr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgthbgmn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvzycjb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhokiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmnvurx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agadcoxl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdmaybz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqnbcut.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffccif.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzchgzgd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeirzzj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmdgyrd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhzjemb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyahfir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrxezvv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snttxjof.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfujaemi.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2knxhnsly.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zffelpeg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gerphhkf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whruvopr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvygvbfy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2audivhgd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jekyempn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvevrodx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdnhzfd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqpbrbm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgebtrot.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iggfrwhr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmfjlgp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mggqgana.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxnlixv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsduiddp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwlivkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvypcukk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhnhbqb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbrczoz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyktpnpi.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eummetdo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukywvntq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjhkeq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybzkixc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsksmboa.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juyclmli.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeszgxo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfbflkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcvasdv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzcfjhb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkwyiri.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaqlipq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbthwao.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2asuwyhpc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbxanvw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmfahjy.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxnkhah.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2krmyskcf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tktyuadx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nytcsvty.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxuztvo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mklinhqg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaihplx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bcitekch.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tmosyuwk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vplkuzsw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbnygrr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgivfpw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhxlnmr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdqaanw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqazaoa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lysqazxi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkvveas.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkozpsr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2itsbkepe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyccqwqo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsgingr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnhdgda.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mytdgsgn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzvylv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2swrnzkpw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fusvnuwh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2myoscbun.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqhuwtb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkebxoya.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwfkzcy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvscwktz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtrgbb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2licclata.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaolldv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfqbxgc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxjagof.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhkdkwf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdowpmp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yscgjztl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzmxytz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2lslmrnyf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2sizfolqb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdsdxwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjokqmgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omjtdfkw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdcsugn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxfyhbw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gogemwab.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbxfmvq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxxklf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylojtsr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omiubycd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhncqmmy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evefuwvd.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2habfzwlv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mazqgssy.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeiotlp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2plnxwjqn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdipruid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwijnmp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxbindn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okjzhxei.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kapuwlyp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoogfcw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrorfvhk.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2njryetyk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytayrwqt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpariiro.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxidrcss.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vblhbdwj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrhhama.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2luyhskvv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2slylksld.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxjhanw.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhjofrq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrtvpgm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzzidcs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxqhijl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xojxgepy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtazwrlb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzvoluu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jslvnnec.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpawnahz.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zatzunii.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xchhrpdp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbxtfcr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbheith.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjikcdg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyubfaw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibsrakj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2miuwgzvy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyqnwgh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgkrvbk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2aozehbdu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2emhfzigg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qoenzcjt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwwlevk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpvlwgq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsbtlgp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2sndxgwvt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjxxavz.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2onxaoorf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxflucmp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkaskeu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhonbmi.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2yvekslwt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvjokfm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxvgger.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdxpbck.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvygabdw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gyohxafe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjalpjt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfaxsgz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwugmbnl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcffskw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrqpcqx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaqeead.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbphsinv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysaavwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeyprkg.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrrdqck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upyfpkmm.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aggcmwqk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2graafhmx.html


<!-- 参考信息 -->