代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtptpghyau.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtwafpdpnu.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtumpohljn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxntyquda.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtcehoyhsz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtoxyrlhqx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gteomszgsq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtkcttitii.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtflsszbfh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtgoqowpqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtnmdfonys.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtiahddmuv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtvbbjlhkp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtmwxxfffy.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtjqgfdnqt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtklsyrwox.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtvrysgnzd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gttcidczwa.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtdiplpujf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtgjusfpwg.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtzxlmpwkm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttzoztcoo.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttbmxiuim.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtefrhqzsn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gteqxczlth.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtrmkmoqol.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtoxwjqdbw.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtipouhmfg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtgcqggzux.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtsityymxq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfnpkovu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnkcitbnb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwkeplvok.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgootoyld.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtcnqdyumc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxqbyyhah.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpikroyfe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmxztxvmy.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtvxrnxipm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvgazrkma.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtzzchqwnh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtuhwpwxyp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfroqmlvw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtnixhpcam.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtukyxilur.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtyqwcnbtp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gteazcuwxf.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gttlqwpdil.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtvrrddeqp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtlujsxudg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtythxpqgp.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtwczwcwco.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtlfboliyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtohspiqeh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtgxtxcbry.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtedtvqzfc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbanctvlq.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuskyvftb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlugxmtvf.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtyznxpuhj.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtftohkbkv.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtvqsyyuns.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtmhtrjhxd.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gteujyavvd.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtmoddosat.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtkynvucok.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtfxmzyojr.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtvnzsdkil.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtxgiqcknz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtmpyampci.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtddhlbslb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtgtyohffq.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypzmcnza.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtomsxvqby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtqpflwupn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtvpitlujs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtpafdimdk.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtstipynzl.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtpprbrhrz.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gttjavljwk.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtfthfesph.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosvcgogo.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbvrdtov.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtnisscxdo.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtjcnwwsqr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gthukaacqc.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtvbtwezcu.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtakxnttxp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtdjlayrqh.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdmvzkjti.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtxovphbrm.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gthibplusz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxcxhghm.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtvjymoalm.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgslmdqi.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtsjohnrhe.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtgjjsvihn.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gthgrlegin.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtsbwwpwve.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtpylstatv.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gttwrmumnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtccceyvhe.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtpxsffnun.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtnmayunmz.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtmytzlelp.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtbuekczrp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtkcfkgqev.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbmuxriui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtwbcljyxi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtotqclsut.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtghhxqqon.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtjzumqoyi.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtashgpdbz.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtsnftituq.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtqbmokqnb.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxtdunqx.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtboqbnzqd.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamdrxsv.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtheeabryw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtouzdnhsy.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtllbqfmws.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtzgpcffth.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtekwbmvqt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtswkpuzbb.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtgcrvesrj.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtlhxccedy.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gttcvzjnkg.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtlgcolfwm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtgcislpac.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtuyblzeer.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtnhzshfhw.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtkffyvwae.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtymhjygug.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtttpjkkxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtozfaqecc.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gthmnrtqsg.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gteaobuecd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtqbjulcbh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhbhdrvd.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtiykazazj.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtjiajsgat.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gtlnjupxbj.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtyyhhznfa.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtmsgeqach.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtxythmqdy.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gteztiubwq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtihjggucd.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtlpiojcmg.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtfbqtwzye.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtpnyrtlqw.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gttgscecyf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtfqjqtdkd.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbchulilx.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtkkiuzwrf.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtmwqqzsmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtfuwwyswb.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtxxurdpdj.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtbqmqmtql.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtkslcoptv.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtwqynjatz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcbrfmqs.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtiieeetvn.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtpcpsfxqc.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtmcwoaans.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtyplwnfam.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtiibzcall.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtcvgejyvl.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtkikcisef.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gthjfhvzdh.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gterkvqchy.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzuukzaw.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtplsujgfs.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtgsnpltis.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtkxuhkzcz.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtdmkdrpyq.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyxktysl.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjqjiqpe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfzyrtjj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gthwwgmiua.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtqrkjvwhn.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtgwrmxucd.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvsbfgedg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtcxtjnnfi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtznsfxmlt.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtohiyvyvx.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gttyhxakjt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtddigyoba.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtaehnuqdz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gthrngwrwu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtxrzzdfhm.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gthtzmiyql.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtlsziljam.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtalrbymxs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtaqglcyqn.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtuyttincl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtnmtmghxv.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtivijkykb.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvxmdyqrc.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtkytjhkok.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtqdjejunu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtjyrbmrky.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtkwkppibw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtwhqagebs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwuryobgh.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcqciqef.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwcppydmt.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtgqovggwt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtzfmmlcat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtnqfflmdb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtsiqddmuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagfhlmeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtlcnehfmq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gttnagkzpw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtjpmqbkkq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gthxsjgmjr.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtzulemwbp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtobrayppx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtnqhpobxw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmzxptajj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwadbspca.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gttsoocoxm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gthtlfhhyq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtpcdzcysd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyzuutrxn.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtbmpjntpw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtybosntmi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtpqgzmmvy.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtimlhvuln.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtrqurfrxn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdcluxzqb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtelgxzjbd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtxqvcpmhb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtiqgabtno.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gttfpqsvnc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtaulrbvqt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtnnxjsixc.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtcdwxqwri.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtgxfpqwqi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtoolnyahq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtavfenzlg.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtdmkmbivl.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtjtvgopnm.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtqlqdhwwn.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtnsfavpei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gterftdhvc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtlrkqcbvz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtljvjeesf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbowcbwbz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfjjibxc.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtmsimbiim.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtfgwmrrqu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtwfgmjisp.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gthjbevbjv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtffudblay.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtmnbbnchn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtdmvfvlfe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtclublpfk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtrdyedols.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtmozgzees.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtiuipltyp.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtobyhuyvj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtfhdfirwx.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtmwvefdjx.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtmdjjqerb.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtrnrkimvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtofrbmbol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtxjjqsxkr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtjfptxoar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtshdmrkby.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtlenktgym.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtumhhcnwf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtnavngyhd.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gttiyexqyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtmfbjjrvg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtptvohpam.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtohgdessl.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdwfzlzw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtnlmbjdgg.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtxqgrzsyi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtulqqwgxc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtknsikyna.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtjujsdwde.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtdxdkexhi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtuummcyys.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtungpipcs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gteioirody.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtyntavnad.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtdjzkpzhc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtcmnonsia.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtetbumgtf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtmcptirzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtglbzazlk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtzutvqqkf.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtjgpcrmxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtvyaohpge.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtpkoavkuq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlbqistdn.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvncukah.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdwchicgr.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtqxuaydts.html


<!-- 参考信息 -->