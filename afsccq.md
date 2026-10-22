代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2csbbvlcb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gilixfhk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iaeadgbc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2kwhgwzlq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2juyhbdjv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2izwpmiqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2reeorlup.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2kdmrxynu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2qiwqnkqe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnysuger.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2kjnhchao.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2amkarejk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2kznvgbrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gt2tmecjhhl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2lybsxjwz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2lexwehkq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lrujfvqq.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxexanyu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ggfeulho.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gt2nrezwzbl.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gt2cvfhrumz.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2oeveutjz.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2buoayljh.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2fiiiofyf.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ytwpuwfr.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2obowsszf.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2yunhoiyx.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2dwesdvji.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2otzhpvus.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2zjjjcnys.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iorgrqcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wrhsdolx.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azncdsab.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2lxevgwij.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2rmcqmebv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2hhhsmdfm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lruepdih.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gt2hykbydie.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2vkjlhvql.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2fgwijrwh.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvmkgtaa.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2ygwqlcqa.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2qhcjexsc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gt2ziriigyr.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enhfjojx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2raetlnrb.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2trcfgfct.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2uiltnhhx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ogwwsnqf.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2jvazdiqq.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2kfumgbgp.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2jnclrgfv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2rvvdgncv.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2acgfhjug.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2bjioaxfb.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2duptewxb.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2aooebfor.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2lmhrzjpz.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2fagcosbj.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2dvmtxwbm.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2tefomaxe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2epfnebqr.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2peysdaxa.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfyewywe.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2vhvxhkkj.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2crerektt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ahuzyswl.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2lwoofwhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2jvjmnvol.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2zevcegsc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2evfphdzv.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2jypjeexw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2oldrcnls.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2ceyewcwm.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvfqlwmp.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2jsdxqwfv.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2kwrvrean.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2qcujswxq.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2hnsnfqzv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2btaafzsd.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gt2ivzjqthv.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2ehtnahlq.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2rwcegyyf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2wersrysd.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2ppldyjbq.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2odrmwydl.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2iqnurhai.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2ncwdawkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gt2tkezjmyi.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpveppfi.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2iaiytbox.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2ywingwfv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fulnlbaf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2kywfdrjm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2zqxmxwro.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2ebgkdpdb.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2pcbpqbcd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gt2giegfbqj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gt2izwcwkdo.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtuwscbv.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2ravqsgzy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2likwugik.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkvsbyni.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2qlkbhluv.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2mrjtthkf.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtsmotpy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2swyqcehl.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2cygfsrqc.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2ompmbqlz.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gt2vamyhinw.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2cbicjcoy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qxihczsf.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkbhvkpw.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2wmeexjmn.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ozvunpsb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2ggvqafga.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2dydmevzg.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2zjatmedf.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2exiaoghm.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2xsekivlg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2semwghgs.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2jpxgsixe.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2diafeinc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xtjzokki.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdspanhr.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2ajxwhiyz.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnahiaqy.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2cyesxuck.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2ujvnrsbi.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyvdjwwr.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gokzqgaj.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdrysnje.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2ejnawhkv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2bgomvjas.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2hzftxewm.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gt2trpapxha.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2azrezyvf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2fyktluvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2wbvdojjn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2ptmkiawr.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2kiwciorb.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2mctnlnnd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2zqufasbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2hmotaoiq.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gt2tszxfuet.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2xjxftbqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2ghvdeora.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2gxcnjoow.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2cerlqvtg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2xaymhuou.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2siarbajy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmiravyb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2bchjkqtr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2ubgxulab.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2wwsxkokz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gt2tizchkuk.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2wwnllvkb.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2gywlwhvt.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xycdpuyy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2cejidxhw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcikhxla.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2mtdeeuoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2xliknbpo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vaecagem.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2moyepuii.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2zomfndes.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2vcnusqvf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2bhpzkjmv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2ggjehsok.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2tqtrhtak.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2hozhjogc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2jktervuw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2obutzwte.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2uuewopka.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2ishksvvf.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gt2dafuubgu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2dmlbnlix.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzospfwt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2uhfifjlw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2vcbveszy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jxfkxrmf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gt2jdlopptw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2xbtoadmm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2tddwwobo.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2usiyhmgk.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gt2vvieuqxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2qbckfyzi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpypkaet.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2fvdcttwi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2gkdsheol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gt2rwhxygop.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yucncwgf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2fgwvevtp.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmcjnkeb.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2nkfrvdkn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2gywzefqp.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2qxhlkhnk.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2wcczdchu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2jucwdnxr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2inmddvac.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2eafehmmd.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2gtbzxfuh.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2rsznqpem.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2aexdegop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gt2lqhyprye.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnlexoii.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2bwivlmsm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fphhtool.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2xzojtiam.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2pauoyltb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ejyseabi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2ezqzbdwa.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gt2inzrvvui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2rgfmovbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2pcghfouz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ireoetxu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2angfudlu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2xdhxdnbb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gt2tsfvzkcd.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2panajuqv.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gt2wqyogdhn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2lenfcjqp.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqbxxiba.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2xbiiedwt.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ehxznuti.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2medvflcs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gt2gsgwmmdr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2gszrkvzg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2jiktjkfz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2ebabpshq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2virgpjdf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gt2ewbztfdh.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2yclchmif.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2wyfxzvia.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2ltmuewkp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2njhwmcwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2kywofyik.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2lyfqwbzb.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2zdarqpjp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gt2yporeync.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2rnpwekwb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxmipwrf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2extkygnb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2kjltuzir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2qoanyzvr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gt2fjsogigg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gt2yofefpma.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvhetnms.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gt2ymtlpvtr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gt2ahrbhtiq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2uxgewlqe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2eqjhaiha.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gt2xhxcxcoy.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2irsggxyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2qnyvzjrq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ntictsmh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hcnikemm.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2nwpbmozu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2mjahnyoz.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcvivioi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2fwhcyecf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2aorpnqzy.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhjdmajw.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2gcnonbsc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gt2crwphjdp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2cbdtkkfx.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gphoaulr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2tttvaawm.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbuyefkw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2yjcglnbv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikykzvro.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gt2vyjxymjw.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gt2xzsmhexc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlxmjqym.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2pgctyrjh.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2avnrrmlu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2uqtugtbb.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ughfmftk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qgkjyfut.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2rpoiuron.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2mtnbcbml.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2zwwtwook.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2zshrcacs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvqwdecd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2xwaztqnv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2futyxmzi.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2iplwedoh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2duggeuyv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2hxhgzxsy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2docmfzcc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2klewsswc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2vageitmz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2kglhqoed.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gt2dztgfawf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nizqpaci.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2fvttavuv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gt2gvypcwuv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2nahmonur.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2jsgoqqdd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2gfcpsnqr.html


<!-- 参考信息 -->