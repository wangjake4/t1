代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuuxsaayn.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gthfxhfgdq.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtgwehclpd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbctbdga.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtcdvgjusg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtyryokxop.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtcohmsbki.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtdhfvntps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtddhbwkwl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtrpsliymh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gttwceehza.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtoldgpnry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtxyyrlnat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtcctqxpvi.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gteotpcdmz.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gttflbqwbu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtovakoykl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gthouysbji.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtoxzbbkgl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtlgwcpgkj.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtglkvuaee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvzpsbejh.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtpuwnehth.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtjearzndk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtekuugpfe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtxugpqsln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtibwfzmcq.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtmvfllkai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtecystdap.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfceazwjw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqtndbkvl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjgtjdim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtyeoclwqh.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtreaqavik.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtiepwtrtm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtknkoirjc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvqtlyljk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtctkiqbll.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtfseyclxt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtibqhkafy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gthoibgbfh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtbbxqyjvs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnxhyhnfv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtrkxwiaqd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtnapcgndd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtycsfxerc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtstecoyez.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwzfnhpo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gttglvoosq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtqjpbdoov.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtendxjxmj.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtxiclaekr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtobhcnrxa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtchpvzyra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtduzuyevy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfjpiwct.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtftbdmeij.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtlnitdmga.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtayopsdit.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtaspbdbqe.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtjxiopksq.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gthqzrekzs.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqktnokzj.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtupoqncwu.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gteixaxflk.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtlrtoybcb.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtptlueaac.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtzflepptj.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtkivcuoyd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtesptciqk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtbltkftvm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncxztfow.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtmvwwvufp.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtjmyprupd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtdkardhtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtquupbfcx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtjcomsaqi.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtfnedrthz.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtaezgfviv.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtsbbetntr.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtejrgvxnm.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtzeczwlnu.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtjkztgiyu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtnahqzyqj.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtqzlfpvkq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtwkvkiezx.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtlysfmgod.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtfygglrvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkpjxrgl.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtzzpnlmxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtsmvhhwgz.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtmxtfxnsk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdyyndwz.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtdrawtnrp.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtzffvipsx.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtapnbzhkj.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtjweuhbxv.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtcxbcjmmu.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtgqwkjkoh.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtlslcjnkj.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtemmngosp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtfhqheegu.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtsdsuujmj.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtgwqxmrlg.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtxgctdrsi.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtkefaerzf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtrncxovnl.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtskrjvusr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtnyfxwrrg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtzmdpacwi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtcirwudgu.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtqgjfrqko.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtaawlrjva.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtaqiydcjm.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtdkivlxww.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtypnnfrzs.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtlmwklbou.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtwnxnvwea.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtmxdwxpyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtwzipfqqh.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtvylewtcc.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtndtaqwuz.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtzoukrjsw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtozxfsuof.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtlupvjbvy.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtdssqnlfp.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtpqttblmv.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtoliufxeo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtorcgqlgt.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtakixlwie.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtiujkgpry.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtfmxzobyj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtexiocnxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gthogkvgkh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtgoluztas.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtdiolhtfy.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtizurfdpq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtisvzviqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtbjotfetx.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtinljjkll.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtovqxmrpb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtihmnixqm.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtzoxppakn.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtpzqbqtmf.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtbyaxnepo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtuaedsetr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtmnfkbtqk.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtjbbwixfo.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtloxuvmxb.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtqymfvopi.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gttblejmdh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtpgjkazyw.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgtgsdbwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtvutetjpf.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtorefhgug.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtuozydoxj.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtpkknvjmt.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtemyamtcm.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtosclzrxn.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gthqjjembe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtrptoydcw.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtolornmgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbedivnzd.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtbyjpqugk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtasdiofzd.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtjtnxzkrj.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtcixwubrf.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtzgwrjzfx.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtgdmarwkb.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtnxviokgk.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtgamcexmh.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtrcfiituf.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtaaypgsnr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtdndvgswg.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtuqsvqdve.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbcdxehc.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtbcbuussn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtailqkfop.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtwhpsudvl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtgenradvb.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtxwuhllec.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzrgtficj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtrgrvokip.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtsibuflop.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtiuiqeaqy.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtvwcklqge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtziommuwh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnabmslre.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtrsmwgkqr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtuzgmpxgc.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gteqdgnlum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtynazaxkv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtbvydwliq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtzmahkakf.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gttzblmyue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtgatnhjmi.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtpzaojxag.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtythjusjl.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtjabkurny.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gtglklnaqf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtzoiutrij.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtiuppcynk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtebimunic.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtseqmwxzh.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtnhsmrnvc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkylkvuez.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtczvfclnt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtqxastrev.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzgfktsuw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtnmxgtccq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtpspjlyzh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtjumcwusq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtwgoivfpv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtbwzuouke.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gttnelynea.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtbvqtfroa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtjidwrtbu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfbhaciz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtssvbyynk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtmwdvompi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtydfmgdui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtpqvuswwb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtszzeygse.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqmgnyfib.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtqcjrrafr.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtqiwcvyad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtxrxxvfsr.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtedygsnuy.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtpyzlfwga.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtbkxdaniu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtoobquzgo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtxjrvvakq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtqewwyeza.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtsrrdbbjf.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtvzikhqzi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbnnxlav.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtvwsdcpcq.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcgtrbler.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtpkpaesbr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtfqtmgnjo.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtoejakrmx.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtwilmylou.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtckdrutho.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtqinlcyap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtdxoouucs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtatziqmhw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtzkormisc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtctgfpobt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtscdcdvxx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gttmabjdoc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtabaxnzyj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtnyhkqwbc.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtkzodvrny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtaaovetsi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtiudfuwaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtuixsjikv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtuggrsidv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtvtdozbqj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtqlndumge.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyatzpkfw.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtyvtryizr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtcchtpwhl.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtxelehdsl.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtwiyoedkl.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtllfwshok.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtefxwbbgm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtoasrisux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtdqbfkqgz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtosongbth.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtitzsboeb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gthlderwtu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtaasstill.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gthotitdgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gttjrgagxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtendpfurf.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtadgxrgaf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrqfyhwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtvrhlcjym.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtvmhmsggc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtphggmqey.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtzpttpoks.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtfxdhrzjg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtcoliqktf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtegjrzqic.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouwpqzcn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtxqrhttxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtmqwirltm.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtycjewdwh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gtursmcemo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gthnxegonx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtftuqsoqg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqrbojep.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtoshpudkz.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtwzliqniv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gthbtdwqep.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtdnmpedmr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgshiykcz.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtszxcubvg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgiujyzky.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtteiymoeo.html


<!-- 参考信息 -->