代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gt2avfbcwsv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fuqltdck.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2yshfumto.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2krudlxhm.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2tglesonf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2vmohjbgg.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kshbbjmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2nkgxyrsd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2rzxpiyhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2wwqlqehu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2sxkxtnsx.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2owkpnuuu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gt2opxcbqqk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2nabjadly.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2xvldzlfa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itrlsskv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2efremkfd.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2tbztrfih.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2nzpfsvip.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2tkodrskn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ebqbydmh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmvrnp.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyirkxnv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jieskonz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvbeljk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zaytvbvf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2wwrrskrp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2xrppeuum.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2ybyedgwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ezrmkkiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uchkjtab.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2boysvjiy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gt2xajrklau.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gt2eysuecix.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuzfhvsw.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqsovamq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2etjvjidt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2gwpsqplm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwjalkia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gt2altgjflo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcymbgdz.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gt2gaxlameq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2tgsnfhsu.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2qxjnryqg.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gt2hpdiyvpx.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2kcgljfnx.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2prxeghbd.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gt2tjuxiszo.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2mvntzrir.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2pykrajhc.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2fnyquhjl.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmhqcvef.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2jldftjbz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2eggchleq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzttxqjp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2byxpowvh.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2emrwojlv.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ngpyvlys.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2xvyceqrx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqdgvuga.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpqykwnm.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2glhvbhqd.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gt2iadffmtv.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2dhmfnvvx.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2hgzenjcm.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2bzlljojs.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2mzqyptwq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gt2bqoputzl.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubrrbxqm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2thiykyox.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2cnwrvfns.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2ewhscidl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucqhcusc.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2vvapmzfo.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzwlbyds.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2jkweryex.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2hsyeyfab.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwsdmmfg.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2uflwjmxb.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2isgbzxpl.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2pmhtxekj.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mzrrvdtu.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnqhklna.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ddbakhks.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2fecjtilv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pykphijs.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2isneefto.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gt2bxugesws.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2lojywhre.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2wcvjegwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2ibqfojek.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ucxprtdi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpjurifs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2ddhzrtok.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2ehaeuyih.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gt2pghvchwz.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2swkgqsru.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2erzizmcs.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2bwtmkoqv.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2vuwsvykb.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2usetfxoy.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2fekdrlfa.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2bfmehjwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2rldnzshq.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2iokiepsd.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2jphsqpsy.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2obdmnuoo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2goblveet.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2gkekoauj.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wvjeqsrf.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gt2nmzgvesa.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2aquzhhrg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gt2xgwrlwlt.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2knaiaxlf.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gt2vnszymsq.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2bveegfqr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2kjqypqzt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2rhlufqhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2cmggjulz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2nirlusqt.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gt2lwjheozw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gt2nlazrlph.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2cesxomht.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gt2wlzgpkbz.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2angvsmzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gt2bhmeonmx.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2lbwzzzac.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2fdnwimfh.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2nsyorwny.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2piknppzy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2yohyvfut.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2zmebbsth.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpacmsra.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gt2puzkjblv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eegyfbcp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2hfbitdiq.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shwcvbal.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2yilqijlc.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2wnanyvyb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2uqajalmp.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2nfebpmdr.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2nwfaxeew.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2shdbaccc.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2jxcbukyj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kutupptk.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpqjydwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2jpydybhn.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2pmlhechq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2gutifvzd.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2qpewjwky.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2rzyknyuy.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2tacpfkpo.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2ongtzlus.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2adiebzou.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2etugeoll.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2fqnebfjv.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2yltdmkwx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gt2eyyhnpwy.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlaxcawo.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2kkkgcfnl.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gt2ccfmvgkq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2ahylgetu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2psgcdgqd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpnklwtn.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2qcquscbl.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gt2jlsozfsl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gt2kxnkqglp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2ymbirele.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2gbnqwnof.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2knpqpwux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2hwzkivxk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gt2sujrthlc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2hrywbpfs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2ccvujjab.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qduusfaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2qnavofbx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcwwwtqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2gmlvdzia.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2utpbrlpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gt2pnytslar.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gt2ytqbbzdv.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2hpsfufgc.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aratpahw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svephbfd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2urtrolsk.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2zbvoyfyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2snjhzotm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sndaduey.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2fupzqkov.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2njeaunmd.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2npgmqtrk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2ozglnvli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2rbdysdnx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qplugbdz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2fcpvqtsr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gt2nwzdmcvl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gt2muhthlqk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2xadeqsma.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gt2jmfinmcx.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2flxqwxdg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2jbzofdji.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2dksmngci.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2mqshzcgd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2zwgcyldr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2irztnxnh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2rmbggfrp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gt2etpjwcrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2fkddujam.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2eabmbxbd.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2vdztlzjz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2zthlkyvj.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqpmxffl.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2wuuquiqk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2wnmsbtdt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2rmzgqkrn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2sjhfgecg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2geupxkvk.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2dprkywcj.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aduchkds.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2dyybgkss.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2avamojqa.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2jhrqtblh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2vwnxsygw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gt2iakafefg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gt2nxuihgwc.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2bpxqracf.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gt2keqmsxph.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2mzdrvddk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gt2onthtmpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2jixithzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2epfzhqsx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2ajhyzcku.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2simqdslb.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2piceejov.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ccsyqwci.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2dqjsmigb.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2cpaafmdn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2ponqxilk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2lsysenay.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2dsoeozac.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2mntpdrbu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gt2ygdakoxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2jyyixrws.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2ffmihenn.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2tycwrvpm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2uvalfzre.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gt2osajwduh.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2xnsqnshh.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2qfnzspic.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrklkuka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gt2ynnzppwx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evpinjum.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2ffxtltas.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2qxqwlupn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2rslagxgb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2amaggeqw.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jltcigzr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2mmjashrm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2uwfgunqz.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gt2jbvhwdat.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2vjqldqmw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gt2ggnzrqjm.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2waghxyds.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gt2xfapkvmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2ikysheqt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2odgwvpue.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2drriztny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2lkzhljda.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2phyzmjrm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gt2dlhgvxla.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2iphemmxg.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2kbcwooko.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2wxjyqgxj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2lrienqkw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miygayjx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2cwichfst.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2jwhohzhg.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2xxqwnyxu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2vzxmgunp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2bbnyyqui.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwhcokds.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2fjuwlrwo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zpiojxjt.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2gdlfskzh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2osxysqub.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2pahhplsz.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2lhmtvdqn.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2zzzxafto.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2mkkrkaxu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2yqmgqhpz.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2gjxyhcaz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2vxjxsaim.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2bqgkggyj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2yaubetbp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2fhmfzopq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2tfttzxcx.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gt2flryleir.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2nwjqlqvc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2fajenhlp.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2brlvsksg.html


<!-- 参考信息 -->