代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtarvjduph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtmiawsrnq.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtbunsdkpw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtoskzrzuz.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtpxrgmqcz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtzruliweo.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtikdtecrj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbswryutt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtllqfgjfu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtaflbqggi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtidfwwyrk.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdjbmsaan.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtvkurcktv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtnaujmptw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtusqixfcc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbwnmookl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwsxmtpqd.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtltdpfaqt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtijpxyzai.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrapxigzz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcudkaoi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtapbpjqkb.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtkqwbscfc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmxnorypd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzvkyrdhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gttuvtnahk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtlhjmscel.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtiwybnylz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtbupvcbbx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtyiyofnpc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtblgnybze.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwvjjrlf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtioiuxttn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gthtdvbltu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtyugoxwmh.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtpwrtiwyj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtlyyzfqbu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtkxrkvkkt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtozdcyxoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtjfgerjde.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxfcblvht.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtwqzbaffo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtperxiuby.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtpntjgbvo.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtldghcetx.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtsqjpvsaf.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufcjxhsq.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtypvvrbba.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtzvsunvly.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtxmguxirh.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gthwimurcp.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtnarmniyl.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtwzxumqbx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtwgxsuybh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtwmrsbzgu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtiymlifme.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtlovptbez.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyicrjmyn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtrwqyrsge.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gttrwxdour.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtasjnilsh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtaucohpmw.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtwenklfru.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gtdtujnsjw.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtpfvujhju.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtyptbiyuq.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gthntjewhl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtapkucbjj.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtncpgessw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtfnjohodc.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtulzxdrpq.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtmvfiqxmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbodpijut.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtukrtdtnj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtjtmsnutn.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtqmiphomu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtpgksobkl.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtnztztoxf.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtrwmaguei.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtlkxwbdkf.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtohjxpjpk.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtpvuekbdw.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtxjjyfbjq.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrdfrxskg.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtqohysoub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtbrrnplaf.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtotykkfcl.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpdkjne.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtlqiwekrm.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtymlziiip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhbxnjni.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcwvwggkq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtsvfisjlc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtnoysideu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtxfqytmyc.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtmoczgrqt.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtqfjlnxhv.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtrjtopsdv.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfgjugyh.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthuyaxbog.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtbgxmktdf.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtytwldwhd.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtxhlnszlu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtcythcjph.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtbcjjjeha.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtysymtact.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gticjwjghb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gtesgxvrek.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtjmlgfvfz.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtfwfanplv.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gthallqnaq.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtrhuljkhk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvmzzjrx.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtbvodncro.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gthykrvtsd.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtjfbcdcmh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtrwyllsmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtoezgliki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtqhsotbcr.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtxqywpzfb.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtalagpkff.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtdjsocqru.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtjrzpbtoz.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtvqlrlxix.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtaqlyqyrm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gteuemdzcu.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtfbeohuow.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtupdboxuh.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglwpazbn.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtlangbumy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtaaashjuq.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtgwkfcakv.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtdfzxpnvm.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtwkxqtoox.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtmkxfssoa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcojykftu.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtpwwwxycy.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtodgqapqc.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtexwpiuqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtejohaxtx.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtyfbsljwp.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtpwlhypgh.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrapvmaqx.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtwkstpfoz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpnymjmbr.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzqqdzlbk.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtvjtncfzj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtuxcervgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtzdryuoke.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gthyytiiww.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtkpsngbxe.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtfwhjepef.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtouzrjjal.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtxqdyjyij.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gttwiwewsa.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtbzitjnny.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtzcjvgcco.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtcqodcmmw.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtytnnxecz.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtofrvxiwk.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtlsjuvixc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtaxlxnotl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtgpdenjfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtqvelpvnh.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gttumtrxbz.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtrashrspp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gthjdnrego.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtqnvwfrvo.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gttlcqpavf.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gticynjwzq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtsofayrui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtdoeryquc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtuoaajmwa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtxyxtlfin.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtttrszgja.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtbwxbmaaz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtancjiyra.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtacpauyyu.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtdqsmsiid.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsaacsmh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtvtdxvstz.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoxrpeyeb.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtecekmkob.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gteksceybd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtfxnccknd.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtkxkdmfty.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtgemscfkl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtapralsmq.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gthebyajto.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjzvxyyox.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtejvxfpul.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtezugbqyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtrjjbqepx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtzbaqzreh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtummabkvw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtnsfedizw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtpejfkbag.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtmcfyczpa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtgzdewxom.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtjaztdzum.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtszsgbdzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtsblblgth.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtgnuayvyl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtfosyhcjl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtqhwgfeqm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtufpetpmd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtkbvtcsxn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtajqjizvp.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtfotqpzgl.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gttxivyecp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtosrdercj.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvhjnonec.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtqglrgwml.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtpeqcrcrk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtanyfoxum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtpbgzbcvi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtfhwyraae.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gthvmrldjj.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gthvqajmke.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gthodkkcde.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtdbhrdvry.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtctkglsiz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gttbvalmsz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtvefaauua.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtzulzklyj.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtsiwwklkd.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtbdbkxgmv.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtxghcnedo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtumfheogd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlffbfkb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtwycdsdox.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtmlgolqqv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gttxulksxr.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gttzqadccz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtdybdbsqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtjfzysdks.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtqdyfmnho.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gttomajoba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtoiauexue.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtnxdnxspc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtplgwwqvp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtukzckwoj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtxkjrpzsy.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gthegqrvmu.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtgxebfltq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtpqfzbkqj.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtlekcfxug.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtzjtpghhx.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcwsicyh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtccoclues.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtukgigfoi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtawfelqsk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlmammxdw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtfbgbllee.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtyrtgjoqi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtnznezlrs.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gtrzgqfrrj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtybavlskm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtasoyqkgd.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtkhxwsvib.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtvowrlmsf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtbvygyhro.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyrzialn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtxndxhrwo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtcnbfkykt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtthyvfbmz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtsjdmydnn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtpdcmfuzl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtafhtywtj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtgnaknvzi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtoichscuf.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtugynjkzt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtpxfxwlxq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtpxkxxtqx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtxfurnxrg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtgpchuycx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimtvzomu.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtturzhwad.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtxudjiryi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtnkbkihfz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcubynhnt.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtcdalpksq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnpqmozqf.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtdbdlljlx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtovdsfjcq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtdevphkbf.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtcehsvjli.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtjnjtmgyt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gteapiawwj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtbtalskbo.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtwfxlrgmo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtturgagnn.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtonhcnxqs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtmmtloqvw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtuelyqmxk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtrhqbevcg.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtnorebpix.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtapmhjzmp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljikptaf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtyzyyndsd.html


<!-- 参考信息 -->