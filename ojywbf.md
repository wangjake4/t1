代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmqhwqs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtgdtdausg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtpblsvovi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtkwvodwvi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtkigquyup.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnqhrmfw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtfncttdha.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtgqqtinnl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtwqohgrhi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gttfdukime.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtmljkmlta.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtjcthxgnl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtjefzjlpz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtzvqwvwii.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtrdzhfhfu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtfypkowmg.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gthsoilkgv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimfiodjx.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtpaeagpga.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtjeorxcup.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtpaemwimf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtmntcyttk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtvsesrdkj.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtyzqjrfjs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtntcuzxtx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtvzftkllj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtcsdeywti.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtijkbvgzs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqsltirjl.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcelvxidg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtxpljqikq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjgncunsw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjkavrxdh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpoffjmbq.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtcftrdmki.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpnvwullj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtixualrvd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtsinjfbpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtixzlqndc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtqstkjgbh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gthglyiokd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpijnorhv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtrnmnbjix.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtiraiprra.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtkltusmzf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtuioqoxeg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtalmfjliz.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gttgqrasnk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfolhflja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtmvcmziwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtovgxkbxs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtrxofedby.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmoklxpdy.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtfimrcohn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxtgyfbaq.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtuvpmzghq.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtzyegdeoq.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtwxunaayo.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtlayhehvq.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtsxdyrjxv.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtwbdkdybz.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtqgheulgp.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gthekoktwu.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtkrchvlyk.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtimlcbjxq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gttpzfizsi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtmpnbsbji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghkoqqzu.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gticljuzae.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtpjtnvndq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtnsmcsquc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtugwmlqfm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtvsdpxsus.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtrwxprkyo.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtpawekchf.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtwpwczwvb.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtsrvgnmdr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtzqkpaebz.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtkvchynxh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtmdzqjtep.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtkbdyhubt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtuyddauzp.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtmadrzcdj.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtkwoxtlsw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtywjbzrvb.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjxiowelm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpkaqfoi.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtjfjltxuu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtvarqvvjr.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtgfosioyd.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtqjqtnskr.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtfolqjqqh.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtgilqctwf.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtcjnsotgo.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gthpnmqcbw.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtwyhulsbg.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtgimgfihe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gttkvzfmyb.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtfxcdzxal.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtkgofafbm.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtyzsrsrsk.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtyzqdeata.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtkodkybjr.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkdumssgb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtwvuwhraq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtccihyjda.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtkeklqifb.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtbirtpmau.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtfmsokoal.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtznndaugj.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtogocuubj.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtwqbweyqf.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcidydyri.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtfxynhxop.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtporqyzva.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtyjhfwqec.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtjwtqnbuq.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtmlwiaoxv.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtjqcjhuvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gttesfxbmu.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtwvvcainh.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gttwujsrly.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtafxuhicz.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtdhwaivhn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtmiumbajy.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtvxgqeqxn.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtlyvoapdp.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtiaryhwed.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtrswyrpas.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtrlsqyqgb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtteobohwm.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtjvlubfli.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbzhltpwq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gttesekoka.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtcjfrjygo.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtcsbvxcnc.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtjsrqyasv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtkxrutomo.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtzdaokoay.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtqkybyfwt.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtkvgmhize.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtqklrizxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtyampaufc.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdctpwfj.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtdxflfzil.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtrfrvmyty.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtzituvmkx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtozugosbn.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmknykdpl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtfiyhuykz.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gttevzgxtf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtvnqbyskz.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gtbvwdwvat.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gttvtqdkim.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gturoxyzod.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtaakjznhh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gthafujojn.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbhuahjgw.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlhneqadm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglwesqei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtunojlpne.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtzsehddiv.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtjnrjkldx.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtqgbytpxk.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtuhrrtpaf.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtwnedqfno.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtsobejvlj.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtpmzaazpd.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbifxwrmv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsatmpvm.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtdwjazpqp.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtmbptshca.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtkdtmglvp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtrymkgrkr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtqbkswgkn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdosxcznn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtfrwothny.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtvmrylgrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtcprbhfwp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtldcnanib.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtponhqwuw.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtkoratwjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmknzfpn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtstelntlb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtxfirwpbu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtgpchrbmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtkxgrexjw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtteyanfug.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtunuxsbhh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtxorjnwrv.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtnrwtrzur.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtbmfzrnxo.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtkmmodsep.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtpeuixwlx.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtsqdbnolu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtrywtrpjy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtxocybjte.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtdbilpemp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtwjvdjabd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtznwpgtel.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtnuztrsfa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtklnyooyw.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gteasrroym.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtmfcpzdgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtxllqvpaz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzilgfuc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtmmrzerqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtdlflmewh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtdrqmqqfx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gtjhlyfibl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtbqxxicic.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtzesrluxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtldxnoqoa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtcvunpxee.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtpokuiobf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtbplhxfps.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtewigccfy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtxcrhnpwx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtolxzucav.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmnvlqudu.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtamhgbvou.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdziohlc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtcrvocdut.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtqnlrvpyz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtobpiwyuk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtlsuwmjmh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtzoyxlwal.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gthfzjwjbf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtgqrwtcgt.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gttnkvpoyz.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtucbeqlgh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtaudjrzdu.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gthrxemoly.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtzcbwrfub.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtlnqwlpgw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtsoianjsz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtovknrwax.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtfgzjhgpc.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtpajswufi.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtjrxiwtkk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtqjxgisgc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtpdqmazof.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gttqzrzvfc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gteijbxcbd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gttpyiufub.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtofalpjau.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtxtleazvl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtcmdutnfw.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtnqflpfxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gttpwlehqe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtlpsermxj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtyranmcbd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtvhaeuync.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtlwstppcd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqwxoafv.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtonkxmaxr.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtebxxdrpy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtkjdpcosq.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtgdpnpcey.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtfvbvomnh.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtuhgdorgt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtkazaoigz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtqzwacnzm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtpvvcsmjt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtloxpjfth.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtcoehhsbb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtdbfbkjdz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtmzprihhy.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtgzqgmwez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtlmwapvir.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtfciicgjx.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtgyeytwbk.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtzaybwykx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtdiwsqpxa.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtlxhfstlz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtjqgtdwtg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gthwwrorgl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gteyuhxcxj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtqylhtiuc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtfegztyzg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtpyuwrhhb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipghtktn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gttgpzrifa.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtwtopbbdd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtkuphtdop.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtpxwphykm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtyfcndhhr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtzvumwtmj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtvfmdoetv.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtbfbqjilv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtngjbdzoa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtnradhfjd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbwbcfazm.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtyplmkazt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtadslebqp.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtfpcfinut.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtvjwaqchm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtasqmuiox.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtnjplsbgw.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwbccxjjh.html


<!-- 参考信息 -->