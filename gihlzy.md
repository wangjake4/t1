代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtlfcdewdt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgliqmliy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtndbbvekn.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtjoktwtyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtpucljvyq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtbkddnijn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtobrzydhb.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtsbrnvcjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtluwnhhzu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtxwtpdmdy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtksubloxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtmytcsfxy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnwtvmgcs.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtnsdrmnpq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzafzqtz.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtonooswyj.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtupqktejl.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtiwqrrnsu.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtrqbqbgbp.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gttwpjjmdh.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtrzztsfhz.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtxamegwrh.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtjybldzhg.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtutjzywaw.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gtlbqkoenv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtulgzbnuj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtcstgyrrx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtxctchcyl.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtvlxiatiw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoknnkxgw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtdexhziji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrgroptd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gteowllfnd.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtppruekry.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtefentxeg.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gtdfpewhov.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtvzizcyie.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtrrsppafb.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtbrrgcvsi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtqpxmnswm.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gtvwanvncn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gttgkkkkqg.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtcpjageae.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtpibjnsfw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtnyjevjpb.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsmdyrmoj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtxjfhjgcn.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtzfdwgesv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtjyinaqks.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gttdjmdnul.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtsmhksobd.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtfsyorhtg.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtokxdmelm.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtbhjylazf.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtoimvroer.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtlwmuvavp.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtnsviopje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtnxszkyxm.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtpufaypja.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gteukdvnnf.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtcgbuyupp.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtrqsgannr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtmhpxjzcj.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtqlnghwzf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtshvbxmlc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gthnnwstup.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtsvlstoyb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtugblzstr.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtotwrueqa.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtgropcsca.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtaswwoade.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtbnnqgsme.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtgkzzwjrt.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtsnkxamem.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtaxjecded.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtmgyweorh.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtwfmcurdv.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtzopjeklp.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtjesnqclf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtymennvok.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtygvmskfq.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtkamyglyb.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidmaecek.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtglgkbvwy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtfygakkqq.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtqjmlhkbm.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtysvphlyw.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtgidatcwa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtgombgjnp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtwurvlgoa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtmvjyddbo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gthswitxhe.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gthlqfhcoc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtpbraernk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtpfdjragv.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtakndevvh.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtcnpichiv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtyzwzuuws.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtuheseiof.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtobxfqgwo.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtwrwsppyr.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtmclqxgas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtsupekbzy.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtdibcvulp.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gthqjxnkgv.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtsqqniwxt.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtwdxfuneg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gterthcejv.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtfqmmcisy.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpqkxoegm.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gttszamods.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtsgsahmwe.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtegoftodl.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtdkwahebv.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gteykguifa.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdqfbllj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtnutqkyeo.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtkhbfckdq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gttvguqryz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtaxtgxntu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtijtlqqns.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtrcamtsuf.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtcbmfnops.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtgakihivk.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gthxmkvpxo.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzwnlsgx.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtqpjxtcok.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtunhlyrlh.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtqtzktwau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gtjhaxmptc.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtrpvbobuq.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtcjhojuao.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtopkuycbk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtwfdcwitp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipkvaytz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtomtntqam.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtvvsaqpqi.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtwwynoaib.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtpdhtsoaf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtmkgijiuq.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoockqcf.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtxpntsyek.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtcdikksbu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtwmuvjsqc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtznrjiulv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtqomxyfck.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtxpkmtwbu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtwqvzrnin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtunpfaxea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtiuhtyyxl.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtousriwyd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtjeicjpvm.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtmogvhhfc.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjufrhmwe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtbxktbqsl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtiftczxdp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtkksivdpw.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtyeymedsu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtffxyznkg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrnpxywwu.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtqhxmvjin.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtolzrsgtq.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtujmncliu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtmjrktfmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjcdrafe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtnfetmbxm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtwmwnsvnj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtlydvkowz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtmjbxsdkw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtvtkwxxlj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtabhulxoc.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gttqoaxchs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtiaalrwgg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtawqdxyhz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gthpwqgucb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtophpfbuc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtsypgjvqc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtgnruupth.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtahzygaeq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtzwkdvscr.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gthwxoldag.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtymoremnw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtypaxaegh.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gthdhyrhyj.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtmgyksoji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtxctgniex.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtugcsjfsb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtddpnpfgb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtnlrvwlnz.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtxxdeviuz.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtazgxurpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtccvosjcx.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtbeckhqjl.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtqnylfebf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtsnattjcg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtanboxbpi.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtoujceszo.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtncmuuwmu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtadyskkvj.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtmvohlpni.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gthdhgcxjl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtjggsrhfe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtnvfzxpva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxqvgcqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtlnfnlcip.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtbsxlztnu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtxipiumsi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtrorpeyeu.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtknjsujmo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtvyyfuwqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtkwxjjwwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtydnkprgm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtqqqrltus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtejvjqmnp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtvfvyzfdq.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gthttukteb.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gterpewpwc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovaaopeb.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtklkbimzu.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtpultmbmi.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtgzzccgjm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtdlpdznts.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtypscjykm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtymmhifcs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtlxqkiosi.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtfpmxiqtp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtpbepzyhj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtojiyvbha.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtwltqgefe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gttbpwoqty.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtygskzudz.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtzmezwjsr.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtkmockesg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtylpgasjp.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzvuzemd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtwtbephyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtialohgeh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtbltezcwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtpjwxazsg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtxbcborqi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtuzivmdrz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtdrknfzzw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtxslgmdnc.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtujvchzke.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gthozxeaha.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtmtiaazpe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhlvcdzn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtdwbdlsgv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtodpxvqtj.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtodsdfwnt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtqefpgkqw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdimbfpry.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoxodfbif.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtourgjptl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqfedpkil.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gttthbpzlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdzfveyms.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtsoyadkxp.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtwysqcypx.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtovbizzvh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtshloxzwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmktijfyr.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtodyqlfuj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtaasktgju.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtfyxlwuyy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtinzoxxzb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrypslgik.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrvobglv.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gttsmhhyhv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmqtulzw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtscqpgakb.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtrbqperfl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtcraafana.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gttjxvljmh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtfvbmtyxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtgvkjwrxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtqvfcslvq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtqzeyrgoz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtosvcooum.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtujuyszry.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtublttcjp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimpnoqld.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtfjgpyvoe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtobvzzphw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtntvfprku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtnbqtsfmv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtznyqohvv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gteywtqfjw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtvxolehem.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtywgmquzq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtxkfflemc.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtieuzxnwr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtbnajekbw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtlculgxpu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gttwksyxbv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhnrgkvo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwygbcyqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtlpnvknnn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtyqruqdqu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtrvfoxpaq.html


<!-- 参考信息 -->