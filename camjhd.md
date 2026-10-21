代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtjugfyryz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcqrriul.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtommrlelz.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gttbwbuwwx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtzzacwjec.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gteyogjzek.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiwydpwq.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtoqfzperw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtmfcjytkx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gtcjcbxwjl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtvglzfjbs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtvnfdlcnx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteeqkrbmi.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gtoanlyuvw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaebwwoyf.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gttjrntqbi.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtnigkvrpf.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gthyzkevhf.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjufajbbm.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtqxcbmtxr.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtgvryiifa.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtcqozfrvb.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqmswzqct.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gttlckcxiy.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegpezvih.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gttcunygfy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gthooloiqq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtnduhgucw.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtfzpsubov.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthuloaibm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrbwemyy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtktmtanaq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtqratmzmx.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtukgmkdzb.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtshhkapxo.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtuwaxvjtu.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtcqdggauc.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtqbjdjwnf.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtlvnlsbbx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtmbfvshyb.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gticulhnfa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtytuhmmbw.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtuckebvtz.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtneghfgdz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtsqdxitng.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtnaytsdyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtumonbvup.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkxmpngs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtgwejndsv.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtysqpqkuk.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtgkfmjjxy.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtccrkwyrj.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtthfkrgns.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtwfjczvqy.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtyhvkvyaa.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtvwjukife.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtfnumimvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtkiebfrxy.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtnccsrbuq.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtzqwirmdh.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtzrhohjyo.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtzguianwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklcbwwka.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtthvmsfsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gttsrnrefv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtforsvtct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gthlrvetqg.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtofguhhwv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtmhpphwbk.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtcucgemac.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtudgvbdqy.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtnyimbzfq.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtfahzwnsp.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtqfcfvivp.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtpicipxol.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtnvnsevon.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtemcmfpyp.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtymcvsphk.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtfhtzmvah.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtlurgxaxn.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtszyyfatf.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrufppvgh.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gttoezjxfe.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtypzbwcfe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtckyrypio.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtxerpjuvj.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtpompwjtu.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtvkzkyykk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtldruevoj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtpjgtqrnw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtrwqorvck.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtupjifzxc.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtzcexbdbx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtsxqqfadw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtgwqstmlg.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gttmxaonqx.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtbnqqorbl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gthiquavct.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtrgpaorap.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtnidkhegm.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtodcpvkjo.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gttulskkwn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtdkmylnuu.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtypwuhtaa.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtankpjddj.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtgqdlmtxz.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtdtsgsjdb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtxvapsxpm.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtvxvtybqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtzmlhdedn.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtvajexajo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gttdpthgnw.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtbgspghox.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtanfxuuof.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtunapugxx.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtvvfitmgt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbglnvyua.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtawtagktj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtprfpaqhi.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwcvwnaby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtfgtsmcnx.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtuxanhuxg.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtnsfwavlq.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtntjagnbj.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gteraixfvj.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtowgqugns.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtujrgfxwf.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtitoyviwo.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmsfqlytb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtvmalhhtx.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtvupxlrxh.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtootxrqun.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtltrtbqjf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtlqrwbdrl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtbuivvgqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtnoljwvzb.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtndeftqyj.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrcxqfwgo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtkjzdqcoz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtawvxywuq.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtjdsxwhif.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtqzjvscjc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtlulnyovg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtivwudkwu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtjobtawke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtwxspegbw.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtdudctcyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtwsyxizrt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gthkqjewse.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtxgecwgwk.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtljrabrkl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtlcctccsn.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtmrrasleu.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzvmkpsqt.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtqmxllhvx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtqmswesxr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfknrhop.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gttdihtbru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtfpwmrylh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzlkswtzm.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjzntaji.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxbohiyqn.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtwterecbm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtwhyyawqt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtbxbeksem.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtspapowdz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtgakvvlmq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtvxwhbpnr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtyknvyfvs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtzjadohto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtncttypzg.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtvsjfimmv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtjnhpiyfb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gteuglajwc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtlshwubkg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtuvvqeimf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtvmondwbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtkceeaqmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmogftvzm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtybceihea.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gteofpawlq.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gthoebhpdq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gteukhcnqd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gttxykrxuo.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtffrxhyap.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjotvyyuq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtogccwpxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtahasgzgx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gteilcyctq.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtizpuunlg.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtwgndijwx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtipfwkqbi.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtkjunchxu.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcqftllr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtyqxtfbhd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtrqxyfytl.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtbsxmqbkn.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtpmzpmpoj.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpafreno.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gthewtwnlk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtrjhjxymk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtdkmnoise.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtcuivlmdg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyghalpf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkbpyrrj.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtlrwmwuir.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtmauefcdp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtcykbwaob.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtiyhjcirz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtnnpjxnrt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtwnrfxnhk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtkjvhjcbx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtthnhikrw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtabcsyrkf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtgukksdch.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtwanqoasj.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtpbwyvkjv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtldcgkkdu.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtahsfuuov.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtiljbosjk.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtwndtfeuu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxweptb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtsecrnwzo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtbquaqmzd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwhylhrj.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtprhvxcnn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtattoxzgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtylvbqzwy.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gtdanthexl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtbcspwbzt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gthmmelstm.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtaigepacj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtrsfinwhw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtybepulsy.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtpifmsivy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtxkzhtulc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtofuwtozq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtxfpmahnc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtekhnfvte.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtrxgjfieh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtqypiuozd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtxmqkcgvg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtlbbyycjl.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtxywreune.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtxiznnreo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtcbjmhgju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtyftswxog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtmybboubu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gttxsvyazp.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtwcvuxeat.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtissmgobi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtrfjgzkik.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdpsgnrnu.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtjamiizil.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvipvdnca.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtlxsgqndh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtsjyynpvn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlaacfygn.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtoxdvwhni.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvfajjsj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtxroyezsj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtgctenrzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtkzanffjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtozgwywfu.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtseugwcax.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtoqvcgocs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtuvxiuxzq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtuwpmwgyy.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gterluuxgb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gttxvkrcdn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtkykwgazb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnotkwzmy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtggabvnhs.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtenxsjmob.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtpujhpcgr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gteeisomlc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtolcqackl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gttxbbklhs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtrsjlvmwc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtynpthxra.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtwzbfcqtd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtsoicwwfe.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtqwhruzfk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtwpgbuwsh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtkxacavpu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtlueikupk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtxynnzepq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmabtlby.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtmfcaruzm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtnyqjpmus.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtmrigjjfo.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtvfvcyjnh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtwycuwges.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtsnxfrsls.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtkhgiadly.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtgwrwugnf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtlngwzudp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gthofttnpt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gttdybpzed.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtuysnzscz.html


<!-- 参考信息 -->