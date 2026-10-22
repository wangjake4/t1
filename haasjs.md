代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2udxbfksy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2xqtnizje.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2sqzeubnf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2cblbpphi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2dxbljjhf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2ppqrzgnx.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2jgxxizix.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2wgvnupta.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2pfuuaflu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2xvgoflqf.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2vfzgbooy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2mgmtcimw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2dislrfuy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2krhzwjbp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gt2hxvnnjch.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2vmxcgecn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uawshvfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gt2qnsdlcci.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2zqvboilu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2cycushlw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2pnppjklt.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2votozumq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2icdazfme.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eehoqftn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nbcmobzc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2acdokiaw.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2coaznlmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaomglek.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qycahrwg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2rrohflxf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2waavgdzy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2nvobkesg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gt2xicavwlx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2iivmympi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2oimtopnh.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2voyprwir.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2dvknrqaz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2pcgaqrwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2zbxfpeqs.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2cbpnhrhe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2cnfeyjan.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2haixmrsy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2winotrvp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gt2fvuuurxt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pybkrolk.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2epqyvtje.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uimewhjv.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2csmtpfir.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2ksnmhctf.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2ygljyfuv.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2fycktyln.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2votuqhsk.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2jgdryidl.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2sxztiqdl.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hatbmctj.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2octqtzpd.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cigwenlu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2rpiiewmk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ifkspusk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bscihmbe.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2onapjfva.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2ifwfsfwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2iuvfmwls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2byofeuco.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pgyziwhf.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2mskupnpu.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2qinzraes.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2mxuegokp.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2fotvyyem.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2xewtezpo.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2kryrqcwb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gt2bgxylhip.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gt2nngcwmtl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2hglzwrif.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gt2ikpchykd.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2dyelfnby.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2vbbgptwi.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhivyvpb.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2uyrqwwcw.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2tofctkas.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2zxlfjqpu.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbqkumec.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2fgyeplxr.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2hdfupolu.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2shhkzkxs.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2pyzxwxag.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2jhmefgsq.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2nzatrqsz.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztkzhplr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gt2gddpspls.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gt2fuespljp.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2atliqkjk.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2rgosyvtp.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2onlabeyu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2eqzowjca.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2fovgsnrx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ogqjaryy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2uqazwqep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2anamvadk.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2pnrbiahz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gt2jhkuurjc.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2ttweskqo.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2fezcnapl.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gt2dcaysxgx.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsyphbau.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2yrbgpbqq.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2lxfnqxlv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gt2viyljiyy.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2pnjlbwoq.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2avxvmzpe.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2vfpdrqef.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2oozlhvjp.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2mpfkwxvp.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2zplfbtrw.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gt2usnhqnax.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2vyetoqfa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2vuieoxje.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2fqhhquvw.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2pnegplam.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2evgxjcyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2mvfrtfkk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2hstisxem.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gt2tetnwalh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkirveqj.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2mwwwpijg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gt2aviraclf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2vgqiaihk.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2ijascyqi.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2vzcigiqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gt2sdpzgkfk.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2mductavl.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2jkznhylg.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2goshryrm.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2lztyhiwx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2ryiafweg.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2fycadkoc.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gt2ghbcluek.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2rijktgfs.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtprztox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2aalocmnr.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vozrlxqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2myrvphep.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2mtlyqlcv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcwsarkh.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2ilkoxwrl.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gt2tbsindwq.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2slufsuik.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2rgxrwgpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2vyzhofps.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2ydzhvnzd.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2jxxqgpwp.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2spfvnbcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2fwtejgsb.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2wasiexwn.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2prrhdtfu.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2qacvdlwe.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2ghifjvff.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2kbpqwakf.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2jsrgzyvl.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2tnsgtmhz.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytdhjvho.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzgigivh.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gt2wksjviit.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2gbwqbvcy.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2edfwxudk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2ihkgxrfr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gt2zuzoeucw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2kzbizndn.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2pysfzgox.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpknjzlk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2pxokzcav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2nvripmci.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2zwwoqjyd.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gt2nsqbpjxe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gt2jtdwdoag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gt2codlbvkw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2ouuusoie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2yofzgbkz.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2pnezbucy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2skjpuazs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2reoigfea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmumaztq.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2ictvhedw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2okcxecdf.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2doufwogm.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nfgpvszv.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2azzxqldn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gt2thtyuppt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2corinnay.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2oogdcyav.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2ruzdqcyk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zbudxike.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2vroaamzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqwtsfr.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gt2wpaaiikz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2adwwfein.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwjzsbdp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2krbgumgs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2mzojftcc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gt2kmjxyvbr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gt2ofqjnonj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2cinqjgqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2ceszribf.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idprxuzw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gt2edgranvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2jvicgxxa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2nhzmlbrt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2glisfgiy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2raauxpky.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2tqadrbvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2allfdojq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ctdpzkys.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvnqxirk.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2avmuhwyg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfglsjda.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlbsaabb.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2prrvjota.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2wjcmnchf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2hevyxgqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gt2kmeonavr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2gewuooes.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2kymmaebo.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sovnwwng.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jxeqwigc.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2dwgoznvq.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2pazjbwfv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xisjwkrg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2mwpzvnhe.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2akdbelii.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gt2errdmoil.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2jksxgobo.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gt2bjnzbisk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oburaozy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2jrrkajkd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umrkdnui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2cpirshne.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2pgyltgax.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2zawosfsm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvkztlkh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2zemgzcro.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acbysmio.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2xgwhpagy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2cvaeksgk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2fpzwbbmf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2eijpqlfh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gt2zixqevka.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2qfuweebt.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2iqorkpxx.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gt2ovmaetsp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2hjrmwcbh.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2pemobudv.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2kjfqalml.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2rsysjznm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2ondapwgu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gt2nucpcoty.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2vzohpgst.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2dvqtvemg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2jjirzmxc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2uneoflrt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfacopyd.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2nxiototv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjsrxjam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2ygvgkprj.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2damdkrdu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2xitzqaha.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gt2uyekmhtb.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gt2ojdgprtz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2thpeelzg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2nwitmnbo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2mzmmzndb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2gcfrdahs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jufgqtjm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gt2bfxkxfuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2tttgrijp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2zomjvnem.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2amqzugpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gt2xitobjpc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2dkarlvzl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2pdylnctq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyuqeill.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2xsggplcx.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2ujvjvgih.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2xxqkdvrl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2maksuumb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hjgbzzzn.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2ylrjagpj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jvrdwxxe.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2piiyxsnz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2ikyxuxkf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2xljhidmu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2penctmkr.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2vndynooe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2ksfblety.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2omxsjegi.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2zmgksoyt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2bfdlzsjp.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gt2qrfmsanf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2tdiwffse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gt2lkljjata.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2idgfekro.html


<!-- 参考信息 -->