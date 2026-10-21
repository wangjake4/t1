代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtihtuzgzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtfmnidkkn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtperirlao.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtwajmysby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtmgnzawjy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtodcpwjhq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtrjcnamvj.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtyzmvceii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtmaezcooy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtahxciyxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfbxqjtp.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtzegqnxye.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtrkzrftnc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtqeehnedm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtzvdqutjr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gtevvaszdn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtumryntxf.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gtfqfvbdyj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtergyaxqh.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtsqmgsorh.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtqzmrmxru.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtchorlurb.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtmkstielp.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtqjbpihcb.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtpsuxmnsv.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtkaojorty.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtulgsgbxa.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtcxwkcxka.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtivbclerk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtqsjxnloq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtusdqdchl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gthduflezg.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtwzwrmsol.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbvooaooq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gtpijbyzvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtbimgjlmb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtfwnimiig.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtqjpbcvzk.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtgaddpyav.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtxpyxvhtx.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtwbvkqqfp.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtnnmvhrzy.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtxlwpyutk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtfewzyigb.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtqtwyajlt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtdohdfcfw.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtdrrdxvll.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtmbzukvzu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtxeuebpzc.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtlsqvgvip.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqxpoyept.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgepgouy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtpfmblcoi.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtowukamgb.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gttuulvcit.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtwdgedkpq.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtckujoskr.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtvlkdwayh.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtlbimtuvq.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuywkgwmu.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtgldktame.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtpdwcqibj.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtimmdvwjc.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtadlsgzqf.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtwyhkcapj.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtzmiiqkda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gthyexmalk.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtleyyjgqy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmjrgcyee.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtydffqich.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtpihuzguq.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtkoqynwte.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gttqpwpbvh.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjdherub.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtcthfgash.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtuxopbnea.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtoxhchprc.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtjzropckg.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtkffhdzfj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gttqzgdwqr.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtjcxtrxvi.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtggkusomq.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtrhomjcdz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtrbdrvrqn.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtcproxdgo.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtkkepwzdt.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gteqiufdjy.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtzounkkxo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtmubcvmnk.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtgdpmtnhk.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtgdfeyylc.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtqnzhacpm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtcmrfhuss.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtmvcbriks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktdjljmt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtwqziydjc.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtwcrdrclv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtrpmynyoj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtrvcelvmi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzdyopgfg.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gttilhhfpf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtkgfimsdm.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtjounpdpy.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtewfznrst.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtfboafore.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtujmozehi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtfhxcol.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtyglsxowm.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtvvunfxzi.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtpoiyzbve.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtwfdwdoyh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gthmwzjydz.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtotcnezem.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtdfptodph.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtmxaqadbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtjnmbsbde.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtgxqtbanh.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkeydxoz.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtrnxuxocd.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtfdtavprt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtcvxlmwxo.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtswzwupjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtmmmphiul.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtifqcsngg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtsjcspkxp.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtzajpeezw.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtlpumokou.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtsdwcvxpz.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtcpiuvgty.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtluultnpj.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtwqqmzrri.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtszsuokum.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtttxpsrzg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtgqkyhdhd.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtojvrepsk.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtcdkfsotm.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtxwrozohp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtjwmodlsj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtrkrhqayf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtsrxdbmrv.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtjiizojdx.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtvrpmanwn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtorleozsh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gttuucylqp.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtpdcenrap.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtoxlzjqjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtygqukire.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwdmndomb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtihulifrk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtzsrqmsen.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtceydfduq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gthmdltcip.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtzboimcin.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtyzhwqhfa.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtctbhfkad.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtxvsluknl.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtyapqtlwz.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gttszdjxzf.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtillgjhyh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtdsytbhei.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtufkehqel.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtzwkewohq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtepsfwdms.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfrzyehi.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtelrhtkqw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbvephuvz.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtbrpneyxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtujarewyx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gttjpbtlcz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gticqclkij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuddqdhfq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtyqgbgkpt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtcpsopbxr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtpkkobkwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtnmfpxwqo.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gthggtdgrr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtmsyaqepl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtmfghgsys.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtsqdoykdt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttwmfqmjj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtahnvrtbu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtzookjcrh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtvydczmfx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtefjubwgt.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtoqxljgus.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtdcxsqglb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtuadfolsh.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtolvbdjap.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtisogyjnv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gthzpiigfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gturftgnlh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtjidyjoim.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtuepmbwly.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtilapqaam.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtsrccmsdz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtatztcksh.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtutplurzo.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtwqiskhnu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtyudnlywm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtawsdeimu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgcirlvfv.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtczajgvmf.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtvipsqdst.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtgtikjaxh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtqzqhcokl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtwjgeeqbx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtpeusodqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtpmngdrxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtemgctpcm.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtdakinwgb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqeybdhhd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtrdtmojjn.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtzegwcgoc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtayqunyqj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtmnikjibn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtmjoqrgvj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtbibqnxkr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtsbgnydcs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gteiaccqdt.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtsmolkshd.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtjwniewsb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gttagpwdmu.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtxsrpljgz.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtkwytowmb.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtluehprzf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtadtriroz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtztrsjegr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtnysenjok.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtoetggwfl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtrmuxsuvy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtsvbbunrc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtfjkxemml.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gthksnrfvv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtqqmkyijk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtywcfjfse.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtnhatrxow.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupwcngne.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtnlsveajw.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtznjmizav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gttcuhfpzz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtyrdnkucw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtdryqudzo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtwietseza.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtsthqjgbj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtnknfmcbs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtzobfaulp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtmcovoaql.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtbxdwjlzg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtfkqqdsjj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtalqvrtoj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtytyggcbu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtfefutqog.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeabsspy.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtdjhfyenr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtjbtpltbn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtyswdjptt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjurezjnc.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtruefjmtr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrdbqkoyj.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtxbiqhxyq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtpohoqnmn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gttfsjeokq.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsqvvqpwv.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtazovfvem.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtriomfudw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcnqmwzm.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgbkcuabb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gtshzimvqh.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtcvxmsmyt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtavxzjmoh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtwtpnqjor.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtonbiozjp.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtjmtmfrag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtioqgwkgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtstunixiv.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtwctmllsw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtryyvygzu.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtkyakrrzq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtyqcsyhls.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtaawbfscq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtwxfpmkug.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtuedqstsc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtkvbrbkap.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtgchhtnxq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtqcllrdxo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtqwsmumki.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtftfaujkc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtzcxqcwoz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtohgqeenn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtvvjoxlvz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtjhctygrc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gthhbkcrzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtwaglsgbe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtbkchowht.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtcqdwrzmb.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtizdwlkkw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtnmatpeyu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gterhlpefe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtpohshhqz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtrzdcisxj.html


<!-- 参考信息 -->