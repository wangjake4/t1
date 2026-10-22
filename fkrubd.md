代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftlsdlb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2ygbhvhwq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2vjxslugm.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2hhwuxtwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gt2cyrglbvy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2iphmsmml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2nztloyrn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2jttrsjew.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jpzuqwou.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtkemmgw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rwxnnpbx.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2gjlbgaad.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2nixifbdw.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jumpetro.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2tgqrefib.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2xttjtcfq.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2aydroeaa.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gt2jwajfxib.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2bncrtjml.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2tspxqonx.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2gvztvbsh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2uukrzslr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2wggobpen.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2ydqaonzb.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gt2xtkyesmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ttdorfys.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbvauiwr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgetmxoq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2ppcqcfcz.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2yjfnfoef.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwxhvq.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2rvqmnoqo.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2xwzlacnh.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2xdgmkjsv.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2hmuxoqpe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2dwrntphq.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2nrctjfgn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2lclfiemu.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxzzoxyn.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2otjzdvzz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pcssvzgi.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2osgatnrz.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2zhrywlrv.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2goitrxvr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2yymowhbf.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2jdkqgxvu.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2kgtoihbs.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2isubdvoy.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gt2solqjbtj.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2tanusuny.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2nfvhavxc.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2vbedjzqy.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2skjkxbzi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcxugmic.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2zyxzvfgr.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2lzesefqp.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2ifrvvffx.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2heakmhhc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2opdocjht.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2pvyhwrla.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqvgrhux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2xizfhebx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2uxyjvmkk.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2tgtpvinb.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gt2pqknbsqm.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2lfprsufi.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2ubfxcrdj.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2kmuexkyu.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksdxctbm.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2bekgdaiq.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2yjncheqn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2akokgjkj.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2urhknbha.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2pnggomot.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2qcegirai.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2alvfncva.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2kdutsear.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2olnjimwp.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2kgtaxira.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2itjyksyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2vonntmxl.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2ftccrhoh.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2lqgtcuip.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2irwbzjem.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2wwfiwhdg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gt2fybtigde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2rwyaoozq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2kghckwso.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gt2ulhixhvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gt2ustrjuyj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2htmjmqie.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2rvlijvla.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2yoohmhlq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2xtkdyzqw.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2kgqwxotr.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2rdexeeab.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqyalekm.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjhbvfqz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2obpuyqcu.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fosochpe.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2yfwvglnk.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2eggfzvot.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2qnjygyvz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2wxmdidhj.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vxgkaswl.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2uhduwsdi.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2birsdaeb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2sclgllft.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2dntyicsv.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmwvgkeq.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gt2qnwemfjx.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2esyguguz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2blpherfn.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2lefcklou.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2czxizenv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2tlhyscql.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2myeshmjj.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gt2yxjcvsfh.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykfkgdhm.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2cpftfkle.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gt2byoodkxo.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2fkdiqteu.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2egfwgqgu.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbvmibnx.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2miyyayze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2aujxuxeu.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2jrxnvqxk.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2zjgikcmw.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2nxwoiruh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhmgzhw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gt2hcijcnbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxhisgf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gt2ggpwggtb.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnopspvq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2qtcuqtcr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmfvzofz.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gt2txxywsbw.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2fwckaxyw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2pgkxrsye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2xlrulyjp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gt2mbpxtzno.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2kithiqbe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2mipetgkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gt2qxcjfwxk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2zlcrvejv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2kszigine.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2tjsalugh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2bwbxbibn.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2mvxxxwno.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2xorahmlf.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2xicjbpcr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2uzrwkscb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yffgbbii.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2tkpcvgzf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2egkltnti.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tlcuasyu.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gt2zuwwvagp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wvyhguvn.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2opeueezt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2ceuvcfcs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skitpism.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2nmptchly.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2hhtnuwhf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csufikze.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2cutcnofh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2bvsazxdz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2jfamufiu.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2rdouzqbt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmwjxdga.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2gepkxqxp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ufzcwhtt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2vorispbo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2neqgszvz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2cenzcmyv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wigemgsq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2zlxxcpoq.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2qbpsglse.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2tdasjhrm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2ayaofzzu.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjuewrxw.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2wumluvgd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2dwuedywx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2shpwdqts.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2dbddyoac.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuzsaxuy.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2kfebtiyx.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2hwxttvhq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2yjbwteri.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2ptkjvhcz.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2wqnlvmze.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2kqchpkwz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2lacdhtsb.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2eaihnsal.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2mnckyrup.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2quqfcaps.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2ykowwwsa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ltontabu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2gganzykf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2crbbocxn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jawruozl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2xkqxmwze.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2dylkvzox.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2njfxhmbw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2giwbcdio.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2aimwbdlk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2ywuicpkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2lynobmfv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2oyvogmgq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2hmutywwj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2jxcjctdp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2cwqhqoij.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2mqxahhxb.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2tocpjtzb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzvggefv.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2ctbprlfl.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgvhggmb.html

TS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2aecbhjgx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2gjgbekyw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljxzhtae.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2jhyzpzfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2ggliqvsk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gt2txpeydgl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gt2hwqsbgqb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2qwlfkhjd.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2koulxwkn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2aeexdoou.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2hzguffoh.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gt2ntpvygvd.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2pjqlfzkr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsetmkoe.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2kramnjlt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gt2rwwxystq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2szgpmovp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2clhlqlqu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gt2tekedjrv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2ybucuwsi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2lzenkuwd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2asdixuui.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2azxeoxgc.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gt2hbmidinc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2rewzbwrb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoilidxs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2mffhjmqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2xqzppngg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2zyujhcht.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gt2twncqggj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2rnswrfnl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2gjgglrgh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ynwbrnhr.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2pnwrokjo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2anxiqkfv.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjwrkxmk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2uupcwuab.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2gevsytyp.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2rksnbtav.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2yjnlpdrw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2oycftrpt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2itiqyutv.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2qlfnrltj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gt2avzcxpqv.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2jbwwzqzi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2wsehmcnx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gt2korfirey.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2bpykczqx.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmfitcpz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gt2vtcjpcvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2wqkwrxkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2xrvwmqrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2oscsfjnz.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjgiuuvm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eagthmtk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2mgdhjlgh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oecgakfb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2juubvlil.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2kcnyzfdx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2dllvordk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcynbcfz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2aleicfts.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2tchjgbks.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2altblbkz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2rgrokrdn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqhlopqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykzmrqvt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2brhtvkjj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2urrsxgrw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2lpstjdds.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2ggbpzjgg.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlxddnpj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2ujbroxru.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2stftoyoz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jepqyyou.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2edxeuiud.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gt2lwrobpgr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2dnzasoyq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2byptdjgk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gt2zvcirygy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2lpvzqhyg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2hfyqsvmn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2qawwzyzf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2hfgyrlbt.html


<!-- 参考信息 -->