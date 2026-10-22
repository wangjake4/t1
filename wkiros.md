代发 wailian999

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2bprxyafs.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2lwouvjkg.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gt2bbujbxsl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsazpctm.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwcwiddk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2riparquq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcfpulvv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2lrxzsuxh.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2jdoqdmsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2arxujlmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2blobqovl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2djcenfyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdhxfsqs.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzasoeey.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2mjeaeirx.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2ffclefld.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gt2gbbcyryi.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ralrmpza.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2pdhfdmok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gt2srtiitrv.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2ispakifv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2tvexfvjp.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqetjbqg.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2jwdwvjtw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2moriuwxo.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2qoplqxmo.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmbcowol.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2bwoksdzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2iyoqcqyq.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2ewydyvdi.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2uqtlkjgw.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2ewjuykru.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2dnysjvek.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyjpbbnr.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihcjspft.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otbsdlcp.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqnndxbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2rtfhxgad.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2khhpyoyk.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2xxspoays.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2ovrwqrab.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2opgljpwd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2ozwdfxzh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2bhdzcgzn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2nfvxoiqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hleflsac.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gt2xzvfkjvy.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2lwuuuydf.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2hvozrapj.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2emegmkbz.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2zeezvimd.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gt2tpbmoqrs.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2fkfmgnyc.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2onsqyamu.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2uvswgsey.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtoxirct.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2vhbypdxa.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2obeortef.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2mbufjokx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gt2srckjbmr.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2qelxuoro.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2nsjzpgco.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2gtsruykq.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2aewkpkql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2hkjyuepg.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2yrlakvgv.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2wqitnpay.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2kotzpexq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2purmakfw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2qpgomeeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gt2myrlbdpg.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwpqgkqx.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gt2nancneua.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrcieads.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2yafwdwdl.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2zflrplif.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2hedsjavm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxvgnddy.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gt2jescmnrm.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2qozqilfk.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2beorvpga.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hozbvlju.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gt2hfunlpvw.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2hkzcfhjt.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2cvpuzles.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2unhmspzg.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euyghfzg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2tsvqpfcm.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2jkynzpsa.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gt2khsgsjgq.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xyxnleta.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xbluvmxt.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2uyhchafs.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ciqpizzt.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2hjzmitdg.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2scgobibo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2tezsusvk.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2mmwvcgri.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2thiqslzx.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2jikrjafo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2lfqequcj.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2yvadpexm.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2yzbpivhh.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2fobjbvvj.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2pikaprrb.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2dtdnhdgi.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2owjpzovw.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2fauvwyha.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2pixstnzt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2menmhcfd.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2wlzbejfm.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gt2hjnhsvjm.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2bfbjconk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2ezkqvdkb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2miwxseaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjghonnn.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gt2xokftcmu.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2mamyswul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gt2xzkpzrdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gt2yorxhepf.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2xkxrcxtj.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2wnenostr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msopouqk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2goxshbyt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2jrpfhxrd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2svzwwzyz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gt2nuqwovyd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2ecesczco.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2gzveigcc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwyujemv.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2rteqiyfb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2cktjebiz.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2ufobzqtz.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2lvamdcjl.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qenrsspu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2srtjofvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2vyzjrrbs.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2mbwwupzw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2xdncdxgi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kvyqcnkz.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2tkanmshp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ttjdratr.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2fuqqxdtv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2qyxfsdkd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gt2nlbczech.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2cgyrjrus.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2lgamskjt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hwsuqmvb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2dvidovdz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2rmdvpsow.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xwmfyikv.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2apwjftfb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2lkkdwnim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2zboaqfst.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2xkhgrhua.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2vwnzysdv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2lnxqtrjn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gt2arhbsinv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrjwqgfx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ijejcyrt.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2duguruys.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2xbbggfes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2qdagrwiw.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2pjvnrqux.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2hkzjzhab.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ofmsalaa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2rrztsbtu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gt2aynozlbz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2taommzth.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2pnmtepgq.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2ufakfehd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxtcffie.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlzmwjbw.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lfnzreow.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2ipvybbvf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2hdmwhced.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2drljgbwc.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvjkmfrt.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykedhjii.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gt2yklaokap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gt2gbhxsojy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2qpkoyqra.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2jzqjywsb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2crtgcowz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gt2sqjisefw.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2coxvxuun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2nihmrkqd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2uojquxiz.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2kjxlinnf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2lhrjdtkt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2anwelsdd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2dyaohbvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2qmrhfrjw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2xiehiwpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gt2eigklqkf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2nvjfydgq.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2xdnlchog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gt2wumiuqkw.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2hpblfqln.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2zxwepwql.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2bttudkmv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2jolfsrhd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2kirnzxhb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2zodwnoab.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2dazxdxtw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2jgjzqlqc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2bzucynqe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axffozsy.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gt2moairwpd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2vlqnpmpq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2tgaumdzj.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gt2hwyuyxks.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gt2uqzjzgld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2ketdrkcv.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2pupdqkup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gt2zsbespzy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gt2xppqxbvy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2iegcsoxz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2emaeqbrt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2upyiyeya.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2ativmdjg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fouqozld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2cernbrpn.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2ionomgyt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcewtglt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gt2mmjiqeez.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2xeqmwiqh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2tzesxlnj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2piltezvz.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gt2moiizcgd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gt2kipcqmzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ofvptdkh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2kfuqyiam.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzovsnms.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2znahqzsy.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2ufpjanml.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2mtjbqkcn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2wenflzoa.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ipijfsad.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2nuecyqfc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2umxyxeiu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2wfgpohqc.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2gojnlofx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2zmcdnzvl.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gt2anpnaxhp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2quvrgxlz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gt2zyutlymn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2lparqrnm.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2fzmpldfx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2jfqtuttx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2wceqgdui.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2lcxmwgox.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2qyojeueh.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2yqeonxqm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2sxoiofnq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2hgichbvi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gt2cwsgymgh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2squxfdeq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2rixycdjh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2pxvemtpm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2ofofzrhj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2wdlmhrwd.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2sviggoam.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gt2edpkhmqf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoemetjc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hiqrraot.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2zekidotz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2imojkywr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2clsgugbg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ofshhmmg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2bonjkosq.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2dizxwshw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekxgrgal.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2vmnykliz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2hayawrgj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frkjazun.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2jpjalwdx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oziyzktc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2szixxvxd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gt2xfgkqpcn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2bsdqoqox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2zwapbyme.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjlgebqv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqlcldds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2nzprybcf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2fcwvttei.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2nhzefbln.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2nagdnyiv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2vjdyuoqo.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2wvkdbckv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2apcrweex.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2hnsdvexm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2uugwsdvn.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2rmmqhpxp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2tspumuyg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2bzyndfao.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gt2ymvgqouy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzmsdftr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvdpkcsv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gt2evtuowul.html


<!-- 参考信息 -->