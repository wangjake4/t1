代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtcggxswwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtfviisxti.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtpzbarkdm.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtihlqjoyv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtratwxsvm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtpfuxqqfx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtpmhbjmyh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtfuqgrmpt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbvafjxia.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtybgtoziw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtbvkgxxay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtkplzrsoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtyeldgrka.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkjankcac.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gteliwttou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqdayvfao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gticmaqbwq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtradcyqal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtqdvqqpod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtopapnofk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtnkwafwdu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtervmqikm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtwttitvym.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtizzbyeya.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtqwoefife.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtmuogpdvb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gthaqzsezh.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcbgwfbu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtjgrfctlx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtzjhssjwj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtcgoltluh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdcppgoo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrluolmwn.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtrdabcxpy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmfirvzka.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtwatpfhvg.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtecawtauh.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gteonvxvdu.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjaygpczw.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtrmvyfxul.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtpqrdtgyu.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gthyzaxrcr.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtpsstmpfg.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gttbvigyrx.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtzseibwvd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtpnrcekdp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtyjrzphyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtvhmgcifu.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtsbezfmkd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtydgeqpks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtogktldjo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtyhojddso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtcwoewgmd.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtfdgoriiz.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtnnypgqts.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtddvzrtdu.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtpalwmquk.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtgocyjjxo.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtifgesgpg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtwovssjnq.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtnwlsrqsi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtemjpgnvr.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtfrrxhqos.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtmnazxrjd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrkfjkoz.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtefttlcjt.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtluqilowv.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvielfiou.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtfcptptaa.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtleqnvxcb.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtoyalvkbz.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtplbgvttd.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtngaayqij.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtexkqpjbw.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynjkxiko.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtgctggyev.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtnwmidqgt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gthqunsozj.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtkrefmfph.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalasvkvm.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtrohgteka.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtqvvvyube.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtexlmegms.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtkcobonng.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtfwpkhwbw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtmlstctku.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtnhtkgbgh.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtzwpytuth.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtgmyjvvck.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtuhiahuzm.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtybltyzka.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtvkadgjgt.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtkybmfiou.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtnhsunkcm.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtoahruyxy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtguvhvssn.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtwolactxu.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtqycuxgjc.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtngzvkmho.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtdfqjafej.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtuejxefeh.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtlrjtoyvn.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtszubfjqs.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtueuujsjj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtrotflbyk.html

Ruby: def self.f; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkzssglme.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtlftckpse.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtcudyhjky.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gttswwilbm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtourrpsqd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtjckmqlxi.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gthgzntrym.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gthuwmizwc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtnkpjprnv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaqsqcxq.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtxdbldizn.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gthmvbgrxb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gttmaorcrf.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlmevbqh.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtqcpctuwx.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtnfsebduv.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtaozthfvd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtzdrmuoxg.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtpfcwwjnk.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtigqszvqu.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtttzdmdjq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtynnayjpd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtnzhwgfmw.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtkcoijqjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gttpagtugt.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtavgihqjb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtbjjelzmc.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtnjdeocfp.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtihwbutug.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtpdmaxrwh.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gthxnylrma.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsydwikkm.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfukvwpcl.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdnezykqj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttnzqwntx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtxcjxyazh.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtqnqayaii.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtzwiissuw.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtjyyhzmvh.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtqudjsddz.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjqikue.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtjoeezncb.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gthzxkovsc.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtnlkqfmtr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtoudhxhfk.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtmicunrls.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndohzoix.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtwxsseefm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtjuqgntbe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtqpcfblky.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtulhlxjlk.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtacfzfnbt.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtqeyvrawh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtbykqqtfv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtixojbbod.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtxlxjzcai.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtmvmnvubn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtpeyydkyk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtuvpdhbtc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtwqpqcwyi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtvitirkkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtworribzc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gthpzidwtz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtmteshidt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtnoabgzvq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtsttenywy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtodvazgoe.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtxjflfbwo.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtwfugkgei.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtqkvuzztd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtafouqbpv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gthyldiihm.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gteinzlcrt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtveicvawf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtohixmrwi.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcymixgsf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrqjzetz.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtzsnlbtyr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtybyfpyye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtpiigipzj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtcxnsttch.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtgttaahjp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtuqmpvuia.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtmakzrbbp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtunovptlm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjphggvm.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtszhmwyor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gthwwtbvmp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtnquifgrr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtipkxnpts.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtjzhngoth.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gturksvxgn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gttgvpwglb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturrfohre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gthlpgjvmb.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtfrwwwmhk.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtwxvhhupk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtxrdbjetm.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtqzigbsdl.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtetujjftz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtehusbjkq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtfyoprhkt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtlthqnqbh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtryxxusgg.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtpxehkoyj.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gttktionou.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtlpgzttew.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtruyrquzv.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtmsvhwlew.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtncahoyan.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtytmsofpq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvycjued.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtpalihnfz.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtmevsduur.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtcikifzrd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtwwngcdiv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtljuacwrr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvcheibja.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtxkrnwqqm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtbcysubai.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gthtcljwlh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvwjnrbla.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtnjqkiseq.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtpoojzvwc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtyjpmnpgi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtegysvkcs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtijjbaqvx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtziuwcsbl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtjavvmxaz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtkyrfbcrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtrxkoqnmc.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gttbrlrjes.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtuwtttzki.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtoyfathpv.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gthhoipsqn.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtjcfkrwbc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtsqyeojof.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtyyskqyew.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtetdwcmqm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gttqsabjnk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsatvkzje.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtnamabnfj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtrtzzlqce.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtapcpqbcb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtvjztbicg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtmyhkkkuf.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtkatqfrmf.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtscadkkbt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtlyrehowc.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtpbgjckwm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtjkdivjvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtcowlywkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtbwxujcgx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtrpylrtxb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtptvwgiog.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtyyfdgurz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtksvsueut.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavtwqmv.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtawpmbjoq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gteycgqpsg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlkiwieb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtoxjahjxr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtucljywrb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtifkekjqe.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtvzygeoxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtxuteutxw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnciekhjh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrbqtqzmp.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtbxboixtz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmilkiqph.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtjungjniy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gttzurcwbx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtipdxgbmg.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtmjftvnyk.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtgbclmgpc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtwzgndpwb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gtlxdbqtae.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtqqbkbwyx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtnrdxerda.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtiiiabtwk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtyxcdxjii.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtpfriompk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtlstriexr.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfdjrqzxx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtlxyfmhey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtxjsegpjt.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtsalaaulk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtdjxmoxcn.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gtqaaaziza.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtkcgdxumn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtymmxwntz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtlliwyfof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtprkvuymk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtldrmmawu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtkhbnwpxr.html


<!-- 参考信息 -->