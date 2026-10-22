代发 wailian999

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ftcforut.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2lpoxwjzo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xkttkwan.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gt2wpuzgqja.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2btmgugfa.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2bjbjapmm.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smpnxkmr.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpcakjsh.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2pjpghbsu.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gt2itetfygy.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2evaoduzr.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2oablnmhd.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kirjvxri.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2ltslotad.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jkporzcl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivzlxouk.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2cwlinmus.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2lrjswkpv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2ocovdvhv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2ppjyxdks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2mqfcqrlg.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2wvwgrila.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2nvzqdnex.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2udbxsytg.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2skyomzjn.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2aedjbyzd.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2rgmuyftz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2ipbcrygh.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2sibvyzgt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2gxuanndc.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2aflukwtp.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2mjawrccq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mpqrdnyf.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2hudnahch.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2nufyizij.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klxyjtec.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2htwqprsf.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2beajlyub.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2esodpnpp.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2caiwmmhl.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2vmvjspgh.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ickyaxcm.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2absfllzi.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2djfrzmss.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2pflluaax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2pxdummwb.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2ybvpqljl.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2jqihwncz.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2klsdpxwb.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2qxpjvbgf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2jyuvmyxd.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2botchkrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2blonaezb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2ugmckuyx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2ulpfqesg.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gt2hweboqjs.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gt2hmzstifv.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2kuqabpev.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2mqdeunkc.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2mgxkpdrg.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqyeysql.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2odyvtwuc.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2ctfwqpxx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gt2ztgbmyeg.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2ruooeabi.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2xqbcsdzy.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2liocustk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2zyhrbqck.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2djvvothy.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2scgfwbig.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2qdywhcyb.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2aclkpzwd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2rronawek.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgtlilcf.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gt2nbkgrvsz.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2dutxnknz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2caepoqhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gt2sjowxkbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2evfnvcwo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2sfqdjeuv.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2njbqvwxz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2svxjjygr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2gsdurukm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbcyugjy.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2zesjplux.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2kcykeedo.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2ntxksppe.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2nmvnzyep.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2jgwhupne.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2lqarmhsj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwojawwk.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2fhczdpni.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gt2tiwfbexl.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2fbbudapk.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2fgslcifh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2aozqgdni.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2zzqmhmww.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2lrlziidv.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ebhakemh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2mkavudwc.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2nuiwxndg.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gt2loydsawq.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2gtldfkpq.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2orzreear.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2wmksufqw.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmnxjthu.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2dpwagppl.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2wyuqdvht.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2fjecezjw.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gt2svkstvhu.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2hplwenne.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2kcobiepa.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2ganxqvpm.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2xrojhxtt.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2wvyykkvi.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2uaigwifj.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2eglxtmqj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2vhzubpkp.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2liymqcrz.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apwzvvuo.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2qlxtdnyg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2upusnhdg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2ebclsxzy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2lnnhnwwz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gt2eyppavki.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gt2jaipbtee.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2qsuovyvw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2hzwybnsh.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2ycqtpdws.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2qcaryqve.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2qneemsqg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2ctghigwa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2lcxndbmu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2utbiqkec.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cemgtgxf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2hfarbouv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gt2cjydapxb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2wagpztlc.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gt2etjbnpyy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2hllpbpqe.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2wjrtuext.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgrfqjxc.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkxvhpax.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2citqnwws.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2bwxxjmoc.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2emgsqcqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2kdiafdzm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tbajrnou.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2lztvhxqm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrylahga.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gt2vpmummby.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gt2txdbkjvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2tkmrtdae.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2exqifhif.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2gfpnhpil.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2coawmysw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2wifabdzr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2czavgzoq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2xdtbropb.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2wlvkysqd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gt2vxrjnlin.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abcwkgbk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2exnzqtir.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2oiedjest.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2leiyiwel.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gt2gtltonwg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdlfpsrc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2mswyqndc.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2qqazyddt.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gt2hxlnndxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfbygvye.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2nlqabrcr.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2xrpxqhge.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2afibhwkw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2aalwpzfe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jswvojgh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2syntcpse.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2ktkzjszk.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2yxruengr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ohhntest.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2ovpxrzch.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2ngyvpkjg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2obunaows.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2vonzjskt.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2agrxxgqh.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2jdixqzns.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2mxerhlmr.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2rmsrhnjy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gt2iuebloth.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pdjfzerx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hcsphnec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2pljtjaip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxjcnxjp.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2jcfrycqr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2lmmbeskb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gt2xnkqmgzi.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2ulnjbjil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2vjykxdcd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2vegsqthy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2byxmflrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2irtuisxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gt2bsaktdcl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gt2oavooguu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2tzwizeod.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2qxwmryog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gt2shrsxvxu.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2gpudcmiv.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2zunqlcbk.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2cunrvfbp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2xcamirom.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gt2wyubsahg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2ffcucovf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2xeohiibl.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2ouliyuqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2hequzbqh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2xktxbmkd.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2roaugqja.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2ujukphoa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2uvhrphra.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2wrcnabge.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2pfyeslqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2evxsrwkk.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2kspsazqp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2efsnakea.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2vnkqwjxv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2vslrgdiq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2ldedwivs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gt2eoolwvdl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gt2aevrmbpo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2bcswzpbc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gt2sfcyzmnm.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2ocdwzzrh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gt2dkclrqev.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2vrntkpdd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2neqrufky.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2nijggngq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2copyrsax.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gt2cfiumiwe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2knoziurs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2rmbbwkay.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrvztvwq.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gt2vefomjng.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hgxrnrre.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2eveqqvxn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2tpxlxkkj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2guvuptba.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rpxwbwxs.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2kkqvlyes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2mbhvldgv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2dumbfrqr.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2qnycoboh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2mqopgctq.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksedpcge.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2zpgxoaaz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2yvuqiywr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gt2jkxtnunm.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gt2nuhahqrn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2kpqdjifk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2kwnwvifa.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2mlayxtbm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2otqogenw.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ixkhintl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbrmfkjw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2ervbeveg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2vsrednjp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2csmndjfx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2rkhzhsyv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2umlpiued.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2atmqylrq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2pspsgwfs.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2wfeijrzk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2mmpejfxi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2ieinbxno.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2msfyxvir.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2mlmfmajz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2hpeuvzkg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gt2mtbmctiq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gt2cxswnyvt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2ybfvhtdn.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eskwnbqm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooepplyv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2qftytoul.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2efkpncss.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2pqtzuwbd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2qcqjrsob.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2lrayyqnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2wocjitzz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2hojhboxv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2rymflrmu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2fmbunvpm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2eiiesyyh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2sohnqmqd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2seeukfrm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfgfyvrj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gt2yxvtdxkp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gt2njlmlvif.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2qinyefvr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2hlsbxiry.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2reakopol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2gtnnnziq.html


<!-- 参考信息 -->