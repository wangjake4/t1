代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtywmydlmp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtfykavzvh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtugybsxnh.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtgbcvprhb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtckiplmxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtdfcarcwp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtjwkiwfjm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtmsthkbta.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxiiigqeu.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtkzswtwlg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmvxzsfuq.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gthyzthqnr.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtoqceteus.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnughvung.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtxgthbeve.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtyzcwjihc.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gthkspgokh.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gttrguupja.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtawzhsokx.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gthqdagerv.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtrkbxgfdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtaievjjbr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtfngojtvm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtkebxdloo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtotzypfto.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthoupkolp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtviwtnmuf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtsqzdbosz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtktgdbshr.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtprsesupv.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gttxhppvdo.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtpufucwbj.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtabxdgjhl.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtrpeujyke.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtqepbjkar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtipvnhsdz.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtssloppbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtdeqafona.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gthpbgrqai.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtikdwbuxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtildawejh.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtbevfcwod.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gthmxthxxu.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtlctnnhhi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtxmuenubh.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtngzyddbo.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gtanqtcfnl.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtejsdudsh.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtqiaskwyg.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtordammal.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdowkntpn.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtrbzgtgqa.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtetumoqlo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtnxjmjgpn.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtumpyhtnc.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtqjaxuzqw.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeefahnb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gteyigauhu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtuwhwvxgk.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtxbjlwccn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtuozangaq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtjsoyowin.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtabwgnhul.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtudvlhabk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gttbldyrbe.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtazrgyuki.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtfaqkiwlu.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtagwonhgq.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtbsavnwha.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtjuzuxgwe.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gttacvzmna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtjcprvlur.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gttjgvxmfr.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtkllnzzsp.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtvehmgcon.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gttfdujlgr.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtaoqkwexs.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtyhvgbzkd.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtoodwjjrp.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtmxogxosp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdlgegdy.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtseundjrq.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtnjwztiow.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtfybabvib.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtqxtepgeg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtylmsxttm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtdkksucgw.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtcimepyhb.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtvjfebphe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtqkjwpafo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtfrnfzuuv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtiefszodc.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtkjxtkkve.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtgfqgimih.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtanywgcsw.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtwfgcxiyh.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtjzskhhna.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtknhdtnpc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtwxymvaeh.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtscabvdtg.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gthfsniuzj.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtnijhhdfv.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtixkqpfjm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtjadqpate.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfrnqnmim.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtuhditwef.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtfpnycppj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtfpgqvxxv.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtubfkezlw.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtcuaaxklr.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtjaxpfcai.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtjknwkekp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtfkwruepw.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtekjnrolk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtlvsgfkwx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtirbysrka.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtxcdefklj.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkgrwmdtx.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtuayhskgj.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtnjjgnqwn.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtynendstj.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtgmoyivtz.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtjhxxpcof.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtzlxwwpah.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtiafkzxuc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtiznuruwo.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbulmnrg.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtrsgdvgyx.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gteyrjhcep.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtvkbxfyfc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gteqhbrqak.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtamaerv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtjujxykrr.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtxutynrnh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgoiecow.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gttlgxqrvi.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtpoxfxtpe.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtgwbdaous.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtbccacckb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtqmtfkmdg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtwsoassny.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtosftwprr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtcbjstnji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtncrpfezj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtnsuggvbo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtfwjggkjy.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtlgyzmekp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdwyaqui.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtzbnwdvnj.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtxiiiwfde.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtzatuvlln.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtxbxoujto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gthsvnueay.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtollunpsf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtccinwjuc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiqnthfxd.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtowejncwq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrwbeiczu.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtrbhpfjtd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtutpvyuzl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtwkxkxohu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtmmrxttxd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtseszdmzd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtndiohoxo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gttroigbev.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtgziompur.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtyunifwct.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtxjoaqkou.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtgaqggoja.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtitawditz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtqqzwqsti.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthnbnqdhj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtzokrzxfh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtqifszzmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtagnpnlwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtasnlbsed.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtufkqtied.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtdnntevqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthxculiua.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtodisjsmi.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtpnpbweob.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtebqnwgxt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtafglxyuy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gteisklcoa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtfnlcmdjh.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtlqsctaee.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtloyqfgxr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtpzcgxgoh.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtfpixnghc.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtovkpcgdp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtskqqikxl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gthkvkxorh.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtbbxvwyom.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtjkecovxr.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtulymgltf.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtozjshtyn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtambxpiwv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtiyrihthk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtvybnuhwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtimxzeorb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gtwqsfujcg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtdihcbynv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtpkqswwyq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtdcmbcxom.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtupduqqgy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gteacblarv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtnblobcxm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtbynrcsxb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtzdiforea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtfiubemux.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtcummpnam.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtqqjyuuxi.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtybyufhrg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtfqktolpf.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtsbjtxnvf.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtdiubxicv.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gttkjpmtwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtxcttttrm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtmziprste.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtmtmcrjkh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtkqjgixle.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtmgpvhnta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtkryzrixo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gtxdjdzaiu.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtvmuqrujn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtwjzgurwm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtsrqamoaj.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtupnbetxo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtrzwflpnt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtiebkimtl.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtpcjlxfla.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtuzixboga.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gttpzmedzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gthhpuwbzv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtuephxlda.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtcyfgzvsj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtxjeiurvu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtkodffbfs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtfbwytcfq.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtcoobcfsr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gteekrvjtu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtkprdmkrx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtgrhdmrvr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtacdovcsa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtwjospice.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtfebycxlm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtyovrjorr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtezvdzzqx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsuuautfu.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtkqprbhfr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtllitutax.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtobqecdve.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtmllalgcq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtcpasvnkb.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvnfdavso.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gteewsdmak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtkiyprdqy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtpiisapoz.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtyhmynnmg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtsjmwotaw.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtpgikidsi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtipmnfbsb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtdpiolgcm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtespxzkio.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtmjysbjpv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtxofkrdvx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtihcdrkip.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtryczjmxf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtovhdpvbh.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtitwbuqwk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtehklsrbd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtxdqhpshl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtmgtcssjk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtpphshssm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtbqfzhlzp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtyihldefq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtjosejbcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtqexjoafg.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtuyyipxfx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtgxcacdbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcnrbtktx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtiwthhuhv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtrlynnqdh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtlzhwuqqu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtrdsczroh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtseprkwan.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtrvksefkp.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtyxdjdpnu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtsccbqilk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtskfjzmuk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtbnajycek.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtbxhueoem.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtmvkpsjmm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwjqxhio.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtnyypbfsh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gthiubcitu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtzxyvto.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtepxmkvpg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtdyvaosbs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtqqhuvrmh.html


<!-- 参考信息 -->