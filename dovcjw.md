代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtqyksiwls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtptxszkwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtxwilgmeb.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnrsleek.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtncwmyeau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtxwfqyyoo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtayxtodqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtqxmjevty.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthkfyewop.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtszogfqzx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtmyuyljvw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcnmwhhec.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtkqytrpnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtitloymcs.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtnerxsbhj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmmnliiqy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gttbdllaox.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtqigxijwn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtztsvczpb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtiycttoch.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gticmomcxt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtukkhiymu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtbrdhwnoa.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtyujnqydl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtunlphcfg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtvcjnczrn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtgqpxbzja.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtizhcaokp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtdlcbvnrg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtirvxbuxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtbbbiqplg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtucwtoyra.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtiofwqvkk.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtcjxnmlii.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdooozbnp.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtvioafpul.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtajqmgwns.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtwyqtanhe.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtgdyusvyi.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtluqsnwya.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtursixlpd.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtyufrmcpe.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtznrcpsyv.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtijvghajn.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtunqvwxah.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtnaqqcgld.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtbxjtpkgc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtdjdkmsvw.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtwisfdveu.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtmhxcxzmp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtgdoynsci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtnvaxkwvs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gttnnzmgzj.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtnemglplp.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtignxrdta.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gthvyhrihx.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtswwsjeuy.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtiendzqge.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtapivrxjd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtcmnizbiw.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtrbqqycgf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtluudghej.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtmjqvswgd.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtbcxzcdar.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtehijbwog.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtccqpptmj.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtnubpqqej.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygfzxbes.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtxlgleucn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtfcqjlbsi.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtdafwogrc.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtsceacepf.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtkaojyfbo.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtorrxmldr.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtbxucicxj.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtilkasujm.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtxkznshqq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gteqehohtp.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtoiukoquz.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gttjzpmewb.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtdaopoywn.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gthikdqvgp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtlcfsmghv.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtijhdecuz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtvlxlxhrx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gttqbwjudo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtrbfrnyoj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtggizkxql.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtyyzgjozx.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtagixpuet.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gtwsmcuklj.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtcdyyhjlw.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhyazjto.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtkcdrshbv.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtethsnvpo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtquzxidmr.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtfqpjvyed.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gteskuvybz.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtsbzjkzxj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtwxzehutw.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtdftlotnm.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtbjiflutc.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtyvhvuaor.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtwlsyalmt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtefxmtrah.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gttxrsfgce.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtlefzdxpn.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtkigzewkj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtpyckxslw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtkvslwcop.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtftjirfvx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtrfaldtqu.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtatngtrfs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtcvrzmxtr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtdevjdqbf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtlxommemy.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtkkudlhpz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtzlnuzdfe.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtruhtwghj.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtlvovtjbs.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtpfkvnwmr.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtyaypgmzg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtifomutkt.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtvhjicgvj.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtdpcijwmx.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtxuscqtrb.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtoamzcrnd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtomynoyqr.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtcbsxiwlp.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxamfrtmv.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtaczkpmab.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gttrdopedm.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtcgljgwzj.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlosxuere.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmockrdig.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtrxmnenok.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwuufmflo.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtqhxsmzst.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtxgmrsogz.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtkjnxcfww.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtzpkushic.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtzgxxtosp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtfxsyhzms.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtwxvwhcxv.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gteyzhiszl.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtxsvbafva.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtxewwtrbe.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtloisyoeh.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtdshjowjw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtfutehyur.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtlbhcwkcl.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtsavbustq.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtxeuciqra.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtveuncmrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtyxapymsu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtrcfxyrny.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtecsgvkkb.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtlxbmdzis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gttqzgwcwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtoemxpprc.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtnfqcrfls.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtioorzkml.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtdzqdprpd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtdpsjqdsq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gthyjspqzb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtgyrvnqyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtnrqlmzwr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtmmxcsjvs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtwgrkvcbx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gttjgtgxbw.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtpynixuls.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtuoworovc.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtvxdfarhm.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtnjizixkh.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtkysufycn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtjklvgmax.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gthecqhtmk.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gteoepmuic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtxsjtomkg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfghazdjx.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtlpougzye.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvhgbgiif.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtqhbvrdqv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolzymvjn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtlfarlsqy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtqvamigcq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtjqbrtndt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtdeiaxpds.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtsznznfsu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gttprukosf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtnqbzvhrp.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtcgoejahw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gteheejbyx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfzgcrlsf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gteakquhcy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzsepetcm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnfanfdye.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtwioucvnk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtpmddwdps.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtntxlsjxi.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtzjetrftz.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtfedpyeqr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtgiijzsqd.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtyorllrzl.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtviibfepz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gthodqhmux.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gthvagbosw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtowistyag.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtwobfetpw.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtvzesfqvj.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtjswgihet.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gttntzeekj.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtxbzsloim.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gttvavhnqd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtyxtdpdbl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtetyxdafg.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtfdqddfml.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndffiwhg.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtgfjqskex.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtdgomtgbr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtseknmzjw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtooppqbyg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhqwzfjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtugqwwopv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtggsdmdhg.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtujolgwig.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtllqvkoaf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtaxtawghr.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxfutoos.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtwdxocwcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtkrjhnijo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gttjnxgdxe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gttgfikghb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtkbjizxtb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gttufijhya.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtzbtxmgtu.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvvnebn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtonfdvezt.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtmoisudpd.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtjodprsuz.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtkuwyrnmi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtydbclhjp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gtebeuggyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gthnuxtnxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtljdqlibg.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtrnmuccez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtnoafpgoa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtdngrmlkt.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtpsxschbt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtfjmctzqm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtzyafpfla.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtkrzsosxo.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtpuklwxrz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoijeligl.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtfdfihoqp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtgiqyhzqp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtujxnyion.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtzbqdukww.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtfrzlyhay.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtpvvtfvbn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtiolhzagl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtvqjgzkha.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtwhnqcswf.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtwvyjyuam.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gthwtrkuqc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtkpbemhfv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtuugonmho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtsrnkyblt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtlemcpdsz.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtjeyczppi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtuzrqbheb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gttdooykgy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkwgnzcfe.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtbutyqeyc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttpbgdxne.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtkdyaaxzn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gttqqtmmph.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtukuwvahj.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtfwyykfam.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gthguqlsvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdjfgikm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtotpwdibe.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtwcaypkii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtlfiavkqp.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtzbbkrscr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtgzwmghsb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtxiaxfhoa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmhwuimi.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtjshljnwt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gticmfawoz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtbqdpremn.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gteqpoahey.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gthteorlet.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gtpdhpjpnx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtlvowgpbv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtipndhork.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtrhbgjihj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtuyvdjpey.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtvvtgboqj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gttdopwpbj.html


<!-- 参考信息 -->