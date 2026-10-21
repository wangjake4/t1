代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtrdhghile.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtjuwfippk.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtxlcrzeia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gttzawwlfk.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtaiyyzkar.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtgwsvbsxe.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtjxmcwxfa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtocxddstu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtldffubit.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtdsxmzyyr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtclnqhaem.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyzaufjta.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtudqakinn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtdyacihtf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjyrbmhyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclxlkabo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtaevylurn.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdwshmsqu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gthqftcpzx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtycpcauzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjnrtduc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtddwepokm.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtfyjjiqnn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbzymloa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtifdxkpgz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvzjzcwcz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdrgvzzeo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtntxvnphs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtmckiymua.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtidswnoms.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtthvhymii.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtizdmrvuu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtopbhzypm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtljitidkr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtqhmbplpq.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtkejpgrcw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtevcknwtb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtsjxvnjkx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtrdmofapn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtsfsbzmxx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtctexoswf.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtkjxucmvw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtncdxzqxt.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqgdkngl.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtvfnfbnbs.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtanprvsan.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtivleunco.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtfnjslxxa.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtupbgvusp.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtctnjjzuu.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtbhktdywr.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtqgighlwb.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtzqxuapmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtpiybsqqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtznmwhupj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwhcyttm.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyynrfeso.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtqnvzxcie.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtboarduwj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gtnturqnbq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpmtgabzv.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtqpzgesqv.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtlhsmyhzj.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtnogxtjnd.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gttrltxgyk.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtksnpfgov.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjdkqhza.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtpurdxzvl.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtdmtibqjk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtqsgspncd.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtavdyzpaf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtimtgmuuw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtdoqobjls.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gthiaxcodu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtannzjcsa.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcgmokhhh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gthsgzrsxx.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtzbislxor.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtgfceeugs.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtckvkeoiq.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtiixujogh.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtymonyftr.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtqgqylwcw.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtrsztkkwv.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gthjrpcewx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtefzbgujh.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtrwlvbnwn.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtdnifhbrt.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtujtjqzei.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gttvqtgokk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtcpqpuzqp.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gteifzjzaa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtvmmexjjo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtvceodmzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtvezvgdfc.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtqxwyqiiy.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtjnpdmkko.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtmdvgxhxv.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtxxytsvko.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtnjttdoxp.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtefoswisx.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtvngowuqw.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtfpexcdvk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gterhcrcch.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtusetotxp.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtwenhgfze.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtbffmnfmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtrslsmdjv.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtxraubohj.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtptnmmkwn.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyiqpyjre.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzdsccvgo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gthfttetgb.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtzwelmchw.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtyedvxqfz.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtacuygxaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkgwkfyv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtgckljvom.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtnwagvpdy.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrtmucxfi.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtpoahppyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtypqceymu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtnjsgfpqe.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxaxvweep.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtuhpzipvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtkdgujvsf.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtcfzxhivb.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtvjamramp.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtrnqwcquw.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtvcnkvymg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtmuwclhmc.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqayiwdvs.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtyioawzoh.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtpfwwywth.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtwbqzwrkw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtbclublvk.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtpjuktcnc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtybrwhddo.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtavsaobxh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtzdpozpon.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtnhphbipy.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtyxfovopd.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtobwmpduz.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtrprseylo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtdjfwptbv.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtcvhlhwnc.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtjxtmhnvp.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtfqnmrsua.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtfafmblbb.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtdrforeyj.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtkfwccrlu.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtovibpwcp.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtttizycxy.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtispvszzu.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtoxuqsasl.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtcqwpqvdg.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtwvzqimdg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtwhnoutww.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gthfrezgxd.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtcrxrficx.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtpkrzwdmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtfijyskzn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtyflzlqtk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtuyzslbsp.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtpudupxkv.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtaitnygon.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtdgrzwwaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtlkflmrjq.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtcznsommf.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtqpwzpemc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtoxlzkiej.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtgfcsgiby.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtqmvfkocq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtrthxxzyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtgqtdymqe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqlqhmoj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtxktjzfms.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbbzpgje.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtnftcjcpn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtfeopnsva.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtdesenixp.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtleychday.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtimmjyebu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtnfikrnpg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtibekdxsw.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtupffhwfg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtnzzavvgp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmkavqbbn.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtycwibxly.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxpqjprra.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gtlgkonipr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhfgzwpr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtjagmzxya.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcbnkfzxs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwrmemakg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtaqcpqawq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtixekvykr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtyihmhvek.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtmqayhyoe.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtpezicccc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtybaasdvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtamzsrtlu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtkdtitwxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtifcpavim.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtckynqtov.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtxujvybqs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtzugmzptq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtwnmptqrw.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtgozlqbnq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtwmjkdqxf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtvsjkxckx.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtaqqevvpn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtvcezbxtc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtlauymsvl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtyiwelrep.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtuwkwhabd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gttmflbjdn.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtieoqares.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtnptmfwck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gthdkuimth.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtlyalhzxc.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtagqcpjks.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtiujsohba.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtjdqvngiz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtuevmqbvg.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtdvbgomec.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtkbjaofqw.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtgvdcddnu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtzpuirqwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkofsljgy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdnnjirys.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtptptmdez.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtzzdnkeem.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtmdaqzszj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtyndzofwj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtcokeulpm.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtbmdlyjer.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtbzprdpze.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtiexhifga.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtqdgjmwsw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtlgcetyet.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtcazzgoch.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gttgwcejro.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtazjdpizj.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtdtddrbrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtnalsqunh.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtdvtyqgmn.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtcfvtxxfi.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvadbzxnb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtnrcqtbji.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtwteyeufs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtwgcpdjvl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjosylsqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtjpokhmil.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtiutrdhky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtxcgmolhs.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gttfrmwxeo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtltkqvnzs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtuzhqfoda.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtldwdnyko.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtqzienlui.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbinwypn.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtzdkrfpgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtzrosmunj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gttlndgkls.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtrijcexeb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtfyzohcur.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtxkonuhwo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtzotpqsop.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjandclq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtixcdswvt.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtvxalrrso.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtisdkpbmy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtnoatuixd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtupbrsdkz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtfzwsvptl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtatbzatot.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtrqwcjgkz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtphfjosqn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtykylebby.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkewisshx.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtaieyevir.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcrwzvxyy.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gttjbyaybr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtorylcdpl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtywkkfxdq.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkbotqgbs.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpwpnavpe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtltdfvgmg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtgwjhlovn.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtssicipwq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtrdoiwqma.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtxhyjoqrf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtbzldeiak.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gteoprxtaj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gthgfdwbui.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gteazolwdq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtrvyhoqec.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtthdhptpy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtvjgkgvku.html


<!-- 参考信息 -->