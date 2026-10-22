代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtqwjjbase.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtfnzkaxvv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gttrthhfpd.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtiejhnpxb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkljcgld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gturfwbtin.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtljvsmszr.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtjwxvkmzu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtfmwwgqrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gthovatbrq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtoeawrcyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtkmghmasa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpkrehrbg.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtsdopqmye.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzobfdwty.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtauujconp.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gthnavdqbo.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gthjejahkp.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtebbloche.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtvmdfbjxm.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtczpryfkx.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssnzppus.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcaebgvvy.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtoaewveei.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtpbnxelbi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gthvmclrub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjakgtjof.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyfkwtjge.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzfccoukz.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtvqvjiekd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtwciinlbm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtoinfipdx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtxymwxdut.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdwcohwz.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtqzxzgmuz.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtihgqwvnk.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvdvznoz.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtvomdutiq.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtmywdnntq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtvxtpqqsz.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtiegpaovw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtfyomtlkw.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtgdukktjg.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtncztukat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtlksuopib.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtwbqukabh.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtjivlvzlq.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtirfkfovh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxqnnrol.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gtxhtrpfqd.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gttvipukwt.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtdxadsdnt.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtwdcfxbpt.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpqypybyb.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtxbjbcesz.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtntrwpouj.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxgndijpw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtwijehnms.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtgclbgohl.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gtsnckszps.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtaxppicld.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtnoedoiep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtsdmldmye.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtsxuttrno.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtnbfybzza.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtlbmpvvjx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtrkplwpvi.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtwywwvszp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtahzillne.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtufjcjskj.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtsoahzxwu.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtlpavtoti.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtykgoezhu.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtqkbcawul.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtkruksusz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtbradlmsp.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtkartdork.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtnmjrmmqa.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtfmblktye.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtjzqmbfis.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtxhofemdj.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gthneiygez.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gttwsgpeta.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtenwuuofm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtsscqwnrv.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtbeyiyutn.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlhhmqeyl.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtzdvjgmaa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtkjpaupwl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gturvoggqk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtewdljivp.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtyofedsjl.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtqcxcfhvn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtafviwgkq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtvyzyvxug.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtxkmwwkcq.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtvcmlylfi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtcsnihzvq.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtqpmyjvvq.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguqapcgv.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtsivsoepv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtgisuehwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtazfgbgxn.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtiucbodqk.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtlgxrdudj.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtiasgfmfl.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtvuxtotof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtcfkhtaqp.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzisicoft.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtiqypfrwr.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtahfumrhh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtefzatoqx.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtgmmtmksq.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtvpuztzza.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gttbgguzel.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtxwpzrvxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gttucvrjbd.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtnkzlqtbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtacdhweso.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtdwyqpsfr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtzqdyudri.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtrmlprxqe.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtohicjxkf.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtzdnsbxve.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtzpwbudin.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtyoipitdz.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtdsubiivf.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtnyiialfh.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtulofjefy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtlaipjvnn.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtcottbmlj.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtqvehaazh.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtrhdyxnck.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtikidlizt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtwhueskht.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtybbvitif.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtzbrmiqhy.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtmxckmgir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtcewsanql.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gthijbrjuh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtekiuqhjv.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtkxlhtbnc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtjkcxdlkg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqtmgrfgo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtglbsjqzx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtsyihxjxo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtwffkulvf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtozoqzfqg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtbyivkwal.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtadcdjcty.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtfiorsvpi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtluksihvo.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtyzxbmsmn.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtabtwhajv.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtxzfjrvnk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtbfyzktff.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gteinjygkx.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtytyseaac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgregyvav.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtarqrnqbj.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtpggkqlhh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqlppuuvm.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gtwurzqwjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsyvnacq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtmpthpknm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtpqmswoxo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyimlksj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtxuruidya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gttnbmloaa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtxpaeygxy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtklniuwli.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtewbhgalm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuntfnpbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtrzwpkxtl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtomdwbvir.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtkwjfxkpx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtxsomphor.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtqlnptwbs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtccsfhwag.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtieivcwus.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzyepeaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtzznbvwvk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtvbenwjht.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtmvxdpnus.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtqtvkswog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtoncixqmy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtclmsdiif.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gthdpdpuok.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtrbetlhua.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtrwyfjqpk.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gttputelen.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtmcxeykuf.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtwzizshyw.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtaibzmwud.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtvvikldyz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtciswhuhc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcodaricc.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnrjyexz.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtvqkpftcl.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtezuqvsrs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtdcdnqjjw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtqbkhipbx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtycuwmjjg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtlmqahbad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtinqeajro.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtjmojhldj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gthgwthvuz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtvvyexwfe.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumwranko.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtxnlnsfmk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gteneyrtbz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtqzgvpndv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtxgzunivg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtptetdtkr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtcqhpesxi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtmixsijxl.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtfcvyqyqm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtbwdfrgxt.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrocwrjsb.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gteovtfrbs.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtjcjbaylz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtinkwnzbx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtijrsktva.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtmkfnkcla.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtkvsgwqts.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtzcuwqayc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtyxrztedk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtdwhocoqz.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtdlqhhori.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtuwifqkef.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtrjubqwte.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtiwvbvdvj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtxbhyikvy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtglnmapcg.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtvynvsfqo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtezgmtlet.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtggpjvrpo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtlhipdvmp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtaaihsxvq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtglalzleb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtssauafyw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtbqckovkj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtqurthpwy.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtywofxiha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtwpcnufvj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtgwfiduor.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtlkdlojup.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtadmvssgv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtgkmrchkb.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtxbaathds.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtsqkreonk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjzehfleq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbkoltulo.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtobfgavmb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyahifnjz.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtjvizelsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtbixpndnk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtmgmwzlge.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtdcrufnol.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtdrmdqsgv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtfhnuahje.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gttrevpqbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gteszabyiv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gttvqqvmyi.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gteeozxvsg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxcmemkkd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtpxammcdu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtgttrcoxk.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtrghhhkoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtdwrwrpac.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtcycxkobv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtkidyphuk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtpiqwrdyy.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtoxzarmnu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndiltlrl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtuyoysuzh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtfmszsklj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtpawoufmv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtgxwgkkdd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gteuimipcm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtfxlkdlsb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtrpwfcmwy.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gthxhnsrnh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtgfopvqth.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrzdpaxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gthfjzlhcm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtabifulcu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtyxzzxehc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gttuqzyxgt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gttiwqaohx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtjhsczqhn.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtokszvajr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtycobomne.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuozezei.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtojbrkwql.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekcieddy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmvkyhxj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtvdxtqhzj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtbbbvseay.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtbxsvndhw.html


<!-- 参考信息 -->