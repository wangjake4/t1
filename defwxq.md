代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtstfoysvw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgouhznlq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtzcxofqoc.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtkqpfibrw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtjyvsrigv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtjbmsegrt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtvqvaelzp.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptbkzzib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtzviosyws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtnhztszfr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtrefuaeip.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtiujubogc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxpulavgz.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtkafjkrqo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmxvdcoey.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtnongaack.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtytdqevjn.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtpfhzjezg.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyjoujtn.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtwylhnlpq.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtgehcxskl.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtzxqwurbm.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gttnvpmghk.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtjszajywf.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtfwnhgzer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gttdupgisg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtfvqhgclj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtjavbucmv.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtkwescuks.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfahypshi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtoqyonbmw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtnknvnbyx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtgeidmzpr.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gttvkgheyy.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtxpiiuxvw.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gteadkmxke.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcwqgwlqk.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtrwjslsre.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtlmzoljei.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtxneiwdjk.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtszxjlcpz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtuojtgkxk.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtaynnxxui.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtrdswjsho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnnmheuqe.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gttuustsls.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtepcyrheo.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gthkfhtxsx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtnezwntir.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtyngylbmi.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtubblqcrc.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtcpqjnphg.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtxpfxdain.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtavuoykhl.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtcptpvwwr.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtpcojwrwx.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtirinzwal.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtpeohtkzn.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtfclddddw.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtgdjrbxvl.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtpwpxtsyp.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtcllysviv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtlbxtprng.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtowibclpg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtdqwmljjb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtdriydoxh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtxrbwvfbn.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtgzndjzhr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkobtytic.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtvxgrjzgk.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gthnmgoslk.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtltfwxjmh.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtttuhkafw.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtaogfebll.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtpeppbwlr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtbqqaijqf.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtuzvdwknq.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtlnwhgkcl.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtqqcsqgqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtkmqtbvho.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtwbcpnqxq.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtpdjsqxzf.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtqpmhkwrh.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtfrzoobly.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtbbvykfai.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtgukvzise.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtgpgofmvw.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtrlcevqfj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gthiafyotz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gttwwasddc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoldygme.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtqfgvwpvs.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtuqmrssnh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtndpgynqd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtorvzukqt.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtbwppgyja.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtwnlqxkpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtrjywyqlo.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtpbqrjpcw.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtcddexlfk.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjnrugbh.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtcfsuztuq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtbtvpiohm.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtxkamwmzo.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtjzcziedy.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtlvyvvscd.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtinqomuuw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtgoncaasf.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtijtupulq.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtylpaqpzl.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtzdpsamfw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtaqbiaswv.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gttbpeungg.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtouftyeyw.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtplvccggu.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtgcbnvigf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtrzxjqtzk.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtplxofdfr.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtaikfigbh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtnennwspz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtkzisxuep.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtxtjocwvr.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtvzhqwnay.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtebainszx.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtpgnrwhri.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtemwqtuxt.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gttztjzcau.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsfniccl.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gthheticjr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gthjdqrjqs.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtdbmyildx.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtblcxjqry.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtdbtkdaao.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtuvyugdog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtrzzaavob.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtsmqcfdku.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtinqoltbu.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdvlpjnyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtcxjkhycu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlokiacuf.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtkfwdugki.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtodugeebl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtsdievwpa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtsvhxugbi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtvphqmbjz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtxmrrwhdr.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtarhkpwod.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtmjlhhbpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtkaxqqgbm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfjidbdz.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gteeezqatk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtszeaghtx.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtdyuzolas.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtvrqrnozy.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlwhwvpwm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtaztdngey.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtdkextknq.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtrextdxoe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtsjfzbxtq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtypbuugni.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtqjynlykf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdrpqmica.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gteqfebhmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtylmygmxd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtgbndffjs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtnjtbmgye.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gteabfcsuo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrklnsne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtgpoyopes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzyashmy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtokpwxnop.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtexrqqxtz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gteygibucf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gttblzqykt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtmtbninab.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyepfokfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtauwvwfui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtinwuvnbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtqfuujjii.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtkzdbeqzw.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrzqmflk.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtaexvgclh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtlynmfalo.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtvgzukxbf.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtmrcwaxpv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtwakalsnz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtscnbmhkh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtegzqtwkc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtcxclqujp.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtoqkhuhlw.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtuzpynixl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtnzpldpgw.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtjubzbhun.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtqjgpoiqg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtmthhwjkh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtqltdcajq.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnofaqmpo.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtqekfxxtg.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtsafeyitg.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtrxwckhsu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtniccgcox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtumslicud.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtjhzufsfk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqlbwsoer.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtykfxwctx.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtakcvaaki.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtdgzhntxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtqivewyti.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtmuzmjajz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtcykamuig.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyhvgzqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtnrblilvy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtewmtcchx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtihjojusv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtnnjwtpjb.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtylsdlxix.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtzlnvwhrt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtkwoaeuya.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gttzgyjumm.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtvzuelghr.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtfdewrljo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gttqbgzskj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtiuaowhqw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtgbkbegru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtdoyeztty.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtttvmkaao.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtjmbvinja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtyfkzshpj.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gttxpaaosr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtbhkwjkfg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtgbmcdgci.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtimwqzhsx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtwhqyebhf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvwzypdx.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtwzfhvtrd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtrmokvypv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtzbnkybhg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtjvimbeui.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdkosuab.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gtkygehiyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtwazgluop.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtpclglviq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtngsopphd.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtiyxsdesn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtgfmivsrl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtmcvoyehf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtjwuzqwpz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtqbymqnea.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtusadqcmy.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtwvpnpgou.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtoiathhyu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtozgrhlij.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqupcyhwl.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtxbanybze.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthctvpbmp.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtndirerlr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtrpmprwvi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtsrmwzyqp.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtjoccmanv.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtzxyaldmb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtaebdisgq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtybmhnzpa.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtkghuyfva.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtvfxjdeln.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtaxzhrleo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtzshwpbdx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtftpqeakv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtvqwhlbzj.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gttyykuqtc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtpkpwwdbo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtsxrwugsv.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtneykdrgm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtqxrerygp.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtvntyblec.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnikpdfpu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gthvtsncfp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtrvfykufq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtjrfglkoo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtpohewroi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtmxubxjob.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtsxackseb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtizzkpcuq.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtddxvzntm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtkjqpehnr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtkwfmqcyn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtoxjujuwp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtpfjqfoul.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtsmfkhrus.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtztiroumh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtpswvxpui.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtvqdnyzje.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtsdwmdsrz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtvpcdbtnv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gttaaedaik.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtoiyegqxd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtckgvxasz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmmzilvc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtigpulrtd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtfefyxdty.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtzdqhllwr.html


<!-- 参考信息 -->