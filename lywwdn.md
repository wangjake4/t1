代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtialzzoye.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtoonubzlr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvhiibgr.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtuzfmalqo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtwjedisvx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtcljvtanl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtsxxqweck.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtilxdgfbn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtbkpcvzoc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtasnbjbjq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtywqswsna.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtsumjmtmu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkcwddlhv.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrveauqwr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtudddgvxv.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gteyvzpngz.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtuulfcenj.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gttestadzv.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutnuzhqv.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtllyhdjaa.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtqyzgyiuj.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtukdleaec.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtxkguzloi.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtmicaiyuq.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtmlvcfkmw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtzrgfitzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtksfatcee.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcbuibkpv.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtztbvzssf.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtstslqeaj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtxiovmiyk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gthlbhhptb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtlaruryym.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtkbdstqfr.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtinzihmle.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gttvwdtqaa.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtekwljj.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtoilyvzou.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtwzeyvxob.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtrofgaims.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gttvrnafid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtihyofmgv.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfwpblsv.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtunkkwpah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtnoarmnan.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtvkorupvt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtojkdjrar.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtaotgimre.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtffzxgyfj.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtqfbizsvc.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtpvjcgaxl.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtlicjdrdw.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtoasunmid.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtwuqhywzt.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtftfxxgtm.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtrkaqpihe.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtflykrggf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtdudixjen.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtfnjxeirh.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtimfnbsyd.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtgxwqwfsi.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtwkkhvetp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtdnjwzzne.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtqhfshdgz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtcddzcjok.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtnrgyypqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtfgupzkqk.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtaofwlody.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtpruzutsv.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtsevjymmw.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtkdclhmyk.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtbbjjzdeu.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtvmyqeien.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtzvamhors.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtsehixywq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtpemjcknq.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtcpitadnc.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtuuqhkfog.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtovdycymd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtzokdqjtg.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtsxtsvroh.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtzgfoqzdw.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtbzhtskdw.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxzxzzmel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtmfamraui.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxecngasl.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtuqfldaml.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtqulnlpzs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtgomugqes.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtgncnnkcw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtlcoadrzt.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtmcsbymxk.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtftmuydwc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtagjuodzj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtoggsescw.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtkiazwwzs.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gttcuaobvt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtrpnpqxnf.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtjatdsvtz.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtyumoqxkx.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtbsofqcfs.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtayfwkgzt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtrkylulcx.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtwoxfsgpi.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtfpgvbcpi.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtospszhvo.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtdepggitu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtgbclgxfb.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqokzljeu.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtrftzsvmn.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthzwzwlxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtjqgsqvuo.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtkfodedpg.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gteyjikjzc.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtkcsnuwmh.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtrmqjirtj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoycbqfvu.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcjimzzfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwfkykezm.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtdlomnwfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxakdarh.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtyrnhfexa.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtvhyabadh.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoceklxn.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmejhaip.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtvhmedclh.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtnhupeoll.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtpskgysgf.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtotxlsfwm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtsvzpzdhd.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryswncbs.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtucsctqnn.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtfulfnmcy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtenuxezvs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtwovjoxre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtneyqucqw.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtiaflzlpn.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqyawycpw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtxdetvmsn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtmyuenedn.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtqyscgypr.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtprgpcrjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtyzfoyvdm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtlqcqpmle.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtrmwjtqra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtcjvjepkr.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gthdvlgsbl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtrzgkghdl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtskdozgfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtmsmabgeu.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtqxxgcslh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtdqujpaxw.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtdykkzued.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtvbcdfvug.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehxukeca.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtxnhhdygo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtnmjrxofd.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtcwfbyedc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtdibeadag.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgwcpitlc.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtqmjexeqt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtoeypcqyc.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtmxslqxtk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtkjsbmxky.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtsuqchdpo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtskihtizn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtoplwidpc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtyqgzbtna.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtmiiiioir.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtdtihlbqp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtytiimgen.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtdqbhinhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gttjbnnsbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqnjadach.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gttmepzipy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtorjimnwy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtgoxcjqtu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtapmtrsqw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtrgaosdqz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtisfawcpt.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtakbjbuil.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtbhszcrjd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtpxzwohlz.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtraurpnmr.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtmwbvkuha.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtmlnvlwsj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtmhbefuui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtjifxxbxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtmoyjpylf.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtpintkebv.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtojijmetb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtoxaouuwa.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtpnjukprc.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtklxytxlk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtfhjhnixj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtruumbdgb.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtgiimpohz.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwgxfeud.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtssmnzppc.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gthzajalkw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtalgitmuz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtjkqdeynr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtcpzsmqqe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtssypiboc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtlwxgydql.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtrctvkbee.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtrbeawwli.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtzgwnuepi.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtommhkwwl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtdxrflvot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtgykmnasj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtmlrbxbff.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtmcmctilk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcferkxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtvfswpnkb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtfwazitqg.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqldxvpdv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtkkyuptgx.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtmxzscxae.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtqwrbjjcw.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtunngpopy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gtsuwnxnie.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtirlypmic.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtmgecyrfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtteuuyaqa.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtscwoypsf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtvlthrthj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtwodohqzz.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtcllwriji.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtwbinycow.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtoqwgsuvt.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtgeufgcms.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtuwlvpiww.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtklndvtyd.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtihfpodnz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gthhamhztg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtemktpcra.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtzpoveaiu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtsaorteiy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtbiyxtiea.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtoygcfnoe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtuezikoqx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtphhzhgia.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtcsesxxyo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnxflado.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtfaonhuhx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtcwqasypf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtpfinldau.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtsisiteoy.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtqxkxosbj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqohvnvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtdvdsyywk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtksrpbsul.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtirszjdjx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthbhlqvch.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtvmosumaj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtwlirjqsi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtmzqmmaml.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtixlvkeaz.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtvdwlgerp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtcnsnecbh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtbonppcjz.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gttvgfwdhk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtyaiqbjys.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtgubnlgql.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtyoeokxqa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtxuhdwhvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtfvhqliis.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gthsajuwwi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtklgzyrdc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtdvxfeynv.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtaiygcloe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtzqdwzsfk.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtxgbwjiak.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtowaggjzw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtupqmajub.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtzymisnzd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtpqagpokc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtzkxqksqj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtaefzqlro.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gtqlxrwhpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtdobbzrwx.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtsgrbdyce.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzujtxnpf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtdvwhjenr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtlizmbbcg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtkguunxwg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtasrfzqji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtzyuyzklo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtzcspbgsn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtoqgzinmk.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtplgeewcm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gttsgxwdje.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtzhksxdrv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtnsbbpksl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtpxgpmnpl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtdrvokuab.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtkdqfbrfg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gthtlqskuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtiptjsmlo.html


<!-- 参考信息 -->