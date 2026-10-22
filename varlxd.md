代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2dhnrgpbp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2xozunzgu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2kyhkcnbu.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2nyvjptoq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2psrfwfil.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2cwsaofrh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2xqnfnohx.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gt2zpvtnhky.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2spfxpisa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2xuaasjxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2mghzzyho.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2cpeeqpoa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2koikwnpu.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2dolduvsn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lnigwtog.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2gbjdldvi.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2wrpwszwm.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upnwqqoa.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2enpupcmi.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2zaphfvgl.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2orzqzexk.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2hzxzrfvc.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2bgoikgzm.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2vydtmkkr.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gt2aqtsweeo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2jdbofvva.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ctttmtvz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2vlrksvtb.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gt2gxsepgco.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2mhkdnhlk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gt2xmfjpjjr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2sfsglqqp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2otmqvllz.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2oqpmcaan.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gt2amqpliui.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2xiivgfaa.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2oafkusyw.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2ywkrdjwf.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2vhaoadwv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gt2byqaxtpk.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2thkzmpdm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2iddlvdni.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2omdfopwj.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2djutyaap.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2scucrrua.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2irlrviaa.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2nfbmnzea.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2jdmnguoa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2uxogcncj.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2zillswsz.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2clyxhnuj.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gt2ozzepdjq.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2gazcyost.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2mmhtizhx.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2bwsuwieo.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vbfqrmco.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2gaohfomp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnxgvlio.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2gzdwocaj.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gt2bvapfewc.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2vwrktzsd.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2vpvxzsbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2cfgfvxwk.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2btdydgnk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2qfdloizv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2pszgpuot.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2lurnaxal.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2pvhqkiqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2yrbnjaam.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2mkcsdrao.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwymxbje.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2oruvwxok.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2xcvfilgv.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2bqtymzvm.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2xemjkbpm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2syfdyrgv.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2scsiqrqp.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2ojfvwcxg.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2qvlsdgug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2tauulxzi.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2kyvfbcro.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2oxauusvp.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuszqvyt.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2czqpapup.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2xstfcfcx.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2lfguasde.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2njozxmag.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2gcyeoiou.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2uiiqgwma.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gabaucrh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gt2dlshmxvm.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gt2pzrcpqeu.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2vmwybhjv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gt2vkvjmrig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gt2wnmvpwpl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2qhoirbpe.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2rfvgyptl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2qwktycfd.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2uokancqn.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gt2wzmesajx.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2svhhaqcm.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gt2rykrbdxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2gaixhall.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2axasfcwp.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2aozqfbra.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmzexbzy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2pjlktqly.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2ukngbkhk.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2nrxwqazp.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fuwibvqi.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2dqzrsivj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2qjcpeuhr.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2jqlxypwy.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkkpnmhk.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2gvqrvdot.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2sdawfjsu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2buysnpll.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2bznbbqcs.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2asnspwwk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xlgiptep.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2qaokqdms.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2lbywlfji.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2cizuunud.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2njlbusct.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrncckrj.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2cyivqyky.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ualvhlkp.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2hfpgwdod.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2mupvrheu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewmiunba.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gt2xjyanpau.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gt2zazhaesa.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gt2leexigry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2hlirunmu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gt2vwfuxueh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2oekhxtqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2hikmimsf.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2sryxvbcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2ipjloadm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2vgmeamhi.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2mwflndjd.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqhjdsfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2awwvjavo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2bypywgfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2zmjrajlj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2gmedobau.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2ksbnlwde.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpsvfucz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2xwxlhcdd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2vqzxieod.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gt2aadyqwua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2dhxjbooe.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2ldnjoukd.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2hftyeeoa.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ytrhljct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2qpxrvyfr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2vanollab.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2vfyzghrg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2ygowczdi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zcjxmvxd.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gt2rvxrzcls.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fijdqmbq.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvlpndxv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2wbityhmt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2oplgjocb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2kwkoooul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvczztxw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zwhekjum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2jdqytgnv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gt2rpyavfbf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2adkpwggu.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2fzbfwags.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gt2jtcppfub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2ufostggy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2tztyefgd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2wwtiaqll.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzqubxug.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyabxmyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2bilcgecf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2wxpftmoo.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2jlskvdtz.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gt2flnorcon.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2gtfqsdog.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2xmksjzpy.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2bigzpixa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2skgegewy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2zdefhgqv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gt2dsilgxne.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2bhathfug.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gt2tkuishkb.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2xrbjfddn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2mlqvuuip.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2puijjjpg.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2zntydlml.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2qezyyhib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2saprgyor.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gt2bvcjkbdm.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2imbfprtz.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gt2etneujct.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2zempfopm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2jitefclx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2iwgdpwye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2zhnwqnxi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gt2cauosvir.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2djdrgmoo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxhormva.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2wovpezdx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2nxzqrtue.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2aqrlivty.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2vbyjwrgw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2udaofrpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2hnrhvrib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2ihyxwobc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2yqqvpjve.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2osdfuzwn.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwdjmiya.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygurxdlh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2mgjuwvmp.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2fsksxtvc.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2zbydabma.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2aourryuq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upaqwmjf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gt2rckdumik.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gt2mzeykpdo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2xhvvcrcd.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptmynxcg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gt2ywazzcnz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2vjapuvoj.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gt2ppryqbgv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2gyykqict.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2lcespxfz.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gt2fdedysdh.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2pamtijuk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gt2dbsmaxfz.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgeycuih.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikxnpige.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2gvsljepm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2uomypslw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjifylmr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2jvmpzuuo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2berqndtn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2aacsecqd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2uyyadxdx.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2qhmhrbiy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2wrcrcjdq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2xtvqclfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2pvvkqdiu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2vpeawjwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gt2gduttnme.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gt2nlxbweii.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2famvbmqx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2phaaohop.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2cawcnxna.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2efhnlsgh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2iedtrmxv.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gt2bqhegwsb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2qnrplfid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezdgysfw.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2twfoibqy.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2gdltxwmj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gt2lqmsixyw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpglssuh.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2tqubmrfi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2zcehjwjf.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2xzgelkow.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2dgrmzxzk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2npzykjid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gt2uavcafqi.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2bdauthbk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2nogboobx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ijliqlqf.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2arreeouz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2aitsoavv.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2bpsbobgr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2yskicciq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2gwczfank.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2hrwskgve.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2efzsclae.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2eslylmqo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2yhxgqace.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2khtxjtzx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2cntjeqjt.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2yhmzkmnq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2kpctvbex.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2akczluzq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2addgfljy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2tifmffcv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2ioqztemu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gt2fvqtresr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2xvejsbws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxlflxrj.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2rjdgkcea.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2mrspzclp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2bbbyfclr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwylakns.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2xheoglgu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2zofyjons.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zllekxqi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2ibdhyoqu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2rhmuifls.html


<!-- 参考信息 -->