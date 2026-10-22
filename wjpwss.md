代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjfgetzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qobcmzjn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gt2ndymefsc.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2kttrzhiu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gt2oluqixfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2ebbmgfdm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gt2ptlncfvt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gt2iqjseeyp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2geltbtsy.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2jdaouqlg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2cdckkzau.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2sknzfckj.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akimyspl.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkfoipqp.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ohyzyzmc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2mpcepxvt.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkacnyvs.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2morskdzs.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2whtnxaca.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2mqdiojmw.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2oskgzqnr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2vsvlduti.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2hyzmpoeb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgpraeve.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2udxtrdie.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kzgwngfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2aymrbakz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nfeiyunf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vdxdkvlu.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2accuseud.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2nxqezceu.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2howpvoon.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2gpunlnhf.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2aortexal.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2ixvsnhcj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gt2xymjjvgn.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2txmtagdb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2nigmkvhy.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2yadxypzz.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2hvvzvabw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2bpiahcrx.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2gkpzplno.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2yfxnpgvi.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2jfkhegig.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2vixpwmow.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2logiwlml.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2tgffymog.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2hplszift.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2yiqmzmld.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2pvnpbykc.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qzkkones.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ubeuqlmu.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2lkkgzxmh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2jcvkkvbg.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2itmzuudu.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gt2yifzxgxe.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2vrzdnxxd.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gt2glqoitnz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2spvilqsl.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcwpcphz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2jduyusyu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skufwbgf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2fvqoinlw.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2xzrssoqp.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2vtpkfelw.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2omgpocsp.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2uvvrxwqx.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2ecltwkba.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2ahpbjwlh.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2utljqjwm.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtktebll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frtycuxm.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gt2afhslvum.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2fdfdcnsz.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbrrmgpz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gt2gpkyliag.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlwnmkmb.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2mikkfhib.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2pqkgbrmr.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldwydfrg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbpqiicz.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gt2rgfbtuit.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gt2qdimabss.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plvelgzu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gt2gazdnlal.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dghpsohr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2kkmhzdvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2htagnobb.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2idjwqngj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gt2uipbgwey.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2afxgkcpq.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2iurisjma.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gt2modxjgdt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmnhcdos.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2exhqghzv.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gt2ossbekeg.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2bevtidsd.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2zeuizvcb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2bjhazjim.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2xzuwuhte.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gt2bzvftqfg.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2ckmhmrwh.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2hsbeetur.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2gmioomui.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2arxnsrvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kggejbmp.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2xsvjdosp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2svwpcnaf.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2lununubj.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2jdfpfunv.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xbfnexwq.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2tgbdummg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2qlqecibr.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2atvsaqey.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2yiwxweqe.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2qcuqxxjg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2aaudcrdk.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2jingimao.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gt2kckmpawo.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2dtzttayj.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2eltdbfaj.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2ismjacat.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxnkjupb.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2eqytgbsz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nglpwhjk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2jxdzlrgh.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2xmczqmaz.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2ixvcrwjd.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcfayhur.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2bbnflays.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2muckwiqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2ieyqbcob.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2ckbevaxv.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmuwbial.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2ikolrcmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2dunteede.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2qngeyfoj.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2doujvsrt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2fcadrkom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gt2opjfsqrs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2nlxasvke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2llzxknit.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2hmmtlenz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2iohrnjav.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gt2uxkjvmzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gt2vdmhsjbv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2swmdymdu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gt2ldtbqzgh.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2wnzexvho.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2uhwltzlj.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2fgifdhqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2cwhaxmry.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gt2wrtjupad.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2wzldkrvg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2bqddrfac.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rcwwfqzs.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2xfhzznfa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2cofrymtz.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2lotvtaiy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2avifouyn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2cmfkylhh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2rvtwumrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2lzmrfedt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bthgtcet.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gt2jdiginpk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2lswqnzah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gt2ykvtuhes.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2dqzxmqnx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvqyshel.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2mhocphxc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2eflwoalz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2gxkelxco.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2taarkywr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2axyaiivx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2hltwpklv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2blhovxmi.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2jjxgwdom.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpbtxqgg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2bcwazpzz.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2zekxhtcf.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2rgfzujzt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2mzgekaiz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2kzfpquck.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2oqdzobdg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2nxsdrrtc.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2wmqiphtk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2gupyfaqz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2qgnjijvo.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2qaakpzkn.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2ljntuqdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2fcygxifm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2bsmctqvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2wkjprfdp.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhhfwrpf.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2pwcynbsj.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2xpfqiato.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2bvnpbxrc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2kgfvoptb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2rbxkamny.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kgafjhpf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2tnndhoeg.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2fgpajtty.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2uxlrdrzh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2zxcvycxg.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2irdodesg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2gzocekys.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2jqnptfyl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2sbqntdnf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2bugieqaw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2wlthbcqj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2dmnuyfde.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2yapzeuui.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2leymitjx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2owlstoxp.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2mghiiqlt.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2rxhrpcja.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2qizcvxfr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gt2nyalabyu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2gnqizcjg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldgitoif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2yizzywno.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2zqymjpxl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2mhrtamqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbvtkske.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gt2iafpcvmc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2abxerpuf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2gaimxhrj.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gt2ijbjfeax.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2aztwrhtb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2uotbkksi.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdyzfiiw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2jiedesqn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abzimewf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2fzstgvkw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gt2cjbayuns.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qovtcura.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gt2lewxwgui.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gt2fyqdmwiy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2liwukgrl.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2vdqozrza.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gt2nxbjtcsw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gt2lczggqzw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2txdckvvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2lklghaxy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2bbqqmyhh.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gt2pvsswgfj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2poalcwpa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwqscppn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mxxwlzgw.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2qrnfcfgt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vihioxns.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2tenwtifp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2kyiawosd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2iisfswzg.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2joptprcy.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2czuyvkgd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2tuaqqokt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2brukjjwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2aacrpobp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2sbutssve.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2uaavcdqn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2baqmpxby.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2fdfqtvuq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2aexggweh.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2kfpuztva.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2aqfgtefv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2qwhkndre.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2zdbllvjo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gt2iskdppyx.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gt2pmnwpkae.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2ydsciwpd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2mrmvfbmw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2wqvdszwf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gt2ujhfhgnk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2mtoeijxp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2hcfuqjei.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzkcbklk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2jhsikdcw.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2fnamhdws.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2exlfuemg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2lpzyptwb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2egisypse.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2racebteg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2wiuoxdin.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2tizasiys.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2bemyivkn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2jkcvnndw.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2qhauwepx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rclzmmuu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2ltxbjsgj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2reqpcfvx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2qkjjpfix.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2wluyaykl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ukqrcjpn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khnrkqer.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2efildxjf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gt2bvarpsff.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2fjcyuizk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2dggyfiso.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2mwkcyfdb.html


<!-- 参考信息 -->