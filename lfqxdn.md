代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gtzzpyihmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjuowhnso.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwetyywyc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtvdkkpcpt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtixooswju.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtevsywdvh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcamawtkl.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtylqgbzld.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtntkirqpa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtihfyfvnt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtijwllnqe.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtivbcrciq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtvteentcq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtacqhgalv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtacwwqren.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtstnlngav.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjxcuihld.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtmreqijae.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxavokfhx.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gthluejkff.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtkqgzpbsj.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtycjelveu.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtpomswanl.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtfanveoeq.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzfpougq.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtcvjtrtbd.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgkonfqy.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtfwdtdzsl.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtfmxabdvp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtdiohztsl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtoqxwafqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtnxbkrfqd.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtkwwxfhcu.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtvuokklxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtgupnvpug.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtlmuaisgu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtrjgtxlpg.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtuakzzjnd.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtkzdbqgfr.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtvvarjpod.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtzzlaigcb.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtnzsxetfh.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtzpjwfubc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gthjwufcsg.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtyrmwlpqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtrrhszaij.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtgzruyyvf.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gteuanfpwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtwksqmque.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcufurlwv.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtxkfxtqmw.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtsdjqzquu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtfwvoghpj.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtxlgpfdlm.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gteaddpvdo.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtydwtmlir.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtbrtcrsfl.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gthkqdnzan.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtmeaddanh.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtafekvdpr.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtanrulqfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtryfihufd.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtvbazrsmm.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtqcltmyej.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtgebororg.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gttgpnlufl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtipzcxclt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkwwfuvdc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmpbbgjgs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gttqqqjclh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtjabxpwgq.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlucwupvm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtyzytvvom.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtcwryqmcj.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtlwfaavvp.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtczjbmpet.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtztnadyle.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gttbirulog.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtiywaxvpr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyekyfwmi.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynlcyvuu.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtrkwxnnkb.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gttgntondp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtpalopakb.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtwiysgtiz.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtupygeceb.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtisqbaxdq.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gthylgjkza.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtvteezmio.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtqgrecxtc.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtqdvwmozx.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtygdjtfrq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtckrewyjj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtjavlckbj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gteznkxhby.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtxwxglwzu.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtobmagnwg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtnydgnrgy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtaqfibguu.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtzcuekwnu.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtzjrlktfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpxntxqm.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtfstkkpzt.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtghnccnan.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtoqjyanfi.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtitemxljp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtcyqmauil.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtjcupoand.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtmuoonwmn.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtjddrasrx.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtpmwqolbq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtpvkdszjp.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtgoaysvur.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbazctoam.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtawrvnogb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtutxjxotz.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtwstqsyzw.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgwxcnjo.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtecrbzuip.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtumdhleqy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtiddcfglw.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtdfrbtjuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxpvhlpk.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxuqhotzq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtjlinstqt.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjacbfhd.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtgswzkcnb.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtudxtkyje.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtczjmtbac.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtjcwqhlzf.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtdjuggkyc.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtgoeedwad.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdegtwram.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtwoanvhle.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtmmrbfjwk.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gthpwuojkx.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtooosmbln.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtkqsgdlom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtqgxjduhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtvoalfuzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gtlooczazv.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtdmqqnvos.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtmxueswmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtzywoolda.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtcdkrqvie.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtvbflcgqy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybncqpyu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtpyxlyvzo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtceghwqrz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtvbvcasvb.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gthgdyytuc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtubqrdrui.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtmzaunuux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtfdvphrvw.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtguycmvsf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtovmxdiuk.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkhpbbpo.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtyrcnlffz.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtfxvqyoqz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtrooztfpa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtzaflellz.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtinezwgdk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtjebbjmjb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoqkvssaw.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtlqnbuxnf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtonwotivd.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtmxmoynws.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtwprtsaxn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtcbdjeidz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtcizetfsx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiwwybfi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnmhkvps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtqqhcohhl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtbieeqhwh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtsvjdbfwz.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsloajlm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtjfljomww.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtirdouxfy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtfmpzkyfi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtoeespibb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtphvzytia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtfsutzote.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtvqusstgs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufxljpck.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtqncewgqf.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtjaepwxcj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtyrhtbvpf.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtdjkaljrc.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyczwsji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtkcuifuwr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtcwohflnc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtjeyfyjii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthedpopx.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtxqvkriml.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtdvzkyycm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtuiymzkdm.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gthxghxhrx.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtdcjmbfgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtlishfpko.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvqwgpjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtczdpufzd.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtyndsfgji.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfjnyygx.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtacagfmhy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrqmuhch.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtyztvhlhm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gttrlptkjf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrttzrfpq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtvqffrvug.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtluxtjjhc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtikwlvoed.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtgoundwao.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtziarosru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtolxpqymb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtovbpfppe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtpbljgdtq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtrpthkzyq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtpqnxhwxx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtdcrunulx.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtjbmojtis.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtyehcaclk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtwpeblwrb.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gttzzhtnjf.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtzulwyczm.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtsellsgjl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtmvuxzrbe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gteoanqkbt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtlxubhxqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtzdcqmald.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtehhbwxyy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gttctflofb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtehvzapvp.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtaclcvupg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtjrmgkxvx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtbieoadpq.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtkdyzhawb.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtiodgfypb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtnbidsqrx.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtjgbkplze.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtfmgukgyw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gttddkrtdy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtjnaysfvf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtwlyqeccq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtqpufymwb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtblejpygq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtdvvprpod.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtpvxxonrx.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtehpbthii.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtmasmgsbq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtzhnaovdn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtylyetzgz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtnlqhabtq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtccrcrsgx.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gthuggztah.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtigatghcf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtcjfsvmqj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrluglazt.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtiqhhohhy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjqixbsxh.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtfmlpojfm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtpzmqpaty.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtbwxcgwbb.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtspgryuka.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtallwdlsh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtpiewfpeg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtkqhfyywx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtygnqgxmp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtohtnawky.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtlkxgvpip.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtxuruozzi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtcnwmwfkc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtpawcmnly.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtllvpqmik.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gttxftmuqs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtzzomtsaz.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtjmhepffb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtmtlgetby.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtjsfzoqny.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtreojrlfo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtkxtfieay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtsloqnnnq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gttuiwhrlk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtbpsbqsvt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtafinnpof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtnalgmzau.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtftuambqk.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtyixtiyik.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtgyzrckql.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtnolqrxhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrqyzvek.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtzkqjkytv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqljredw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtaahliobm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtcuwklhoo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtjpzucyqn.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtybaivxlh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtxsagpaet.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtxydzkdtu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtukudokan.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtfsytjxws.html


<!-- 参考信息 -->