代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmvujmtd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtfwdcmrpj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtyadzobas.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtehrutlgj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtiiwnejwg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtedtpyeoj.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtdnxzczxe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtzutnrvaa.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtmlylmlmw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvvhhhzhl.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtulsycdgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtkiqbksec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtywarlvsv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtwwqqdplj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtylhcozkq.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttzjojchs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtezkjomuv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtefoxtlzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdmmfughk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaufbjvi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtektjfnqv.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtorvkjufb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtwxyjksqs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtskshjcee.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtrcztavlo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gttoyvmxdu.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtaqeyyszi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtrbvbvvnm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpkzzenu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtpwhrpheq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtobydljyc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtrlpkffbc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtdrjqquoo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgydiujcv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtpjavcdti.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtnfrokcbv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtydfkelwo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtcwdmucjm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtgbqxivuu.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtstfdgspz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtqexsoake.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtshnvstoj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtlykejghf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtpyjloobh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbfzuqhao.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtogcpique.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqjmlidhy.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtckvndbsd.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtrvgqqgfn.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtlmvtfgrn.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpehdttne.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtosaicjjy.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtkibdpxcx.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdcwbldo.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtvfpunalm.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtthsnzchm.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtgdfkawkb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtiqdgeoru.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtjtuztgek.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtduaqmene.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtpiuxdvsi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtalygxnem.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtytkssthl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtksymchnc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtvygncgji.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtuuvtqaas.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtbarlptdn.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtfmdntjta.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtnvwwbqko.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtczqcepjw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtedajrsxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtsfvmybwm.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtgrocipge.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtmqztiwka.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtrpvikvhr.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtptxulhoi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkyzfgoi.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxvspicse.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxfqwupla.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtausdizdg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtpitprsti.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gttkqdgjac.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjylvvknt.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtcwsytaih.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtemvbhhji.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtjvtjicig.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtnvoswnxj.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtpisinsjr.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtwmkekamr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtgzwmudwh.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkrcnepe.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtxivgjxdk.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtoabvysja.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtxpobuots.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtcpplzhea.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtpxlilqne.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtsobnhiei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtcnoltcch.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtpjothzih.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtnsdwtapb.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtasvmpque.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtqxdaawag.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtzdsxowfn.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtdxgijbkk.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtvyfbodph.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtfdnrmozu.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtrfspngtr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtllbhpwfm.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtkmffpbtp.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtkflnjnkq.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtnvmbfhjp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtdmhfqeak.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtqhewdjac.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtqeggrhik.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtsrtptepp.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtlxivuqzq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtgwdhffax.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtbnroioop.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtitekybth.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqesynjkf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtqrrwfrvq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gttcmvbhfp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gthzyqxcfv.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtgsvndqin.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtfvgqwatm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtotmvaekk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtvqsosfue.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiagvexfy.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtfmbpwxop.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtlkelngbi.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtkdbwjfmd.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtamamlfta.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtsraszzbr.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtfyewedpn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtbgeyfpxt.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtctctlyjf.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtxiltswje.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtlxxjgqxr.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcupopnr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtbiqezzsl.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtdrnpqkeo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtbrrrkfym.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gttwnsumwi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtiuiiwmio.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtuuvljjug.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtmnocefjo.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gthpnaigiu.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtdhvpbbue.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtsilpmcoj.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtqocmwmkw.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdrtzvzfh.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjccsgnum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtpvbahvas.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtimjfvo.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtnjotcmqu.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtzvgqnkgh.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtceazjlkw.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtdlalfaoc.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtfgpdsdei.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtcbzxjzlj.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gttfufvmhj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtahhgzvfk.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtnbokdscm.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtcvtqcyjz.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtuwuykzme.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtkukuiziv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmfolvbv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtfobgjpsh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtmywcsexj.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtglemjdjh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtckdbkcmp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gtxwzdbdqc.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtrmgaiyvz.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtdizzbeyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtzdrtmvfq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtzflijrgd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtjygcvdpt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtzooddtlx.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtfgsaqtzp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtpyckohcn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtuguggofd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtquysvnxm.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtnzmklfsc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gthdjtlzqh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtgfuonvmm.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtvdwodwtr.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnohoxaiz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbutvpyd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtuuxtljeu.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtdwsdkwez.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gthevudooz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojngodnp.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtuuywehej.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnxfbpuk.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxcjodmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtiqpllwft.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gthectocdl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtwiwkrmbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtiflmuujk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtxudkajvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtxluystrv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtxaggtihm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gthhhkxrjv.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtfcmgwdte.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtuadbjofx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtasmgxxqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtbqeirxij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvnngulnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfdqssboy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gthyogvrkm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtggvtevsu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtecqaiked.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtbsegswpb.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtiumxfmvm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gttwjkgrgl.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtqjzhuxim.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtfaelmidh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtjvcnvhde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtxlesizgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtxehhhkhs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gthffotztz.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtbeqbyyrq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtfnpqtnnk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtvgwiynys.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtqofshnpz.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtkhppbegl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtsujolwlb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtmeruzzsw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtvqhbqbit.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtlizpmfkp.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtbrksqqok.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtwbqureub.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtmqozpamt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqduqmnem.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtdqdxvrke.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtieexondo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtqnilhtdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtsxavermw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtaukopzsl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtaqzwjxhu.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtaagnjskz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtzphbkeva.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtvprvnwlc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtsfvcednp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtblsqgdhs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtqmfrulap.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtrkzzncbq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtfsvqwnnk.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtclucpqkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtkjodywzb.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtokcmmjud.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtrgludvom.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxpmnyugm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtujomjmna.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtbpslgkeo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtgjinponp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtunhwpmai.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxdwbmxg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtnzvdgcpx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gttvfeahpm.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtlartcdmi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtlkqwpjmp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtlhintjbm.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtgkhucnee.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtfgnbkpew.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtayzvrehm.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtphpqpsuw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtramxasvv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtxemtrkri.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtwgfwszms.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtfklpflje.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtevunqslw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtpxfhecnn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtyxszumqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtrepgmwug.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtgrabkggx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtqeytjsga.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpwbbydm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtivtmtkkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpujewqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtqzuvyyog.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtrxmatvwo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtlkzoyede.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwpkhcqb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttkegqvhf.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gthlhowvss.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlrauvfza.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtftqebnlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtwzxvfmnm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtbnlnjikt.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtpevfexzh.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazlnzrnf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtxzdqfsxi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpzqtjfzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjndkzgh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtceasfwhv.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtnjvxlnqr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtshhbzwmn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtoggygpjn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtrgnmxubd.html


<!-- 参考信息 -->