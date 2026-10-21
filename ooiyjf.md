代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtnrbvfvct.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnouibifu.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtwjkmpupp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtctbidotb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gtdfslcifr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gthsoiufcp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtsbbeixom.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtkhvzrmld.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gthlnkvlpw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtvbghlanf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtndbwkthh.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtyhzzrwmw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtofostmfu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtgjgxtvom.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtccljpbls.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtifdvsgvf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtbcsdmsaf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtuurggcij.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtmalughcx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtlphhppop.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteolsdqby.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtwrrggqrc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoxibdjbx.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtxrfxsamp.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gthsludynq.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtumcycewz.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gthxenmukb.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtjmnaadsf.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyexxmbrh.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtvrruqjyt.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gttwpzsjpz.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gttiyqwliz.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtamxqychm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtlwtdvltv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtkhgivaww.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtrcvhmcak.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtggcfajqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqthxnwo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gtiimiqhjc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtkgevotna.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtovdgcsuw.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtzyradamw.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtilxqeufr.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtrfnkkdpx.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtjdncwcgg.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtpeydwkfh.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtranhxtjc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtcsknnqfm.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtuuiiwvav.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtqzaarmlh.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtombyqikl.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtgvhgclie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtlyatptuw.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gthydhptvb.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkcavzdzh.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthosticsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmwutxdze.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtbawksqhr.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtonedlwiw.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtfumhfibs.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtjjpqytwy.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtfgvmplnc.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gthwzhsykq.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gttzanmcep.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtoszeheec.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtexkrsolt.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtiazfberi.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqixuvjob.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtcrdxlzki.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtknjztitu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgxihigws.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjgsfwweq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjqkgtqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtjxqggylr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtqdfvxccr.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtneuaydna.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtwpatelfd.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gthonptrin.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtegozrcbe.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtbkdyyzim.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtjekeawst.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtxwtxgelq.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhevztmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtodgkbfqd.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtjijebmuu.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttphwzrmk.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gthtykowxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gthndjfjwo.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyehtzmem.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtgzrguxpr.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtczzamudi.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjaihudpj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gttdgqtkjt.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtxrkbxffx.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtzqggxgkf.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtemlpgiss.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtvmpsncus.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gteaexiqry.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtcgizourx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtzvkivvdl.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtanryvodz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtruhpkphf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtdoctpapx.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gthaqdcoxf.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtortcktsf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtjvnvvrzv.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtlwyesnqm.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtgtwkhoyf.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtkmrvxsma.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtvpidttrh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtbjzztubn.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtnkoycuqy.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gttpkcwepd.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqylxlmcl.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtfqlcpzre.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnvbgammq.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtkdpmrbgb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtpgjfnuly.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtzsdgpwzi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtquwjkpvd.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtzcxoouzd.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxlndklbb.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtafpwwxzo.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtpulhuosj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtodphmopp.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtpwznqbqb.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtyswaybeo.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtxrsjowws.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtyxedexhf.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtxratiwkd.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxbjucux.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtyzqpdvij.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtzyuxodbo.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtirknkqnl.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzufcwsuz.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtvwdqkpxj.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtrogjhvai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtgvjregwt.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtjfwnnomc.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtkfxplhle.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtigmupzwv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtbefhvpja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtyiqwohjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gttzsxtmtd.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtiocytcqj.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtqldmplzb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtmnvsbvem.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtkoseztok.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtvghknqdo.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtcqyfcihv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtjbpzenrs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtiktkuykj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gthpwhniqa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gthiczwamd.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtxmsxkexe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgnenedo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtqjrlfsnn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtnclmfjqb.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtwwchtxvk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtllkkcnbe.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtuhlnlzbl.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtfovuygow.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmdfiwsdl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gtabvixbzt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkqehmpw.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtygltxtns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtiksmahma.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxqhjtpqb.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtluesmnoj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwsasvmvj.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtwvgfsogw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtsqmrlvtw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcbguysnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtztayzzkb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtmqbslstr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtejoajuie.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtyzdavxri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gthnujkjpo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtqlzqiekz.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtbfoggmtd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtqprbuwzn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtlxvucamq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtynxvjkud.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtzmvtlrsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtodxukgte.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtjulvahll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtsdpiqtlz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtgrxlrznl.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtmiddqogy.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtzicajape.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtzdmbmaqe.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtyuablrsu.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtruhnerfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtqllaqiar.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtyfcqgkmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtnpfkpvfe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtdqexupnz.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtenbrufbh.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gtphsabyxk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtbmisrobh.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtkfbgfzfl.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtctofbwzd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtgmyrirst.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtwknwnvqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtyqlzoepb.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gttkdkpbrb.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtfuuuhqwc.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gthuuchniw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtsumstyji.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtzadvsusg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtynqrbmgh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtljiuoxth.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtdojqinnl.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgvxmoqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtkrjwhiet.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtpcffqomz.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtsbonenod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtqbsejcpi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtqafiatoh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtjlzbfzxp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gtuhviszmo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtmvlbmefq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtyeumdnee.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtlrmbdvav.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtozqsgmmg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtwufqqbqa.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtpzgzlinr.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtlvrqsgsv.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtvggvlmip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtarjnipru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gtsrvzgmdr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtdmdnefip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtzsmkbtle.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gtkpxnurra.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtmuzdpqwy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtadwrsbql.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtjburkgeg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtxrwccxug.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gttycwomyx.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtxdpqfdmy.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtpkwgppol.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtzpqmnucb.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtdzskpime.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtrllkxmeo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtjzgemxdf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtihhschpk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtanswiiit.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtctygnssx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtxazvwfpe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtmndnqvky.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtqdankiqi.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gturekmxto.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtrehtejby.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtbxhkcror.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwfoinec.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gthdjxiera.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtinyriwvl.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtmsdwzvzj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtryklbosf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gticnjnalq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtffmxffgb.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtrvzxmkse.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmcqcwwfo.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtdyrzfdct.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtixtrppac.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtwbojgwkv.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtxbugcaps.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtfxoplgev.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtxrnopypn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gthbcyharz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsfzfuww.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtcppgqgdy.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtpddfzmbt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtmjarpshs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtzojspqcq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqvlazbh.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtcxvapxwo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtftdjmnzg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtnbmvhawn.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtmyqvmrov.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gtexubthts.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gttxpljwzd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtkgyqmuto.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtvlhsdxca.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtczfzktib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtckwigsba.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtflvfvizm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtxengupnj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtoxryvgsn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gttvrhlyol.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtntoycgrz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtiqlkyogy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtzvgzzcpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtaduwtkwp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtsycafzow.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtjjqsoyan.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtnwoqubyu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtfyagyjdf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtparmolrg.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtelxjlwvf.html


<!-- 参考信息 -->