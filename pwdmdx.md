代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gt2ofkgfiah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgriigey.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2buhsgacp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2yhpqxxib.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xrjctlue.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gt2iylhjfri.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2aacdxdya.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2xojoylxn.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2acazdmmm.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikhjzepb.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2twyhbalq.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2gmbgxcgl.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gt2wzprstaa.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2cabtvmyu.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2isarjlae.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lhdrfjug.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2noxakxgg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2xltxguau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdnqyvzm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2vtykltxz.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2avtkmuvj.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2cvindvwx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gt2mrrzjcpb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2cgvflycl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2qbgvvgyw.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2seahexbt.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gt2bjcaoypu.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2fyvsnyvj.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2jgzbhjbp.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gt2dcmjelty.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkuzqhra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2zlavwryk.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2zmaodnce.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2itgleeuv.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gt2qxljawvw.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2xtfxdwfn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2mcgzgvcg.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2obqdyrtk.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2iahmdhzp.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vgwebkut.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2wqcpmywl.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2iftasnso.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2eoevjnwh.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2uesyiadd.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntowaiaz.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2nfupbsbe.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2pbtsvatk.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2sreybmba.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2ziokpaxf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gt2qzsaxbvr.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2faeavzkp.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2sjfypjhr.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gt2afcplcjr.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2yokpcdge.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2gyayhvbq.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sdllpnkk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvnzfyil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2nqciykkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gt2irbupudx.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2kndbdalx.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gt2qvwlyzcg.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2lolvuibe.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gt2hsocqkyy.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ehtmrqcu.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2kksqlsyh.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsllaily.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2iazybtfk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2ljgtnhiy.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2aafxlnwo.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhelcjxc.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sctgqahe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2ecuyrsov.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2vkdnhklg.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2axfntevg.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2wtfqkpeo.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2cxgrhaye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gt2csqpfgtj.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2yuftpanx.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2vxgjrlyq.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2hdmhtxko.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2fvhdkzzk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2lpqlzvmx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2imamvtle.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lgnycslz.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2rktddztn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2wbggzsgz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2pqjfieum.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2tuodvifq.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzkisalx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2kjfhkequ.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2sysgqifo.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2ipndhfcl.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2jmfjbpru.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaelsjp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2mxiviqta.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2mljeienb.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2nshnftjg.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gt2ovvjpnqg.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otqdclvp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2nmqvdiff.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2kijdfdkn.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2qfkjwewe.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2slcvlomf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlwewyxy.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmkurtit.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gt2edvmzyhs.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2leknepxd.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2dffpukfv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2fvvmzbtv.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nscmdpvw.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2izncdeel.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qwglqalu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2gftqoyiw.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2lknbnfpp.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2blgriezc.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbeikjft.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2qkzjvstd.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2bejgvwyg.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2lhsknmiy.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2ujnxnriq.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2uaotvavr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2qgpvxjtu.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2wwfuawfr.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gt2sasqnspp.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2vufkjrua.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2lwuvmdys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2ibyroods.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gt2lfepspow.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2fmzvufyd.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kslocxyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2cuymcgni.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2ephnmlfp.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2poavkijm.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2mtcrziwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2raimsqvy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2boabgtcw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2qqwlmgxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2hcsmdyqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2bonxiwur.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gt2zbopmmsj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrwfgvtt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2wuzybudd.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2scsngiuh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2pqcmvlre.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2xunhuswx.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2thndmlsv.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idcfjmxh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2azmjarko.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaveialk.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2mvqszrqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2pzxbiyus.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hbqmswgu.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2ohytaoty.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ycpjwjrh.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2bgsnxybe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2bgosaduj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2biusoerx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2ikgkatbi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2imwluqiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gt2yxguasoa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxqoooik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2qrikuqlc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2mhosrgzc.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzznlxhj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2yjmhkfcn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2lmhwmlrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2urqwjnup.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clyhkrus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mhdgmkfn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2fdshefdl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2fgmyrkjk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2fhjzntnw.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2vzxjpnih.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tespnfle.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsyysqtw.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdlqurrk.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2etpswzxh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2ceokfqip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gt2qpghdqmh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zeuprwku.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2erijmrxl.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2vtnyqwmv.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2bcmvbrnv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2ujxtwaey.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2jowshdfk.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2awhtrfiu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utkvdzrf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2qjoorexv.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2bujgykjr.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gt2qxozjxly.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gt2ugevgyue.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2ntyybucm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2gyiovumx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcgizlsb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2pnxizwna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gt2yndetgmy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2aqtjjass.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bglgrvxe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gt2nehkhxxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gt2popriasj.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gt2ideysskr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2ljgqugbk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2yizzoiww.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2kugbmdqb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2zceqwahu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gt2stlkgyrq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2zntolaia.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2csllhsrv.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2engbjfje.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gt2qvvnglop.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2gucsluip.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpbnlmog.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2zlnduuzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2etulqowt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2suqjxrzs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2vanwgsbo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2uqufennv.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gt2fjygltek.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2nuzprsfd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2wnqdeero.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2pkvnzlou.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2iutmrltn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2zungjusj.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2rikdhlqi.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2jcfhamxy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2ssuqhncy.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfwkbjcw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2dmvvphsh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrlcaqoh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxxjzqum.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2hqzjvflm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gt2sxijbziq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gt2zjhdlhqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2bbjsmffz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2fueggnqp.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2xfjfbywr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2cnqaqcsx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2jqpbgwkk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2iamcyhrn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2jqxgnmqh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2bzhizxok.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gt2owmoptbz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfqbjkbl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2shuqkgns.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpywmrix.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhcjhcqg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2nmvryban.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2jjuvdcto.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2aevfaowq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2adqfzcrj.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2kfjcxouu.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2pgffbavi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2gywqbfcf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2fbloxsby.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2churclup.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2wvuhcxts.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2tqyefoxc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2whdzrekx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gt2zxbaqdyh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2yjjiaflh.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2jzvsxifm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2nklrxzzu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpjwicym.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2tsgleddh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2mzswlpql.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2uyzashdb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gt2jjnkhbzd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2yimifokd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2rxnehpke.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2mqtuimzo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2dwrgtsop.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2tayayqwg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gt2bmdhwvdu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gt2hhoundif.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gt2jddqelaq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gt2haqypzit.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2sogkvaih.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2pzodlvpz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2memtbpiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbtvwnyi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2eyjbxzrk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2iyyhjvls.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfisqmw.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2qsoylksi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfzfnbyk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2zkbawwwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2zycsjebu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2xbbwaaty.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2njbpolja.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2arpktwhn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2ytdklxht.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2atbjuzrv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2nqzqkuqa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2igehvnfx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2bsnyxjtl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcrdudoa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2scyswyde.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2yjrcqzeo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2gzpscosp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2snnilkje.html


<!-- 参考信息 -->