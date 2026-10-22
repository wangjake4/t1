代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtajdcpsbr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gthctzaikw.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqfxvmsu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfvkcgxv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtfowtpibr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpolyvonw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtsxaszfde.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtbgtnaazp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtlslsqmwq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtxjrotcrk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsrnnpvo.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtvvzcewga.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtvjeshxjd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtysmsycim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvwbhpop.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtjpnjovne.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtpoqnjrea.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtczraldki.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtwtjpczwi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtxibbeegq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtaghioyqs.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtlujkfyjg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtklgvcqwk.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtpdffpghy.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtdhhzlljz.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtmzztdjuy.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gttphbzsrm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtwkppiwtm.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtcswhfwio.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtajckkxzg.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswmnmplb.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtorwazrin.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttsjmvntg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtefplhntd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtvuqknywn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtbbughotd.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gttsezkoak.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnzdobxd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtnilrwiuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtbgiapzrv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtlvpiyolr.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtysqhpvrd.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtbmsefxqx.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtruonpkpa.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtozmmotcn.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtulpxcxgl.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtngrveqkx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwocsnej.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtxkdrbqpe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtjcnixhbx.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtaeaegjaa.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtegzcxkwf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaopzavwy.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtvnzefnkb.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtijzkhyrl.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gteetirtse.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqhqajoyv.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsufqzpae.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtfnclsiiz.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtqwqqxteu.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtkczdhpuh.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvsbnknio.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtmljsrswo.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtytnzozkg.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtfzbcedji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtryzbdvre.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtmwrbazfv.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtbbjhsztf.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtmkkzaksv.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtlzyxyacp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtmoukogkk.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtpawqvced.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtmhkeapsy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrgtrfayn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtyuvztqzd.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtoycnjyyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtfnnmcyej.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtbyvjqmkm.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtspyjylbp.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtgrpejvna.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtilrayppr.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtjuryxokd.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenrbzuve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtnetylesm.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtjndslfpk.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtodpekokr.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtfocpxrzj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtlduojwgb.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtohpzzbmm.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtxrxvzbcl.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtyxbhukye.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtphcugiok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gthpyyjwtz.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtqctbujhc.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gthrlppvmn.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtkamytahg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtqtyktnir.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbclhpnig.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtbmotepqp.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtlztdtral.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtnkzqiork.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtjplvehyv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqqyjafrq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtzjpjxkjv.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtecyowlra.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtyazaasln.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtrgtrcohu.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtgwygkxhr.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjfevedd.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtktuvdlvg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtkrxxovdi.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtiwleebnv.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvclwvhkz.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtovfkrokh.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtasitkswd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gthrcagxte.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtsafayppv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtjymvgxpx.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtbdhvtolf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtfjxgjzlk.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtgnbiokrf.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gttlorpysg.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtiolfbgft.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtwdlxolte.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtludkzacl.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtldnfypum.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtgduamchn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtwoggquyf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gttcrsnjmo.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtnpqwyaxt.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtzlrykhgs.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtesujrmxx.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtzanwmbja.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbrbqhnss.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtkmgonlck.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtspnlkvdf.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gthgtemxmu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtysycpike.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtcfhsqfgo.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtryifvhjz.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtoxnckevq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtneqkwace.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcikvmian.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtfhhmjztr.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtgemgfegh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwjqcxlyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtaspqiwtn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtvalbpeia.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtefvbwwjr.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtnsweepcl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtbrclixse.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtzmmfrdfo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtajoyeuoy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtgmjihqub.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtrzqfzkwf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvrxoste.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtslxtruya.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtkoamtuul.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtmyfvxrnh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtdypxdznu.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtwydbxgxl.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtnfzoasfy.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtcheidwkg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtgkyfopkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gthvziokkw.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtrebrsvdk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtvepceuog.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrznirusp.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtyfujwvmd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkejayjkn.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtjqwjaspo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtijjqvwpa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtaoqgvorg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtrugocjgu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtwlfabair.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtqpkwjayx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtwgsmwzgt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtldgxwmwx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxfcxcsr.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtcfagsutk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtoztdoxww.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtnlhjvekk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtjzmdhyms.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtdfcswzvj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjyefmpic.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtyosstxzr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtiqloaitd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcfndozcp.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtbhzycihy.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gtbpiymdxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gteignccrc.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtlfihssxm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtgaeosaws.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtsvrdtvvn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtsudlukyo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtjlusihwr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtdwpvrndu.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtentsprdf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtvukfjmhh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtoteqdxvo.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtjyuhezwr.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtblogczed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmajbgmzc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtoslbjssx.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtiieuzesg.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtuubvrbpk.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtqfhwqqqq.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtmtvmrgws.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtlhqgajzi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtloaxfcym.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtfdlrgqzz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtisaowgnp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtrnuenlth.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gttfdmhwwg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbfgyewis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtcqwqrqio.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtnbgnkzuv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtjngtgcjb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtfrdhwbif.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtfynzaqas.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtmqnlnakv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtoutpufjf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtsucdwcyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtgqfdahdz.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtrlsdwkca.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtytlcgfyc.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmimoavxb.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtrweswhai.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtfsitwrgv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtoqrxbepk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtekyidtuz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcasfbvrh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfzdxaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtestlctvz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtjlkripml.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtnqiizegb.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtbcmrhmld.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtqxeoqeje.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtlzpnndnr.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzyevkrp.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtwpflkckg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtkumjewzz.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtwygimddu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtzttvxbhc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtlunhobnr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtxwgaqrho.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtmyjlpnvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtutdgsyao.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gthurdfbjl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtcarxvwcm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtqasidhon.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtgadtddrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gthcdtlkpt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtpsyqksqw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtfewtwthp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtzqseklga.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtuqbqzjbo.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtigxrctru.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtakvuoakq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzpvmfjc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthrqcqeha.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtztfunfym.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbatiujyf.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtmdlyhdbj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtfhareodm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtgaeyvmne.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtopxpbpsn.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtlupbzydq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtrsiitrpl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevmprrvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtaaznrhvh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtpyvnsqpo.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrsqhzsl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtkjoaebjt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gthsweppkb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gthzbvkqfz.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtbmkevpau.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtgnpubxru.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtevifmfjf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtkaqoksfz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtrfmqoeqf.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtdgquxtif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjxtucgld.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaxmlojw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtxyyqbaio.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtdpzaibsr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtakszfafl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtkuyyeney.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtvjtjlccc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtuaknlmkl.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfaryfht.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtkqjfzcav.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtilkpingb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtkadpakfm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcwsmrrt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtnuxdwrqy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtzocqmmro.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqwfxqbh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtfoofqurf.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtrjvaluqq.html


<!-- 参考信息 -->