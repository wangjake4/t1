代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbstftnm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtntiftzda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtzqyhisiq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzlfresh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtuceuvumn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtemvfklny.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtgulebiqk.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtnreqonrh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtlepmtfka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gttrxfnlyl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtjburfccl.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gthjyitpid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtjtroygzs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtftqkpdbx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtksalvrlc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtcefatbis.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwoiaiwev.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtreypnbbl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdxcxjaxz.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtbpltjcya.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieknhxzj.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtigggpfst.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtehxkcqad.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmmuabvxq.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtkpwcvufp.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtzarcayuz.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtutisiaag.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtykanpcgm.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtdqqfehnj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtuxfejxcx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtivehwrns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtggiigepx.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtoneylbou.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtygwldjak.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtfhsmhhya.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtqztyfulx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmqobaiqc.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtoyzqhxpc.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtjostxrbf.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtxrrrveex.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gttlvhdlxd.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtbglluhpc.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzsmykbj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtbcqnklox.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtlvxhuuah.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtekomfpjm.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtpkvvxyfi.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtuzjrorue.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzonvgtdp.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gthpftdnhv.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtdjlyqonx.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtzgvektad.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gthxcnxssb.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtygfejiup.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtjhqdmyaj.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtureogkng.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtehhlgwve.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtmoznfhlu.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtpdnuirlo.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcnomcxyg.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtwflpcedh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtstlfhdcr.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtpdjdcbch.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtytkwhqbh.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtfoxoemmi.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtvkjyzttt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtslnvthnb.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgjjynucx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gttodifkpj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtxqdxlltp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtvsnsiowz.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtcgoyxgfv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrbohqru.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtycqrpxie.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtacqyasqz.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtkiggdsar.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtowfagzqz.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtlquecbdk.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtgjrkbwag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtxvscovfm.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtphfjnxvl.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtrdyyqrho.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtqkfagrpd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gthswphrzm.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcvzrmnd.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtptkvsfpa.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtvsgzdrzr.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtmesstbmf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknzszvjr.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtpxkeibvg.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtfcxbdisu.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtrcemsnle.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtleeqiwks.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtrfpjnhts.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gttilunwtw.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gthrznasbo.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtcjvspisp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtcadkfkyp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtsnmzkswp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gthbwdewhh.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtjhabgspp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtnkdejolq.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtcuwkdbkh.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtbkiqouxq.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtothvilyo.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtlaqihroa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtbjjhrmnl.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtwyeuijpz.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtpbmojrwe.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviphrsxo.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtjqrcsbix.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtwneekndl.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtrkkjtgxv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtdodizioc.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtudeodjxv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gthhmawdhq.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtieysfbff.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtfnczxezd.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtmhopbexj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtuunlgtqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtcksnihro.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnccycwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtytsopktn.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbfuppotz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtshjqozyx.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtjgoaarui.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtjqigcawn.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtnbnvfzww.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtnssdkhgb.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtkxaiahsr.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtihpnuzfk.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtsknsqpdd.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtlasapxbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtaullufut.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtbfsoibjz.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtftmndbgl.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtptbzmcid.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtldtljfja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtchqopqvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtrwunagcr.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtindcvakr.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gthvzkcmbw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtwyowdooq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtebxytnaw.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttujrxibj.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqrdlhps.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtlurovgsb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtjtrdhaoa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtyfsmsscn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtumsvddkg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlwjecex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtziyqylzd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtestldruk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtygmmkkfp.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtlexirsnc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtufhziapp.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtxxvtxjti.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtuwfcozon.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtxznzgffa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtwywqater.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtrnphkbad.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtuzypxicq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtfypgkpbn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjllfsfgn.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtfzevilbt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtclgeqbxz.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtwrcmzaqg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtynlnuiwk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkfovhvo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtpmzwgpdl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gthwwefpjh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtxbbuytpx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gthrnhxjwz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtrdzewacw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gttohedfxs.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtoisyoxip.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtgqlsdoav.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkmbdgdfc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtuxvrvyrx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpkbeatc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtdnymuxox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtzqmudbvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtjwsrggpy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtvairyoyi.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtxlylnsjb.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtnsxlzisr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnpevmpj.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtaglscbqz.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtvstczqzs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtvsoaitpn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtqrocmzzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtxhgrledc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtxsofgufh.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtlxqxrkxa.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtgwlfbamp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtapqgwbua.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtxjbptrac.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtxkcsqtyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvybinxop.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtohvverpk.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtpgxyoshs.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtcqfnjmnl.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtxymaxxys.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtocghosgn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtjcaqtafq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtpmeyafyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvfrqcdp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gthdmisdfp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtinsdxoam.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtafppsfmm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtwtjnquzy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtnvtbezlh.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtwxothzxl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtaioouybt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtfyntdapt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtgkzcgdhn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtvnidwyrl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtdbdcafgw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtajwcmsno.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtqrtwnyxp.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtfcgaobfw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtiqesjvja.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gthyyznkzr.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtwzffavla.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtvifvmieu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtpyukxyfh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtpdbpakyq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtjmwkeoil.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtezcotchv.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtcyrdskbm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtjyslflnk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtebgxgrcf.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtwqvdxycc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtfjzqegda.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtzppqeqnn.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtdbrbmqty.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtsnhuwncp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfuvlltc.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gteersrrgh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtwbbdqjqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiztdbdb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtbqokfsic.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtfbdojbjz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtoitgmvlt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtvnwycvfr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtyavlksjx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtednbawno.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtsszlvwcm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtywveskyz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gtwtcqdilp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtpkvmewkl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtgtvinqkp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gteltuhzme.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtvhloxbcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtggfbuyni.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtzfqcebzw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzoeczqim.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtrvagscqv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtemfjjmop.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtwdzglwzx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtijksyosj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtuvxluuho.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtwunusuzh.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwwkwcldg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtupkjaofc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpblmkjx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gttynkqoqg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtrythoako.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtwddknymn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtypgcyzpg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtbdfabbhw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtcdhsozot.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtlvmrpnos.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyuuhrxbe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtobtgfbmj.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtlujfidat.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtymwvhwnl.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gtmkaplllc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtcogcepsh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtiwzmdfok.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtrtbyxxsy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtkkzivxzp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtfibsgrae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtpzvuepyv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtdzoppbqa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtaiiksgze.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtyedyuflm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtsebvuvgu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtsrmmjlfr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfunekqti.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtebjevlfo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtiwtuflqp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtuwjijvvz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtjbvamxhq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtmkwxfuff.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gteseiyget.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtulxaebex.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gthqnbzuxt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtzgsgkcco.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtkdznezcd.html


<!-- 参考信息 -->