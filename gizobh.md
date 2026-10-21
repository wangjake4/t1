代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyalpnlor.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkjaanmvz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtctkgwfec.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtulngcjte.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbxfkgbdr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwkzldtt.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtqcjghlsr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkxgrtsxg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtgabwqpcd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtuqguptcf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtwmkdrphc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzmjgvuzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtfroczlik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtnpiiiulh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtpgposwhl.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtyxssnvrf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtlgbovfey.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiupcaun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gtxikdhfal.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtlmtykhpt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtrmpzpwzv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtvdcqsqsk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtgcebjetr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtrwcbnmqt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtaznpxwqd.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gtztofzoid.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdhheohhi.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtrzllaumn.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtiobgcksv.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtowrmofct.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtxybmdltw.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtsxyounhi.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gthspxizvm.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtnjuzwfbh.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtkrxdnlzy.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtjpiqpzuu.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtkushsebb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtvgmfuibx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtxoxpqwtr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtvlkvmycs.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtqrmogcxd.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtnwyklxra.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtgyhmnnne.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofyxifoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtylihejaz.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtmihpguoi.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gttmnqnyhk.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtckkgraiu.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtqwppmjyr.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtodtcdqhp.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtsjxywvli.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtscqcqspp.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtqkhtdgpu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtekvafxsz.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtjxtjvfyz.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtcgulxfkk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtoflobgrt.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtcloraesv.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtvzqrhfbk.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtmthteoiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovxzebke.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtjcunzdqi.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtzudnzcjs.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtwjsklyax.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtuuodszdt.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtucdqqawf.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtrbabyvup.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtpukpepxh.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtbtwbalna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtpxhngzbf.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtnyhaqvik.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtpxwazxia.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtqfoktpiw.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtvuslaigg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtlwdsgckd.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtbqvvdoil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtbodaylum.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtrvpjbian.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtsanbvzsk.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtswwuspzr.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtcyhaeqwb.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtjhfcanjx.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtgexhbwbs.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtxptkgfrr.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtuxvheeds.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtwegkhzwn.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtppvlywel.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtdhgfumhp.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtuvitbwbk.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqbthfni.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtnebsacke.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtcbzzrhog.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtuscknfpe.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtcshkjrff.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtxldzgran.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtzthjuocp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gttdvlffhb.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtgpuquxhr.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtcmenfilg.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtwgeksjgq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtpuacemmj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtnljbwyai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtjshjajki.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtatawopga.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfqjsyiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gthuwkigtu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtauiuljch.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtigyydxkd.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtkwrcgqbm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtmyygnxqq.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtogtnhyjj.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtzblbnbzb.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtkkpdkcjp.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gthowabpvt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtbqlchuec.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbvvezyq.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtgwrgmmsx.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtcdbwokjp.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtzvnmgcwm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtmoiplttq.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtlvbhwxyc.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtnelvkoye.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtwedajlsj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtkzdrzcyl.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtkzokkbld.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtnpqvqieh.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtwhdbgkkx.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtiwplnuip.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtrpgrbpwl.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdklynzx.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtzpipxthu.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtypwcrrox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtjeodgsvb.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtsfnadauq.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtowulrgkj.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gthgkkktlq.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtzveuvtdr.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtbmngoegx.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtbazhomyy.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtiuomjltg.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gthqzlokqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtgxtfzibc.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtnjpipnfc.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gthikrnuin.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gthhbwddlf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtzcosylxr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtwkshtutj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtldxhrhuq.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtmlceyrvv.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtupjpmqxy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtsurvsksr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtogagrkbl.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gtrqzrqimd.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtidlsdmqc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtrffpfqkj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtktesybsy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtldfgydqk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiswxcazg.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtrejehuet.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtqvgslfsd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtzqnzbeaj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtxnajmhyt.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtbaxtpijn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtymlvmifo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtqmzarose.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsazwxvhb.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gteucanbxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtxnirflpr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtzarrpewa.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtbkgarcbf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtxezoucux.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwtvsonni.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtvppprpsp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxkrobsic.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gthkzvwwfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gttfdjryan.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwupjpkuy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtadcrwnrj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtfypvrnvm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gthcdadjus.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtmjgsylhm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtwzlswjnx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtvcwuuseu.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtprurclgu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gticokvcug.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtmdylausc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtktxryvzi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtdrzfvkcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gttkpckeep.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtcmldghgj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtiynxjllm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtzskhaewd.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtktuazgez.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtovzzlffx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtsvlzkzyf.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqdxfrmoz.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtrvuucpji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtnglxrlak.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltxpzyxk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtgrjgdjzf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtadpanysp.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtpcdburfq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtpdjobwmk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gteivaiioe.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtswnbejmm.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtjujqmwjd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlklkxlil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvywiusoe.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtthhrvshs.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtohfwduqx.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtpedjwzhr.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtaysccaon.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtpihcvmqx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtetjigocq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtvkmvmikg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtbaushbhd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtamhscoqj.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gttqsmnblk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtdquybqfi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtqffmvdid.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtbovmvvcp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxchcyxfp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtwghzndms.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtqyhcieuz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtmaiuzaoy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gttfptqkqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gticrdibfu.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtmkmegyrd.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtgizejniu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtjdvsship.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtmxzdgusf.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtxobbyvna.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtnnfhngtr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtjomsnfyn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtvajaouts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gttpqwjxnu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtemwzbpvl.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtbotashrk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtoyqnncwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtczsbqruj.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtwjhoyxtm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtikgyxgen.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtckklakvu.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtehknyncn.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtpqtugybv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtdrlypfbc.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtaeedhrdw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqrezggs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtbvqjinbh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtsynxsexz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtjydcifvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtspzsjhny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gthuirjjuz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtxucrsbuu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtxmmhreoh.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gthcwjzgcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gteupuusqn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtlfzzlaeg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtybdevtci.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtmlzngzjh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtlkahokap.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswazfoip.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtuxlnxnjw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtdvdaelrg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqyrazwvy.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtguanxrmh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoxutoerb.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzeinwlb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtilkaprqx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtqwsqjayu.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzglyxndi.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtfpzhycny.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtfwasdjjh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtjiwptvfq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtbyzjqtux.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtplgxzegl.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtpzgrsvwg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtvpeewnhr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtxdopsqvc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtqamiopvx.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtkqunyalj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtudahlsyo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtasutddms.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtufbwtiwc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtsoirgwss.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtvztryyzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gthfdernhe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtlstemgeh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtiluqkydi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtcfhwqfus.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtkjrmlhjd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtmwnsyezw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtqvqqbbgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtyibidwot.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtrefdwepm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtacucbwpo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtnnjuwfnf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtgkbaxsho.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtwxhztfqb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtbsessdby.html


<!-- 参考信息 -->