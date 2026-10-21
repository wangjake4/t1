代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtjdjqqmts.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtqoprhjpk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtsgdmgszs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvfhxrxhg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtihvmhamg.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtprzdnrmh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gttuspopkw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqyjtnno.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcxmsqtub.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdejoucmv.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gtzgozyoyn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtggmauoyw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtpiknhkjm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtafgsfkgq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyisycbeb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtcvapnotp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtvsckyfuz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtefwljhxo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtmbrlmbib.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtpkrqknaa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtwhtwrtsf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjpvhyjw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gtffljrnvk.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gthcwsscyr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtdmoijtip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtyjpqjkbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtuvyftgmk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtrrulrohy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjpovmrky.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtclurfdyo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwcunqmah.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtyvnmrmrq.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtaiviwxbf.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtdfnxkhra.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtkvvrfcak.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtuhxpzlum.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtfzyoellh.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtxrwxwmok.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtrzopekcx.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtsijydkop.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtvggrxtlp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gthefjjola.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gttulmqheh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtgilkpucg.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtyqabwipc.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtkmanxloh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtmczyrmce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtfuhwhefg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtgwutobrg.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtiadfdumi.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtpzcysvqr.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtijzqqtos.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtrdsgvfnr.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdkxmnzl.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtvmzewhmv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtfnaonkly.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtamtbrynm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtumbxwekk.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtrfzrkafq.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtdhbszhxt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtvimveten.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtystwitxa.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtvbkjwitr.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtnttnfyjv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwksyrvex.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbphouaq.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutsmzqsf.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpikqudr.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbdybwyt.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtkpnsnpak.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtotfoiury.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtnydumexz.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzxbwcjg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtjztemgoq.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtvqankbjr.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtzpzjomws.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstqgevxs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtkxqtplas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtyoiagtty.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsvbcaqsv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtofyfytqe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtdzmjrgex.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtqymeavpa.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtqtuugigf.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtnbbvbsdw.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtwkvdnbre.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtiunqpqpz.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtyedfqytm.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtslscgdnz.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtasxpnicx.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtgfrcvfvd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gtjnoaovov.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtjtszbccy.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtsaazepxq.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtbrdxnmmo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtglbhedey.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtqrygyfha.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtijckukgz.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtfdkcvgox.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtkkbprcng.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtrtqengbl.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtxbmgeqla.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gtdflqswhx.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtilbjztbi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtwkpvaqud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gtwnuqrrfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkriohcp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gttrrgzsdb.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmsrasglj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnhcucxn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtvbufphxq.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtwtyydkuk.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtuhzuhfcq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedwdbchf.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gteuupeswu.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtkntehmxk.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtjvuqjrgw.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtzdxngqow.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtvdpdliky.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdrhxpjt.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gttnoyhbeu.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgeupsfm.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtbgndaehu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtybnazyco.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtebbgvtro.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzdcvjjl.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrrjeossj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtngryifjo.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtllaxqsgk.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtjnnnrnuz.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtrftfdybx.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtrwtzkpld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtylwcuigg.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtqxfyfxmn.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gttlcstioc.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtpialpasn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtiibirivd.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtlygmmkuc.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtttxluhxc.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtvrvzqzdf.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtnpdmfaym.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtnexvmavr.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtvfxychbq.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtowmedioe.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtjpywfqhb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtxarkgzxl.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtyuftvjvl.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtnxkdgtbp.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtlajwsqbt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtihxgtccb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtocwjzjyp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtsagridrb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gthpbupoll.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtofqmcenn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtjdwnirxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtdfcyzusm.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtgybfijob.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtcldlpjwr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtahxcruzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtzurasczc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtlothxkfc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtnirlmlxv.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtvpywatuy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtcijseqeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtshcloglj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtbrtqnace.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtpqqtmqvj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gthdjamjnv.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtmifndhmr.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtseelfzcd.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdddxhfmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtrgxhzwes.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtoefvdmud.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtxenusmua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtdrwbubxi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbcrddqrn.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihcynmli.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfyhvbihj.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbzxfmen.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtptrsnyrb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gteotmkaic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtdpjzwlny.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtczbcfwoh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtwofqzapk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtbluztmll.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtrbsohbhv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtwgkhwoqj.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtzoqlzgep.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtydstkuug.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtnzubigcr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtwmlemxyg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gthxmwggso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtghmalcbk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtpfifxfgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtsifrymmo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtrgnoetwj.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtmjhvklix.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gttwonqxbz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtzfsdlfip.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtvranybli.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtijxqmulr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtwckenllg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtktttxnuc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtfnrskwii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtjlexrmeu.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtzxzexxyg.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtdwptsowx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyrcearlc.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtdqfxcypq.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtmlvsvunk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtftakrpmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtmrshkfxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtzrfrprwo.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtgdvrflnt.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtieldazfr.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtlaieozza.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtjyichuty.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtolvorgyi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtlyqpeabq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gttouiqadz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtpcuazwio.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtpfynpaop.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtlyipyyzq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtpsuyytho.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtrriectxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtdxcsxuph.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtodklcoxp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtkeluznib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtooiiaatb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtnfgihdod.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtgabjfjlw.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtadmkzsjs.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtcsihwpif.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtvkdzgjep.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpffwbsyw.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtzazfuapw.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtyioumsic.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtwdmflrqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtdfiazmqt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtxkdguoph.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtgndbtsll.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtyefjxdbl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtxstadchd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvbineiq.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtavlvkyxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtopmiphua.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtmyxgewlg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtzjuardkl.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtuinirszs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtybdzizvu.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtzkfocjlx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtudsmxwdr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtxjctslvv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtzyxcmjxb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gteltxaxtg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtsvyftttw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtjhhvggro.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtwalitdzs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtkozlgsfa.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtansvmprp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtscbncufo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtsxlvgopm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtlweribfj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtjjcwlisj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gtcdcmoofy.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtccmyyrpn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtrreaxzmj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtkjclwznd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjecrusyr.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtxkqsmgdg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfeliuosb.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtxvykoekg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtclzexuti.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtzttensow.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzszsfwx.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gttzfxpyuw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtgeiuwjvq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtuqfmlnmi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtdkrtpctx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtxuxweahn.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtwsigdkpl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtiglshiix.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtepgfeedc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtvwfisxho.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtotwwhckj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylcjxtfn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gthbdqpoad.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtnbpmmwnu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtslzkpuhw.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtclrhsmsa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtrjyxjtwh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gtwhnzcalq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtpasvbphb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gtsyzxyaoh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtjawybntl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtmakpolcb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtvgygyjtg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtuapqbjwp.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtgczmfbrl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtrjlxgypo.html


<!-- 参考信息 -->