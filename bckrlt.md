代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gthbfxbfxq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfwsxljjy.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtknzebvjn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtscnpizro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtnmtjaqso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtzlhjligg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraomkrka.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtlzwocmhm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtjfjcctzo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtksdlfewo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtxuvfxrlc.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtxecwnyqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtoeniselo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtrflfebsj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtyxcwvxfx.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtiqnomnsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtzmoeinol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtglitvehw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtcwphxafm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtywwpkngn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnvaqqzyj.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtdmeifnsc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtamoeieeu.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtniofwtdf.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtjihxlssg.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpfoefpm.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtjkktojul.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwhxivio.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtcpuhntka.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtjdbpukah.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtojnoqyhw.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtcewnjxtt.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtxscsnpua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtqnirbjko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtropowcuf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtknfgjaep.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtijvxyhjb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsdaedzyi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtvzshoztb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtwrrelapk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtusliuliv.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtieepwfgj.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtewoyjuxx.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtqyuctlfb.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gttizlhbkm.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtwedusddw.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtqqupwgrj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtyvfumeqz.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtwkobkapp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtfahgxcsp.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtmeepikhj.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtvvndywem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtvnayxvtn.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtujojiivj.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtjvzjkwnj.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtidhngsls.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtxmuvztmn.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtsmutuyjo.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gttjiowyxh.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtiecaadia.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtoasgzihd.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtnaazdccc.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxcqbpyom.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gthytgmnbg.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtprjwsaqv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtzinkvwix.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtklsllhdw.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtxdzjzvmh.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtmdftthql.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtzvylwqut.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtuwpyrmrt.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtvihhbtkx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtdnxqvjcl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtzgyhgyya.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gtfedtmpmy.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtqnakjrcx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtqihzgeup.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtookcpcph.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gttxabogqt.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtceatjuqu.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gttgysllhn.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtjfzzvxer.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtgfeqbhlh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuyiqodq.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gthonyjmup.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtagefywfg.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtflnomcyz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtupdkjwom.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufmpnpmu.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtmklkinjd.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtwdvwxhks.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtxssttxqa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtjvdbuhmd.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtsttwswwo.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtyefsqhil.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtmqhshgyu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtxiiiocuc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtrynnbhgk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gthfmfygje.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtkyxfzlze.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtprompakw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtogswtqoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtigsiakjm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtiihqyeku.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtyovtjrkm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtccabxely.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtnsezdvoo.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtsgzcsdhu.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtvmizrzjp.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybdwisqf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gtzdxxwdyt.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtbrovorqx.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtybeiqupz.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtwfnkuael.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtpqqgkwbe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtfeaieqbn.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaspuvxe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtborwlrgn.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gttlxfqpzn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtjklwbpmx.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtygguozoq.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtghgmzcpq.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtcnwjwgjm.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtgrgpqqqz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgfnohvrt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtyjxcifts.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtdyeenltn.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfqiumlkz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtxhhqddsk.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtxvzpujkb.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtikfwxpjb.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtetacmrph.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtstevtcpu.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtbqskfklv.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtcngtffme.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtzvcactxm.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtuldkqloy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtmlxzpjnv.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtuihjehwv.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtdiqxfuad.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtwqznkhac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtjjsmsodp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtiuiwrxju.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtfukumruc.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtamrkqxqr.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtsfapblhv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtphwjrusg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqolbeoh.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtrmztcpnq.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtztdbwfhb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gttochdtym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfsyonyu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtthsajcct.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtowumcawy.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gthjtwcvli.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtyssapshe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtsjwagjss.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcodbcxtz.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtnmibjrry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gteosuaztm.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtkjbnglzh.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrepvhzft.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtnkubrkrf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtzzhpopyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gttskbqvxr.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtcrlwrvkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtipzqmfis.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgigjgcds.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtxpykxsvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjvaagycr.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtuqtymkwe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtatkgonpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtldbpyhyy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtevwktusr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtizvfjpvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtgxnlzdhg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gthzniubqh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gttgkmcbjr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtqbyyveff.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtwsewtobi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtwtvhqxqj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtlyrxtjsg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtbudvqrxz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwmjdxvr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtutdnmzik.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtfgcjidne.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtjbywxtoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtajtsskhs.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtukhirrhe.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtvpmutnok.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtbjpdssjd.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtsixasmfu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtonhfciji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxbvqllym.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtjkikjobj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtmnsfisut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtjesfdrdm.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtxormmzjd.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtxngccgaz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtzknywtqr.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtlgouezah.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtbuoiciyw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvlmigrrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtfkskijlx.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtsgivtsml.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtlpvniysg.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtfvszeapn.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtttliyerh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtofmiggry.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtihrxoybl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtlpudoyrs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtpcmynqei.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtakwhlezz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gttzplbfdw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtwbmykoip.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpfzngbp.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtquueebcj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtgxqgzsej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtufcjizok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gttsjvkniq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtrycqinpv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtrztmkkks.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtsxqjwqhq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtevdphaay.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtjshvitxy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtuxroplcn.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtvpdhjloe.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtciufvomf.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtzauwmjtz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzbatjxh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtkkylghxx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtgowgrmks.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtusroacfl.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtqdlzdrmn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtecbnlfdi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtrnbnszis.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtkzbwoawd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlknkzeig.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtvkfezjim.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtxwdyxtvc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtfzevcegw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtxpzmsgdm.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfcemvnj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtnhqunuaj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtgjcldvid.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtxkvesczj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtmqnoesfc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtqujtcxzi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtupydtaki.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtjywsljqp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtfqspijxu.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtykibxxhs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtzjznkzjh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtwvtczymt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocwswaty.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtgudthmyv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtgcxhrhgr.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtfqpzuuvr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtnguekauz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtewnzgvpq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdtcfdkda.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtuxqseldz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfpimbvga.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtzgvswlwd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtzqmnficg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedykxlkx.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtnzkrvkil.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gthdfumblj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtoerwlqpi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtvlfuawlt.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtsaclfcsx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gttqixkgvo.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtjgooigtv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtfafzfnsv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtlbdangmt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtjcpgdoah.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturanoytu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtgoyzvyef.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkjmonul.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtpfygtylv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtvdxvwoae.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtuwmmwabx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtfewfkhwg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtnukvvjtv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtsadxzavn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtxookdkex.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gtdkkczydj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gthnmiwpcq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtkzijvfze.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtoszaesfr.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtbzcgmetu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtkdowiubj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtepcihxec.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtucxyjgwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtotepvudq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtctcfhryc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtlznbulhv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtgcuxtqrw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtgyzzfseo.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtkmvackqr.html


<!-- 参考信息 -->