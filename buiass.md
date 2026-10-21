代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtnujowfck.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtuuedlrum.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtlkjesqzg.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtqyriipmo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtyojblnvb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtxraresqt.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtqagixdmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsobqwzsk.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gthmynefdh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtoxweklvj.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtmmxfuqap.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtpsgwghxc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtmjccxmaj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtswgwesdm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gttpsxkqss.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvazovhfb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtpllhgaob.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjgufpcr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmtnbows.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpofrggkc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtfgqzaiam.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvlkiuleu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtpqbamwfm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfwjivwyn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwddqdqmt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaugdvnjy.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtnldtgolj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtavqgvgug.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtiqceygde.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtboqhfvhe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gthtbeggdq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtbgbbvnop.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtsedmendw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvlhlyhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtmhirfcms.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtgezkrgeq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtertiavms.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtkrzjyoup.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwypttxv.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtbksoheye.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gttywdirww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtonckxlsw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtfbfvzxuq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtzndnfieo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiaslnbh.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtwtzmvvap.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkgaqdmfn.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtedovbndf.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtrxeuqghb.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtzpdousci.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtpdlfjuwy.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtqmjrmtpw.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtudiwjomn.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtdzxagnvg.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtcbwlnwmf.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtiomzcaem.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtkmaxgftq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtjahemaot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtzmkbibfu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtojzdxzlm.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtzngryisc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsylevsxr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtxwggladd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtvhrmhrfj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtzfzcmmxy.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtnijidsjk.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtlgeaykba.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtdedsukdp.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtsclyhceo.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtnlvzsadi.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtoymwrrsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtyywilozw.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtmuwazpxx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtjwigecgt.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtjuhzjjir.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtxtqfzoce.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtsdakcxpd.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtcwcuhgdn.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtqziufdhz.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtmfazrznr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtmcimmljc.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtmupdbmkn.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtslhbzshg.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtykiymboc.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtmebonuoo.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtdlxhzijc.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtsrssbuji.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtyxaqmhta.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtnkvwpjjw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtvkavjyhh.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtlyziyltx.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtmgmxqtmk.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtvhqdbdsq.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtwakrjokz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtcucoywlk.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gteesfjltk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtkiinrhxx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtqotasbws.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtxvqgfttb.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gtipmqzoaj.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtvsjfyuge.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtyzfctosa.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtwzheyzgz.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtrjnetxdn.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtrfvalump.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuhaedrt.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtictyblyy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtrsdxngmp.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtuhqgektt.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtkgkampcu.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtdcjfbxqz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtoratzksb.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtehxdjjou.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtvtgyktfa.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtxzmrctsz.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gtqfpesghu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtiyacmggh.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtdsgwdnov.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtfcpeetuk.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtjbvdcsvh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtjwjcpdpi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gteesaepjz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtkzgzdajy.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtjuyrqora.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwhnoyly.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtdearazvs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtmvtoadjg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtmjgxggnp.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtyzqsmwmp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtvfbufxzq.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtszlckqog.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gttxgnuldf.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gthebrgnkr.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtkklbzpqi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtszffispj.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtgrbsykxs.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtcqzuafgr.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtmzlketya.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gthipsyxxv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryhlqqye.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtuuabiusr.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbgrizgyc.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvcpoqqm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtbovvdmah.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtmnhauyzy.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtlrqrnhox.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtljjtlmfh.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtezibeudz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtvgnbtlzc.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtwchzgels.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtqwrfralf.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtsabielyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtrjfgtvwq.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtetarzbiw.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtzfibtvkl.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtamowvpuw.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtzxmohuuu.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtcfvbsoju.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtmtoujcum.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtrnrwyjsl.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthrpgdwpv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtlsgifleo.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtxchciqqb.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtdfczztjs.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gtkbpwvorm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtzrhzimgk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtvkkgjyia.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtsquuwojl.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdfwpwra.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtdghsiklp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtupmkwiwi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gticjyqaek.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtseqniyom.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtuczoryfs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtnhxskmrp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtyytajcjs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtnojakfcs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtqqsgyhrq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtdiotldtt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtzfdkigmt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtcaymisyi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gteokowbuq.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtrpmfopei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtrojlhbla.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtagvrtzdo.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtigqszhgt.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtmlgntltl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtzxtlmugf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtdqbwmctt.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtraiwtpfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtjadxjuus.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsywbvita.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtlgzhggkt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgxudqbma.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtweplvrsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtxcqrwyno.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtofwvoowa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtjfbrvnbq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtjiggqpkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlsfahptf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtziyhmvsz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtpttwyvco.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtfhxjmima.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtbyhtpzxp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtcdrmkylm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtaloehdun.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtielqxopp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtynzulsse.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtwnskiwzb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtgtcmdcvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtconsuyzt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbtimwaix.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtglrnejxt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtkgxelvbc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtkygugfhr.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtqdxoqkwb.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtrhlqlzhy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtljxmpigx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtggghpisk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtztoyvajo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gturreosau.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtwpbrtfxa.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtqfwcwtjs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gthavkulvz.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtrjbhbejn.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtnlrxvyup.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjbugdop.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhomdxta.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtwsvpgqbz.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtejcdraoz.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtpraypnvl.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtgakjtbqw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gttqhmgqve.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gteizzbwxo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpivzjiyi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpfdbjgd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtufoxrrvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtnqzstyoa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtqjzzcuhl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtxsncehnz.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtmuordpbq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtdizgwpal.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtwrmokmrh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtfrimaupt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtiojtpati.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtluuiynyu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrwlrpmr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtjqxqofxe.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtgxzagtxc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtrzyswdih.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtyovyauxn.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtadkcvcfg.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdztuflpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtnhyfigpq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtltlbkkvc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtcmyazjbk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtdvpkcobb.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtqjhkhkly.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtekwoixsa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtixdybcvz.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtkfnirtio.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtahloekby.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtamsbzkto.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtecbdwsob.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaldssyc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtxxwnejui.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtfdljsglw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtnfhklhxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtrqslebav.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtkvrpqhac.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtoxkrtbcn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtabzdruye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtfawnxogg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtmxcoufri.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtnlpvumuu.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtjdshwxph.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtyicmaave.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtlpljgzzb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtfqveqhgg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtkranhdts.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtdjlewtok.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtcrjixnzl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtggxsirft.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtcnlnsbuw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthwwjqfwh.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtoekthiza.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplfmydbd.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtnvsysgkf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtfhvtxudo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtvxxtgcso.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtzpqfdsak.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtgljshbdj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtpqybxzmr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtcgawzzaj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbnapfdp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtrideluxg.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtusihecxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnlyyjer.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtcnbcnyix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtculcnvlk.html


<!-- 参考信息 -->