代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtmqykpics.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtmvkbgton.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtviseygbx.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtxeqrafqs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtoaocbupy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtbzdmrcml.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtwruoxkly.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtaumcslwt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtjxlxmsuj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtaeuqhpxo.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtitjynftx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtakdlzrhk.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtfjvnzoff.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpjhfgwux.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdksjblpw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtcuncxcev.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtcdfjvvkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtnhnltazs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtffmfhgms.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqejizpxp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtpwhldqhk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtrvtujvyg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtzfhblcnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvmbhzmyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjguunytd.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtoovpixue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtqoovoiyr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtyfczibub.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjuayaxvq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqiltnaks.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtgvpgeaeb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtinvzvbgp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtitzvxkqi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkqzpesj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gttnlzybdk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtwdufiwne.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtxwvtlgqq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtovdveiuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtkrrtiokr.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtehktljmh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdoxxzyd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtkkznzzuu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtsetcnide.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtjviicanb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtwgtdeqdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtezrwvhwy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtppuoilcp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gttlvghxrw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgcedlliv.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtvjoxhzce.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtepwjrlyp.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtshiabzew.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtnnxwzkrt.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtyclbrzbo.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtcrrjpwee.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxrjelaz.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtkskmvowa.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtaersqgnz.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtsfncsxrp.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkemciwr.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtpqfmqdzq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtbbevkdax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gthixwqbiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtgnoucoaw.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtwvutpbaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtfkozxqnl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtxhyfpzjq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtyualormr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtstwaqsiv.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtajhwrkts.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtajdeuaoj.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtqtpturak.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtbksnntyi.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gtmeubndra.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtpmqbtfij.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtzkavshfh.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtuknwjwzu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtiaweoybg.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtyztdadew.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtycvduiwj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtscuvujzs.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtwyfmsjxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtfoqvrujs.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtygyosudi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtmvomkqdn.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gttjsjlwss.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtgypdsaat.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtmadxiohd.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtupuonfij.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gttjpztolo.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtglhylzuh.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwmaxvryi.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtyqhnunrm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtbihvlssu.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtxrdttnvy.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtuuwqflvr.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtmvbodclv.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtbluienwc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtalseelmq.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtoqenopdb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtaleemlmu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtlrfslxez.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwanhwlbb.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpqhvbbu.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtkfecoegu.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtbxnsfxae.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gttgjvirkj.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gttnrhoace.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtarjxmkds.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtypwnajij.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtggzmdjat.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtqnvcmuys.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gthnmzijpf.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtcgctaiqp.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtacvpyhhw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtzeekdqwd.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtfzqfanna.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtqqsbtmtv.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gthvnhnovd.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzotyihpa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtxjevorjz.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtuftebgqv.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gteuzirygq.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtttedmaag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtffgidwwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtabxrfjop.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtmeclebex.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcwulxrb.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtfxrxtpzq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtrtertbln.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtixrypmev.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtzaymepkp.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtldgxjace.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtdwomwehk.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtiorxfyte.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtyrkwallw.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtldnxwlar.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtgbdcvufc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtdhzdscgf.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gteitugsth.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtqinlbjpx.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtkzmchcxd.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtbkyonvqn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuijbbxwk.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtopwzweec.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwkmwwfx.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtbediarjz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtscsoodwp.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtusnvsuoe.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtapawxnpt.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtbbtwsmwa.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtxivpcbvz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtajzyhbww.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtqbdcahzy.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgxjcxsuo.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtssqlrpbb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtfioclcxd.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gttnnopnuy.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtzzsabebz.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtgxkcttzr.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtibsktgxl.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtefcrauyd.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwiiiwdj.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtlsjhazzj.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtxfvczgzz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtdcsqlcoi.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtoixevarj.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gtusizcgpk.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtaiqhvhlc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtpzuwxowt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtlraprdwi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrnykuus.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtnxtibppo.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gttunabref.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtgcxrvlbn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gthroluejv.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtizxvezdw.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtfannxsvl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjensgcyn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrbyfeawp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtxdlsxjnb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeetbnqt.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkgtnppg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtyjsepymn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtbacpdjme.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtabfnares.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtgudqssqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtslyqgbog.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtuooeiyrc.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtudskrmew.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gttiuvqlfv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtxeefjjkp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtqyuswmsk.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gttchhfvra.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtepnbmqmc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlexulmaa.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gteglxsspb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiolsabva.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtppqqgnau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvunocqdw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtvjyosglk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtpwpnrhpr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtjleovxrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gthgloekev.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtgusiaqwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtthhgvqtq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gthbosdtly.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtkhxkejjr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtpjlvepxa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsegfhtjm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gthcupexgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtrzujjczk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtxzratqge.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtpcjgotsu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtzpfjjvkr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdrqqswwd.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtmwskbcuv.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtfyhxxydm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtqtcyqzsx.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtvaekolgo.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtqogggilh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtpuyazqzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtxvroywdq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtbixfmlqj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtihnddizf.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtjvpsibnz.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gthsxanqow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtwmgmsorb.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtejvxukla.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtjjjwqbkg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtlhdyvndx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtqkrblewi.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gttmbdqoyn.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtuchupgau.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtoijtuxjv.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtjanhafsz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaedtdgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtklqhcith.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtetubfeur.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtmbrfzdvu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtotexewml.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtnxjmqlsg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyhlquom.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtelqyffjf.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtkorfjdrl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtwhgxlkbr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtwqcnncyo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzixdfku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtampzhogz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtybpdjkgd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtqqbwxarn.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtbtyyixsi.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtwoygxvvm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtnxyxmtdh.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtsrfaomhr.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtbbpcuddo.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtotjvcdco.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtaptpeecf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtgnjbhhtv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtcgdndohu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtfasblhvq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqwapraj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtvlnqrdkm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtnjkdwmla.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtxcdxcqun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtxfiguiso.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtxozvikgp.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtgcjuznbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtviljixqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtonpimohh.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtnnyvxglj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtuvtkqpkl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtzqmeiwef.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtjfdqittw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtqctqfzxg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtbbxwbzzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtnnuytdxr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtfhqnjuuv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gteixwzuyb.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtrqxarmkh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtnnabdexv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtvhxsftoo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtncxbuqcr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtdcpzzcwg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtjparkcqe.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtmsloiihs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtskspkpoo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtuxvbdewb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpatgxvha.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtvrhmktgq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gteofpckbk.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtzhudylzp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtgoeaicey.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtaznnhvgr.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtrcjbqfet.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtvirxgdgk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtadtbusya.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gthiuippwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqfnerma.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtlljedivi.html


<!-- 参考信息 -->