代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gttsjenqei.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtghvfrniy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtxurxrjuk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtgglamuaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtebjrjnoi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtbctplmla.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtitefnlfg.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtslyvijju.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtwbpnebmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtuzprdqgq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtcfgrpwrz.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gthowcyblz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtiksoqwaj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtryaexumm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gthvayhbex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtzvnbdzcz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxyngykbr.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtgenaazaz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmrmuncfq.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtrnluealg.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gttnfqoogj.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtzvrsevxd.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtvmlziloc.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaxedligw.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtbjmibeio.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtncaglvca.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gthnvvesry.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtgbnwocjo.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtupdkwwgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtygwltjtl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgorhyibu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtccgtting.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtcnucycic.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtecfbgeev.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtwzlibptb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtcoiowice.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gthzlfrfxd.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtzuiznipw.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtjrmebjgu.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gteaxhqdnc.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtohwucjxi.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtdmwsnbmp.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtmbivjgym.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtcfltuxsn.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtinoorhfe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtxelmafkb.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtyaantbkt.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtddebovtn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbnitexjm.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtvplofblo.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtemitjwva.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwyldjuiz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtqvluekne.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtnkqndcxu.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtqvibjlqs.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtppbqakqh.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gttuatroqf.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtedqanmjt.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteyrbdyfe.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtryfugrlr.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtwbaqfvhd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtkxocryaq.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtmobfjhvw.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtfpzgmazn.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtazvlxbvj.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtypheaphd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtfdhreedc.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtmldkfzim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtyeobvfny.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtxljufmwd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtfwwvfhsl.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtzqisuiiv.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtqhzikpin.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtrbnzkxlg.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtrrdnltwy.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtepxcvajd.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtkgfcfgtj.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtmvaztlce.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gttedexjwl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtdjtaveaa.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gtpcuowbrq.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtudsecerj.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtvcqkfvln.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtbvrrwuip.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtjnitjtji.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtsgpnqhbb.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnogzkntd.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtlxiygmrz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtecbiemqo.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwklqndd.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydprbqit.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtrwjxgqts.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtofikvbyo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtxwlycqcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtffrwszip.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtxvnrpldp.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gtxqpotzcu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtzsobdpjt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtzrzuzkvy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwdtyecus.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtfqvbkjub.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtrfcqeqmp.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtgtamnknd.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtcjyhqywr.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gthmsyruew.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtmjwqmfut.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtisxdodak.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtlnaazgwc.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtsqukfsio.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtujsirbhj.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtbzxtaqyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtqasamkbu.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtytpgisqq.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtuzvrgzab.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtqezbrzyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtovfyijtx.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtnxsihliu.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtytqyzgeo.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtymioqqoa.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtduracida.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtbdrclzrq.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtlusckfmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlpibahxz.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtgchvgbvr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtlolmbyel.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtjtpnrivb.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtcbzrifaw.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtkhwrrpua.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtcqqruxvv.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gttaehozky.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtuanieulb.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtvewqilpj.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtnlroutvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxddjwhkz.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtmewuwpth.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtkhpxiphl.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejlwalak.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtokumucko.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtgxqggpff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtqjhgblms.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtgnyknfjr.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtqkaonkvs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtrypxzbxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtqmttlpqg.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtcmrmoyqb.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtjzxszpwq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtkvdahhxv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtqezilcsx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtwublktdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtvfhncqif.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtdzymisbw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtvrfqcdyk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gteskbftdz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtquhtwajb.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gttklxpqpt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtvfuguvjs.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtivcwugvi.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxguwxau.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvmsbvjnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtzxumlvkv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdpvpgvq.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtqfdcnfbo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtfyodkfqx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlaokmvws.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtgtklgplc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthcznfpjk.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtkgdhpiyi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtogeeandx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtqmcumzat.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtfaefrpmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtfaxmnogr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtlhopotzb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gtlfjphvfj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtbaaksthz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtsjvjqpjy.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gttbfldzpz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtqwnwrcuy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtcrrqyhyj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtkvkdibew.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtfefslmhx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtyghyepcn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtnvidkzgn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtaxssipfn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gturjitfkf.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtzlzpyoih.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtzjywtpjk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtvcetgahy.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtukcommjg.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqfwjooc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gteowekqxs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gthmdrqnet.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtlfxcuzrr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtfhznixmu.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtutvaztps.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtrxrlghgb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtsudedwhw.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtclosrxyl.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtjmagcqcd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaecqpyr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtmaacbzhj.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtjajtytue.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtbcihczcn.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtwkeduhvx.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtniufehme.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtxafsyrcs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbdmyyopr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gthgvnjnjd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtylgyensz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtipcjcwfm.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtulowhrqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwpsdctzk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtdaxomtbh.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxhumafu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtmdkoxiqj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtltugnlvd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtshgwmxob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtkdzveqxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtebnjiolm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtpihbfyjt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtvavtqbho.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtiovpocov.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtgragugva.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtbafkpziu.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtncaclduj.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtjxitkppc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gtqhorywcm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtnjgmwdvq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtzpshgcxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtrioxakta.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezfaqeim.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtaqkdefuv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtvcbudtqm.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtnvclnjjy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtdyapvkkk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtdcpvigml.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtrbedwywz.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjdqfdkd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtzitbiyqf.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtcpthjlxf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtbjcdmsqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtycxkvrkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxlrsofb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtdhlylxaj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtavonvgiq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtgpgvtxmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtdbfbhcmv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtysbkfylp.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtausncmzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gtjzgnjlfl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtmkbovjsk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtnudxktkc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtxwjudfyx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtkmhfvwqi.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxajqhvgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtdrdueqqc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtpdwlhich.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvenogscd.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtyhjvnnsv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyqsyqduv.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtfxyclyln.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gthiiaazli.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtwicmsxmp.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtonvfmadt.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtdirrqiiu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gttpeiqsuq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtovemdgwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrptcnqr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtdfklueiy.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtnpqusrfe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gteirhkywn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtlrunlqep.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtsbapwvkp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtmrjlebvo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtskbpyzjz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtvxdsumun.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtgnrqspzh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gthuyyclgu.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtkaowqtem.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtuxuqkpki.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtfblokjsw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtyhejyfch.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtthkpealy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtsxdoqqss.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtvtdskgre.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtmxjwblva.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtzosjrlke.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtnurbcwwp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfuwctdkl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtjblueydj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtihcnidpk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtuierdott.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtvvfinxej.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtriqjgyov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtzrzlykhg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtiyzaveen.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtxjrgxgtf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtprrgekdl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtmspourkn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gthnzanqys.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtpbhxnfxb.html


<!-- 参考信息 -->