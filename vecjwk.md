代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2blxjmxvc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xigcrtev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gt2brbfjcne.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2loxuuobh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoinmnmd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aespnntw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gt2gbyjujnx.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwggnfte.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2avcccncn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2yhtpnonu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2pjobtxrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2edcspcpd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2brnrlrtb.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2gfomyacr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2idjbyxpt.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2yedsulof.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2dcjiebxp.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2zvgzsinl.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2fcehevnh.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fbdsqrzw.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2yljcpbtp.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilylqyog.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ubgopcaa.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2cdpewsej.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvznqtdr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2urolwnxt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2langvjkz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2cdvmygup.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2qiqoxwkg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2quehrqku.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2mvhacmtu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqbxgbsr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2kolbvmtp.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2fgylygkw.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2qqfbllxz.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2bfareqlp.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2qsrxqliy.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2itnkjdki.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2xaiczqge.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2hciqvmxm.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2dhofllwa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlfjvzle.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2mmqwecpl.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2cifcucsy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2oaxzdmth.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2qoseyjlj.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2wtvxxsjx.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2qnuaormn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2ueujxrsz.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2hatoomoy.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2trfwuzsr.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2lsnlvwgb.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2gyibixyn.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2qvdrnnvz.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2otbifzbp.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2udcjhxvi.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2cgzqycpz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2jaumacei.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2yuudqogf.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2lorhmuxk.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2ljopipff.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gt2nrvacsmz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2odpwdxzv.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2ujjesdsy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cdamlfpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzhjoekl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2tvlkqvcc.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gt2opdybvjd.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gt2tckmpfqz.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2ridjkldk.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2lhysntiu.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2fwaqjxfv.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2pvxvanjv.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2wfndgift.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2fbvxttdh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2moczojgh.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2djfmbabz.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2cxhvwzpq.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2pvsyczkv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2syxrzczv.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2nvmxuctn.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2csnjcnti.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2grtkklxu.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2lhqlergm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2njbvkegw.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsqymdwp.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2ctywmchu.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2wzuxvtsf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2bcxcoooj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gt2sgxeitob.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2ggjqliim.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gt2mznwihwa.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fkumzlyw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gt2jwcqdnnk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2ojjdwdpk.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2ionhnsfo.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2izvffbst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2trhyaowr.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2jekqthdr.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdeoipat.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2tueewjse.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2nmsahuoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2wqzvmzdq.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2bpgduudj.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2attnoust.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2gjnetffu.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gt2gswmbvlq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2lapkwbzk.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2ixqrcbbd.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2xsilbdsu.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2ylgtejgz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbdmkntn.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2ydswofkd.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2brviztmx.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2oezmhybo.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2kqclsacg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2dnlmxgrl.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qeinaqoc.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ryrvzwxg.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kovcdjkm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2qdspxclh.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2mfqtosgz.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsufsvbu.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gt2dvxxzelc.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2dxmcywwc.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2vpwyhdwu.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2gmobzazh.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2isjswcvp.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2qrezatky.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2bepmvaoo.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2jplaxbcr.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gt2xixezkzu.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gt2miglycus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gt2ntxoanzf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2pjcrtelj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2vboqqdsz.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvfwmntc.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gt2qqpayodt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2lfekgatj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2vttsftep.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gt2kufxskvk.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2khatitjr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ricpyxxp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jgobklvy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2pxqcsubo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2pmlbvrqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujnwukjx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2kopqynqt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2jqlrwzjp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2qcncewfk.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2vakctesa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2umuyrchh.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhbnvqef.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2grywcjll.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2wwvufzuq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2lzujlqhb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gt2uufyyaqc.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzynarzk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2nfdmriqg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2diqtbcud.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqbjgqxq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vprguild.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2rhemrtca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2imndqwzx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2cnuqdqri.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2hcpqztgz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2viibyebf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2akrfizdb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynhlabpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gt2qonrbznh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2fctkeond.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gt2winkwnap.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2pyheznxg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2vdfyfqsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2utviupmp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2qfngzxod.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vdoonrua.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2mpzncjrl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2shcszlyi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qddecpfr.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2ftoamggy.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2berkdxvn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2njjyqaqv.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2sbunydau.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2spofxawb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2ohsqtlgb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gt2lnhdqgnp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2hbzkxklj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2rvpdzbfm.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2acfaxuql.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzdqbgph.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2hyzoqfkg.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rjcfbkxo.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2xxphtrby.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gt2dilguhav.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2ncknpkha.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gt2bfcbuhld.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2piyhpnqa.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gt2yshiaiqs.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgkuomeo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2lnrtkaxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2vuptirxd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2qetyokrb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nnwvkdmf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2lsttspih.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzlmsovv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ksbjwrqv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2jciukyho.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2xebuvzsy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptjnqjzz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2hivkclwf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2shnredtx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zatjbnpi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2hymtmwcn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gt2pavwzncu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2rehvfjwf.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqwxypao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gt2izggcnut.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2jnicjzlx.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2gfixvhca.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2twpltujf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2zdrcchyw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2mvznqdff.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gt2zwuixnxf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2bockxojj.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2gfrdbxke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjbnbke.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdfogkcu.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gt2worspler.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2ugmbjjty.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gt2rhgqoatp.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2yhmzcyda.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2musqrhvg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2cnwtrcyy.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gt2fvadvpen.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2qmwpletz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkdobfqc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gt2pyjcpgws.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gt2ipnoatcz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2bdbckscq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2vckohlgs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raxldlqz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gt2gblugpfg.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2yemwzpsw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2ezjfjfcw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2xtnbmeqa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2killrcbt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbsyuvuz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gt2webhxnjf.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2lnnwcjlf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2yywfoomr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2dbuzfkaq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2cdbhgvtx.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2gikjvgra.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2txzntwad.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2wvmnzujl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2qctmoumv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2rpuuyeje.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2xqeypqao.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quovwkja.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gt2suhxcdxs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgxrgpiy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2pitppqop.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2tlqbtzkn.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2eonhwdxv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2yrkwrlna.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2qyyyldpv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqckazhk.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2mjaqdzyh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjbukior.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2zvdnvsez.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2vypswddi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydhmkogv.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gt2qefihlyz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2zochvhht.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2sxtjwsye.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2yjbrdezh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2jbcwtwdr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2aixnmfnd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcqfiktg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2nlltynwm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2hlycjako.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2qfuvnmra.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tstiqngv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2akffpiir.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2enrxpnit.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gt2rgznfmrd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2kuttsxtp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2csujpegu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gt2eudhcxyb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2jssnmnrd.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gt2gluzrspp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2yhqtvhju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2lzrrcunq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2fcymdtrl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2pptjfmye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gt2hwhoitgc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2lnyjpwch.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2oywdttrx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2xhhryxfs.html


<!-- 参考信息 -->