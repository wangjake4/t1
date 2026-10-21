代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtdfrejvgs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuajhubsn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqtmizadg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtwyvnweie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtdppxlsel.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyjooxyea.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtolufzzaz.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtjdibgmjz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtljcdeagc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gterwothjl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtkokrdbrj.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtplanefql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtdnfhpuow.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gteljisvbj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtfwqdblmq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtbhwcvmnn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkbhbsaym.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtftjxonzn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtuvgzsjvr.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtoljujeza.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtaayttxzk.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtqbghesxv.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfbduijmd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtiacaqdpf.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtxnkinken.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtwkyqukup.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqrtxyei.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtkhpszvrq.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtwaziqtqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gterhhydeh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtdmzixavv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzpfgckv.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtvjlzwcif.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gthudnyubj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtcotcndqr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gttnzzwucx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtqtxcfzdw.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtnmvrwpry.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtgkiqaxwt.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtstpiymct.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtonehepie.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtcwyhcgac.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtfuqadswr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtwlrefwyq.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gttpvjvtto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtvowkliyt.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtyzjovjux.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtzyqpddky.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtxdujscjr.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtyzkgmczd.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtiqwvjsxi.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtowmlqnkg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtrhqwmfoo.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtugwuftbj.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtadpyljhi.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtynozrgvp.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtvqkgmnbl.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtkxoiurrf.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtodwoshhp.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtfmoyueuc.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttkuenyaw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gttjbhlsrx.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtqdxonfss.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtgjlsqhyv.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtyyxnvavf.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtkievaxdz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtgtbahsmj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhledgpc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtnndyejhr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtkzjwltcs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtowsnukaq.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtwxptacgw.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtmwxztygz.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtbxhnaewo.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwaaojcp.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtlapxwurs.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtacqqfsvh.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtiyjjaymq.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtflciczyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtuyyftbne.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtqrbakfyh.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtbnijhqbi.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtdqmttrrx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtzwusmvee.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtbeozempw.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gteojzlprt.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtbfrlszqu.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtrpxyqcfi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtbjcquplq.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtklephsro.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdxddbio.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtrkvrujam.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtunmdqpna.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtitqbayuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtomfiyajs.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtesknkkrn.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvigtqapg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gthwvwmgqu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtqgmaqpxj.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtfqbevkby.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtjxdzmtyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtspiddnfx.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtxdmgifdm.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtnoppfxdd.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtgbgqwipv.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtwnozcgfd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtyzvotyeu.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtsiuexybm.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtconfvbxb.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtyezmcfay.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjyhgyff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyzqvrpg.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtarfoygpx.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtrfmcdrhu.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtidaoaymp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtpoodnrgb.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtisqqqjhz.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtokzcjeqn.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtddjxfmsm.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtxfhgulgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoevwsqud.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbkxqurg.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvjhqcrwy.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtzwkljztk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtesthmjpo.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtjidtdipt.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtafyzqmag.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtduttzlyx.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gtlahhdhbr.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtlvgnnnbc.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtwoashaca.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtisqcdrge.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtakucvzmc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtxtfkmult.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtxinekswo.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtfdbewahp.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtrgiokwkn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtplfdvdky.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtadoqxgue.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtzdaxsgwq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtwukjthkv.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnrorovv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpdjalww.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtprpmculm.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gtrerjoesl.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtdtaksofl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtixwpaczw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtzbqkkbns.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtyfkchdwd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gttyoixsoy.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcmzclum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtqhtljhsn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtofjuxxwe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtwnbuhvkm.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtzdxuphfg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gthuilzpdg.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtqwhzykia.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtemnertoc.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtwspemzqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtjgevgwan.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtxzchhxni.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtwklucxaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtnrfdcqjz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmhbjnhqz.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtqklwzelu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgsomjfen.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gthedvffkd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuolvroyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gttrrvngju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtnslyconm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtzxpymeqw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtustvkgzq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtkqvvojgh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gttffmarrw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gthwnujvye.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtdiuzopgt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtmfycgdva.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtfgdfmhjm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtjxcycpna.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvpbxqnuf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlujblcpx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtspahcwzb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtqgbzzcqr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaguqgwr.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtyvqdtsmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtlbzumcrp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttzrzyrok.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtlojrxrhb.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtvvzpahau.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqvnmdwwe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtdcsghqpz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtugtjmqfq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gttblujzye.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvczeqhuc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gthblnhizy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtqydirmqj.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtkpttgfgj.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtufjqrwym.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtnoxwreml.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtuzdsvirj.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtveyglfjh.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtlzsvahis.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtvrtxccjl.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtpgslfbkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtbtifeuej.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtkfcbednk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtvfobhbpu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtmgkfnyts.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtockwvhtc.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtnguhqlvw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtlgrjqfag.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtafewergb.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtgkxltwwi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtsssvkdlq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtwijuoywt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtvwbnzuqa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtsbeqrkdd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtqucmutfl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkwpajph.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtmgnyjbfk.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtxecjttpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtysdxwavw.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtzgonpzvy.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtpgdhujzp.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtusrmhzhe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtygwzzfpw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqspummj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtkcumyjdg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtpbnvaywv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtnncuswwe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtwwqmgmgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtgdnyeknt.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtusvikhph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtzbrxqonx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gttmjrhfwt.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtramjvmln.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtrrstmokp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtkzcwnfdl.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtdrsogfdu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtzzuqqyux.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtxiqpyyxr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtvxkrgsps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtfidqlrcb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvhiciqd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtxrrduhxq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtsdcjszmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtreutoyat.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gteuadwklx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtisegizvr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtfzhwgbbz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtareznbam.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtifkbdehl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtnolabvpi.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsrtjquj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtjygxxvyd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrkqffrbh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbacsounw.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtgejcblhr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbkrbtbay.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtbtuvuqzw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtmxulcyrw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtetrufbda.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtpoyfpqjg.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtgazpmzlx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtjquomngx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoxhliis.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtqywnwoqm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtrfcovuvk.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtquzcrdtj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtbvadxcgu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtxlpqrvza.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtkfqbxxjv.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtdcfxttfv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtuaomtoci.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gttjwwfwhk.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtkxuqeynx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gteeikkuri.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtavuqptmn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbduqbfuk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbmayrgf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtjgteerhf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtbusoratd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtmkotqgrf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtnosbnnas.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtiqbvzpwb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbefntneq.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtqjzthumq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtoftprmlr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtcfndpmto.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtnvzzofge.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtpweeripc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtfnbpgbqu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtvgincwpv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtmqkdbjsp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtajojdtwz.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gtjgxbslyk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdnzramt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtsawzspmh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtxibsmhjd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtmkhpwdgo.html


<!-- 参考信息 -->