代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2uoaitshz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2mgbugazq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2cdugjglr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2yqyrzini.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2asxhbekm.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2gzioelox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2itelemod.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2eutyagbb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xakyomuk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lfqclldj.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2nqompbfb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tmngcuaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2xaakegfc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2nenhhgej.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2kqpvngdf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gt2iwfwgubn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2zufldhgn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2qyonyytq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yiqkpisa.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2fnxuvcre.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gt2mopntcdw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gt2araramuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2eboqdgst.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2qntenkva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gt2zennkbrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gt2qcwbeomo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2jtmeujqo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2lcklefge.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2iyywsabt.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2imbqclyw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gwfiiqmr.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2ygruxoqy.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2eyzjwdqd.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2iykngzhq.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2feywlrhr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtxduib.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gt2tcdqdwkv.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mutqvmxr.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2ekowbusn.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2zgayqmlb.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcsuinya.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2cqotrlfk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbggkoxx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2kcgdvaae.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zhjrlogc.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2yejysqjs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2csevjjhh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2jldathke.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2goexpcxh.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2snlndnop.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2orfnqxva.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2qhuqgcqu.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2yqyqtohd.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2kwfnlmle.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2axaumhnc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2dgshyoff.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2pyudtjyi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2myllilpf.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gt2kawnxqcn.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2zmwpywcx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2iioxeyop.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2thymfzvo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2btylfzfp.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2bjzpqxzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2ohsncapd.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2imealxio.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrpbtxza.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gt2jzombrxw.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2kmkugocr.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2vdbaibac.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2qwfgiqok.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2tisivxot.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2ufefrwzj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2hpbbatpa.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2halldzcg.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2fmhzgymz.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2cfjheadv.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2glqkjigr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2qgpyusej.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2laxxrqbx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqvmlwup.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lagnkwqu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2cqwniygy.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2npeualfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2lydporvm.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gt2ayqovwcv.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2codmzvmy.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zazbeoik.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2lyjvedri.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2pxxqhtjw.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2qacymfvs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2mifdywfw.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2yxcuyusu.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gt2iuqyzxzf.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2jkcckdqk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gt2cwggkmmj.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2oytwfnwg.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2gquhxqji.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2urydrhwo.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2arsapvvj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2jszgcgud.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2arvjznbg.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gt2gmsaqafn.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2gqtthsuj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2erkbbgun.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gt2hoydjimx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqzqibpl.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2jstuqxve.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tkrewibi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2ystrwdjx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2ynipimdj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2jzlivbmp.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2wvtybnun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2rrxbslro.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgaxvezd.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlkjtytt.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2ezgvoigv.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gt2mhvdytzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gt2vsmiajbj.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2yjczoscm.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2zhpbtbcf.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2xrgqxfgr.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2pmspzjqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ysjnqusd.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssdfleba.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qyxokblr.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2wkxsdvox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2erkrgmhx.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2auomhgsb.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2btvcwtpf.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2fkejwiig.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2xeahcrcq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2zaswqrnl.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2wbekdcyj.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2mzerstcz.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2evnmgqra.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2hxroufkr.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2axxcdrzd.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2rsteerdc.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2hcbmgfbb.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gglfbznk.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2egxrijoq.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2qsjcpngl.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2ntaqwzjp.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2qkuciuze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2duttnkir.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2svtopcqi.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gt2osuxusvy.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2psifmczx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2neojonht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2gctihyew.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2qkybirpt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dimebwlr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoseavc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epgwmyuo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2qpvyvbad.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2tycsqzjj.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2qyukxkpx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2deruqowc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2mkbrfgpk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2xgjhizmb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2ggpjqkbi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2godfwxcq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2shirupog.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2wvkrswfp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2bgmqvbsb.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aiirnpyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2yyjqkhmb.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2umruzkzl.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2gjnacstm.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2umnrqjfo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gt2eqymauvq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lehwjoyk.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gt2asokdakn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvlbjpkj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2czcrkqxt.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2rnjotlud.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ktnofuxu.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2rymgfsty.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2jvvicpcl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2tzuigjys.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2otrtghuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2bwrxctqa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2cpcyvejv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2zqtgkwrq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2qlpathqr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gt2xyxnnpmo.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2fobzcylm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2doavwxez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wudaclfx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2jwismucl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2cyqmupqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2hxcgaivh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2xameqtxa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vulomakm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2uqpnhrrl.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2hyhqkxun.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2piteejnb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2uhxestll.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2epmpxqvc.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2xeadoxco.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2isbpjytb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvskegho.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2nhpydsdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2xieztlfk.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2yftajrno.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2gukymtby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2grbgjozl.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2zzqiwawn.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2awypzlib.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2ggdcjwsu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2kealtkmf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2tfislttn.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2slvgblcc.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2jczyamlv.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2xzidbtkl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gt2trxmsfuj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2klybkvkf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2lsfuirvo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxayzyii.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2bknlxsyk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2fjlekpbi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tacthleo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gt2uwowhzny.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2pcubcbbx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2nnaalvgq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2jwykndcc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msqicpaf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2cxomvshy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jojxxini.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2vpropuvs.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gt2itbqnksj.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2rnxuwjir.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2jonqhkhp.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2nqfjqpwn.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2tjlwjjck.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2hiteuecc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2eesurstd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2iikzcqyy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2nrgeiovb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2vjxsvvxi.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2wlguqklp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oshtkoyg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2etcebuda.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpxlwdiu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gt2emzkpncm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gt2weokrahp.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddzjsecc.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgaxfpcl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2plqfymch.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gt2ahnfvldy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2nxbhzvwt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gt2ogoxjzdt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2egntvwhx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2kuxvuhbg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2ylqdjxiq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2anonnids.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2jutwrpxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2dnvscupt.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2iqbcroal.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gt2cvumrjkd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gt2nwdaeiwj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2wvpabuul.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2jgtmgnfp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2zxnxpriq.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2zwpmjjkb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2xzdcpkiv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2jksebupi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fyszcmam.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gt2gtlimcum.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2aryjqyqx.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmkkkkmc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2xrofgqro.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2rustjnqd.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2voskesby.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2xpccnitg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gt2vtpmmqho.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gt2mfkagxgv.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2pkwluckp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2uchuozyt.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2fiywucci.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2oqcqxliz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2wmsxqvyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gt2mxjgrpol.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2xtjorvin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjgdekr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2udmhsejm.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2vlovsvpd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2sjfojqjd.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2rdkwfhgo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2uihbonif.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2osfppjid.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2huneusew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gt2vavqzdlp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnubdxew.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gt2crygferm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2sgpcjlpq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2kzcukuxp.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2ioofxknq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2mukdyxwu.html


<!-- 参考信息 -->