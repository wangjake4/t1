代发 wailian999

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtivxhtpwl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtygnwuvyr.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtgkkuqpkw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtavbhrist.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwopwedo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtgaazprpf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gthqfbygul.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkyohgdfz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtxdkwcvrh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtquludqbd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtcbxmriau.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtegtvwrre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyetsvhjl.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsthjvapi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gteetgrcmd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtiuvvuzxt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjgliddql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpnpztigy.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtvgwtgeps.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtevmwaiih.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtvtogracu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtjfrxscyd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuejmdwok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtrvwbxmsc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtybwholfq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtaihtqwez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtpqelnelj.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtykcjhhrm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtlbucrshf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtneyubmwn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtbojvtejo.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtvysibfbu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtzpebpile.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtytkntohv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtujcrlxoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcmzxomo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmykglbuh.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtuvnreqeg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtngyanwpd.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtudvdndqa.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtdcyssjvt.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtchjnkhhw.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtkjqmjcjp.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtojcuszuy.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtaxhqtkwu.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtleabftyl.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtsicgbdmb.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtgdfhkiof.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtdsysbkra.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtfxlasnwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtwltxatep.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gthpzukdvj.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtmeiewqli.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtdruwkzok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtcklmmblj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnemtaulk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtrnqrgmyd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtmwdvmhbn.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimzqqigp.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtmefrpbix.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtjqqovweb.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtotaxxcqj.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtkezmuwaf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtshqfrvdf.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gtjftywkyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtpaeupwmx.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtibzbvbcx.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtaqyncrpg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtvceadwxw.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtsgywcqor.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtijbprfep.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtpwsrveio.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtskfhcgpn.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtoczshbnl.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtbwufanuu.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtqmqmakzk.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtriipggjh.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtngcukvfy.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtjoxegnom.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthaghdbrf.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtzcojrqax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtmnixnewb.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkgccvj.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtgpzfzwkn.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtsrvdcvpt.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gttyfitweg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtyudxnvhw.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtfsmdceru.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjcxgblho.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlmhnozcd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtsefqghdj.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtshuvajek.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtgzbpbohh.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtmajhapeo.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtzqgrhncq.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtvijxschn.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gthkxrkkfz.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtbcqkcpua.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtmsuaswql.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtugugybcv.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtgaohczah.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtzjkcfyan.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtttgxiibk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtrkutwhoi.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtfqonwoem.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtdsqevxjh.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtnpxwzcff.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtulrprxak.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtbaizlqpk.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtadhvpegy.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtzfpswgeb.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtuzexgtoz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtaavcexdt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtjegtnzaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtrmbxffan.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtdgtonvzy.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtkvtfqatg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtqbtvfige.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtixwrezqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gthwspddlb.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtyfijzfsn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtvsxfivhn.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtgcuhfuew.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtmeoqptal.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtwfjpdnkt.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtmdssxlsl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwjkbbeq.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtgsbiccri.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtnuvdjdoq.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtlonmmbyk.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gttcbfuckc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbiogbda.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsesqdyzg.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxvfvtizn.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gttjwnopao.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtpihvvksr.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtvorqhfnw.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtetkmokfi.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxnrlmcm.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtaqzkbjxe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtdxqylxmz.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqkxovtk.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtlkdqdlrs.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gteqqmbzll.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtfoqxjebo.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtfeuktrhr.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtectelotq.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gturhzefiu.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtcyzxbecs.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtykdsjles.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtmtyofyne.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtkcbpzikg.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtnbjquqeb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtlmwzstjk.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtnmqbrvkp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtugrtpwby.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtmbxuwjcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtmoykskhn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gteqaodpsj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtwyownhag.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gttaydoiuv.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtvqrimvni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtnarwffzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtxhtactfs.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjmppgxj.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtzphdwase.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtakgpdygy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtbeuekyqn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtmpwcaimj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtkkpllcnz.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtbsfcyloi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtprvuskhv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtkqbpmixk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtxhsjukxa.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtpezfdqhi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gttmzrsozs.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtybuyrjag.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtixgpswiy.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqyzfrahv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtmpknndur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gttdhkmnis.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gthkgtxsgd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtsngerain.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuqlrchbl.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtkhxisshh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdoauunkn.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtdxsfrmrh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtgyjhbjhv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gthqykfqgt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzrsnabaw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneenqifp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqnbcvok.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtahpxxavx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gtrsbqmkyz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtrlhkqvju.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gttpbbdbcl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtarknotaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtxdkywocl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtmbdboaxf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtvaddhdak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvujndblj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtozrmbxcn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtpznpldcb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyostubar.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbitutxdm.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtmohqxwyu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtrivwdyvo.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtnlyuzsoq.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtcvqdoran.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtjhzhtnvq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtgcudrivl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtfxujiwhd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtffpkwbsf.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtlaygkwqt.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtjefzvmcg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcjsedgsx.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtrrxtrmuq.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gttwkydtid.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyvcmzlrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtrkxalvft.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtoahqudun.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gthtwrummm.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtmnyeyqwg.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtzufjgbgj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gttscahepd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtvpovktpm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtuvzbawmt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtiecfedyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gttulupuvy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtujvbmevi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcehbygna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtrugwxmyl.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtzpeeajyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtzqveuadp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtucfbdygz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtcieovcyy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtpywupyny.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtyhnwowri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtqngerdoi.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtccjaklkk.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtnspighbt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtzrnkcknc.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtpmrbetgu.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqprifuzf.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gteuxxlame.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfnhkofe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtxxajqwew.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtmiaxawvs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gturjqnmuw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtbbqknfya.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gttdvmyonf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtbgxmqaxm.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtydaukumj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtejwbphju.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtfbkvpgbv.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtjltrcmix.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gthufzeykn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtwzatsmxb.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtuqhlidgu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtmzuqhrlr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtsafshfha.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtacummhya.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtfkyspuzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtoidzvdww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoklsdlyd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtgftllikf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtsisxzjpp.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtaorechff.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtwvaowhmt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtvhppifio.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtsigwfkml.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtoawososz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtdrvujcur.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtkinpwwbv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtkjolyqgj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtbhyymlpr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthajtplch.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtfvpvzuru.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtocxdfdvh.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtgmcmlveq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxloggont.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtayrveowe.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtkxislvhg.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gteqipkjpf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtatwxkqkl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtqjpxkejs.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtkizhblcy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtvuhqewgd.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtyjqparzg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gttbpptrze.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtokpbskuo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtxoblwjff.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtuydwpvdu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtwmfalski.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtesqcqmho.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtksxturjl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtztkfqshn.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtxvoclsot.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtumqvrzbb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmzutitq.html


<!-- 参考信息 -->