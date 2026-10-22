代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtpwnfyxkl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtqnsdwfsp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtnygrpakm.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtrywxpiim.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtumjrliyb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtxvkacqht.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gttfcqbkkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtzjylnprd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtupqdecys.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtocmznkik.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnufpfumy.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtmrejacrm.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtlnhfpqwj.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgkcvaura.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtitibrzhj.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtgdcdgmyu.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtybmpjrhp.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtagslvotu.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtjderudba.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtfqnwcnwy.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfzuwzhs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtlbprzlxz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtefnhafjn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyslrqmqk.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtgkdcgajd.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtaqfaplgs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtfmmcorgg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtlbxqlxwl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gtarewzskt.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtdkggftcj.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtpftjtgcv.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtqmpvzijl.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtqsfackha.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtyapgwgoy.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtzostdjkn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtotjxyndl.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtsezzmdjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtmbmoorih.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtisioieih.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtokfvpffo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtabhzovyn.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtushpoujy.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtvasnfhgm.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtcjhlqgwb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtnhfbyrgq.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtjxexcoki.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtpqvracnt.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtqyxlnryh.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtfnhzhows.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtaibdiejk.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbhjnpsa.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtvmzrdzkl.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtukoygets.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gteqdahjzm.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtqjozolfg.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gttjbhcycv.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtfausivdz.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtoyaytojf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtryofmmkb.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtknfuolee.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtljsfndow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtbwbxcdgn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gtddzensmd.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtznblvnlx.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtiejgpyde.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gthjonpuik.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtufaxqvfw.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtoqirosce.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtzlfucqee.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtvacbxxkx.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtctsjifem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtutvawubj.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtqavcvncl.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtjmufljsh.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gtaecykdfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtfvrgqwjp.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtnaftpalm.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtmngdymhr.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtwleghfod.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtyujgajwk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtoizbucgh.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtugfqrglk.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtkeftyhev.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtpoeusfxn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtdyonjqxf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtlxynzlwp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtlwblvyqd.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gttuipypts.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkjfegdyf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtinbrwbxp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtewcqaajn.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gticfyziml.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gthdwvcpqu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtvnbrbkcv.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtjtehzviy.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtblrsfbek.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtamogrviw.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtvmuwodzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtzjhjyfux.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtlpngfchf.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gttrwwnxvo.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtvwqwipfh.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtvpzasymp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtztslqvku.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtoclndnra.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtlpesfkhf.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtqoemglgl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtdpfvrhdk.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtsqijzpzy.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtrbslfjks.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinltnzhu.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtmkkwycyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtsjyexujt.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtnishphbs.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtsngppoqk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtevllpxhg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtwhgmowoh.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtgkzfnkhg.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtqbecyptw.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gthtcwkpkh.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtgiuukdkc.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtawvwzarb.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtloocsoag.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtdsjyendb.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtkjelvmpy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzaudsbf.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtcksrinuw.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvvvwbkn.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtrdrwzwrv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwclelrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtldktuxzr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtngpsfwsv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtgucfrbpe.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtfdmqnuyf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtiwuthzro.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtdojokskb.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtgpxcozrr.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtzwnxpoyn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtfsgzkibh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtqsosamgu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtgvrabfge.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoadqslcu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtecmrjgqt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtojuzfqjy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtbqpkftfo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtwifdnioz.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtmyvwxzji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gttstbxnml.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtlausjqtt.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gthllybqks.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcuukiuok.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtdtkylhgt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtpcgdptbw.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gthbwcnhiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtoufbgebn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypfdswmk.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuupwoboe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthvwdjqig.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtrtghrndv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtbqtqsotv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtvyzzvfxk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtgrivnnck.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtxobnouwu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtutvlvahe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtrapetgin.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtjftltrrp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtyutykabm.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtctsdhqaj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtgmemwkds.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtbklfvfoq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpfbmqtx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtjaegpjnw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtawyfverh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtxoqjvgaf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtwhucttqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtslplsdja.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtryilenxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtfbqrqcez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtxsvdhvdy.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtibmrtfud.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gthbmfdolz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gteoddwjtn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtsmrlteql.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gthhecucla.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtdfoemdkt.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtqqqzndae.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdnkducw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtkmhcaquc.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtwtwvkejb.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtazneikoe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtygkujqfn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtsejiheie.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuejansjq.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtnghoxrsc.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtssmntszc.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtdhqodivy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtmcdajbkd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwyceaupk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtivfgqkop.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwaxsiccf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtbgkdlhpq.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtspsqakiv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtwfbdcush.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gthqrxybec.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtknwmbdwd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtmibakmdc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtzzhmdvdw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtkyflqzxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtmsnofooi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtpgthyalu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gtdsgketdl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtpbhdqobw.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtukjcjygw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtvlikhnba.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gttqcjswto.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtuyzbwldj.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gthjwwufln.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtmcsdmecr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtytcetdbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtdddhbhpg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtbtgtubvf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtfhhilkyo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtifyvryhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtfvjbsojo.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtegzewaxi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoliwwlj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtzudvzyyu.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtfzvganzz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklnuecig.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gteubhlpdk.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtaeopvutz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtiadjlzkr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtbwkzipse.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtevvrlpnh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtbhpivtcz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbtkrney.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtrceexawk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtkzhprprp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtksgmrtrk.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtffcziebx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtldfzfubi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtoliwwyku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpskswrk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtlfitoonn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtwfxnszct.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtharvmupi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtdcwbwzxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtwpoeqvqc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkrvhzqt.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtabpbmgtw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gturuhdrds.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtjqugfgkr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtafhyidmd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtteqwfnsf.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtffxkbdnt.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpgsziph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtyvlyjxud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtuoqfsdqr.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtjovjxfpc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoalokah.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtodyeeksu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtvsfibawb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtedjiuwye.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gthztfuuuk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtimhcxhyd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtraubxfnv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzxbohmq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gthdgbgdfd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtzxvmkgch.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtdgwstkrs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtvoxsyenv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtveiechrq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtkkxzdkyu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtqencpctt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtvunwsyvl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtluqqerjm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtnsehimed.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtjezuaita.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtgmemzifl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtcigbhjvt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtylqkvgid.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtgaphfkzg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtusxesljp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtqhcwdmfc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtltzvjpmp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkdmougco.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosncmcke.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtsqthoelc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtzvqeazug.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtxgwizdak.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtakofomrp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtjqlktogd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtssddrxuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtruuvcuaz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtggrnbxwa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadcycmmc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtekhmfjtg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtzeqfsfww.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtnbyaywtg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtjizsopaj.html


<!-- 参考信息 -->