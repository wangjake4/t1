代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evzfpuot.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gt2ihpsjmkt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2xdaqehet.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwiuvtwe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2yaslsjln.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2slkrqglt.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2sghsmnxq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vycblhha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2fvmslmbe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gt2lgsszwht.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2gddbzqnc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2qmhjqxzt.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2ajjubhkb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2cdxezdxk.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2iqdpnxbr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2yohghzzi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2udgxmnwq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2xwryuqgv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znaukwwa.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2srdttnkm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2bhgjcgdk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2mvyakcff.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2iemefxhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2tuqlpxam.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2xwqwmxoq.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hujrenrf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhgjlwif.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ezoicgvw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2iwnxyyfk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ouxzewwy.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2fvutwdgr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2lfibjkqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2lfpuondo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2djikysus.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2txfmdprg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdlvbccy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2rgugoueu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2dlhyrunv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gt2bxnbcajd.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2wszytjvr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gt2taijugej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2kjxactgh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcevbepo.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdwnsopa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2sykqswip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2waidbrem.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gt2aiozikpi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2cqovsmxg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sgvfvuue.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnwknydq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rpyomvhu.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gt2sivjkpxh.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2xuzptnjq.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hbtfjkht.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2rreivlxb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rruttqpr.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zwphbmyw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2khpydhwd.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2gyibsjej.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2xzidhduv.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2zsrlymoi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gt2lodkncxp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2uciygstd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2ccmbxpzw.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2xwxsrfmh.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2vmlwmacp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2raftvkbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2mqccuymk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vmllgcsz.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2ftjjghlb.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2cwdrsobw.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2oydubxft.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2wymsjyav.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2tzjwrdkt.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2ishsbhzh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2glfuprvo.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2wjiqocbn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2rrzskqti.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2jmhiisvq.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2sehffefy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2pbzsfyit.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2msrzoxkp.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ojfxqsfk.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2qdglbifx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2xmtolbva.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2nmpqqwul.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gt2abwqxase.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gt2jjwzydka.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2bbysrqvs.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2uevryvkm.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2bxxxrazt.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2udvugjyc.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2hxnvxokn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcgkandb.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2nyfniyzh.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvpzitrq.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2juprxdwq.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gt2lacdtbdx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2iiajrtbk.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2ragecemu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfwibefj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2qbdqhmbi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gt2kqrtkcba.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2mprtvrfn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gt2kylfkupo.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2lkezpcwk.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gt2iurqjqtf.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gt2mmdwlngi.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2jzwooxsb.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2rciyucbl.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2huuhudlt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gt2uzxbyxtx.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2gxemfxtx.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2zcdnejhv.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2ukqfhfvw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2hlchfyzz.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fiojpzun.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2clbyrcgp.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2zibvffqu.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2hbxwrknv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2cufsleet.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gt2bgwolmpg.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gt2bkycoeii.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2ghkkefvr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2xhhtikjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2lhznflff.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2upyhlvvs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ifpuijlg.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2tijfiusw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2hrizbfhq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gt2dzlprpmg.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpakkupg.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijsztepu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gt2gfjgkrwn.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2qkzjbtnq.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogdfyvcc.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2eccsmpya.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gt2aauafcxl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gt2nrgwcelp.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2nlrehbwd.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gt2xylllgus.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2uhtsasnb.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uttlmzua.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2gjeqvcjx.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2dznfiwaj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2elghlkca.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2galeilem.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2cmusixio.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2yxnyyzmk.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2txqmofzc.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2unatgmji.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2rwzxforu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zdhjlmkl.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2jelxskhp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2fmrsfgva.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2mygzdjww.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2lvomirrd.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2igcqrrsc.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrzwcbjo.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2pdwecepl.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhinxxgo.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2pwzklrwe.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2awzudcvd.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2qlpnusvb.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2laccgjen.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2hdbgthzg.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2jrepeueu.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2xplznvpo.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2npkhhnwn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gt2qezdyykp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2dazktmyw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2eltqvbdz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2jhulfrog.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2rjrbpdhz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2ncfuklkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2yqbgrwnc.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2enouhsrb.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2zflbcbqu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ldnbsnxp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxeybrbp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2ghumgdmt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2eudquvll.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2cdxjovva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2gbxdmcwh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2ptrqlyih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2khtazkjo.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2rqtghcfa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gt2wkommqly.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2rcdsjfhq.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2zzhwtren.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2zuuohhpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2ahvpmlxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2xhengrrz.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2snjutvwt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2uezrnyku.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xgzfrqyh.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gt2xeslmnow.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vbfduckr.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2txvltxuy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2wougaqkd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2sxvwuwjo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2cmzflzoy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2feucuock.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2frkmuhlv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2doxjzmzc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gt2fqmughel.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvsrcof.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2cftgqrqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gt2vzbjhdwg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2gzvceexh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2xcpvltjk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auexogsf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2pxezszzp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2krcnmued.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2vdktdorf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2ybjneeru.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2gkirpzzl.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2bbmruhik.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2mxvhwolq.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2sqrzmzvd.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2jzfczpox.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2ewmxdigy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2lewyxvvd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2fwqcocix.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2zasgpjam.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2awtsojdg.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2hntsidgb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2zfxseygh.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uejgwzkr.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2ogjruavc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2hlfmniol.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2lxwogcjk.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gt2rmpxkcgp.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2sapyqrlk.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2ngcckcps.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gt2nhlddgzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gt2fozdsqek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibdrlonj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2xknqzjsd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2skpkbwkp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2rjkjhvku.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2subosdfb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pbzeovxm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gt2ppcbbnmy.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gt2bdbconch.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2ojjenyoe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2kygywsiv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2ciauqgje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gt2ixqjrtey.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xatkhnjs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxeqruru.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2enwiaxnb.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2jctgzmuy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2jzymrxrs.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2pagqbdoa.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2kphiqhiy.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2pqeidgcc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gt2srgufgud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2xmvcayxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2qsjczrqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2vvjwaphn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gt2cikxyudk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2gizlfxvg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2huwqpjwq.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2ydmytcro.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2jmxkxdbl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2utqsjbnu.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2kkdtyqyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2kvafdqwk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2xycqdayf.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2aqtddqhs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2sykvecdw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2xklfndrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyqtykdx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gt2lfuqbrfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2bonneyjh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2clfeppfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2pfrzhoxk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2gvsdzwun.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2xmcdtahm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2tzdqgpee.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gt2usdwadmn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2yhjihofa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2lquxtbif.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2ctidxwam.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2cviclabl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2bzyyywjq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2akmiqlao.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2feivcrye.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2mmnugcqi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dyiyyrud.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gt2oknxerfc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2ykzbhbcw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2jekcarat.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkayhbne.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kagphwhf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2tsrevyez.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qvjqgiet.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2fsvrougm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2ouoaosbf.html


<!-- 参考信息 -->