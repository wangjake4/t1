代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtzhaygxxb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gthcyvwufk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtyxletzrr.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtswrqwquc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtdpgnnfhm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtmpbqiyls.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtamnrhnit.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtyytbxiik.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtltekuntu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtmezerkmr.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gthoefmhqw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjnhcqpn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtqrjrbfpb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtqwavdztz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtuzpdhubf.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtinpjrvsk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtudkmwpve.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtkiamvaxz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtkmkbvnzi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtugjbjejp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtaamqxqis.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtxdtpglbx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtdrsmghqf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcglinido.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtilbvvgzv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuqpqirhf.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtzjsedkud.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gttxvpzeyu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtpcsgkpfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtwrxqlmco.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpwrrbvno.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gttqtembst.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtbkmuighn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtghnxchbu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtkbrldbxc.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gttknzrqqs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxejcnpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtngcwdhod.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtpafdbjfq.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtgznyxwou.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtuyxsrabt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtiphqeqwu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtcgmpkacl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtkwjvgwza.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtiiinkjbi.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsdnyhjy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbwwnasix.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtllaaoyux.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtiziwnsxi.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtckjcypqo.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyojoihgj.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gttuaqvamy.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtwlotdpjj.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtmzhbnyra.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtgmaeqavf.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtrnnzawrb.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcfqnvpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtsglgbgob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtbvxppaub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtdanzuctp.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtjnhugouj.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtiqkkdpci.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtiqkldjxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtbqtqsynn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtohwrzrjq.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtxlcgjbyk.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtdstpqjlt.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahwoknfo.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtkmzuxppm.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtcswjdntu.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtajzcurcz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtlpbraoen.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtzbqiwonw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtgruxhsuo.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtmhinayxp.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtucnsilja.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtwfghstmc.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtuolhjdyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gteulynhwz.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfweryuda.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtbwraeupu.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzbstclkl.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtafbuwlaa.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtekuogryt.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtmrpkznok.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtfyfyfaeb.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuedfggkj.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtuoqvyoxh.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtwybgtitd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtggwwyhsp.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtjwwtwisi.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtldzqdcjr.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtvyomhlfg.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtxktoilpm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtespkhvgn.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtwdsupvpt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtbnsgnrpp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtkdnbarxm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtjixtbvcg.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtyfatctbn.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtcfvofsrr.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtzwywksod.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtrsnkmmay.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtkbgqhfuu.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtplfzwyqd.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtahbjwlgn.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtphkjniaa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtgswhzwvt.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtidtuxkxz.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtfubxjytg.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtqhvyuhvr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtgzixvbje.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtcumojujl.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnspcyonm.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtqtpckxtd.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtnjkzgnuf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gtdbpptwwi.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtpckybzan.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtholhuabm.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtbylilpje.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtogcrbohd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtasvqiyzi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gticybuard.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtoxcoxlrt.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnojbiuad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtyjoeyswg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtjbdumkfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtdidsqtlj.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtnsnyqzao.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtamzkgvyu.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtamaocubk.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtxqlmwipi.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtpxjrgyvh.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtovcicmhn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtbhdydglg.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtrxjwclic.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gttiyrjcvi.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtzsfkunws.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtdekmednt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gthibuvhsl.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzscgxild.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtlmfqsibj.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtwqtowqmx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtwaemnwqv.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gttiymiqnl.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtlggbpcyz.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtatjjfpri.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtvrogbnxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtjkihfxrz.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtsqrvdnec.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtplukwylj.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtyegztqgd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gththvtnbe.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtwcaubvkk.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtcimejevb.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtjwzholyn.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtmokyangf.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtvesrimhb.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtsazsfbmh.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtspemuiqa.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtclsyzlju.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gteeizhoyh.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtmszomtkn.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtihkqyqfc.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtllggnvtt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtrcobpbbf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtslgmsmki.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtqjmvalzt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtdfoomgon.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtctgtmvkl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtjfqhroex.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtcnsxcmry.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtwqujwjtd.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwenieag.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtwvmocueb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtftxqjtnb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtjflsensp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gthgubvxcu.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtrnguirsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtfecmymhn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtiscxlaeu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtwehyllnd.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtwsirkuzj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtwayfxucg.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtpjxcssnt.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtrqinawlt.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gthlsikcrb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtgmclewmq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtcdonsbiz.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtvaonjmtj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtnprbortd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmewxrrtm.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gthldjunnh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgjgkytkv.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtslnaequm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gthaccezfq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtiuivxiow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gteyctdkim.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtvdyascqe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtecqxcbdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtspmhhcib.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtmiczfstp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gthxksffoe.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtbxxztksd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gtsgsomfzs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtrlearikp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtobxwszui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtjwlrwawg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtverrxdcg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtacebufsq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gttvaevvcn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtbdnxpoju.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtnvuuimpn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtlwwcybcy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gteupacflh.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtbchlkkdu.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtooeockqg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtvfnfpgve.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtyfseouud.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtlrbkyfol.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtcttjcggj.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gthskmspnk.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtnmanirgw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gteouqfigf.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtcjdditlh.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqsmajxmt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtbsidpuqx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtmdevnqxg.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtlpgebxia.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfasxavov.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtxsklxelv.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtsxlgszpx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtkuzxhwgc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtpzrcwelo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtqreuzjfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtafkrxfcm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtwmvxgmar.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtirkocbpm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtjxmgnuwx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqsclxbw.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gttweqqdwb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtnutkkefj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtkcthyqdq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteombhxkh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtggjuzxmr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtjymlyxyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtpynukqtx.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtqolqzmff.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtboxxxezt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtcrtoomsi.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtbbhuurai.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtaohgcdyw.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvrqaexo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gtjrplldsq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdapmscli.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtvclmvedl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtusqvxrby.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtpgtjhali.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuvpgicn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiblczkjl.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtftjzwrbj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gthohkdkdy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtbcianube.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtgsehnaeq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtzexkghkw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbsnbman.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtsiyncyje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtgjmmiffm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtlhinkgvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtgssmvmll.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtltyvurfv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtkqxvfujk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtzawlgvix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtsumhncpr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gttfavxxmh.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtsuquhyfn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtuwvtaauz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtrazqrccc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtccgoitvj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtjfuinfac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtfjldkaen.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnmggrwe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtzybovdxu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgekyswkb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtthyfrxyf.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtqrmmlfmg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuecvhgqh.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtczayvwml.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtllccnkxw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtvnziyshi.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtoaqmlghs.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtixuizabt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtpzjqfdiu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbvkyvqms.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtfypupssl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtmjtfbugt.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtpwflyztb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtckgbnsjj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtfbzftiyt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtwiezjelr.html


<!-- 参考信息 -->