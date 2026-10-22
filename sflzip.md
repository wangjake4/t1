代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gt2zaxtygep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2aqqdbdtw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2dnrnlevl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gt2pfbkgcuc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fulflrfs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2mebbqjia.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2xmcjbkzz.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2mrimvjrj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2ybttkhss.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gt2wztmchcm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2jynqkfwf.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2gkcnapyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xletghgw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2owbapefj.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gombydse.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2qzuofmgz.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2smnjcnxu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2jcebpwzs.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2evxakcxg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2kgsacozq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2gkrryqgr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2auzeegnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2dxgqfxoc.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2tyfoswox.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2unansfkq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gt2yhdxkyrf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2bhmokpue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2mvrlshgp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2slmfqdis.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2uhqnlajc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2oxbnsvkd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2barqpfan.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2rpehrvcv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iifxqqyk.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ksyqcsbx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2spqdtayb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2yxjsfloc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2aqendhmn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfarfrdq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2heeyxykl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2vdsvomvo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2tijivrcf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2redrbudd.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2jwzevdro.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2uqtfqusb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2xmdbjncy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sflsstyx.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdslroxl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2dnryfhrr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2hkhzzlfd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2qmtktkqu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2nwcolfpw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ksrqnssd.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2ukwcwyde.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kiubavyt.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2feqtnygv.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2ghdalzoq.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqomyigc.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2bymdulzd.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2qwpuuyfe.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2zttlvblo.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gt2srlinnub.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2bzugsgok.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2kjpozxoj.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2fkmmhaej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2uavqgkoc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2iscijvrn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxncyoop.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnnqbyra.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2ugfbzdaw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2rnpsrlfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2chjxafmw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2oydbhfgz.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2mvfxzdlc.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2xzvfxlzf.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2eubsrrbc.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2aelzoieq.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gt2fqkkivoz.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gt2josvnqrg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2ozhwfhhp.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlalvbrw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gt2ejhavjsd.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gt2qybahqeq.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnmxlxsk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ybtnrlvp.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2zywfvffw.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2iowqmtmd.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2bhuzvtml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2gzszcmbq.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2vemjtttv.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2kjvopyfe.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2xpfvgtao.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2mfqymlfc.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irozdlwd.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lfaxcqvh.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2tjtjusso.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2lkpchpdu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2ugneutuo.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2kotnykbk.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxujildv.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gt2vrnyhxyv.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2vmjyhmgo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dannukqz.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2yfenbezy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2uqplgisf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmhfsijz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2zjlysdmx.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdltldiv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2rvttxmlt.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2coyjethg.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2cxbaiqxp.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2wiwpwmuf.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2vdissccs.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkexmdfq.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2uzesfhpb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2vlciwnbh.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gt2bfejmrir.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gt2dluuxsck.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2dskphzez.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2fcifwmfy.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2rfyejrpd.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2egefhhjy.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2crlxidwi.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2jipxfnvr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2acxlobgy.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2iibjbfjn.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mmagwond.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gt2tvqgeuel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2sthqvzzp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2obcupkbp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2bhbwwkde.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gt2mvgkmfez.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2vhdntqmy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2emfgdozd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2fwqkimes.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2alfssehc.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gt2arwizdjl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2ttydfnaq.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2tdsdixhi.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptoiofpr.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2tdrjaehu.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2sgosodlh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxmmbahz.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2pziqopqu.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2waxgbonu.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2rgckknrf.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2sgmxthix.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2tzsmjjbp.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2penjdgmz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2lfoflivt.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rmproibv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2kkwxrqjl.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2hpiqtmbf.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2eaerihfl.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2hiceyntn.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbdnzesg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2kpizuxlc.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2hcczhegz.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mfuwxkmr.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2aeyikrry.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2zzvcukmp.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2gpewwsve.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2jhozvhdt.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2okrtvjpg.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mklysnzd.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksnbbqwj.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztbgzkxj.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2vhtgxksw.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2hpgqulvo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2tibgwjkt.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2rlcylkql.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gt2yncaqebp.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxkvcfcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ethgboex.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2gelcregc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2sbiyssqr.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gt2ibqnaczh.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ninjartn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2zyhtffyh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2mcdorttq.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gt2cgcfnihs.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gt2hsaxqmih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2stcjserv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2fzdgfbkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2vzgoezrs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2ekxzwphg.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2wqxzrdcv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2iumcoohb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgqmgmcn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2phauegxu.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gt2ukamwksw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gt2hidzixzr.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhctbgxi.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2eyxwevvj.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdtgukmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iojbxghg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2gxtbldgn.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2dtnalahy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2mefphmyv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2gvqmwsjc.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2cbjcqosm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qllopnvk.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2tjwmuegp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gt2kubveyfp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vndasgia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2almhnpof.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2jafymjjp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2fjjilkrm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2xtysifwe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2zccnbbfu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2lladkajh.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gt2wkfyqzzv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2jgtwmgwq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2yuwwiwri.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2rfchtjyi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2caqtplbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2vfvpdhxf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdetqm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2djrkreot.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2heltjxwx.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojnmqvpv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2qxycjxwq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2onvgtovb.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2uyfokuix.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2adbtdpds.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2cibaevff.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgeqbhej.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2opokbvfm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2ltxczlvl.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gt2jobtmusa.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gt2wvpqittp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2nswtnsts.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2mcrgflpg.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jaseqyuj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2nbsptvqv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2zfsjjbey.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2yrbcihhy.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2wdbxufpu.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2reaxbwae.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gt2zjyvxrgk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2kdnzxgjl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuhsigst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2skkyzfuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gt2bnvyxpsg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2ldsxzbon.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2uhmtbyoq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okmgwtow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2jwvjaoqv.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhtkeanu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2obrmhvmo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2qxfiunkf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2ihzckbje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2meguwvyd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2slgausqu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2jijjcmkj.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gt2xyrebred.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2jlnwtwfy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2fwaqdxne.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2asizoijr.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2klsrtifx.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2dudpvqyf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gt2mdnzzcdc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gt2pdmjgzhv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2nhjlnozr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2iwpsnxpi.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2skdhevnd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2rfwovski.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygkootnf.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gt2ubugkmjq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2jdotsebj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2usrdncdj.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2gkolfjve.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gt2bunvnmjt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2nhpofqmh.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2vzskaddk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gt2bjffithj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2hxkwcwqz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gt2ussitetw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2drihvmgy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byajyruv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjkggsgt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gt2ngffnyqu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yorfdslf.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2izepvaay.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gt2gzlkvfda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wplzlyzg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2jrcxprtl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2sxccvvga.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2ubicxivk.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvmkcrul.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gt2lvjizrpi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2okdputgk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vfrcqrnk.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2qwlwnwse.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hfcrwqhp.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2vdloffum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2dcaoueqi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2yiwkcrsx.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2ewjsxnsx.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2wdzhuxpm.html


<!-- 参考信息 -->