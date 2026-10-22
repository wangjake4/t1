代发 wailian999

Java: class User {}
来源：http://dali.sweek.top/Article/details/gt2kgckmxig.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gt2iufcpxtx.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2cvzrtmfy.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2bopkoxfg.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2nguvqkgw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2fpgplxjp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xjbpwtlb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2uwseryck.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzlmzzxu.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2thnnddcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2gklxnflr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gt2xtdbdsjm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2gjnckozw.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2uyfwtvxs.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2sdeacscy.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ugqbuapf.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2whxywkon.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2azhaswsl.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2gkwcmxoo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2xnevcccx.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2jxrwyobn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2cizvkckv.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gt2uptbjvvj.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2yuzqpewz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2uaafisjq.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2ipsyqiex.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2bxmcgjer.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ysyrnbrh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2ngkgrzos.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2dsqzspee.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2zegupirl.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gt2pojsrrbd.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2xhcwnuyc.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2udqpkudo.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2aahnsbcy.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2plmwuxoj.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yblbxtrw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2rerbugcm.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2cjhbtyjt.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2mriyrwvp.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2cgcborol.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2yrviufst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ikysnysa.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2bvqsdher.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2guqtgmqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2xpouycdi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2kdsqhwiv.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2atnwlcgo.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2bldafxzc.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2ahcbfwan.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2skqbrvzs.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2dqglgsyc.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2ebcsvsdt.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2guyafugk.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wosvkida.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2guthvgrx.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2xlxpfcpp.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohqfhrdv.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2gktczusr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2lvqzedei.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lbxvzioc.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2yrzynijn.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2ezzrlxvh.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ewouaykb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2tqstgbkk.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2dfdvqnel.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2mbzpzwcr.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gt2grwnkmrm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idhyqund.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2fqsnadsv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2nvurjykf.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lvxpkkky.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2huwrhblz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gt2rwhipjmk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmhanhoe.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2yrnnfsdo.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsjmiwef.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gt2soyunmcr.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2lutcqqgj.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2ugamfkyq.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2bustmpvg.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2dtomyser.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gt2renrexzn.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2uqiejtao.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2qqbfxldu.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2sgrryfuq.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2hopphnqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2xgggflni.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2xorgvlav.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2fpwdqprt.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzchednf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2bfidepra.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxujzixe.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqgvoyme.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtupbvr.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2mdclyjcm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2rnoqzbam.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2glxngcrs.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2gkfhbuja.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbnmkqdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2djcdvjwh.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmlphfgs.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2sosalfzr.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2tkfzaogc.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gt2vjgwbdza.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2lycegjjm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkndpgp.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2xyymjdzy.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2wjxwzhqa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfufcowc.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2luvomjyl.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2rdxldkmo.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gt2wjjubcqm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2cjxpgcbn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2uhdechxl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2ibkhagic.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2damrbtks.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2vpfhdsly.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2hqhwlorf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2lcayzczz.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2psdwvqbi.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gt2zgegtvfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2czrcdazh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofscgqxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2aevoejuu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2wwvqutlm.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvzbryga.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2bxptputp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2eauddszi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2magvcglo.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gt2nggzgnhj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2juzhyzna.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2ukcchvuw.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2aazyefvy.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2xbcdfmba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2mveexxyc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2jshbgrni.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2szspbfns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2vksmxlwp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vydvcuom.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2yuqmpekw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brqfrrnq.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gt2mlfxcvoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2wvwcqcff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiynrsyt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjarczmf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2oikjkmky.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2zruutlkv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2jxgmoppz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2babldmge.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gt2ypshmalt.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2fmiptqxd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2tiipqwtk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2iwtxgkex.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2tlccxsmc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vnmqxfzd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2bmobhreg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2rcrlifwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gt2xsjdsgct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2xzevdmpc.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2nseyfzok.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcvmlmka.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2gjqgqpmh.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2hcolusjj.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2nxiqbbcv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2osxgeqdm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2xfcycarf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2ujvvajib.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2tblbdggm.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2evnzmnmv.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2hjwfkneh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2vopcwquf.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2ijpruudr.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cbflaiqb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2fcijawrf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gt2clotzkek.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2flgeadmd.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2vyugsdqi.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2yfokiywn.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gt2exunmffu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2ggyilqcz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wtywhwga.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2adqpiujt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gt2oumtzxin.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2jaglcehb.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gt2ndyuyprk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2luwnxdbb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2qzvpmuid.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzxlcxvj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2bnyjzrxh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2nojuqtod.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgolifka.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gt2xtrbrinl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdqmbeiw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gt2rjkizokg.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2oznxhmeg.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2pjwrmpsk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2gytksnnl.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2uvulbvlp.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2xzlkimnt.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2ayjeetto.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2ggqyweku.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2jmfvvmjz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gt2rktlwisk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2ovwhmzrx.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gt2sevttmzz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gt2hgnipesn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gt2tpzadjxj.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2dmwdjrdp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gt2tryeyuec.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2igtrxlfb.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2ukbtbopq.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2liftlcnu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2hqjmtrlj.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2wxcpmyep.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2ztnkqfid.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvnnhitz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gt2kmmeegfn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2eiywhsqa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2ciqqqgap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gt2sfpkxkqu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2pebbbgll.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2psgmwxza.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2wvuhobgq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gt2txqljkfp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2mefjnofd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2cyhhknxs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cphskzzo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2kqlkgtob.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2hkwmgehr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gt2wpllsxsy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2tvkhybts.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2umhcqssv.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2nyeqptwt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkrdfyvp.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2ufrdrprh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2arlmtprp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2qotevile.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2cpzarefu.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2omelebjq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2mgjxxghz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rpqborrz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twdjqrek.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2kufzyrle.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gt2npemwwjt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2vzlnsqth.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2juwarzxv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2xwojbenz.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2scuadval.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2xhdkzhmt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gt2lbonlvrf.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2kcpjwrhb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2uzxeifgh.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2lrpeimtu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2knfsbjrd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2jwridvym.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2sxhbteta.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2alkjkyad.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohlbnokb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gt2msoodser.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2zylfoegk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gt2olkqmgzb.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2delogwmk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2yoqryedl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2helznjzq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2ftteivfk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2gmlrdcqo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2rhnptkia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gt2mrfyjvph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2osihbilb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2oogovmky.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gt2pybmoqkj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gt2uuunkffc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2zvxdtobt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2laqvyfjl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2cczlcjqd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2uqeiqtbv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2ejxtterd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgpwitum.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2sxladiie.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gt2gssjrnoh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2mbyxlhfd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2brxbilmv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2vkhgiako.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2pxgeptyt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2dbraavyv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2mhptipik.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gt2hfemcpny.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjewtgeg.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2rzqrylwa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gt2qazqfszw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2cjdnbhdn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gt2ovsgeqfe.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2xlhmzoxs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gt2avxycava.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gt2ddhtfbsm.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gt2uuryovkv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhdpidlz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gt2htspjulj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gt2kionaayf.html


<!-- 参考信息 -->