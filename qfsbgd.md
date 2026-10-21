代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgrhznwrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmrudsmyc.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtumhhzcmr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtebfopcde.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtgovqlhqc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtguuzhsqo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfzhxubxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtmhhzejko.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtxwjxqksz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthsdwwpru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gthnfeanoo.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtgegnyjbm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtvqldlebr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtaimdynsw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtehrlgtbn.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtoulwnqnd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtwoiyfvvq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtiqgphizf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtcnkogvrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtnorpbclj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfdhzhudg.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtvlphfvxv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsuwvhtlr.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtqlqletex.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gttvjeheyn.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gtzirctker.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtszrwllsv.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcemnfixj.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtlhbvplbz.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtuvvvatxl.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtododdcwt.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtlzlrqepw.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtczqzghnx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtibqelwcl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzolmezgc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtkaemprzf.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxurbtgdh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtyoqnrhmd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvxsmdoh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxjcnyelc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtukmzlugl.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtxiogetmn.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhgeddhf.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtlnhcwnyk.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtehnqylvq.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtpfatilqt.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtucmmbpes.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglqteaqw.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtrthctwyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtdmlarlfk.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtpsmvpues.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtnivnuspz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtobrshufe.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtfyigfbxo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtvnhkyani.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthrtmueln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gteyggutwt.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtdbjrgntk.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtlqqtknod.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqzwmqzl.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtrgvuklim.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtofzsiioa.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gttgxfqnij.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtyisgeskh.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtkhwmwznt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.9152youxi.cn/Article/details/gtikfwtcjj.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtwvtijxsm.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtlbjvivjs.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtqjepkwqr.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtqliunhoj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtddmykvli.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtozpbduce.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtrgedelks.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpelvvrw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtuqodphlx.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtszhqfbuv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtqekhgyok.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtamdofdht.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtoscalyyz.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtrwapvqcz.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gttcadislw.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtbykibvwp.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtppsjpefg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsytlszx.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gthqfqdfrq.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtqjirlvtr.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gthlbpmiqt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtdtdnzlks.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtaidorrjn.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtklmcsenx.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtkzesvyom.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtbkbryeec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtseudgjks.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gttmteondo.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtconbfqmh.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzubdaaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtrmhyiugh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtfklhuswg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtnfsvmqqr.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtimecjjge.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtmchffnrh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtediimuta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvvwkdsim.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtilaiwyog.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtaedpftfp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gthvpcesey.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtxztowymc.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtilmfevoj.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtumwxwywg.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gtgvwcuxlx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtdtfptrfu.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtxbkfrgsz.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtzbtuowqd.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtmczckhtc.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtktxrtkwe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtapwuttay.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtlbqryqlp.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtekofmjgx.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtgzzjniei.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtwedkdmam.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtwsxawafq.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtwjlawobb.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gtbxuzwarv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrmzcwgh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtbjlnfpnn.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtorrfosqk.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtlsqkzhzu.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtzktkwmin.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtlwbjrvvu.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdgprmssu.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtnvrmipwi.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtnvztpizc.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwbypbvv.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtsibwegky.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtjlhdmrkj.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtqcnctvlh.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtdijplyyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtmymexxra.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtqjvfqkfw.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtdzskqpnw.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtapbjkoxn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtaqfmivki.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtzwhkkmat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtcvoaboix.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcplorzus.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtrrxjanvn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtcbhhjwtz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtpiwcfkuw.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtwcaowqss.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofhwxogr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtnmifhpre.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtgfhdekaf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtnzvqpnhm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtvnyhhzyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtulgosjrr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtkjiqxlwy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtwzkognpf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtfkxhandz.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtotrapgwu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtxfgvgltw.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtluwykpwv.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxexkqxp.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gttevktnbp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gthniknrjz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtccxznwdb.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtakdpdkxz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtldcavyqq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyihrbzv.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gttnaqbcqk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnxdervmb.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtavxszmao.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtrfvzwlyl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gttdouxufx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gteofwnldx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtondqtvqu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtcvbgcbhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtevtjvxxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtvtjcxlvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtjkiahwxf.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gthrynojrf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtftjccdhc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzooxueng.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtwmrrbqor.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssepaduu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtmtvxvtuq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtwchlpeuh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gthiwrtxgt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtujzsydai.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtyxmytsge.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtrycdaxjz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtcnwedznb.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtnbgqsish.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtxqwylvci.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtrpeaurik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtqbvpcvfx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtfpwqwugz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtatuuafln.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdodefisc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtmriwbnaf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtitjfswde.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtedtogiwg.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gthnqmqryn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gthjmmkdqz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtefrigiep.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtolmwulsj.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtgttnwfyr.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtomteovij.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtewtmdoyc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtoqdvdbag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtiqjgzqli.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzrwtepsh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtqdbsvrwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtpnqcwmgq.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtmfxcakjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtfohgigif.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtkeaymylb.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtcnrzfggl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgnbzbfz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtzbmehehv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtdiqhnnkw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvyxtuhv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gttagxatlt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gtrvdnpfms.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gttzwbdavc.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtujfstzdu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtgfwuyzod.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtqzsqyghw.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtonwzwrev.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtbhjhxhmx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtlowqfocg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtrcvkjoiq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtedizjneq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtyqzmurfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtweotvpim.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtxftphxvc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtciqtxsay.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtdqsfitqf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtktrhaeqf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtqxqzngxw.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtuqxcwqfe.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtjfacjxll.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtoingpkfg.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtlotrrqzo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtmchdnpdv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtudadfelc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtzscgsqwe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtmrxqixan.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gteoeezomq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtnaswtgyl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtbxdnzzdo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtathgphdp.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gttpllfuhr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtavqwwvou.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtgskhrxfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtludkdams.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtcephwlgt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtkkwbfxgz.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtmntgruok.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtmfonrrim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtnolscuyu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyxxzvexi.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtxtruaesi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiuamznjj.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gttfkjuroe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvpfrchm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtaufeqyte.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gthgidmefn.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtosieuqnu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtfivhgkwr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtziajvncq.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtshzntkhe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtmxbnwabx.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtgxaipdxn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtthwwqwae.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtmcwuqrvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtyodgtmrz.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcovbavnk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtepnisauk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtefenqdcf.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtzpphpkxy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtzskeocsv.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtqeygaiaw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtjxjmburu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtagixuged.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtoalhyozj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtygbqotvo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtglwmfuoy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtbyucvhca.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtjsswizwm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gttkwqiaet.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gttxqvoobr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtjhmurbro.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaklbrmes.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtitpcoils.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtpqwvkorr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtejdzasgx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtpomedsec.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtszrdfjyl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtzkarlpbf.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtchbbpsiw.html


<!-- 参考信息 -->