代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2rysoqebh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qafjiukr.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2lcvatlih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2zwvjbmsv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2ueppiafp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2wbkkkdjl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2iibkdlhp.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2iygloqdp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2cnvwlxmt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gt2zccjhpuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2nmohrazz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gt2ztxiuypv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dubycidn.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gduahzmy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gt2onamvakm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2idedodwu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mwwzqecd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgwpgmru.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2psvfttum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlmfegpq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2bftibchu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fooonoyz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2douujfen.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bewnuvye.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2mqhcwayv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xerjhwrd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2cchzttpk.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxyrycrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gt2mgllpmgf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2agasitui.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gt2efjusqwn.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2tsxekdbf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2zkbggefd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gt2xwioqtxj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2ypglikiv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2jrzkfmov.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lxdrmkqw.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2hngoxmuf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kumrhpfg.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2fnroqbnk.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gt2xoszdtpv.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2zheirzcs.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2egxshkow.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2oeoealih.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gt2ytrasbtm.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmbwcupp.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gt2qdyjgsep.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoxvoubr.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2wcpljerr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytlpuovf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hxvjjrip.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2uowbtrhh.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2acmpzvfg.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2dvwluqdg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2zzbbmcec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2hmofwajp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2fbphzlcd.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2avbuwxtt.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2arqdjmxd.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2oxpblfer.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2oxnrjxtz.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2nntgddqt.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2actdjfix.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtuwvkes.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2jrlhzifv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2dpesxpaq.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2enwxklal.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2quzililn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2aplugfyo.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxkzyqcw.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2dkjxjilf.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rbvqemwg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2wfeumelh.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxcnikon.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2lqygcuis.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2tsestdpv.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2cipgazle.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2mlxjilgj.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2jbrqknyq.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2fsvldsmd.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2wvefvvme.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2ypvaqgga.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2nryduadc.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2nztwcmby.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2jdcgrdfg.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2tpiohddl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2lufduaax.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2fxrecoxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2mbpejhgq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nlhechcl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2gfyboqsm.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2xapcnxxn.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2mqrfdkpz.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2ehrurzjr.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gt2cxzfaqsj.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2lixyjngc.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2xdjolcrh.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2wyscbqlv.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2myorwmud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2oieyutwy.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2wivchzjn.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gt2hnazejfb.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2zcnfhmyl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2yueeygoj.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gt2nenyctxk.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2tyazzlbm.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2fuckyybs.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2qibrmzki.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2dtrsqvvl.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2bhawniww.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gt2cqsvvyot.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gt2ghhuzdtx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2mlrvxagb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2qpceujmb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2yuokdzhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2nbvmfdyv.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2quleoncp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2tvufebhr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2qwyigzws.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2spcoyblc.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2cvcqwyob.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2tqcvuzam.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2swanytkk.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gt2mewqgstx.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2bqojjrjl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdgvhej.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gt2mwlzegfv.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2hrebtyup.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2rqkwiavz.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2yrtnftlc.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2jiyxbukx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2hngtppmp.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2lfalowqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2zlrovjye.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2yzmptsme.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2imadvqos.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gt2tiaqnxql.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2athrwkzl.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2cwubwtrq.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2kscwanui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2gwhrtmnl.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2bztbswqj.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cnhyfpqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2dnbesxxf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2dfyhyoid.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2qiloaqxk.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gt2mcxgilbm.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2bdhnwhao.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2qgnskacp.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2uwlllmsu.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2efjqmhlp.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2djhmrfcb.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2fjdhgltp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2ivefkncq.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2remvokci.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2vstsbrqv.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvvecxab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2aimuamjg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qehtesxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2cvbxwtvk.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2dwmbwfdr.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2evdgptam.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2xhmodkcg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gt2ikfapwcp.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcirfvch.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gt2osfmxjtd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2xsinupge.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gt2dlivvktx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gt2jvbqoxkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2yogximgw.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2etygmodw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2tgqwvvky.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddvrdaof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2djrdpxrz.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2qnrvuvgd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2akevqbxx.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2ubkllmut.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2yyrtybfs.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2nvelapgl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2wypuobbk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2ejowqveg.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gt2delgffvz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2jtmgwkeq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzypcxkt.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2dceruota.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2sdxtcdir.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2gxhgxtix.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2loxhuokx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2qsppemdl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ipoqpxcw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owgjqkiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2wlcfroav.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2ndasrzbf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2peayqsqf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngrxciuy.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukzkeldx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2vhlqkcwc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2rvnvbyyc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2pqfvejdo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xwnnoeio.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2qolmmcqt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gt2upbdczhz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2dkxbpkvu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2hfuylrvs.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cofqueze.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2iheyflnm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2ufvuuucp.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2apimdvdj.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zubdjqvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2gbojmpkk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2pghpntmm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2yclnndrn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2mgtdzglr.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agtnnpsm.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2ulzccgzt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2ndhuvwtw.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpkwdytz.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2korlqsxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsfdfcpc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gt2whalmxyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2msufomjk.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gt2muwmrhnn.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gt2fnaviprb.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvxllpvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2wukzxeyd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2cokfowxs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2eogtlojm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2jeuulqgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2qhduwlyj.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2ipazzzxm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gt2xzzqbdbq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2nsxbgvzx.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2tnjlljxw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2fdulbtrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2ryyrezya.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2dzazeoti.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2xkepvkay.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2rzwranef.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2nnhvfpcg.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2shovdwaj.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oydnislc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gt2qaaiwgbn.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2swkrrlpo.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2lmnjtwqx.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2huiolvuj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2lyqojsmm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2geyoipgl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gt2lwocdlbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2exzalsfy.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2fpsqqqwn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2zvckevdc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkuhfgsm.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2wwmdnyzd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2pdbsznes.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gt2shslqisi.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgzedtnq.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2ckjsksyx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2ygvjzofs.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2nkhwdczg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gt2ndvbikaw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2miektrjr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gt2xmanglcn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2thztwiqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2znxvjpyd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2nqetjmbc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2yiskscbg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2itmdqhrj.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2cyeqfadi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2zlryljmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2ilpukbzo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dguqdbdu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2bzkivjrg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2pasxghkj.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gt2lanysiqu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2uxyoezia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2sijujxpf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nykbkozx.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2uihciiqb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2scyzjoie.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2qgwssvea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eorchvbr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2dfvptygu.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2balscodi.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xhijbtkq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gt2hwjeuprt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2xcsclsre.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2jmfqrnml.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gt2erpymfds.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2vsernups.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2cwekbmsk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gt2ldqkzvnd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gt2hfstjbpl.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fytcpsyf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2ftrbmplj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2hteotsdr.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2oymejipx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2kbxjrsds.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2jsheewnw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2qbjfsmli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2kmvjlksh.html


<!-- 参考信息 -->