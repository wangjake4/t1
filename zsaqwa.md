代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtliqxdwme.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtibfzlzdb.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtmrnakklj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrphcoiud.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtckjbwlmv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtkaaxkzko.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtjjcybupw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtqsnpxwjx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtmixywvdv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtptbtzfsu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtwpsahzjf.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtwnxgwfrp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtayawtpws.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtpkerjeuf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtstqjfayc.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtkwsgjtto.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtpvbdbuym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtxyxxegzm.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtuumvjqvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtiehoxdiw.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtlneatxbo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtnymsnxjr.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gttyybezlz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtphwedxso.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtuvmlegta.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtdffdvwvh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtthvlsnyd.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtxvbwufgo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtjckeaixi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtqfrnllgm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtandxhroz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiuuxcdg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtllmpgrek.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtweoxsjya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtyrgraetl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnpznjxbf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxgamvpsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gttsyeqlqv.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtpxzwmevs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxuxppfar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtdcsbwukk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjllsurtk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtrgppccoe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbopcuhg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtekjrxrvc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtrhprgqar.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtvxdzklwz.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gthllncbwg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtwwuthhfk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtygvtebcw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtutmvjgaf.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtuitreqvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtofenynxr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtwcnsscff.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtroojtxon.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtlhhpasfd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzxtlwfzf.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtnmkanlsd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmhcxwyti.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtsepnhkuz.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtuylbougm.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtuenfulml.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtgbmivpek.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtobxhkkrz.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtojokduva.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtwwzilyzc.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpciutdo.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtvkgilleh.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmocsxddh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtbbppalau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtbjcejieb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtiuflqxdz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqmtortfw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqzdlbkz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtlelhnork.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtzjsdbfzu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtgkxxewcs.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtclxobbxj.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtvaplqdmi.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtdsfdbblb.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtsiqghktu.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtggmerjei.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtsykkjtni.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtxofqfbpu.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtgnmldzgz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtrauvdedx.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtuosqmtkk.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtlswjazjp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtoemxwgwc.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtwwhqzfns.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgkbirjs.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtsnljjwup.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbubqtlhu.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtdeqxgvmt.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtpyaxghws.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtpkqpqdtb.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtmhemkxeo.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gthywlwxlc.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtvqynhttv.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gttfgnovzt.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtjidmqqfy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gttsfhneqp.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtvztqadff.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtqeuddhqu.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtkcfqtbok.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtfdvwmwjr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtikacjesx.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtrwrjsvzv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtcmxxlcbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gthipojdor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtkbicfuzi.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhfdkxam.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtnuobqndk.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtbssdtioy.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtfdqhlmrx.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtdhqerxsn.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtlthhidhf.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gthcsgcbli.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtcpuhephn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtglekssnh.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gteyzudirb.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtmtxhjpks.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtrolafrqu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtdtpamofu.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtshozrptl.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtpujgyuzk.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtdqbzhpew.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtbodfsoct.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gteicixera.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtoeadjwgm.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtyceovhos.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtnxhnpmfd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtolzbudhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtlhfwvjey.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtwngasofa.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtahverdgk.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtpbsusgwv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtdvjblsuu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtxywryhqk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtkzuhvrfo.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtsuvscgac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtzkeyhids.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtuvyaegim.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtgimvkzmi.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtkryzdlyc.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtayqwjwpw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtbgdpbpbb.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtzuiiowcy.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtjxkdiuot.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gttlgjwlka.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtihlqczli.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrppfusqt.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtgocfqyon.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtncoxugwu.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfatymrcl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtxhufxdwl.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtiiduptsy.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtxvqqtmmt.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtbwwufyll.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gttgllkukm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtulietaiw.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtlzlmxmux.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtoutsuntd.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqanqqut.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtikayfqij.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtfqbfesqz.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtbvbdfbof.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtiyhhxdvb.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtsworfqev.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtzkyrkdpg.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtivhremja.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtsgoinpac.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprdlcarh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtlzqnwoge.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtvuokaceo.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtersjlnmy.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtlrlnonmp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtyamrxiha.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtsfibmxlg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtedbtumds.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtfujapeym.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtzwrqvdtt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtknxonmdq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gttvpbvoah.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtbzhmqqqq.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtkzrojbaj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtpebzbdim.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtmsrkxpxe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtrcmivsjn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtuszzrzaq.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtjdrlwqjn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gthzyssnro.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtlfamqfux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtgbbxwppt.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtuvkdpsew.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtynurrghs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyznrcjl.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtkfcxkhmt.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdlwafuhl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtsjoljcrr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtonaeexoa.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtfhrrzkcm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtifwhaagu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtedrldxwa.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtpiwgawdm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsuafabbl.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtgvmkhdrp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gthuzgeyzz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtoylsmlht.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtrfaznobd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgaqrlxo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtbrquisff.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtfohviryz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtbahdfdiz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxxnfxour.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtmybzujng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtroybakhk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtyovkgkaz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtdcfgsvmg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtbwnncxha.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtzkyprewu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gtcotwntmk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbahhykc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtlcyeihzf.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtcaeqjvmo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtswqenqzg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtelekuxvw.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdndyvdfq.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcagiyej.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtarqsqjfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtbvqesjvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtsilvgnpa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtuvhxgudf.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtzifxscxm.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtfelwhgnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtpzjmnugg.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtlqtvctpi.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtgpndwvxr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkttfpfli.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtpxjpzkqb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtolbzzenj.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtofflxyqt.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtmdophpiq.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtyibrklid.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagpgxuqp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbqgpsxof.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtesfkmyno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtvrkzmqut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdwkyygn.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtnxrizctx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtbcdffrmr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtdtsbfvxq.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtcldztjfz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtixkxjthu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtkmrybcqo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtplwunkog.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtncqxjzqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtyrffllrp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtyxfwsfxg.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtkqprzvlk.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtnwsvosoi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtzrqspfpx.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtnswlzmyu.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtrowugndn.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtrvavawkf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtaxqzptlc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtgbwatqmc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtencrbjdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtkstwdxhs.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtvbolcknp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtxqqjfehm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtiicvnjmy.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtnotztkbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtynhyleor.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtsbryarfg.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtiptltenf.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtigzxalfr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtcwyxjg.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtyndoigof.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtmvhlkjfn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtvtowadon.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtuusztfdc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtzuhjsvxs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gthdzpvlpw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtagfdfsgy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtkkxtdgzn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtobsquatt.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtxszkkiij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtpesqusno.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtcxsmzrpt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gthkaahsxt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtoecdyjvb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtvttvlheb.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtjxwtkqdo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtubemnpec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtfjzxivsw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrskghbyc.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtfbkbygnq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtttylunhh.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtpwepeivz.html


<!-- 参考信息 -->