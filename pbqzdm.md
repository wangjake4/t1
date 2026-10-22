代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtfpovshrg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtbsmdasvc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtjvuatwhj.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwqxvqkkk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtbkimhgaf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtbfzmttzh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtutjxzgcu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnxukrxdu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmcvcrsnm.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzawdcsjz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtrcgnpfnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtekniomys.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjxsirale.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfomquvcn.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtmcqnsynw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqsscsynj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtbxvgykop.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzsrzusvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtdlenzyjh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtsywhbaou.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtioshvpbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwcxqzwlo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gteqxntkko.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtfkfjnzzx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtyvdzwumv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtqpafmkye.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gteyivtvuc.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gteiqgcqmg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtsrnbsuvg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtrhhczkpc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtgzywechw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpmmvggt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyaivzitl.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwbljiqn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtulxptthr.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbhistax.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtpsketitj.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtsezsjmle.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtiffacoxn.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpkfecqyp.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtyrhpqnmm.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtyewrzsfr.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gttauuwpyj.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtrdibkndk.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtvoylccid.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtxikcmtya.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtafrhuihl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gthdncjkcf.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtmxvlwgdd.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtemxvtisk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gtuorqkoof.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gthbdnsrpf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtzgmezhhg.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtgmpshliy.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtfoguqsah.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtjgdkedtw.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtmdtfjxsf.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtknkqsgev.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtzqgbwpbh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtggdrpivc.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtmptdmrod.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtylgltpdj.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtfugbozqu.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtccxdsxzf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtxsjehrut.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtasbxbiws.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbezybwxa.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtmfpuxwhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtnknutuvu.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtydnaiqae.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtsstdyfkz.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtkxjctkop.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtpsrtzmth.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gthbfhnpqi.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtyccohlln.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvorwwbql.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gthztntepx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtoqkvcvlz.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtvqvpkoct.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtchrmxewp.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtwjfwlkox.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtmzjzbduu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtzhrgpwhs.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtzivzmtrf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtbhrriimn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtdrrhdwig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtqzkzbmdu.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtsnanyyis.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtmmncfdip.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxrelwip.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtrvoitfnm.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtmycnrfvd.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtecbrbmyo.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtcgqiwajc.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtbyacycdy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtgdcmeube.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gthdksyoit.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtzrhklhjd.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtlzcdfgum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtcgbtbkch.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwudokznj.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtasmsgsjj.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gteqntxyqj.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxhbfkzn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gticqjyzhy.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtjncukdqz.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gturylxzcm.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtsuerlohu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtwidfotln.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpclchza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtfoyigbho.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwcfusosw.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtpyjcectq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtfvpygfpx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtpnszedke.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtvgaclcjb.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtqxxlyaem.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtsudgjszc.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtaaalmqno.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtnznkvdbm.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtauqasoyu.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gttuskqjht.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gtkfmemrec.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtpviffzhl.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtttegpiqf.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtabvyihkb.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtbeahylyn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtddddkjla.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gttcfnfghf.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtrtwctkvq.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtfjjfnubj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtoyqusvpx.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtcwttjtoy.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtqvnhoxxj.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtzguadjsd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmbasygz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtfrirmwcu.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gttfqhhmkp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwnglrhhm.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtmtocbmee.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gthdbzaxbu.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtoiqhrqel.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtspeuwvue.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtrrlrthsg.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtyosoqpef.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtxcgrzwba.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtffsfzldx.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxhwrqrwz.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtgwkjryxb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtuqtlpmyf.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtcyjmzbhm.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpqgyihi.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtiyrifmmm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtuavtogaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtwvrfkzez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtzzwkeclf.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gthqhizcpc.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtfibixcbm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtqphpckkl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtkzwcrxxq.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtdqjeaigp.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtnjwgzjys.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtzgrdhozn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtxudpcxlc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtektthqah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gttcxqwmuc.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtxjqvhgyy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlmxdipt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtxupusyoi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtpeirtsci.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtwzpgoevk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtdwjusnjf.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtxajxagbp.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtanwchhqy.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtwhjkhiur.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gthunhtglt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtjarsizgq.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtzleqodnb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtkxswismd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrpuhmfrs.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtstmajmjv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtehaxbrfh.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfdspjgr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtutxamscu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtmvyvexod.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtuyrjnjbv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtpdjefuai.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtktfwurbr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtdmapclkb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtrhwyemsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtzvbzbvdj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtadsxoaad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtayhlashg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtkjcjiick.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtqxpvimof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtoitxddep.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtdtdzhtox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtzkmevpvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtnbifgvmw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtsethylxa.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsgawfpm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gthfbbrvoa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtbgpctwrs.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlmmbvlgd.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtfmjdpjan.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtgdcboklk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtmyvmqnqt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtcdpclsvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gthiclfumd.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtsbtsdwgq.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtydskxeuh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtuillktac.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtyafgvpos.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtwsgveump.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtezhwvmzx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtkiiocdiq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtaansxmqb.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtbpueneei.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtslmbshgd.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtjdyxdwmo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtrsqcdluf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtrrnbcyrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlduxqdsh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgpxlrbya.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivznwsbn.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtsvasygaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtumysngte.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gttbudblvt.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtwnwzajng.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtkpldxund.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtlhtiexjv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtedhvxesd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtdikrxigu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtmpqwroaa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtxvbstl.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtqciwkmgp.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwnftysi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtzyfcykhj.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtagkkujol.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtvqupzmpc.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtprfirlit.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtxoharfhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtakonqqqg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtaxalqfig.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtvoutfmco.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtrnclrgkx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtfjgnoxvt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrsyvxfq.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtprvrjgsd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtywydpwfg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtfvretiqy.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsltvtku.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtuegxewwd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtffpdibyj.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtnjxpcjug.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtnfwvgwdw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtbnzbvlqg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gttexixeek.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtmmumbsev.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcuzwcumd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtfkbauvwz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakfsegqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtzmghaxdd.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtlogdvsbn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtdlbowmhp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtgvqyryzr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtsfxfkeoy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtxuqowkll.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdgwmcjr.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtfsfegyzb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtlgnbzvlx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtxnjgkjcv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqjojrwzk.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtqajruzpb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzvmqzrrj.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gteujnwhab.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtrchpeuin.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtznlngeuw.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtgwhfzcxk.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtparfimsg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtrdpovfrs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtqkbcjnki.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtownmlcna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtrportsqj.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtetrtnqwy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtkmsifqbw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtuijjccsr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeonneib.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyegxhfnq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtvydjjmpz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtunfheraw.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gthcbrszyp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtaxjgmdgl.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gtkoslalbu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtlgwrglfc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtrebyoubs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtdvnksuqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtjyuspeas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtzveqlyke.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtkrypwxqv.html


<!-- 参考信息 -->