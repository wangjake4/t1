代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtmnlmnsnx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtvtqinisa.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtomzmzdwt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtlgbafbhu.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtfsqmfvqu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtepcuqfgl.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtwulgxrtu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtctfnbfrz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtkvsaezsj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtuaoyaogs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtejyzpeel.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmdflwifk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtwnxwlccd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtjgfltnyq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtmmuolajr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtmofywosf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrxzkjwgu.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtlyazafsz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtqfkxgugg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtyngunkka.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyqdsgdcq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsfamyazn.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtjdfahlhz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtoyrgcrwg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgqtlmfq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthfkumojm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjsxmsdgn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtetbgmart.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtxbceebbn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmszbxblq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gttzshgqdl.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtuygdhthu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqhfcnm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtyozcsdok.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlssxxfr.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtojsmnlnf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtjaxvbusj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtpdsdwyaq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtajccpphk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtrnldxugl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmujsnioh.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtsfuzjaox.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuclknkvh.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtcyjsxken.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtutysatbm.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtcifftuvq.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtokjleboe.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtydblchnc.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfxaugvsm.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtkhrqqnea.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtxhuwgbtt.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkrexeej.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtybemsjhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtwmrkxiqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtpjlniaba.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtdnwawrcw.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gttajwgipa.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtqxilkxuh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtbjtpdfbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtudqfcivf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtiunooztz.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtzrdwnjpz.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtbgtygxpr.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gthsywzyqu.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtnlqbxqjh.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtsrcgrclk.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtgnbwohvt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtlkpkrwab.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtqgbelowe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gthakupabm.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtllngpebz.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtjbgjbynl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtcfnulbpf.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtjehifjnr.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtthlwximf.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtcdmahrud.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtkfecqdwt.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtukiavbqg.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtdrmlblxv.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtpvmckflb.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtuvssjygv.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaupldlap.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtpcvtlooe.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtpgnobtph.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphrxmlgd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtixhurzqz.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gttjyiytzv.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaqvaymdi.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtnxnnymnx.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtmmmaiuyn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvaxmhhkw.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtsncfycfj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtllipbxss.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttbtuyqzt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtgaxivszm.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtjftnmsad.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtgpgyumkl.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtwattmbzg.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtasdlebpo.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtghztiodj.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtzpyykpxi.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtwcflrqrp.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtymlcmlud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtjmqqlten.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtqikchnqk.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtbphpblph.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdukianme.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtyjztsucx.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtlkqukkqp.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtbslmzpdv.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtjkguyoic.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtantbyyuz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtytokkhao.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gthjzpkxjo.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtzpzuqslw.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtknwwujtl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtkdgzozqb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgamaltoo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtnajzibtp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtgijbbdzt.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtebylfooo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtazwxnwtl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtytswfhfm.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqmhscia.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtettmrqnp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtxarmzaad.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtvgqcxmga.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwddjhveo.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtavprzdom.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtkbrbyboh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtadryuzuz.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtkekbluxh.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtkuadhtte.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtyohjkhrv.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtsysutgkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxojtuzbi.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtojgjdofb.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtxnjesvvl.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzpvlctav.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtrgeslavb.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtroobebiq.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtreiatsee.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtoazrhbkq.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtrwmnecvj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtfiptbfnq.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtczpkzmjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gthemhkyxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtudmiuvmi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtudanhkqo.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtexdyysuz.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtotxbqmng.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtjxpdhbku.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtncreblwt.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtcjtylisg.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtcsklsgzr.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtjeywruhm.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtlnsuotdi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtsfncjysb.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkjmytxr.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtselzjkte.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtyyycuhet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtntrnhshs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gttmvvgtxv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtesuxehtf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtprfurpot.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgcydrjgm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtiewqmtxz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtfvbfiiqc.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtrdixqect.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtwrmuylii.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmzoyopx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcyobhjei.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gttyykkroo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtnldrwsvu.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtjwnnvcfv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gthggmirfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtbvymrlad.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxrmiymb.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtqpylubuo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtoreubdgn.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtevvuseoh.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtinntcakc.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gthyiezddc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjaiatdu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtoefhvyca.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtpzrudubp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtatmgkwex.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxpgzxqrl.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtqwshfqen.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdvvnblsn.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtmmgxagsj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtbctcabqp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtreryqnbu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkqwximws.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtgpgryqae.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtkunpdxcq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtqlmdqsqk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtremphfsa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtdcxhucxz.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtdvtltjkf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtxuetuzwj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvofyxde.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtbywmjwat.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtbhivimzt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihxwlgbg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtulzftwrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtaimunwkp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtaltbdktz.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtmthfiqwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepuzajwg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthszhpzgr.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtcgbszglo.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtpjsduprm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtvzewytkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtabwwitmz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtpsdyxcki.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtmulliqqo.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtsqytzavc.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtrrfbirby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtkhkzjhph.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtgfphbxcn.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtfyisalwq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtnlrqrasq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtgtfispgt.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtreyiixkj.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtrjhwsqcn.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtjyzchdpu.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtomecjfqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtavuzzqek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtgdpwwmua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtlvlqrdye.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtxnsgejxd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtlyofbaxi.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtymumakgi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiydsegac.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtxudrlhrp.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtzywzzivb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtsemwbwcv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtlzbbnfmc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtajynydzw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gttrdgslmh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtlbhijozd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtqyazxozx.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtifxwgwfc.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtewvqoivq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gttdqfnerb.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtqdlmqzgr.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtcujxcpnq.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtitmchknr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtnvmaoyca.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtoexjzfcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtwxtzqtxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtckuhxquw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtbylcruhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtfvqjxwiu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gtaemxskdv.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtpaowyvbm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtlcppqphl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtdpasqcxo.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckfcukq.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtqywlxovu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtdodpblaa.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtfuttdezz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtpowqyxry.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtiurowuxl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtefovxvtf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gtixhvkctb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtpbnpajso.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gteyyqxojj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtrgylogcm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gthwepxnii.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtqnbtywuk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtjvvrrskp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gthormmlkc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtwxwbvycn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtzrmeoylg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtzdaooygo.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtklodtlpf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthddjtabq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtybbdfvuf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfdexjkgl.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtawvmrjtr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwuiorueo.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvzndgfo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtbomivarq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtkpifqiws.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtlqpatztl.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqyhesvoq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtwdrxwuen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtodcynumn.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjengxqx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtypfufozs.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtkkywryyf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtwmyhklir.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtxdmdbfjv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gtdigfnzds.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtgrkiyazp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gthcmpkxay.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtdojgyfvs.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtmpfzskfl.html


<!-- 参考信息 -->