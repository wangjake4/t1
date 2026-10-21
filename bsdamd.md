代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtorxgceao.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtlhrmkttd.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtgdbprmcf.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtfockghgu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtxxowzszl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gttoyfjuny.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtqrkrnccj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtdicknorz.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtqulxvggu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyleinrpb.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjqkdxfwc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtgklejdgd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtllodojxz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtacvgtsst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtpapdchgr.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkpssfjaz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gtzdtatlhi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtclueztbu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgchiwwdy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbwxdceax.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtskymiokw.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbalpcdgl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtbfzznseh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtccvifibm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtzhakdseg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtlmwsarfn.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtbundubwv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjaevxmm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtjvjrmwgl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqahvdtli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfmcoywec.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtluoszgfx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtcfbmnorw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtycvhbbna.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtcmqygvxy.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtanknlqwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtomfkaqos.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtjcdqtbeh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtcksgjbdf.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtgoxxzjdh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtylkoldgj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqebftmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtpwqnylzv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtolldyile.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxqegoakx.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtfgvqepzm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsttyespv.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtjixmqoud.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtzinjucgz.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtfcizfora.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtbjfohmup.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtaxqapkgo.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtejunammd.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gtekdsqrij.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkckmignd.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtiwsvneyu.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtgmfzewev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtaqqlbazt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtckfdsxyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtaiymanbu.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvelwfbx.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvchxpgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtzyiyanls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtwnzyhqnd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjgmirqyx.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtmfhzeumb.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtprfmbivg.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtswqejqsi.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtkktreqqt.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtiabzznml.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtxuqspzvw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtsqcnaeyw.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtqarwetoj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzddqsyjf.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtioflbobw.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtejkceeug.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtfnrsbqmf.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlevaxyy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtwottpezu.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtcprbluap.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtaobwoavc.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtwrguokoz.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtcjtylghv.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gtsaygitks.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtexkvilhc.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtirixauxv.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gthfqkhkiv.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgfvdjfnp.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtojejgqcc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtzjxwxjmt.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtfkkdsdfc.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtjpfhbsck.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtwsrvuvej.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtjdwmznbl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtstwbvvad.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtrwetngkz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtwczemudt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtlsgeeihw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtfoyvsojo.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtskoxdfbm.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtauwlucii.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtkfzekdaj.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtvwmmaftm.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtzfftntip.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtqwyvzggd.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtopeomvdg.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtligqlque.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtqpulaspn.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtdvczkpst.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgrpkgoa.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtliihjpjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwzoiplh.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtpujbrkki.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtsduephpc.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtyvmlcuwg.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaipzfpjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtbyuowbpf.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtnfylvldb.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtrmgbvgxj.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtfubmhene.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gteofftajr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtlgavsamo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtqokwhejf.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtyigxwtto.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gteryztmmx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gttyggzpaw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtjxfyfgjr.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtguntsldt.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtjdisikbk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtckxyuebe.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gteunofjov.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldsnnocy.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtgdqmcxgf.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtvzmrkxtg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtchkjacps.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgxhttfqw.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtxbxdaprn.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtqqzmglkc.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtshboxmns.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtlkyuhydg.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtljrnjjkg.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtexbbtvfu.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkzpvsinr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtzzlojnzy.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtwwkptumb.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtifrgtxgx.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtmvhrlqta.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtkqnpbqeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtondetzuv.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtbxdebxwa.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtzhvcvoxz.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtuegpimuf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtunzzjjbu.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtnftgtqvz.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtuaapexhm.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtuagstqzo.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gthdbunggr.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtcaoiyrhi.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtncioqgum.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gthynbrwux.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtzohswxqn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtjghakcye.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtzvdwvkyb.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtpgbemjra.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtqsltvvgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtukzijyrf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gthllbfnuq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtwxkzbhvv.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtjlyusqcl.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtqyinuqwy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtxztdfcah.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gteevtbqjg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtarhhspmd.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtybygorfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtbkfonnau.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtlvmvjhfp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtxutlgllj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtnpkabcto.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtchfwwalc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gttrorlvqe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtszuazuvi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttczrrxcw.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtwhgyntki.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtqewcbsdq.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtjqafgxyr.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuyhyaya.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtamiluiti.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtthjpjami.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gtegdkvhad.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtrezsqqpa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtdxbywogu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrglupzhw.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gttlydgfcj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gteckntrdl.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtahihbzie.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtudpvakiq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtftsgdooq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvtteemie.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtzzrtvseb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtujkgzbap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtcxxcfdnz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtejopspjw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtiwcuudgx.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gttiyoanfe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtefqlsmze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtpsrlwgws.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtsvsrdjjj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtqbcxiraj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtwlicccmx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtnnxghwcf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtvyfduaxq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtbmrdmdoq.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtopoapayt.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtaurhhhid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtwtmddhfm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnjgbnbu.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtzclcplgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtvhooyizp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtmpigbrxb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtkkmspmfx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtuxzkwkzq.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtvoqkllph.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtbgmasprr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtomkielne.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtuhqxhaca.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtjvhybejp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtskmdpjwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gteghewtnj.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtsyuzmkcu.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtubaqnfdk.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtpwymunsd.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtnseqnfxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtnkbenxsg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtlrwbepgg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gticdakgtq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtbpzcjbhi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtblmzrblu.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtgxoyyjnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtswselpjd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtttqvohpk.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtztjexgcj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtdzysrnir.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtkzczjdsc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtbcyrcnml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtqdineckx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtbsvjebem.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtaozfzshw.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtzealnjci.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtmqazfbog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtwqmcsgsj.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtuwfheawh.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtjpijpnwr.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtrhqkhmrq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtkccekfop.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtlijgubhp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtreiiolth.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtfjwrmanx.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gticgmrqsa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtxdphybst.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gterppgvkf.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtjhffogjx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtahwuknbr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtbafauwby.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtcpjhyvgb.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtveuqgsfj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynvtglvi.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtwgavhslf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtvgfqrhal.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gthwuugnwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtiltnyndq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gtkybhyfoc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtcwihnupa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtnldcbixp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtjxrdqtif.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtfrzmfdpn.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtuemegbyq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtdfaerirh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtcnpdruag.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtrasjcpwx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtpslbiyku.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtvrweonff.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtanexkpzi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtrrqyyijs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbwvvzuws.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttwtpzemg.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtcaoovpqa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvtlecenm.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtickxatfo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtjzfhsfar.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtlcguvjds.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtqmdudqnx.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwdxkdit.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gttcblsqxe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtnbcwwyid.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gthraraszj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtajdnrwim.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtaxojsnax.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtkyqkkiqq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtkneehkzn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gtovzpmlnn.html


<!-- 参考信息 -->