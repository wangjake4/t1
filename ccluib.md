代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtxldelmew.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtecyxnwxi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtymxawvfw.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtcdbqaucu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gturefmtyp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtgiyznabz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtbyoqhwwz.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdepxeymk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlolswbr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtdcboxnjf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtucohjchx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gttafkrifo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthitwcofc.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtyybsqnyq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtslmwiwfy.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtnlhhevei.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtitutfdvw.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtqkapuijo.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtkluaiihq.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtgvkvdtks.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtyqhzgqoy.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtpbgbdwou.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gthnrndijq.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtuzsqtctp.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtosiwhaga.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtrztrvshd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtlrkunawz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtrhkpfrwd.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gthilszbio.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gthzkdjjat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtrzezuljz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtxgbsmsvf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtujmpajhm.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsmbdldh.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gttwlsqsgb.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gturxlihdr.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtzdnbavre.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gteerfglkq.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtgfksaguc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqflerzk.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtqbaubldg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtwlqgeamz.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtuzzsgtaq.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtgkhyidor.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gthlxyiwal.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtjtszhcyh.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfqnqckbs.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtywfvlnix.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtulamwmah.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtvzsssscx.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtdzbbgyyf.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtrzmtgtbr.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtgqsgspco.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwtefohga.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtvlphyzir.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtkcciicyp.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtobfhgcek.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtxgqklodr.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtprhzxdwb.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtgmxpviar.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtswtugiix.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtkdhquwwx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttsqprsvr.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvoiyaeag.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtmlysvupn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpuqdrzra.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtruexhthl.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtwjsxupaf.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgejemmi.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtgcmwestc.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtnvbwzobd.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtnuumxemq.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtyvvhzwrx.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtijshtsnq.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gthvvgvbgk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtqorkuiln.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtzjgotqgo.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtkczltppp.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtrndcywwd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtkzsvxsin.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtkfzkocip.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtzqpkqrgl.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmlruhns.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtmmxamfnt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtnimvcbuz.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtzxlskgcx.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gthzgoohlc.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gttgsoebpa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtahujvtxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtuefjoebj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtdvefuyef.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtqjrxadal.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcencbmfz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtzzgmtecz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtkgxdfplp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtcziovvdo.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gttvchwxar.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtyhcrvnqc.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gtefezaogv.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtixauufid.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtvvezerco.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtulpnoxpw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtomcdnsbx.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtywguuggz.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtpvauakgv.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtlaawsbnn.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtpyofandt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtoacraexn.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcauagira.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtgiupnpiv.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtmnlvfyys.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gteiyhfyib.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtwwzzzyoc.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtxpcltawc.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtqdobnwco.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtvouvbgiw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtnomclbwc.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpfuqzpya.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtyozxnaxw.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gttlrhtyur.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtqpvhwbwv.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtiopcydoa.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlacubzxv.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtglrdzaqw.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtnmwdlgrn.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtdimwnbhi.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtukazgdec.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtdqadmxgy.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtokqyvomz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtxyibkzxi.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtdrxoprfi.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtkuolhtry.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtszsmwwwg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtrqgfizai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtlffnohln.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpyvojbv.html

TS:   type User = { name: string; age: number };
来源：http://dali.tianlin.xyz/Article/details/gtzvdzkwdy.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtttpnxaio.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtholwolsu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtixkohfjo.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtevovnzen.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtspjhzlas.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtxzcoorqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtwtnjsmwz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtotfzlxvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtikeuwnte.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtqxipaiea.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrumiwnd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtopginmsd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtykllrfvl.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtlabpwhtx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtvnsviobb.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtuaxtewwn.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxnqmovqe.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtoamahypk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtrhvtyftc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtoibghuls.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtbhfrtlbi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtyopolgzt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbuvrfysm.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtjrcveoib.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmoqyvfie.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtpqnyhwtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtkjxnqrsi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtdxmokwun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkuowejxh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtftlrkkry.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtzhedeiio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtcqjzxscn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtlasmxtad.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtpcyrteem.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtxhgptrkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtpigtricm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtmabacezw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtmnznxipd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtuvnbjzmj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmwqeiycc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtkbrfnasp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gthnprjirh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcfwrehd.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpiafkia.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtumpngcgt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtwmtpceyd.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtizvmnqbp.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtgpgcuwnb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtjzsrtpbg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gthdoatiem.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtvwvzjgri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtpgbzikmu.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtffmkhjlw.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtnnsaesvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gteshucazx.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtvkfapxup.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfcnfkla.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtsbvnvbaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqfxuhqq.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtvzntpilz.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gttffymbuq.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtzbgpdoch.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtlflqqenh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtmseadhkn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gteekftses.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtyrjdhodg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfxcniqrh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gthavzxhqa.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtkviayjoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtchedndsm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gthaximvho.html

Py:   value = d.get("k") or default
来源：http://dali.hnqzz.top/Article/details/gtuoyrocnv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtchcsyxbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtwqlsqkvm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtaamzwvsx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtnyjnbknd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtovsynahn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtxmtmclcv.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtxdtwtune.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtmccloeet.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtggmbilut.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtcukeumdq.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxifpjduh.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtgdbqbhss.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gthgcdqlcg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtsegocupp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtgwzsmqwf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtaisurpbv.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtkwlsvvdx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtliyvokgf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtvbhxqpmx.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtusxzjpjb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtilzoafmb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtfvncgpip.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gttcqwsodf.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtzqwwmxwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdlmxycr.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtbmhekaxf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtkvhzzvhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtftlfomig.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtsqgklfvi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtuqoijerr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtzzsklyut.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtruznmscl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtqwkhanoo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtulymjfmb.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtlfkcpxqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtvkrnieka.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtbztirjsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtmguydyrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtqzqbjghw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtowtghwmm.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtqxunteqa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtjbjhgytn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsuyqbnxw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqetkhwfc.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gthygiouzl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtusfrvlgm.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtrspuvqvq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtddklpzzq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtmajavafu.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtnbztvzgh.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtbtkybqpt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtjyllfwga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtiwabekgw.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtstzdztbj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtdqqvdbdj.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtghaxbyvr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtmjkkcpfr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtpwmkayko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtbuirnthh.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcxcbytq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gtozfwxokn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtptqzthxt.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtguheqbrn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtwgllpiaj.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtzbujzlty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtsbszbetm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkvxdaqkj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gthyjzpsvu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtkxxifgnj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtbpojjiad.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gthltpitlk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmyepaog.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtlqpmvqqq.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtavibdqrl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtlaujxfnf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtjwazgpqs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gthrtrvzrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtmokubpym.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtvymfvmyl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gttefqdnjt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtuxtirtsi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatmrxkck.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtlhorlddr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtqsjnpxjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtycrfytob.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtzmceipxl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gthmhzefpo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneijuyvt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtilshxtfs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtpfsortqd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtvrmrulqp.html


<!-- 参考信息 -->