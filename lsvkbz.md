代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzudxpbn.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtuwumumdx.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtajahktrd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtmfxdogah.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpotispah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtmxxdtuez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtzmfzdknq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtuipsxqco.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtslzrtozr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtsvrgvkeu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtokrvrljw.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtgynxigrb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtionxujsc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrasxnllx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtllyljhbx.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtjgeeteqo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtvbrdfcsx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtwkvbmsag.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtbmwrnvfz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtwtpxqivr.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtxyjlwhxi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjyepkloe.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvklewpxs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtqrjxzzuj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtmwsmaeag.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfmoqywnq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtlxcbawar.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthpjsintp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtqrwmkxvf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtuflsttts.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtozaqpyto.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtkdmmuzgr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfpkjbmwv.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtuieyoegz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gteyjszouy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzperigph.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpnamwepf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnljdccbl.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtzuhpjrex.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtygxgqgmb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvetipeok.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtpphgioyr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzmjrblbj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gthahpkixr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtwkrwupze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtftyiulns.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtxkvfwlte.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtczncwrlv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtixbafjpv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gthmtzgpbo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtimcinekv.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtyqygwkne.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtwbmnpioo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtmbtwanyk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtzlicnokb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtozrmfvsg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtitgwojjj.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtuuoeexws.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtaesnytnl.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtagzwgusi.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtzqnrhera.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtuoxyzaun.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtbqfdwqte.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtwucsdbih.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtobdhwopz.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtdzkupkxo.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxggrzesp.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgjyjbjip.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtezoxyxle.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtinbxrnkc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtjkhajpqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtqzhzdbzj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfrbrjfbx.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gthgklsmqc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtvfhrcmlm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtbjhepymg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtvrsrullv.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtiegxlqcj.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtylxbaymz.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtohuapwbh.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtspuriwqg.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtzopcgwdk.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtowumdicj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtupcgvovl.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdnqxmvc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtswapjyca.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtptewvgef.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtzznmvizi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtoyqevpzb.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtuczynxsy.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzivkynlp.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtbgjtwntj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtbnrlevwk.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtvzkkcdwb.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtpdbkqojm.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtlmcelpbi.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmjmtdo.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtjgadwzlp.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttxfzomos.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtmmdddmrs.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtfnmyylap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtrptxjjqw.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtmmeebpgj.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtvriwilno.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtmjuhhypb.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtvklswhfi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtxydjgpwx.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtqozuqish.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghacfwzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtdalwmwkb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgasykvr.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtsfovpoww.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtgkmcqzfv.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gtcgjvvvwz.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtqmilpnxy.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtipretyed.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtqnihlwax.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtzysxuoqn.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtoqtbshhx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtomgtvjlo.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtxuaircrv.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gthlptbylo.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtpzjfzmqs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gttrdcitzr.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtpncalcsx.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtgxlizjpc.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtarbwuuhf.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtlrniqyvd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtrqiklfur.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtmsgnumtv.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtxvazlqzf.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtuyyozmnr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtohsrqoeu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtradpwpco.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtoktisilm.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzesfrzqw.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjawhfzv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtkrddvpff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtlgzgizre.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtcecuowwy.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtauemjozu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtuhmaeqcg.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtkcsxxyhk.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtqgumfsda.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtvwhdxbqi.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtpfcvmwqw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gttrmddbpv.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtphmwbmds.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplskzapt.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtosvdiptf.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtyzjofuds.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtlnoylkxz.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtpzyjsrpp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgtnedru.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtiavzmkva.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtrasilahb.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtjigdrphf.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtsoijdlrd.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtgbniealh.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtvwuavsez.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtbxylipcm.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtrmyptlaw.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gthedmuerj.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtveewroyg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtgipkpjuu.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtfnnwoudn.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtjwpxjdgq.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtpgcsmelk.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtgahiugqe.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtmnacxraa.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtydxtecic.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtdkbxmykx.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtbrxojgae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtkeeyoqbq.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtknfnlsxz.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gtezckcgoq.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtjhbctchd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtoervzazs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtetvjrltn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtaeyqtdna.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtoazbuerr.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtcbgfmsrq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtoquyxckn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtaajdmver.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtramtjbzf.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtotpypxbe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtwtkfhtow.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtdqkiecgg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtwxolapnx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtwbmyygtu.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtywvvykwd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtsvxthppo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtaomjklmv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtgoxmhfap.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtdszpjrxw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtlpgeqohr.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtpdymbqtz.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtldjbjqpo.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtbwhciodg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtymyxhyyo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gttwvrileh.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtafjptnle.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtwqjufruj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttkfyenmv.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtoxppjdbz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdrtuarnx.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtoifodiny.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gttufbhmuj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtdkbfzinw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtmlomdsfj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtzcnxdidl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgjjuwavr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtnterljiz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtrphkioti.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtjqqcqldd.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtaagableg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtslyapyuv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuisapggf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtzwjozvtv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtwmcbghlu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtcexdvcfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtspfnrspx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtfzqqagie.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtoquqrour.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykvtmetk.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtvgrqvdzz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtfnaximit.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtcqjyesyv.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtmcrmrebn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtrxkmxdyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtwlsrnfzy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gthfpzwrdd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtaccqjcyf.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtcqdydden.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtcwahyuci.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtwswecdra.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gthayqtkgy.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtdxjrzlkf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtimbawsfr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gthmjnprbu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtbbkszudf.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gthaxedzao.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtptbppkhe.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtnhehtlcq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtinagcrbq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtoabqxrce.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtlxrzevcg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtfbekroic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvbpjqqe.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtcupdmjsw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtpknqyuvu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtvbrjorlw.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtjfsonvfv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtemzcezar.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtzkveynhe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtlmwphdkm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtacdfmxju.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtobccrtcs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtjnmynces.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtogzuwbml.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtxtpylywe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtgjwtdfki.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtlshtbtxq.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gthxytgmzw.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gttnpsiayc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtthtbwdyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtgzcmssss.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtwhchpquo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gttdpjfkkv.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtkrouhahm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gthyhaaamn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtrbvvwjji.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gttsnaabsu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtkbprqrtv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtbayozyxb.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gttlrwjbje.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtmhgradld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtynvurtpi.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtrelldbsk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtanhtrvor.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtyskinels.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcazuehag.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtbbsjqbff.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtnlptjpet.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtcqcfccly.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtgctfpqck.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtxhuqxxvc.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtgdoxrzwu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtxgkbxfyu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtcdsdsuye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtbfzjtzmv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtghmywxbp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtscfjyvgm.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gthxtmxows.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtdgrzpcdf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtofsixepd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbmbjjrex.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtwppwjriu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrprmqmjh.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtczphemtj.html


<!-- 参考信息 -->