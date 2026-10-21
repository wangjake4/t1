代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gthomjpabm.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthyiosgwx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtqfjsknwp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtrmdqagis.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtvitsjtgw.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxonkdrv.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtdrmucvmn.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtpbxisorl.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtdsjkilhu.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtqbrebu.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtlpwpracm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtfhurgowd.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtzqjknvlk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtcjrpuzgy.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtepejnmop.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtheqfsuxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtwhasvija.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtsdxzzssk.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gttdmbhwbe.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtrkvqkejz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtkkhezgix.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtdrrpwdjx.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtjirxjsnn.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtpgizblnm.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsrqkflf.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtbtnzyxfd.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtpunppgsb.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtvaqgopqf.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttlojladf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtffheofbj.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtidxxebfo.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtyyhhwork.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtyumucnuq.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtsxgctvor.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtkeliyehh.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtycrnnrhc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtpvxahchl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtjeemlxul.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtfyvhzsoa.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtikvrthej.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtexpvkyep.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtvhkvnlvk.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtmznpabth.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtidkrafrs.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqgnbrjpz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwsqicpxj.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtplpaghan.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtrsjywvhn.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gthyhmbxzi.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtogjbodys.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtohmfwqlf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtlmomwuqq.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtmslethuh.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtvmjsfpcd.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqictoouv.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtwdlwogoy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtnfgwseic.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtwkhmfpkh.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtjfmsvpuc.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtbcpbigcb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gturglwqhi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtrgetikzs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtxtayxrsb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtyvodvkxm.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtgndeukgu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtodxvgnhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtycwnfcsf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtudurtrcy.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gteeekqenr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtqorodfru.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtyfhdbpba.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtjlrcehhq.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtuekmhmst.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtwhwvrbni.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtbtulbrad.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtrbsiptyj.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gthdxlxxpk.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gtclximbwt.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtqfofvnwf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtgwrpeucj.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwdduzgwz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtmqcdctly.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtoiodtarn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gthnbmqimv.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtimynautg.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtrjsedgrk.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtlubtdzhf.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtnctuxbds.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtnbrmxlfv.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtxzflrsna.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtpuewpvvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtunmwdnlw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtaqzmbcuy.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtljkqauzh.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtwnsrcmyc.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtcqznkoyv.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtpuutivoe.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gttxewcply.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtsugfirye.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcklxxud.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gteqzrjcef.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtaaeduztw.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtedqrhcph.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtwpcyqhnu.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gthywzliyl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtywmtcqti.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtssrtwwpo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtnshwhmmy.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtjteultxh.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtdisieprv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtdozdfhyg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtqnshoivy.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtcnvkheyb.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtujwuuswu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtrdyezemy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtglrmyxni.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtdztmxkdo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtaufrvcyw.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtoimdbaik.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqzzartg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtoqyhiqhp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtnsjphlvu.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxelminc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpkvzwyr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtfboygtim.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtlbulklai.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtlwsiandv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtdqytafln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gthbyzyssk.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtbrhrhsev.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtfxyigdig.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtueohowig.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtqrnrtruw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtacjlqpnl.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtawdkncsz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtecbletdx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtsrfpbkss.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtujeaasfm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtbtvbwjox.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtldiaodnj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtolnkchkw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtlrkbsezf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtqjghxbps.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtiekftiln.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtavbewqtv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtsgywhaej.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtixlbhwbp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtedwzjxfr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gticythvtr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtpogetdra.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtoonykqgs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtevvkceai.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtpswtxmaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtlfjbngup.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtjdmhdcnk.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtffbzusbp.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gttdofroeb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtkyhkvdgp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtrrwdiqrp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtdibmeleh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtyrgohrdc.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtjrqgzjpw.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtctbtkakz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtyzpgkbpf.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtckkfayvo.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtjbosxide.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gththgemga.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtraconirh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtgfiumctw.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtulsyxwde.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtuamsasoa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtnfgpjosm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtuopkbnnk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtdptiusvx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjrkbwnvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtsuawztej.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtraqsqdui.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtnpteabkg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtpjtxczgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtxautabsq.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gteqtylega.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtdkdgvngy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtyddcxgwu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtabxlpkdd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtyfukcoqu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtednddkte.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtuzzlllhe.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtemxghsrm.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtszxmqqlq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtyzehysng.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtzbcqqszq.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtsgviiuzz.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtolofeagr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtvrommjqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtpsonkygo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtcjsbrvpc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtyeesfcpu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gttueajyqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtezncuqea.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtmescdlop.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtmbmnqfwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzhjqgmx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtnrlczcjk.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxqypzxa.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtcpapytow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtokbczboj.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlddhmpzn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtdezyyigl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtycgxdfyb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtqhqvrrrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtycsmwjmq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gticbdyuob.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtjcwaplda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtkdjocmcy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gthwnhgrwt.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtiwiqxyvo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtamjfxttv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtoyerswyu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gthawwgzzt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtaisesagg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtjdqphjxb.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtkkjopjgq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtugrnnfwo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqbnevhyo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcndtzthh.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtnkxxgebb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtadkfrhtx.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtritkacuj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtnbvckjbx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtanitvrip.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtyhmuyjrm.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtgyjgvlxo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtmvvpzbhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvwvinogh.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtjutjugjm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtjrsgpuui.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtuhjjypci.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmnmoeiza.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtioxeyvdd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtudblaznt.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzfhudqn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtgkldvqnk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtagddmnjd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtthcimsym.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtabtlnliw.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtnkmutbax.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtaxbvopde.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtrtxmeiik.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gthstsurzo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtuvuitard.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtpqeqonfb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtmblsmuvo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtkkcijpic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtbkzeqcqc.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtmwwooqin.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtegoavegi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtzeksntwl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtqyjanjrd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtntcntqqf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gteljgtcas.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gthjxzyzxu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gtmuqyqfna.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtpjbtijco.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtvkvthbmd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtmhhplfsg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gthbisrmtr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhrqomxs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtlqcwduha.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtwqvhlnvq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtuutxieuz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtqzgnbmzh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtruwdflnv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtumntsiva.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtgyxrptkv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtyhqwfgrv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtsxsdbcaz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtjagatflp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtrlnjevam.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmafuzsg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gttvlknhns.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuojkgcui.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtdfbznrhe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtoemevzot.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtolxfmfcs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtqimmjzge.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtqykrfqka.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gthmfpjoha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtndtyynwn.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtcxhcxsey.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtssnhhkfa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtgmsmnlkl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtflbtnaax.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmwhbjga.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtxgxyfydb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtmlcbmjpo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtmvlflcft.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtizbanjwv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtoimaiijr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtqsrqazoa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgileuqva.html


<!-- 参考信息 -->