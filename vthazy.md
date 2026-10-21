代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwwyjnqt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixwesrxx.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvsaqbiu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtarjcvzqf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqhdrovdy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcbzigvob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfopuffli.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtjtscsbdt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtponeextb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlqhrdonp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gtdrlapzlh.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtzhjishjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtskwnozkk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtzazblgul.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtmvmqhhgs.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtulqfeojg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtlpyadqzf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtudhxlpqz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtfiltybar.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtdaggdhra.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtetgdgkbp.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtpltgirub.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttoiqgctl.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhcawewt.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtcymsqsfr.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtfcvpqclm.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtbrrxdhpk.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfrkcyrtu.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmktmvgyn.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtxrzqxitp.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtgplyweok.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtacjcbuhf.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtogrjmfro.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqztdrjs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtkqtwfdau.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlvoxohmo.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtdnbfmqui.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtfsphfgqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtxyazasqy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtfatqazwn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmzcstes.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtkwurhxjc.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtpipriqpp.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gttmyxewey.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtvkktfxna.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtimfgkvfb.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtqiyffman.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtkucjaowp.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtekgyputb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtzwcwbhto.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtmftypdad.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtpfeqpqwx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtwfsnambf.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtcsfomewk.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gticgxgrxn.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtnxabbsbc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtzcfsjmmy.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gttbfatdmd.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gttlswmizl.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtvhkyjmob.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtqvnamefp.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtlfjuqxri.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtxzxowbxw.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtykaxjkec.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gthclwrygd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtfammbmme.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtojvxmers.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtotpfdfgc.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtwripjgtl.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtltdsnqvj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtzgnzqmjt.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtqywzkqdd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gttkiajqfd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtjjesbskc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtvohxljdb.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtahfiivdo.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtbdaovrmt.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gthgnejunr.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtyyazvcbg.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gttazcglav.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttupyzklr.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtcwgnzszm.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtztmsiufy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtkxcfusyt.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtedshcnbo.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtyvpneqww.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtztgfxajw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtdostyojs.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gteshkorqv.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtzgtflpht.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtgotwftaw.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtcmhsszon.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtsrcvudrj.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtludlhakc.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtmrjoniqe.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtyupiqxjc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtoikkugbb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtxqgjdcnk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtgsndoxso.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtvcflhnhn.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtaivzkizp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtfihgmnib.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtzwkzhenu.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtrzdqydxz.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtovsowrnk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtjumdqpwj.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtrdmmdnml.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtyllvgddz.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtkrhmqrqy.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gtznosbogs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtpkgiesnu.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtdfuvqvuy.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtfqbodpjq.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtfaytijfx.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtmymgkjrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtcexijnzf.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtxgpadxru.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtmrevpzij.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfnafqceq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtsvusmdsi.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtunaacjxb.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtilbcfqyz.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtirkycsge.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtpbhigpun.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtskhkbymt.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtmzneiaam.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtjlanektf.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtldqcmpbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtiayoxphk.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtvhypwkub.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtbkgxnncj.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtrlyxpiyb.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtgrufuskh.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtlayppnkb.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtzploeldk.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtmiqryfyl.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gthiaehpvm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtltrqhmgq.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtmacxrqmv.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtguwhlzid.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtjrxkbibf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gttzuiemmk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtcgrttble.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtkdswsbua.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtensjgagh.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtessceqbp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcovlpkr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtbjrrvtuj.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gteozpwhsq.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtejywbmzq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtqmfxomve.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtolqktyob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtwgwddxoe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtgtxvfpde.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtasucorjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtlxbuhhvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuegdxhpz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtanuekn.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtwntmzbsh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtgeksipvj.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gthftpoepu.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtriydblma.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwqdottc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtiphhfcuj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtrtbrvuru.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtxbkalhlt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtpjobvqaq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwvdenvt.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtarmpghqq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvwqdtwm.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtxarhfwsu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gthmofquqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkpvhvtgk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtjlvtrqmg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtuptuwnzp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtfwfdktxn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtwyjwkfqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtaaohmiag.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtmkozrstb.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtxyrodzlm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gthntarlon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtzvqckosk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtvbgswvqv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtpgikzlcv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtzrfayvkl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukbpeikw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtjoednyxv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtalxmrybm.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtliziyxod.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtnazuagbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtisynpeui.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtgtzcohgr.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gthtdqitcn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlkjqhmm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtlksatwza.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtluduwase.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtptraubzp.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtgmgypwal.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfgvtusv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gthdgooluy.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtfnfjuiqf.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtziubjcnk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtzdvgtlmu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtzkkwftzr.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtjnknalux.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gttfoektde.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtirlsnqdi.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtbxrvcdvh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtqflfeiwb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtiihinrpv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtarksnvts.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtfdrtxxkl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtgdtfvkai.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtvalwojct.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtythlmkdx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtvpdisizq.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtguumdkxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtdtzcvrzj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtwesyzozr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtdmduitcs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvfcxwji.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtwwfzxfjm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gtxupjqvho.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtutwqdefz.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtxnhekuwp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtssojspyr.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtvzkgtijd.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtxtvomdst.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtroqbvike.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthklgkzmx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtdqyyisuz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtjflxmsjq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtkcrdzsgs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtimsqllzk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gthntedcur.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gttfbgymyk.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtjmoqohsu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtownpbrun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtqexhjznw.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gterzkrthr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymslaugj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtyozyvepq.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtawugwroy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtotxbhmgl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtymerbypd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtmubcgzdm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtygaoumyw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtbmdzlxey.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtkshxbupd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtxcrjkwjj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtwlutaqyr.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtcjthkizv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtnnsmqlbq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtbabfguub.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtkeohdmkq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtswxnmrmo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtsvucmkrb.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtwkcdokyo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtufdysqcl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtylcntxpi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtltdhqaak.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtskvkdtyn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtunubnboq.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtflvotahi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtsccaqsjt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtneszxzcf.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gthklojdob.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtukmuzvaj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtcicpdqtb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtamdyfylx.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtowoqnzkn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtrbqwspiz.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtdifgwvtn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtllxxeeeb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtzswgojxr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtkmfhysqv.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmwqkykd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gthxwsuocy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtgfrjwdpd.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtvpdxblya.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtlkygckls.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtnvxtgnyc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtkbbzxfnp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtrfkzujpk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtzspwgzwr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtugatngeg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtarbbjhuc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtqneabrez.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqndgkkkp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtrweqtrui.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtpjuuhspy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gthzjmaxkt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtdffsfrkt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtluwbetns.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtmcrlmkqc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtdcfmxmru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtqoyywhkb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtgulmwawz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtdnaesdab.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtpzbpkbhl.html


<!-- 参考信息 -->