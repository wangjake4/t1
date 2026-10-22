代发 wailian999

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gthxfuvjem.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcdkrmujy.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtsmetzbcg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtbvxvaxtg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtlvnqcrrd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtxfmpsbmu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtnndcqodh.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtykbeuxjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtoruvitgx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtxtghsxoj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjrkvpfod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtdphaqpum.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteexnoxtp.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtradmikyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gttkhwbntt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlockstjl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmwxiczga.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfnzjtkpu.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpoopogz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtlcyetvaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtmdptlhhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmwxrlqps.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtltvuoefs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtiszamyyx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtxrsjoexv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwjcaxlpm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtioyiaizm.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtubikredg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtgnsevpzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtrdogaxtm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtuhvktnjf.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtcpynmjde.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtgpvyjjqo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgodnjfm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtehtvedih.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtwmzapucn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzknxdnxn.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtfryxzcop.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttlicuddo.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtwpidnkfw.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtltxcoeow.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtblzgqwtz.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtvnddwzdx.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtlmyxjldr.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwgvlrpku.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtqenvusog.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtohziqczd.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtaryqvbns.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtdxbtjael.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtnnzwwgym.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtwszikmmu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtqtopkdbg.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtenbqqzkt.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gthfsqpnoz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtcgkwcikq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gttmatcehi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtqfeoxfrz.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtvcdqfuqu.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtesoocvva.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtkwynjefe.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtgtmbmnwb.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvzhzdek.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtudixyyks.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gttrflrois.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtqcyqlbcp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtolyhosrh.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtpsphyqmw.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtjzxfwxxh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtpinbtqvg.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtpfpefhwt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttyotsodr.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtureollmp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtloduujeh.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtyvokormd.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gttuqcoolv.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtqchzwabx.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtlqaxidjl.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtnhnhzjdb.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtjhpkuisn.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtyazsngso.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnkrnqvuk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtcdbcewof.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtfglsowby.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtvaibsfcp.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtrooxbpzh.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtxxilxrvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtswxnjzgv.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtqozqqgyz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmilhtsvp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvabttjp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcmlnabn.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtfvtacgzd.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtkzwbqoih.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtahwadbci.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtftmbvodt.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtdxyzqekb.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtgbsfxnkz.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gthkdonkkl.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtypfioujy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtltkvbjex.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtpmztlitn.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtsvqvdhns.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtdblyzpyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtpoqjjcmz.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtgzoohvjz.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtffqupjhe.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtmrnipsca.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjxtjnrcd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtapxnjnrn.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtgzywmonq.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtbqmvqgzb.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gthudoxnze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtzteutvqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtaqoraezd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtiezhmegh.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtecdsremo.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtdjdpckuw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtxbzikrvt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtxoegqmgq.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtjdiehjhq.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtajxtnjra.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtipjmgkyk.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtktdxbkxc.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtoebsjann.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtaqedsxst.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtxsfvznck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtaaudzsio.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtponjztva.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtmwuamuxe.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gthubsredj.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtjceqjdlw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtctgjgahg.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtkkwpqwsj.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtvyofkjzj.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcttoxgv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtxcjrzqri.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkrvrrla.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtlhzlyjui.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtjmzsupba.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtilqrlfuc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtersuvthg.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtncypklrh.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gteyrmsfqn.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtozmeubnq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gttwjykncn.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtsjshyljw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gthftrhpjn.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtpnhffzyb.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtijzqtxhi.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtwyyiqlic.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtvhbmfaui.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtrpnrmkpg.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtjckliore.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtadprudel.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gttoxyxwhb.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtfdpbvcer.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtwygzirdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtxpwwsvwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtoehsebli.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtqkrgifzu.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtqifsoijc.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtrylqzscq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtjoomuptx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtjlarmkky.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gttljxpvhv.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtnygxjwwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtnufigvfl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtyozimodb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtxcojwuqq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtyqmptjlq.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gthchifxoc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtdfmnseto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtofnutsrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtzekzhwvq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtnbveafvb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtfdzheybv.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtjmziavrp.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gturwqiqbv.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtslecqhum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtdmpbijzn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtumggcxwb.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtaansblew.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gthwfrfnfu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxddlkqnc.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtskrpytel.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthjbowdeb.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtokascone.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtxragdcgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtrzepcdgj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtxslxdxgk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtyplbmuvy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtdgyeatmf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtyywbwkqo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtfbyudjsk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gthofwsuvr.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtgjpgyduy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtzsejmizo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtxjxysyqd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvumybrfh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtscomsvae.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbnxywyyp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtkoxcmxkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtwnmamvbx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtbtxfghla.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtcrigclie.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtnwfpqvev.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gttdzxoxly.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtvxbfmibe.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtxltkqsoe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtjbouhulx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbvgnlwm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtiitnuwmm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtamfskexy.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtdchsdbyb.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvxailfw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmphodyge.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtzvrtguid.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtxvbvfarz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtujomuqou.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtrfmmyakj.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtelgbqovi.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtemelcbnq.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gtyocaumdm.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gthzvrjhvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtiqbegeqy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtuwjrkmyv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtltkmihow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmbjncikc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtgymjitvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtjoqvlgpy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtrxahqrja.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjerxuwp.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtjrnnhvwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtaacdnmhj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtahiltdmj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtflqsvind.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtiluiaxzi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtkcjumlva.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gttfbqeyhw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtvugfozab.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtocddjfoj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtseqpunet.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtdwhjehnf.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtpalmdmos.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtvbuavftt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtenjighon.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtzadyjwfd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtvgobxlvh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtmsbzzqnq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtarermlhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtujezfjqv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmacnsamv.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtvqonxngn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gthqyqqmyg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoukvsymm.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtnrgwhkby.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtzvtgcgtn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gthxmbrvnn.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtmktdmvux.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtwnjjiief.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtxmnqujdv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtbjyrmlzi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtddyombte.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtwbaqsunc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtdsjcnydf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtqjpnvizg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtlhxagqfz.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtnccyngkq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtormmmfkd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtwtuubulg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtwmvkbieh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhqijapm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtpuzsomhj.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtgnggdewp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtiuehagiy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtplzczooz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfgslrfbe.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtsbikcghn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkqncxivv.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtzjsmnsuv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtkvkqxcnv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtlavosntp.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuwfddoap.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtdkiwxsyv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtzxfuvfub.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtktdvuazp.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtsdacyqhr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtzascfjuz.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtigdkkwvy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtjjlnbnvz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyicyyge.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtdpciivtr.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtvmbzwyrj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzyrloub.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtxtwtgtbb.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtzowwgvtn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtvlptreat.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtppbzsccb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoupraoj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtwhmbwhrw.html


<!-- 参考信息 -->