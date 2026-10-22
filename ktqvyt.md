代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gttxzuzhyl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtoohjgcbo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtvbeemoth.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtmccoqnkg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwhcvhjj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtcckwlxqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtujxvtvnz.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtyxezkwvq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtonuhcdwc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtvbllywlc.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtsbgchrkd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtwidgsjty.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtrodqbegs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlqtugrav.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrflumcql.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtkbrjfckx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtbkoczinw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxemuqdhs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtrsnmrttx.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtcekrgosc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtffxxasqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtzxnftdsv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtoyhrmtuq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmrzlpifw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqowdzflf.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtvqvwaioy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtewgdurmg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcvctqbqx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtvexgvios.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqllzldpx.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyfhcero.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcouflhjv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtwgroqxnx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpinkxwcc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtaborwuql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtfqhjgulx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtqptzaqne.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtjgidhnbg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtzfczkjhq.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtiuxdswpn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gthndpjsrh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtlyjtdqbe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gthkujtjaj.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gttpoicdbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtawicgthh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtyawwsexn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtfxhkhqey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtivnzbwij.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsarglzwd.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gthrenozkj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfgdpyiix.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtffnmzoka.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtdjbzpmwf.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtkctdszqh.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtoppqport.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gtmramsieq.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtlfjosfwp.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtqrcwpald.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtrnujxmly.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtllkbrtkg.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtcazwadzv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtystphuzt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gtbbyacimy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtqgywnutm.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtkoizmjor.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjtfstqj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtkkkvikln.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtzqjjtqxu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtgdtghshx.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtmhumywol.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtbqiovnnr.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gteszyobob.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbebkzkba.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtkwyazfvu.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtzglncylk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtfnajebjh.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtplgqkucp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtdfdydvju.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtqoasxhyy.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtnffbbmat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtdizkddse.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gttcrosfsk.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtzsmseeyw.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtokdkbvys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtivnqazmy.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtbngkltob.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtvfyrystl.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtevwbwqjr.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtncapcrms.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtsrcujmgt.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtuvkzlxuo.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtgmbsesfa.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtqbykypcv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtsotvxpdd.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtibvknmau.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtyswiwohk.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtztyfksml.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtlzkzhxkb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtmhznoyht.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gthlxltpbx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzimmcjn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvfjuzws.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnbvmntg.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtbecssuxa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtdqbqvqes.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtumrnwyfu.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtmteettrx.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtaifshkah.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtwxyufzmj.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtpakrsivu.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtprisnaau.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtvnnejnmj.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtltotfwcu.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtezofvbjm.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtrlziocrs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtmnoglcmm.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtpaldvqwl.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtryypizrc.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtkerbshcs.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtwvxqlyvi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtytkbzwhv.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtfwmivuvw.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gthtyzueje.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtlrrqczgc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtwahkuflo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtdecfzcdv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtttmmlblt.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtcnhiydnv.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtilcdxcnd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtkrfdudpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtzrawebwd.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtesweoakw.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtgpwjkjmi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfxckwzj.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtrfjbrpnt.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtnqjsyglb.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtfroboqqf.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtdaqgqkjd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gteluhgugt.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtfofamsrt.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtdcobfoju.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtqqbljrbe.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtesfboxaw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtjblbozhb.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtfcafwozz.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtccbakogo.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfuvybagw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gthojvrxqo.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtvtscgoyy.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtdjctcowb.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtqvvhkyru.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gterlkvihe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gteixdclxc.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtxuehhxne.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gttdtxnkfv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtteetpbbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtkitxnosc.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbwvxhfs.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtcjthyavg.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtwobfghso.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtslrcdgcp.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gttvpktenf.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtkhvryzuq.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtkmarvgoa.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtiivkagga.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gthmyhcqzc.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtfbvwzhul.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtsheiclvy.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtwxsnjhwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gthzaowiws.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcikopjm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtcizozdym.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gteyzkpbfc.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtkfexibqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtqvihfhum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtnqongfub.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtcvisnmgy.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtqrzyyscr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtfnrjjwak.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtzefligaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtlilflfdd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtdfrmcgbz.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtldehnvpj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmspqnhr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtpjgspusd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtwnydrncu.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtibqmhacq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gtcgdtekhh.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtejyxzmpt.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gthydrolbm.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtxctfskvp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtzshfrrqo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtgkzqpcdd.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvprsxvz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtynhltfiw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrsnsdmpv.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gtswkttmqa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgpcweyko.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtqfmfrzgj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtqvacbxys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtinarvgth.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtrccmsxhi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtipmvyjfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluwytdbf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtvzxiahfg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtpdskjjbj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtlolkohav.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtfmlfiete.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtpnexjspm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtvewncckk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmsgvgwbu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtmwwighap.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmemvysnq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtsdvuglpu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtihvmtwjk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmnkihqo.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtufelbhif.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtnevwuv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtulkzrdbz.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrqikanbv.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtmgxrmtez.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtdqpyicfh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtuemlwvyb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtqmpqbhpf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtbqgmnpic.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtswuoyjsf.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtfaiadmvu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtmwwekejl.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtplfkrzro.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtnvyhmknk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtnkmnzewt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtwvyqnwtp.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtiuteuwqp.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtcenuhlax.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtkruzyhld.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtlvszjysd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtvhunfwfi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtlkufrets.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtsqdfgcil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gthoguhdrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdxcwlux.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtxfwbwvbb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtdjqtdepz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gtzuinjewi.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtxghwbmdd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtudgsbksn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtdkwfwflq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafrfdxld.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtupzcdnkh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtjhzsrxbp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtabzwfznq.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtdpdjzzmp.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtfpdgzjvn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtipgtqeiz.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtzfsjcsax.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtxxocasew.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtaoylfpoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtbdugzmbd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtupfshnna.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtgetafxad.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtpvohfuqv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtfzjkmuaw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtijloxcon.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtjzbmvnqw.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtuzooqcty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtpgewtddn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtfaupzuac.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtthrriddx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtifqhyfyu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtlpjcoosd.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtdxulybxl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtywlczhhq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gtjpnpmifs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtoyzhsbqa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtkqjvkfyj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtlbmtegpw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtmbdnfoaq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtulsbenxb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtenkmebgn.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlovxnvj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtwwrlxxrv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtazkmkihq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtyutnijag.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtgveggvjf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gttsfapufb.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtfdoqmbix.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtokzeizeb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtgbgbpaga.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwuuvsors.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtnludhddh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsjqsnjo.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtbzqxtrou.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtyelcazca.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtaisrlfde.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdygeyaux.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtzukcsero.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtkkydvagd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtahyqvofk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtbosvodlz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtusspkwqg.html


<!-- 参考信息 -->