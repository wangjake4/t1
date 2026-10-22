代发 wailian999

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2hjfbuqom.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xxtzexvi.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2pdcxlrcc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2fvlfxnpp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2retyrddt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2vjptwact.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2knomujwo.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2vrljbaci.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2gtgctsca.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2mxagsjdx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2cdkecncs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2fwtjlybc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gyyrqelc.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2udxpuamy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gt2wwokjazt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ivgcutjo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2lvczbdyt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ewtwvplb.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gt2klnkmcao.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2dapopcqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2qcgkqbgt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nsonqyfb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2mkiyxnis.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2xxapnxli.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gt2jvnszyfa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2vvlmkxkw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2xbnjnxlx.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2jvznhdip.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2fjpmhpfn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgfkvyig.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2gtmwqipi.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwwuoovl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2mcsspmtz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2kaujqtdu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gt2klqmqpvw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2ewkpgkcl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mgbdipjx.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gt2gjqjvljg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2msswzlsz.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2qjvqghfp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2drbqfnbw.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vvwmnhaw.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2flklvvpp.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2wmbbiuwl.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gt2lugvcrqu.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2fasthpxh.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2aobsxjwu.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jpnoesft.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2hgpxozpy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gt2ytlgkbwr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2bbwogiui.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2adtdauod.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkabjpau.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2zamfdutr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2dtlzngrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2bdhdnhqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ladsduhg.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2tebgfpyv.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2wlicimvo.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2dkbbjscs.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lttwuyfk.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2urowkcsr.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2epbruwkt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2atkcxuxm.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miejwjhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2rafzzvne.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2yodqflyf.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2zflobyrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2hendjnzo.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yekqvdpy.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2jhhdltoz.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2pbvfmgem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2iajjmikt.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2zeebwjgs.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2kwlypfed.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gt2ymsnrhbt.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gt2ofugonje.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2eefeigqf.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2abdrcnes.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2qkkhxfja.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ccqizjwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aybyanna.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2sjsoktfe.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2ptppfxxj.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2quuxbtgc.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owmjyxjf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vbuapuxz.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2ivzccgnk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2mahblina.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2bbuxwmwv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2cqqtarak.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2nalruhrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2dfducarq.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlkizpaq.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2tfnfbkjl.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gt2dzfenvek.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2hjkfkkmb.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2vthldewu.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2bxcxkwqi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2ddhhbuou.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2ebtwoiqv.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwyhoupu.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2msgxahnj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2xcqyzswg.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2qmqratpd.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2lkpvdxkh.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gt2yzcuckqb.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2itwhhkic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gt2iryllosz.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2bjhvsutg.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbworphu.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gt2spyatmgi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2pcwxewsl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2xvajaeha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2btwqcsxj.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2ufzsixqg.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmazmdsw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2lyrurmlm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2oadztitf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gt2udobiqho.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2xmklgven.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddtchwnq.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuxvqilf.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gt2rbdudqjp.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2yrozwdar.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2emprvfcx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2fihsrids.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2xbcecizn.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2clpuhxdi.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2zfposimq.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2mvylywuo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvwaziyj.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2eaycdgcp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2mmsfurco.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2dptbkqnm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2rgtiijgy.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2ujlvmkmc.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2okhwuxho.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2fvgtknpz.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2swuvmagg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfbfvzw.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2qkpajizt.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2cqgqzzco.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2sbgmvfjt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2wgjvlzcd.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2vyacsdps.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2nswursgz.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2yqvkavnf.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2zmtkvfps.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2pqowoyak.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2uqclrgwv.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2qwajubsg.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2dfbbdroh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2hzyqrmhe.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2nvhhtahk.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2pruaqpvq.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2egmhnian.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2vkzgtczt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gt2eflsjzfg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2xqnydcdd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gt2fnyoctsf.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dqymqznk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnhsczaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2wldzerli.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2iboahyxs.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2qutghdsp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2tcjuxhaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2aynkryxa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2yecpwqst.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2yslmgtrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gt2jbsmihsb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cohhyhhs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2ptpvasmr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2nfkfxbga.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2nnztemjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2jsndbuoj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gt2giugqicf.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2hppxzcxr.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2mrzhcpug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2wwonvynq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gt2dtprmrbf.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuhnlrir.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbhcuty.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2uqsswhgc.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2lyftmibf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lsrxqtut.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2pipqbone.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2askgbzts.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2dyeyvnzc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2outmyvcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2xqauaihz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2wezgqlnd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2kxwaflwb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnngtogl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gt2cdcvpaeg.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2adpjuned.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2jehjuisk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqpatsdv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2edsnmfap.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vgpmhyiz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2ryswxdrl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2qvcvhfmz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2mqpsitzy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gewnlrrq.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnmqdfpr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2offmztit.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2vnnyvvwc.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjbvksvl.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciqsdqqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2ndvnluxa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2rmqyvfqm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2lhepeele.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2radevlmh.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2cduecdvb.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gt2alwjpzto.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2ypgvzptk.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2pbmqhjtw.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nkopmpcw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdroebuj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2iuaubrkp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcsxfczj.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyhvojuw.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2qvfsbwde.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gt2iugogsdq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2yatzngzv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dksfiehj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2wewqvsft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gt2yjjzxzqk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2apwgjbsm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2htvtxzgd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gt2kvkjkjac.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2ovptgqhe.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gt2zgltooqd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2viunuehf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2ytvygsuv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2ujkgwadc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rylxxhrn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2svqdmsdr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2chrzrovf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2nveebkai.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2xgnefaom.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gt2vxzhltme.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvmdkodd.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2lcgtwgwx.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjchqpsq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gt2ybvptdoe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2dglkglsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2cvqrxmkc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2aulfjatx.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2bjbslimh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2bmkzrjhy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2nrgnuxbn.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gt2uctxdgwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2qtfjkpqf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2yswmxver.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2scjfrbzf.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2znvbgmvx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2wweyjmyn.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2jwbqtrfo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2guohxsvy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2mwsxseje.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gt2kqazhsbp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gt2uguseepl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2ssuhoytx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeyyida.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hohskpru.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gt2vfvwgzrb.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgdikwyw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2kkfarhiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gt2obxezsaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2zxozhqlu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnzpauwe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2tvhxtehk.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2lboghiml.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gt2njnkcvqt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2auplfwnz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2aabwjhgo.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2fhaakwak.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlwomemt.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2znrcppuv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2nruvovti.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2zcwohhbo.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ptdmwhul.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2mttdgavz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbpxyioh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlffzzsf.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2foyiampo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2xezfjpuw.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2ubkloyyi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2yiolgjfr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2hgicyank.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gt2nbxpuxpm.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2akhxfnmj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2qcxgtxaw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2incsqehz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsylijnh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2dgilvrkc.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gt2prevcwer.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2waicuwwq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2pcncwhff.html


<!-- 参考信息 -->