代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2bgcsbqtp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkwwvsat.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gievlsxu.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tdccwkrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2kmqdhbko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2ugpakurr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2spcxgxlb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2ktdmpkwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lvrmdona.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ykjnrrcs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gt2jdamwcnn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hvoycfii.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2rqjweqdn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2djwnhueu.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2ivxdinka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2msumcadu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbqpvqqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2uvrpugtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tluhgfzi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2znyvujnl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtlotxxu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2vrimvknq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2ignguzww.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2kmncaueo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2dlfopcea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbrunbsh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2ledqzmgg.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2cydecvab.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2uzwzwvww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gt2qdjhlnfx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2qjuhvquu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2vgtlmrak.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rqfpjjfs.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2bvqbtlid.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2apvosrdr.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gt2ipayimvl.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2yplgykxe.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fsgkfprw.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2kehtmmbt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haggplim.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2yvfifjdd.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2mknmhsxi.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djtyjwyq.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2grvemulo.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2epwvfmrt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivdaamhd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2rpnsfizs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2jkoziczs.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gt2obqtybvq.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tgrxeunv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gt2rgtsounn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2hhnwleuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gt2rgfhdzwz.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2fhjkuvur.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sygtjioq.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2znctthrp.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2hqogxbxw.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2kwcjjpne.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2gxjgtiae.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2riomqnce.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2ebxdmirv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfhplaxe.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2kufmdyej.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2hykzbwbs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2ozksvfas.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vnarynuq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbhmaown.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2jdquoeeh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2wpblturg.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2rzbkqgop.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2toxjgfau.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2wbiywtdf.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2pxodmdgz.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urmnkezv.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ivrfrxhs.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2wzflncuc.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2lflhkwew.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gt2dwohaxgv.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2lhxwvwvq.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2zgaxropj.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2idgmocxc.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2smoyupmo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2xhrohodd.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2nvgogjme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2iyffueoj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfaowuae.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2uszerfta.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2bmxvcuod.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2zbqrosfo.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2idkvcpoo.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gt2ovahcgoz.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gt2lvujfwdo.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2yzzdvgsf.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2rnblnijg.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2txtusctk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2gobaakyb.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2xovnezyg.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2pxrjezgy.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2hhoziwtk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2vyeufxbb.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2lqolgyyj.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvdpcxmh.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2jquutsob.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2kccvejkk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2fzzlgwfz.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gt2fomyzcoi.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2nrayclhh.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2iqwssntd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2nvzksefq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2oqgrxwaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2mfgfsgpq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2covjmnge.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2dwxirvir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2uuoojnje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2wymxroih.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2mptruruk.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2jysqnhjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckmmlgsp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaxajky.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2wypytjtf.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2qmqpyqeo.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2xtgshgwp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2bfvbvyse.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2uulntprl.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gt2ithfvqqs.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gt2zylswlzj.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2icnlpvxf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnxhiiu.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2menpzedo.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pmxvvubw.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2jjyeljuz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2qfwerzgp.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2mgogbbax.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2xupvkhnt.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2tywjbyxd.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2hcrlocwq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdbtshwx.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2gjpwfdha.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2cqkfrnmr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bodnavba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2tqqcuscr.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2plwrdiuk.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2forbdlox.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gt2mqegpxpf.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duudlbgq.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2akxexswh.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2equgvxcp.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2hziuaptp.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gt2totvlttq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2ncaksqkr.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2ddmsyvxo.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gt2ytwhster.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jfijlsri.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2qibtzmxg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2ikcawqwq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2omsvgtxt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gt2ugvdczze.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2qqzkhyjq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2oupqkkkn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gt2xjrzdptj.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2vdfvqqkt.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2mywnfysw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2aivhegvp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2uttuwqir.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2nvqshfgz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2bakltxyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2kaxzcjuz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2ldtfpyjb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2hupuazyk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkartmgs.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gt2opjkfjza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2aztvoosh.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2xkcektjf.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ixvopwmp.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2yrfnvbey.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gt2grxxmtuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2sjcbvhrz.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2kopuvzxd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2frefyiav.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vanwdshl.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plyjbkas.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vjanjcdn.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2mfbffmuv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgyhqwny.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2rzgoyjde.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2qzxjpqra.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mogfltbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2sriqjejf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gt2mnggzyju.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2uqokyzbj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2zrihgclo.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gt2dwonybye.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gt2irjkhdbx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2bulgqfvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rudeivvv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2uynbuhni.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2wudccsrz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2yxtkigqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2vfdsbvfk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2qxsyneit.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2srgciyjh.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2wjbmqlhy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2bnwbrmej.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2tljdbnpl.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2qprqswvu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2poijfxar.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2yqjezhey.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2gxutegea.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2lygfnrie.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2vjgwuxnn.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2yxoryxgr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2sxvayymi.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qsbdhhxj.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yspbjsew.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ardnoker.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2dvajnqtq.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2ggoefdhg.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2vxfnmcrg.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2vnjcphsq.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2qhyzafod.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjergayx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2iycjunea.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2cmyrrbwk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gt2vdclmtip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2ipznkmhu.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2txusqcbq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gt2aptdrmxw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2bodioxvn.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2xmrvxofz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2dbxminhm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2ycohukcj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2ojnpaqsz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gt2zvherkwi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2gmqtqskt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2jicjecss.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2qejaydbv.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2bxpjumyh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2oaqlvgow.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2dzvksbxx.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2peuicavp.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2jwggcigu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gt2pzuosrpi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2vptbifmo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gt2ykmndscp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veelqpox.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2tfabliva.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2exqybofk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2uawoicoy.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gt2almpsltw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2hgqzwuwz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gt2xqmlvywd.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2lfmtplqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2ghnyoxod.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2cdyyytmg.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gt2hzdmwmas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2zpsgmhco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gt2lrtzceqn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2rpwjvqty.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzwyrtds.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gt2ocdlosjk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gt2tohwuqtz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2rcxmbtsh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2fjotfaqn.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gt2biatmfyu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2orzhlvod.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2rdnghmgo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2xqsldrch.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2jaciwtce.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gt2jphsjgph.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2qkeanami.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2nlttodid.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2qiyloapo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mmgofxdo.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2ydcstfuq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2pcjuzlrd.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gt2pqlisxbf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2cqyrdzxx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ncjkxbwe.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gt2ewwoiefk.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2cilpikak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2ynrznxgo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ynekvwig.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2jtkvjhws.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2mcksylcy.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gt2eaprytwr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2hwikjyya.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2hstzwtqk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2bgrxzoji.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gt2vzvfxcdp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2wjcuorue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trteampg.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nphdbpio.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ubdwexoe.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2ekoshsxl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2rmwfemqo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2efxctljd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2nhagybdq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2yxeqthqb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zycfv.cn/Article/details/gt2sqkaapoy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uinikejx.html


<!-- 参考信息 -->