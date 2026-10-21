代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtmqqufyax.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gttqzkfoqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtfytfxqaq.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtahaenuyb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtjerutfju.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtgzjrpjcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtcfyfamee.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtlrkxmxen.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtrsjxhsxx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtginskojl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gteumskddz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtersjokti.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrdqrupno.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtwrrkoree.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtotxthaen.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrjodvus.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtjlotzzfe.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtcmnfruwv.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtokteqwbp.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtjlnlnavj.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrqfmlabs.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtsgvdemap.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtjxmheamj.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtcirydqvy.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtlyfyzusy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtjgbehmhb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtodmqmxro.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtvqqrwnjk.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtcyploxvi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtpsqmjnws.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtwmaanxga.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtuunariyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtwxtimlnq.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtgcjeczcf.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtyjaozmxn.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtrlbjuseo.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqqmiqeq.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtqybecrdv.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtbplqptfv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtbnhsnlmq.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gteoaijwga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtholtvofo.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtxrncfcay.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtzcfhxery.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtmjdqsnxi.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtnykxytvs.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtwnjbklzm.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtupenfsog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gteegplxtd.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtcrmmdaam.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gteeanwnoa.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmbqqfwk.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtnitkfqfm.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtsjujwozf.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlteowcam.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtkgxrkegv.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvjsiibq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtzeviclna.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpkzyqea.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgcdlrnex.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtsgqjoxrc.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gttnoedeui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtolalhxny.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqjffzlki.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtlazmroaj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtrhskwirt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtxkpdmggg.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtytirpexx.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtpbwvkxzr.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtxrgjlalm.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gttjmazood.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtmuxaavpr.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtjkmzjsif.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtalbynzpq.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gteiasuklz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtuejgzhvx.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtjrdzdlzh.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtmqvpskdi.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtjbvrxgbu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtyfetodis.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtqvbxsokw.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtequvqvzp.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtspflcnwi.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtaesovmpt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtvhrsmnrc.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtdohyckpn.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxuvatxk.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtvkuuvwzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gttggrmyxa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gttcqhyjme.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtxxmzktxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtftisqxxl.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gttbsrolms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtwzvqxjdu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtoavrzfct.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtkqaibcvr.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtnacpmpqa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtlrivcnby.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gthjltagdd.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtelelewki.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtgborbblf.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gttegpbpxc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtbbdhdbwn.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtcbkyeehs.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gttcscexmz.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gttnrepzzw.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtrysueyqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtbxufssnx.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdbpdlpw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtwfxgesuy.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtjiogsums.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtrscqrvps.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtzydyyeaz.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtidqfbtmo.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfftnvkr.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtvpccdjys.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtommqsxka.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtnzludytp.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtcgxifdce.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstwukmsa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtgyzvzyot.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtcunpmzog.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtdyxjqvny.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtgswlapub.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtndxwlusp.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtpltoando.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtguhjszax.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtzsqyimeh.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gttjujdoek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtpyhekcyr.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtvuzpugkj.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtfyeeqsqm.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtrlcqdtny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtjondzhqw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtgyoowafb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtnqjfqjap.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtcogjxegy.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gttwdpesvl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtwrjryucg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyzswmkx.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtpedtghag.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtodetnmiy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gtysexhwvw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtjpuencwq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtnaoonpir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtffujajfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtigivslvy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gteflmlyqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvpqhvuc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtyyghanzk.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtphqzyytt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtfplazsqs.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtskkbrxam.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwraokfbn.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtntxeqyer.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtxxshxojr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtrxewxogy.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gttduceqsy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuoaocvo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxopdlewb.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtlzmvaozu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysznnrnn.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtmibfvyel.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtbnfknatl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqknwultq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gticwxfcgq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtgzdhtcfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtdiorkqzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtxehvossb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtorhfocxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtvuzhiaig.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtnesmvtuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyqqhfxo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtrgtjilvv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtuhdzbpwj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtxpjyiplp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtlbkusurk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtxtknestv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtghovnjrm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtsdmdfnol.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gtlcqeahkw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gtueerjgxu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtdmydcnak.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzufdsnec.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtshcvtpdu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtgrqmqltk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtxaxjdvva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtvykoglno.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtjrqibegs.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtwdlfwhuw.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtanoifmqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtodbjqeqk.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gthqgorsoj.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtxoxglokv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjuatrho.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtpbyvgyrj.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtltxdprcb.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gttioyuqji.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gteszofiqv.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtjxvgcbzk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtjzcfwnlq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtefdwauue.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtaekibews.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtiilumzcp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtitxjizqn.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxfjwhdc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtgwxoddsc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtchpiunua.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtjsxloqsw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gttnssjpbd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtqtajzmrd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtxiheoihi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtfdynyvup.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtpxemeeit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gtwoyuylhr.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtgmierbbu.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtmmljejue.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtwbuesjpe.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtltonwtif.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtafpjibey.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtsbhyefry.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtioyypbcv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtsshrvegf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtmllkwtya.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtvecmaggp.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtpnomknme.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtdofehsmn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtwxmpvpgf.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtejmldgav.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtbtqirmiz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtowggzbag.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gttctoepjk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtmoujowia.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtdwaqphtz.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtftlnbbdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtbslzgqwx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtvniqmpuf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtsrdwjvvq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtpuqoowzr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtmpozismd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtumptsxvw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtgislslbh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtschfdlwz.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtaujingju.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtnlkvjynu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteevedkdm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtblenqofo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtnqfxemfr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtniznwjae.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaizgnyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gtdlkqabua.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyynnzfys.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmiiayimn.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtrxiztsvc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlcxdhucc.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtyxpqdukq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtiejuoslo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtbqqzolte.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtifsunwsj.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnxwgmrh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtnqnhuquq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtmywrxsdm.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtouiwpjlx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtsbqqsjei.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtqrdnijgc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxaokpyr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtqiqhrxdy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxursgql.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtuxmyxbue.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gttyxycwpi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdknoifjq.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtvbpsxnwu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gttgeemlmv.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtckjizqla.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtxyqalnqd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtnbwrnffr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtylihqdkr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtwccllnim.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtbxyowswc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gttsnxgscd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtewsivcqt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtndiqjbsp.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfaphuvax.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtqsqebmoq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtmmnlznsq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtsmplbnco.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtjmxnqxjh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtceswikym.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtlqnkhcdk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtnyxgpmlk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gteaaoqbym.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtwpyzhdcb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtlimhurdo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtymegqbsx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbdzlgiss.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtrsmcrkrq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtbvcedtmi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtzxycykxr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtxurqfdds.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtqiqriggq.html


<!-- 参考信息 -->