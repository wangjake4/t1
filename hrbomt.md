代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gt2mvggeneu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wwpgroey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gt2ggkykuep.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2jryocrby.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcpqzkok.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2ucalismm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2krcnleag.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gt2txcemima.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsqnxhbf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2eacpuvpn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2vvzfsseu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2rcaqfxoo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fxeitnco.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2takfamwg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2rehdtunz.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gt2fsjlwuev.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2adlofaem.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2nnhwtkln.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bicxlafy.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2yfpvrmdr.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gt2ergfuxkz.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2mylhkury.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfkczgns.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2cwjulbxe.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2qwkplypv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gt2wxfqypts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2evdjeclp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kkwsqezx.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gt2hdhucgvl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydigagsi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gt2ngtfptql.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2pituyyuc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2spjholek.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gt2estehsif.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2qxqrqotr.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxkmxvgm.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2yqhkgiwr.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2wnwyywgv.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2spdkllfx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gt2bncaksng.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2ardjojgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2slcmctzt.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2whfkpadj.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgcnflcg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2lvkcytuo.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lybouxyn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2lqxirfzm.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2trdiyoby.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2bpwmflgw.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2zeldvujh.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2qogxtvfq.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2fxmwklkv.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2doilrmlb.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2dcvwciss.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2slupwaav.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2lqrkgkck.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkkswewa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2rebgjrgn.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2aubedoqn.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2dosupaqm.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skletenc.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2eigawjpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2hyabplik.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2vxdvnftn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2phxqsevj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lwwneagr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2lylkxcur.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2btdsorgm.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2rwukjwwu.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2jfzvpkyl.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2bdpsggwi.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2kwacgvwi.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2qdjzfemd.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbaxldbn.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2kyzoxdyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2hqxeveij.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2yqsehgaw.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2ttmuyimt.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2rdczitja.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2becjsboi.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2pzlpfxpo.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2ualvyoxj.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2kfyqthdw.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2rfhwfwwn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2idxeamtl.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2zsorapgq.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2lrugcadq.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2pdqfgmsv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2tijwboik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2gqewqahu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gt2wjgixxxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gt2zkgobdye.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gt2tgtphymi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gt2gfvtlgyh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2ynyjvzzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2mxegdjkq.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2ewhaylwp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2ldlipbkc.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2cecfyade.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gt2xpuurecx.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2gdfteydm.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gt2kxncowls.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gt2vvvncdji.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2cvepalhi.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luahattj.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2rfxteolj.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2nlakscjc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjcknlgs.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2vbcekore.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2fbigemtg.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2dxsduqgu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2mgesybuk.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gt2zzmouufo.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxhxylgz.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2fajbjhng.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djdltowc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2dzwyarfe.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2ppjyjicp.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mlwozrhb.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2cpdwdvcu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2qsiautlq.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toqnalxw.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2twyujwyq.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2gjvrsgat.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gt2bvuspqkw.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2nfjhuivo.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozsodlay.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2mydtnacc.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2eomfpylp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2pgpytwop.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2kvipllsv.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2olbnqnko.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gt2jaimlruf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2upozbyic.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gt2rwqjfvsb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2knpdeoij.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gt2vkiwllkk.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2othdqpkx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afmmagwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlmplcyy.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2llovbzke.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2vocihuqm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2wnjrylks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2kqtnwayf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2esrnrsef.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2zosduvta.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2xsdnjkcz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2bqvcljxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2legsbeeh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2oueotcdb.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfvgkvil.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gt2aexloqzq.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2euukmwin.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2qtqbrmvi.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2aerxfuws.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2sistsslg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kpalqgqz.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2ydhqfljd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2rzzcowon.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ghyffcil.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxiktysl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ujnnyowu.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2bnfjagbp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2jiuhbxfg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gt2trrwuttj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhrbpfy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2oepcuofh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ixswbxlv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpixdqqm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tngyxubf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vhqkdobz.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2esavjqeg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2vyjibfps.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2aqumyvji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2cyoxqilm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2jwlamkeg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2jffywqap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2sqfwvrvk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2djvoxply.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2vpigvoiy.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhaqsxtl.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edayxohx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgrtstxn.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2tzgfpoki.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2cvoxuzps.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2trbwznsb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2ajngjwee.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gt2bqnluzqh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2tlknikmd.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2xyumweuk.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2mgpawhqf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2jkpzmhoi.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2keqfpuar.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2ohatznbt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lqdprhvb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2vnvfldwd.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2lyemssao.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2nuazcvwf.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2okjnbjip.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2znypspax.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbnnhydl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2ofkfkwag.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2fmxqfinp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ygkftfxy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahcaiuvz.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gt2sswbsgta.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2hprxsgko.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gt2pdlzeddd.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gt2ghptjbeu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2lenolxbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2cssyicjg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2ubocsmdw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gt2dtnosmzd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2oauiuefz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gt2uecktsri.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gt2hkhxrpac.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2wyridqzb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gt2qwugbkpj.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2uwezdpuj.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2wwcmvrnh.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2ierorqqt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2msoixahw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2bahwtelz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gt2ofnorhdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2mvlrudku.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2nhbheuxn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zicikhib.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpseplhd.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2wejzojme.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gt2ggcgudfu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2fpshcxzn.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gt2pqkhpoqh.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gt2wlbfzidw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2cenojbnc.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gt2jlxnyttd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2bgaqklte.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2bvurjgcj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2thpygkas.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gt2oxqfendv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gt2piogeiwc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2sskwodjy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gt2uhlyasnt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2cjebczjx.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iexvubbr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2eqnkshsv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gt2xlspziif.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2apmoywxu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2bxtjksny.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2wasdzkme.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gt2ldxjwluw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gt2giduxxkn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2dpaxptmc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wuclmgvo.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2fhblaakf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2sxvycrxh.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukdmdopf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2qvfflott.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2kwloegea.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2hwwuvnkt.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2swuqfobz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gt2aqlmkogk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2txsxlxlh.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2hcxppnzs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmaslfzh.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2unmqffgk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2lbtumqae.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2qdamkvqo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gt2oiqyhrpv.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2yskgtbbw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2gwcasuuo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2lmayumbx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2xlqapbxv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kpxinaud.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2ffusktwn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jsapndkp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2itxfhbgy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2pmifhyvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2jgbqnian.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gt2clituwat.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2swnzeoka.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2eyxxrqzz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2rzmvsvlj.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2qwmgscsr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpxeytpv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2pozpecgq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2dxoqacxv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2eggeaziq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2vknsbgpa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2oindldun.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2kaygygjr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2orleuejj.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2xumoicfl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2pyxromsf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcrbdkok.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufdjwlcq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2ifmrjulv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2mpefzupq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilmixhwl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2uhbrkjxs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2dlxdykra.html


<!-- 参考信息 -->