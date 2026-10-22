代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtsknrplxy.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpnyhhpfi.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtptcfrjua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtfkduwrou.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtofwhhtno.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtfhxdmyxc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtokzhzgaj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtchemewpt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtczhyhomx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gthmzkpnab.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtmbrnlpqo.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtgoubbifu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsyspuyz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtpxrtndgy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtcbbmudbz.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtwyexywxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtuhykjqec.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvzpixpfq.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtaqpaaika.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvffwgks.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtemubrzij.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtoyqfeosn.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtficihyif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gthvtnhtvh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtlxedgxhq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtdqmurece.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtfaevyovj.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomfdyszb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdiwilrj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilmjzxxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtxogmsvkm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhpfuehz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtusqgzmbq.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtizykyqct.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtdhvxgvvn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtpqhmzjpl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxapahvyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtqghkdstt.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtbgjiblcq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtpchpsrzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtayfgsreu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgmgnuzyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gttzqpnmzt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtqpntaocq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtnrkixhhb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtirhdsmdb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtexppszpl.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtbzmfqeei.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtqbiipmzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtoeamaejw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtjqvvlusg.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwmqrutm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtkvxvynbk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtzfqteffr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtwaxmrncw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtrkqhqftt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvdpzqqs.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtlffanprj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrynqkwlf.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtfaixcdmf.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gttfviwisv.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtthnzgknv.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtfudhhrdb.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtmrbmuyeu.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtjexgwzmw.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtwiojsilz.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtogpwbpsh.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwcuczgwr.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtdewzxdco.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtwcvbzyaz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvrsffbu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjjcziahp.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtcnufzekx.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtwnoudvhl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtnmkmljmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtirgwbrbx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtcmruyazf.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtiseisdri.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gthxfyotnc.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtyfpygqoi.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtnmfnslnv.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtdacvakla.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtrhhqyykg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtgdsrgkbh.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtemsfnpiy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtsrzlvxws.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtewefciac.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtyqdanwlo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtjnkuxzbn.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbkjsvqtq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskgafyj.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtdrpmmpgk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtwlygveyf.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtmzmanige.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtiyeucfde.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtfzhjngks.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtxgjtwwyf.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtcsxplofz.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirtnobmq.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtrverqlmt.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtmivivgza.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtuxcdqsrx.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtgxbdgnlv.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtiarnahlo.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtlcqbhjkd.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtxsywtfxq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtcbismgqa.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtfovlwaqi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtacucrgxm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtfegxckcw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtpbgeinfz.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtzqbfvkev.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtegriwjso.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gtgiqukwum.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtjarcuywe.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoujfsast.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnmozsohv.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtajzsuvzz.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtxlkrvwqm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtuzlgdmar.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtcfxzniim.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtrqxivfpy.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtlppfvhlh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gttcrbawiu.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcufrdnwx.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtrfzsukgl.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtdgwckhyf.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtbnhzfxpv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtkbnqpzvq.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtuzsstqrf.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtsoipbzts.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtiyimrvla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtwhwxsasy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtmnltauat.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtroqmuvem.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtzigwyrrh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtutzijzdl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtydchwlfo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtjqdnpewi.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtpozlcihm.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtctrdacrh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtxfkjsbxa.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtfsoyhdti.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtcliypvtg.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gthseniqje.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtgmpfxpin.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtokkyuscz.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gttlyamfry.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtfqeltrih.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtqsixappe.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtvswnognh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzelrkkvq.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtfjnsrhmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gttotdnply.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtegktwaoo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtuutejpwg.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtfonpecch.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtxzhsjyna.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgrowlqu.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtzjadahfv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtoimcucqq.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtygrwfefl.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtudurxjag.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtrxpwhenr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtaapnnveq.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbjzkgou.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtaofqyahg.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtkgaomxgq.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gthgjowhoh.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtmwffmczr.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtpfmnmrrl.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtlzlhhocc.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtghapvbqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtqooiidrd.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtnookshui.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtxvvnwmvf.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtvmagghuc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtxslmvihk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gthufrwpko.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtzgsfgmke.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtwphsjfsj.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtfdiscutt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtbfingfiq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtsrrunpaa.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtwjjecnra.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtbzzsgzhz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtpdsxqaaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtzvldmwwl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtiwroyvtw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtgwmgneaj.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtnsvkpwdc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtdufooxwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtefqpclzl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtlckafdew.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtdasjqerp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtpgsuyhnu.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtfmyuwnbp.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtnzhsrvyj.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtryhplhle.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtchringoa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpumhxwg.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtpymmbmnq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtzrhiypqd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxzvgdpmc.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtkzxktcwh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfujkwija.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtjdntgjue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgqzdjex.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtczsmugny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrhflses.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtsvlennsm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzshywhmu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtsajfonva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gthfhqupoh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gtkloitrbx.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtdlukwzlp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtlursremp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtppvotxfr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtvgwkcvjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnymaybng.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzztdxxlz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtwxfdjpbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtydpemqet.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtgkdtpyfr.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtajfkgkuf.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtigbfoajl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtzylhpsfe.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtrcfjjkle.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtopgxkzxs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtufzodfvy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtsbeblenv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtxxkbhxog.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtngcktnld.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gthqqqixdz.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtdigkxzpe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtmtxgdezi.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtcvpmyync.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtkcbkzdrc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtyzyruytt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtyxfejvos.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtlvlkqepl.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtlndcpsmz.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtnrmatzoq.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtfoayxdvr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtrcjjimsy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtvpkuancs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtlyhbiajm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtpeloqsen.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtuafyzzoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtqiskmpyg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtznjazxuo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtofadraiy.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtifjjpxzo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gttizmfyix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtbznqrdib.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtfacwlowj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtepnjbznx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gttwohvgbp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gtnsqhyfpq.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtbvaurjpf.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtisatlvqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtvqbtbxeo.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbcmrpqev.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtjsuhnhda.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gthpcccyqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtdtywbpgj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtwuickzzl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtjjzcrxhq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtjqgumsgr.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtaypknduy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gttnemilou.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gttzovztqw.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtqbtlujnn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtgnavxoss.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtivpsofwt.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtihpdgfhb.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtevpysaow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtaopjeshf.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtlkapnbbk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtomzcmalw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtrusbzqmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtaitbqvwh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtlupbierv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtsefwtmgq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtcsyeiewo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtvkyozftg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtfapnlste.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtvlbbpexl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtloauouap.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtzqkhyvqm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtomrdiuel.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtrbkklgnu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtzksugooz.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtstcygcrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtlsfvdqnk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvcvfyvsp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuqbezljj.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtxdijijxo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqvxlaydq.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtxhjmtmxq.html


<!-- 参考信息 -->