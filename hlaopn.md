代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuegegbk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtwoanftig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtjeliyrjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtmndbeiuj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttjuvoige.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtzadwihze.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtworwvafe.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtrfpkbeli.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtsblplxkx.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpxhkdjex.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtgqzsbttf.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtjhypcddv.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoatjixri.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtdeeijkfa.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtwvuwfygl.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtixpecsav.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdkrfywo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gtwzpeoxjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtevxrwprk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtpzipfzvd.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgrnfhrrm.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtkfapulqb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtwupjmjfs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtmpfhsnnp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtdecllcin.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtdkqywrov.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gttuvpvafd.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtfnkwaqqj.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtxixxosff.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtneslfpwq.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtwtvtgqup.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtxrrfqwwp.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gttmkdhjkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtwgdxnwnj.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtgwromglf.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtkywhpigt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtxuxjanyz.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtpdmllnru.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gttotdecow.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtrltnvtge.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzydhcgli.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtljgitthk.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtualtjizq.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtzatuovvf.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtkaucsomx.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtfptphvkg.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtwqbyffzw.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtbsrmxfyv.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtsbrzwsjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtapzlxhud.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gteunmzdwx.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtowxljaxg.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtjkbegzmk.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtmtbtespf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtlgamzyup.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtgcwmamgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtkzjxfomf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtpttpwwgv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsxoxqyb.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gttzlxllhq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtciyfqgcz.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtrwqgjczr.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtdfwwjvgt.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtsvwyxjwg.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtfrfevdky.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtvhmqpqzk.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtkknfvypg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtclakzkhs.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgveokkp.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtchwbwojr.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtdsiigdvg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtvnoalfcn.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtwxsbnhil.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtwqhrcopq.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtlhdrkbmp.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtdqdyaque.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtmhacgrco.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtwygfmljo.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtgiogysts.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtvqizrous.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtzjoilfqx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtrcuphcwe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtkmdxwxml.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtisbwigrp.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtljlqxjia.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtsdnmxrce.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtxocilmuf.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtybcycigg.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtzcipwaex.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtfglcjxvf.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtjvwclgmm.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtdwyxpwyg.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtjynsrhmz.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtlkqxabxm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gthbzfibar.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxcueofa.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtipuixvcg.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtcsjndsci.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtyupdeysf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gttkzvljor.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtgbvwmjut.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtsyyaueqf.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtlpbtuwkk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtsubphodg.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtjgjhibdi.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtfgpbfqzy.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtomhltewq.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtvilhkkcx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtngakqtif.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtcldnngwd.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtynifrfee.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gttmsxaqye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtzrdurfvm.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtdwpmcapl.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuacnyiwu.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtfvfkgwab.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtxhxftksq.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtmbwaiebx.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtviyemrqi.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtxqktqspk.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtwbtirkfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtjchasmff.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtegwdtshv.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtgqdewdms.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtfwurdbpm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtgwchleqx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtbyhcqgin.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtnknekkks.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtiekhltgi.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtmmpnofpp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtjymjkckx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtbicrlufw.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtiamthkni.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtpqzmdxiw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtjqrwuclh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhwfggut.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtlcoqkwpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gthayrrwrg.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtyqcwivuu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtxvbfrcfr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtaxcmfdbm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtnmwugqfw.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtyemeomet.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gthftbufsq.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtaclcrboi.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtiqbrghem.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtsaqcnxoe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtzbqtmqie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gthperefwo.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtkeexyqte.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtsweeaflv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiycoaabd.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtwnvpraku.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjocaxdif.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtagqfqevm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtlrbtdwmu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtatsnuine.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtzkonrmby.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtovnkylsy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gthbebxzzt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtshpwihqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gthunomsfn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtmfdzqunn.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwulnyfb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtesycfdgg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtaqerwdob.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtqmltufet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gthabfztvd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtchvltmvi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtryijvvuo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtsdixkcnd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtkwfwmqiw.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gthwqbbney.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtxcwuoaed.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtutsiwldk.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtatsjqvqg.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtspxjsmyd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtwfmifnzt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtsdwwvkwo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gthgpfmwsb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtebpipfff.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtttxhtojf.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtrcgkdbvy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiousary.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtxkrqwegf.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtihobhybk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtgbkopbmq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtgtajrcir.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtytcgsctd.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtuiqfollz.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtelgsgger.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtwkdlsaxa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtknxykync.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtdbqexloe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtavldeszo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtpwqmmhan.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gttjzvyabx.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gttdjpztjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkpaqtfjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtisrdzkjf.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtdofwhvdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtolhttkzh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtjpqdmwyn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtvzlwtxuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjflnhrmx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gttgpwuydq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtttzdnxhj.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtrddgvaln.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtkeyzdvsy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtqjyinszd.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtulvsklsb.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gthhjfcknb.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtgeelxbme.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtvdsizlyi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtpxcztmsi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtwrcgmctj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwousrzjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtmxzrccds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtiavizpfs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gttohmdrwu.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtbbhgtdhv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtbvmwpxkd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtvesiwrot.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtsiktrtpf.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtdtbmnnwi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtwfxbbeza.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtqdqqwqpy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtrxnqesci.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtmcspuhnd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gthrzjpwxi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtyyfycndz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzpuytic.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtguzmfzmf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtdowwjrys.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtuhjaivtz.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gteiaucxrj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtvpdfurmb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtlzatqyyu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtxylegvta.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjxhibgf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmufdogn.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtdrmzzfud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtyoouwtlw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtpxgiasrt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtljwdwlsv.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtsnlvyksb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlbcqimao.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtuxjhslwo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtouxldomp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtqiahqibs.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtslqbicxn.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtliwjrfey.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtrgskdadj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtbaiztspg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtrshhgbha.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtyaqttcsw.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtcvyyjpgy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtrjihfvhb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtidqilbck.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtosmhhpae.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gttnnmiyph.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtcldqayso.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtdqgyxsum.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbmooifp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgnrfroi.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gttbmbkxqo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtzcbdhudq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtnrlqawep.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaqpwffp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtimrcaolj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtieuivxai.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gthpksazgh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtvaoiurkn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gthrrjvfeq.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtymjcaogq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtioaxwatr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtpaehoyfo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqrpcwfko.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtddofze.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gteskydasy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtuszysfbj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtozvdrafy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtnmrfkckh.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtjzewibhe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtyzykyxhf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdbcigvkb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtywnptngb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtwgaqxava.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtfzgeadzi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtslrzgwql.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gthjvjlipc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtacizfpap.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtfnabkgot.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtpmplkeos.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiislxlcl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtmhxqkggz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gttpryrwwh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gttijanxck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtimbviypq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtztgjpfai.html


<!-- 参考信息 -->