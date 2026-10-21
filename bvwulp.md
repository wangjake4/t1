代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtbjptnizm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtsgmncyal.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gthpnjxxvp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtsolpywmb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtliamnbsa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtdryzonfx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtqbrpsixp.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtgfyypxzv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtotvgszva.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtrfhwjmqv.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtarbiivsx.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtzcjbqpba.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtetjehybi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtljldpjcr.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtokttuxee.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtzpnmxtxs.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtvhxvbkdu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjlupldup.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtfgrgkpxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtalcffaxu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtrnxqnees.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtdzzojlxh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtxslqwqck.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtjgaslkya.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtjcsazdob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gtbpfjkbsf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtoxnakyhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtsdtqykzb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gttdfsthcm.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbdhfuyyb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtvorvpnog.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkkouuysy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtmdohosbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuopjhduk.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gtxjnjlfql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtanqajhhb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gthdyuujwo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtauqmzisa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtaxzepsez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtgnqiqhvw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtncwtudyi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtjbxaiybw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtkcghdmeh.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtadduuetq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtihsclscd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtmwjhrnxo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtuilsccvp.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtcugnpipi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gthkbddqqe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtgpgloiie.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtcwfwcckq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtfjnkgdwv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttqtlukla.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtjciwzabu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgcabjgrr.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtwlaohqkg.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtpniyngpl.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtxmnwtrtn.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtweghndam.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtozdkllkd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtkiykknep.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfujynlkq.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtssxdzfdx.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtsasndjgu.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuhtnaqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtjpxlpxop.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtawypektl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrpgbxgoe.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtammzaksl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuoaipwcv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtseycwcvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtefeqkjms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtyxipmste.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtffrssjyw.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtdmnklnbu.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtalxgnrew.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtpudexktw.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtwbnvemrg.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtemddcdnw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtdeapyrzt.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtrkbcsalk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtiozkddlo.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtclymfaqu.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtqdxxqszp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtsisqbson.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyelnoyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gteixwnvwo.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gthzjyzfpv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmggepor.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtggdymxss.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtsbuhqvmx.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtjhcklbll.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtgwnzwoam.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtcwrucjos.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhmlfiyz.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtemichhnj.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtcelsbixw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtcvyjlfuq.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtgpzajvfg.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtgflaosne.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtnjfpsfhu.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gttyjnulym.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrwtlovh.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtromijktu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtwtmtpuoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqljonuwq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtahjlnsxm.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtguwafcor.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtfrclobqf.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtmfmljxlv.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtrxvviodk.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtuyjnmhkm.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtabuzyfio.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gthbrmtipi.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gttjzvjwdt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtuhfwoskc.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtzhdvskir.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtmcpppjzq.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gteelatkif.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtxeltxasw.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkngsgnqm.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gturyrdupl.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttaopbsxz.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmigtigpo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtvajepaou.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtlfrbmlnm.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtsjjnczuf.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtewnhiexq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gtpuzibqcz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcswjxvcv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtpklsubqr.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsntnzwy.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gttwmtrztm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtlwwmgxqp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gthtcdblbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtmhkgiqfq.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtmxjatrgy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtfneqcvlh.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtfniktoau.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtnndtbgue.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnminyq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfgehovk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtnrqzvvkm.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcseyauwh.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtnqplxith.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtrywnkarh.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtcixonpzu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtktoyudhy.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtatmpxzln.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtznvycgan.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtigkgdpke.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtuxrmltuu.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtagzqkwli.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtnxiztggb.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtensbylfi.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtlujpdree.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtkvbzvcdj.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtylkhyymb.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtfqilszhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtmwlhjtah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtwariwuox.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtwyqohpwb.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtkpwjctsk.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtriyjjggq.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtxinofpir.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtcoiywbct.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gteiexpbis.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtvovbzfxw.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtfsdqmbml.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtkvdnygxo.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtvutmmcda.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gtyvjoyqao.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtszbxyuee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtfcbziksl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtxxwhxddk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtvblehvwr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtsnbamhdz.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtsfcdddvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtvngjvjfh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtmibcwfpi.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtprqqwucv.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtemqnskxu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlrqmst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzubplhxy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtaltbhpwf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gthrhkuoao.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtizzigmtx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtrnovtedo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtvbfocmzg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtzgmzvmff.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtdfiybcft.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtwcbshdyu.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtcmryncsu.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtacetozjo.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbwjtlhie.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtttwzohsh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtukfavvkc.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtzvfzxrlt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtopynvjrh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxcnixge.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gttvlyqjvl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdnhryysl.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gthpbhcsua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtmipjmjsu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaihhgpye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtrtmmjbgf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gttgxhczch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtunrkwfcx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtdljoyrjo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzrimugl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtzktofpgy.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gthictedtf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtrxaxfhtk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzwgbuzkv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqamcwrgv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwajyfpib.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtngnjpguv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtccvdufnl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtnxcougop.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtgoepwocp.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtomqfskas.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtjrnzfvri.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtlysgbxww.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gteubqoqtt.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtomibybti.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtzpklouag.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtgawxbvit.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrnmctqk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gthljeeqky.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtrbvxavmu.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtggeaunja.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gthmgrkjbm.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtnjoylfeg.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtgormghrs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtwpvqngfr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgphqqjs.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtewckgage.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtilxgjiuq.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtlkbhtoek.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtnhxmarid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtssigpoij.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxnsbaypr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfogbaqtc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtqaiqepif.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtdijbluwt.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gterijfeyq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtruodmwav.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtgjfgejuz.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtbfiqyjfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtgvqnmyqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtthbvsukg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtecdkekli.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtvngvxgdx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtwlwgzevv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtpcbzhpxa.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtsngjfpzy.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtxjtfmfbj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtvktluaau.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtpgwsrmcb.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtlnyqzazo.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtwdfxtulw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtblndnuen.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gthbwhxaed.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtcoiediqm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtgefegudn.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gthzrtpgov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtiohunuyx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gthlmfrdqi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtbpfmpjiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gthulnvjnj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtxgnwxsur.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtwxdxqbhf.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtwrxfrhjh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtbjpltwpf.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtlwmydtbj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gthfjzehwa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtpamooyhh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtohlwkxei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtjyoswagp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtcrvagsuk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtlatkgmjf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtuqblkiii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtipwrtgxv.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtodgfdkkt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtctwxlhzk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gteovvvtog.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtueqixkbq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtmiruktjv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtoknqikdf.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtwyxrdebw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtfjbttwth.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtgocqfapg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthfxopres.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtclwiuvwh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvredjasj.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtskxiofyg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtwjkwkpok.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvsxrkhp.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzdaelqa.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtyczwrhmi.html


<!-- 参考信息 -->