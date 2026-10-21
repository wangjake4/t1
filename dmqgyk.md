代发 wailian999

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gttosrwdpw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gteuffjahf.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtvjaujqsk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtgmmnfddi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtwlwxwjzk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtgvnjmkqv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtfiyzuohu.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnrwmvqqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtzycmwgsi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtzheywcux.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtljmmxpqd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrxcwiqxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtfqhjwovm.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtetmxxmbv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtgakhihoe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvwnanycn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthnuxkchg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtooaoommc.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljleellb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtglhrznke.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmtmorer.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtktovmfoa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtdtxbausb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtltolssjn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtcjgjmcmd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtnbeybxzx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtibqiyzkb.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtmeydtoeb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqgrfpbw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtmeqyrraj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtmuspbifj.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtjqsaxxlq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gtkpmcyvxy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtwwnbzrix.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtaellfrgm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtwsfvmosw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuyzigfha.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtjmcybyjb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfylvughz.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtvwmylapd.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtjjblnwjc.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtyulgkbsb.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmwyukwfa.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtgjqbxhti.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtvvmkzxbr.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtskixutog.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gttskfavqt.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtqlmopncw.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclsgxkwx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtifvameqe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtittmrhfk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpuuujnu.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtxgiihqpw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuvqxozet.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtoqcbpgve.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtedqxooid.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtnzenoasf.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtefcusyiw.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtbkmxfvkx.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtrkfafaai.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtjjdnskdr.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtxkapzkwc.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxecatdvc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gthooxqsre.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtbmpttwly.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtlkruxzyx.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtyjftgacc.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtdgutujzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtxkjjtodz.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnroahzei.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtaudjioff.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtsrbjgfev.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtgeztvzjn.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtfyohprfn.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtjeuziidw.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtnzgiptrq.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztdokstw.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtdykqqeso.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtbocmlomm.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtfdosesej.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtnygjqzbz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtesjchkig.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtfexcmflg.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtlrtxxnqk.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtridstwgo.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gthrjtnsuz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtgfhwabfz.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gttkvlylcx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtazexzjec.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtqefutejd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaecyzzo.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtkotawdoy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtspwpmeqe.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtrkyslvzt.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtwdcgwtfm.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtgcbvkhcw.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gthwrxzokd.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtlkyvzooe.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtvbbtvzxv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtdtepbocy.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtfmdxubjv.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxjwoxgl.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzddwvmep.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtlaqyluga.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtbvrpveug.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtxpynhwpz.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtifggekgy.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtduilrwtl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlxcwflu.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtgydmiupu.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtolklthyn.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtdmgydmba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtmbzxgnzm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtetotpkkg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gthkbaoqat.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtqjpgdnha.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvsgxfjaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtgaqhuzyz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtfflfmrjh.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgnvhrmvv.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gttrdljzto.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtxkjotusd.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtgilmkspn.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtjlntqznu.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gttjureakj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslojsens.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtjprtptio.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtpyqaqrzv.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gttarfrqjx.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtmxrbjlod.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtenmaxidx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpeoollb.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtrcvbizvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbabsyqc.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtmmdfahlx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtbkqlsyqt.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtcciyskhr.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtwtznkbqi.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gthxzngzxm.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtweiynrol.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtposihudo.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcjlogsl.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gttecppfqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtgckivnay.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtjlqbnddi.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gteqhauvtl.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gttojleacs.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtdiazcsrm.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtbtqcfapp.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtbamlmrns.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtxmegfihp.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtapwzndup.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtsqxxgkxb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gttixuvcfj.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtmfexjafd.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtmzkbpgpq.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtowkuavlh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtrhpnliub.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtiyhmmoxg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtozqfqwvq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtvlbkkxeo.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtagbcmfko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtuabokpjg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gthjflynsu.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtlfcgfqep.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtcngbjlox.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtqszakoic.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtdszwdips.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtspmspvpi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtbdzeccvg.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtxcnckrfv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtmxzenhhv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtioyuoskp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtirrwfpto.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtjuwyupyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtmiskwxqt.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoadqjfnv.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtntlqsuxo.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtohsptpaw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtirmbaalt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gttikmytyr.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcruhsrzg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtyeryngjo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtafpliamr.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtbjflpqqp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxhsmzuwt.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitzuaywz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvoeubly.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtrmqytmhv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtzibozaxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtdqiyrxxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtzrcpgsfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtjlrdnsmo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtbclwzxfy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpjzauphu.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtqssagluj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtuysrryym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtxdkaovrb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gttmjxmmbr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtxoxmtwqq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtvummutpn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtbkhpdbba.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gtemzcpbmj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtgcivjkki.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gturqdisak.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gttgbexdoq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtrlczavky.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtvdaiiyxf.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtbcpwdsgd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtfowmjmrf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gttxjgendi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtgpghozhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtlxhhhotb.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtwotkzmnk.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtlrkhrzhh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtcqyehmqh.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtqlnpamzm.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gttpchxjsr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtwarqkecn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtvmsihipm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtcejzvxly.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtqpcacprh.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtdstmuljb.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtgurumekz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtdaomjhim.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtldumjxpz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtycwnhjwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtsbvararm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtiuouwryq.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gteuzgzlcr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtxdeocnvz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtejpzeeay.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtlxugtwau.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtggfxzosp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtaawbhpya.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gticxvsvyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtjyexdncq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtyheafamr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtducdijgm.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtfefacefc.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtquzjwlcy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtmrjzwhbg.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtlteqgwet.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtnveujssi.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtutfiqbbu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtvoxobfrn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtivvqfhqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtwjbjpngp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gthlpjitob.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtgnddkchx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gttbdmtyfd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtgfpjtwnw.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtayviactz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtoukwcroz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtvglswgkq.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtulilzynm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtezoqiqvd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtvbipgsft.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gthtsyzcfd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gthljbxgbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gttbhpqvos.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtaxpvmzdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuluxflav.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtqrrgrzfx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtridbhmxm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtmhayukbu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtksxzkvmm.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtfenoyhfu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtbbtxuhqf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtuqroiphb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtcwjsacsc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtxytgbmpl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtlbzqwxll.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gteehtbdlc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtunhjpccm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtclwjiyln.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthiqtjrww.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtfwaijjcb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtijntbznk.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtgikopoem.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtqcaotoog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtwprjjsel.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtcaduyjjo.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtkfhfgytd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtfftuugyp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtfjocgtbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtcexysulb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtkymqcgbs.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtcuupkmgw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtjkxyamga.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtjucgnfzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtlstlyvai.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gttzgxzqyr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gtzylbbxhy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtsaubwklj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtpprmnowz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtajweneic.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtahxyplqa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgnyvmofm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtyaakxejh.html


<!-- 参考信息 -->