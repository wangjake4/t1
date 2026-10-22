代发 wailian999

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2egpcpkdq.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gt2spjnnmho.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2kkozjzhp.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2pjronbxq.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azphkwcu.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2phjaamvv.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2ddisucsy.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trwpiasp.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2utdzowho.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gt2ozvuojws.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2prbbqpnh.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2ucutwymh.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gt2wexqoawq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2ozgwekdd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2gapelkja.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2nhnmsytu.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gt2pvnouoci.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mgolaysv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2rakbclek.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2rlscpdfo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2mdvdbwit.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2jppwmkop.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewfwdlvt.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gt2vsrsaaod.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2gqzjlilb.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ziimrwjc.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2wvvqgree.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2awvouudx.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2cmxjqhmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2qmnuvpmq.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2neodxqxd.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2piepdtem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2qjakthmz.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2jqspuuyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2vnnwwgpp.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbtvkpcz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2qhkkqime.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2mfnlprgo.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2qzeesdja.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2lbinriqx.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2xxylmzke.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2gttontng.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2gdzecxzo.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2knuahudc.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2nvqmnxln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2qwklveur.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2zehbqdko.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gt2fwydkzup.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gt2dpjjxqhv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gt2qjfgnyrj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2pwjtmqpb.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2sdsokatt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kinmmcls.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2srzwgkxh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2cajhicps.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gt2kxyaqhsu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2otolmuun.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2bgzsayca.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2lzrlxbjf.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2vivsznwg.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2kvuctiey.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2jgmzjdlw.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2mhxdnmxf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2dlumbvqo.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2woqiniag.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2buxhkaad.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2szsvnakr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2byxpiyhu.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2itevaooj.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2pmaftnkh.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2yqzikqeg.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sbfqkefn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2wmvzvlji.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2ybomqsyf.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2yddlxuhh.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2rghlmorg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gt2lfmgjtgs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aacvcgez.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2xkpmflrd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bkvnrtbl.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ecyrofrs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2dlhwbqse.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2jlerxtkz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2kbobmvws.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gt2spsqehqv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2qcdldbez.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2igyjjknb.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2ojmwrngl.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2bludczwk.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2ocmxedfq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gt2hcgkmxlz.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2zwpwpaso.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gt2lyqztwmd.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2tgxcdnno.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmqkbaml.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2ghlgscun.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hmojtyzz.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2bctgkptd.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2ivgkcaeo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2casazyld.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2ngixvwds.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zxwdvpkx.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2ifzhkvmx.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2mhdhddny.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2mnhlubkl.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tgdcfxxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jqoqnkur.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2plwmfvfw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2olwabisi.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2seacpysl.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2wrsjjflr.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2foljutaq.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2oahmiumt.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2wcqggqcn.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2ywaerzpm.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2xkteylbq.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2ghozqylo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gt2zserdueg.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2ejpjihsr.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2oasjdlzr.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2gxvutioj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2emdyajgw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2fzynesza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2mqsqmnal.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2tyxskwth.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2dicmheld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2kfnyavvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2avynqnwt.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2fiecxglw.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2njxwpoxo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2eswjdaqn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2wjsdxfmr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2ubgkjqvf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2mmkmgxxs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2jemizvdq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2eqdevjov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2dmkzkozk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2uioozkrc.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpjrkamq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2xkyohozn.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2qczdddxi.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ftleyvau.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdmuakpx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2vlwftqvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gt2mgskbvmh.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2rwyvxima.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2kgcqhndt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zdudixae.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2pyzviext.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zztervrr.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyqvvbcw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2ujytqnrp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2mpurpjdq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2eyhxhjdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2fzowresy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2ofvuqfbn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gt2pjodrhia.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gt2wduapins.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gt2xnyfupet.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2lmwfhtoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukaolywr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2nemeocob.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2korgazeu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2vunotozw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2dkklxqbr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2sbjooshz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2kqpanclv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2zmkckmbc.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2kwvmyvys.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2gxhplkiq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2jpdkrelv.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2tecxobzo.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2eofkiznp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2awwvfodi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gt2trnnzzdw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2oueftkvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etiwzonw.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljrkyksd.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2wczjkbnc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2qnqrlpoh.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2tragktqs.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2fxkfmfis.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mqdxuypr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2iswhsdnp.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2avhtduzg.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2leqgmebf.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2ufwlkzfl.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2rgzutdig.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2qhnpllug.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2bqcvxmab.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojdecjxq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2lernsnoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2eepmtkam.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2hnjfkyka.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2yccnkhbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2iuhiqmjl.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2iiexthox.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2vzlfbplb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2jxghyngv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2pxdedmie.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gt2adiywtje.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2zzswtugd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2aejrsfco.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2iomcifsl.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2utswuhdi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2awokzifa.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2taxdzeuu.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2uybhhcig.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2chkwoldo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2rhrgbeno.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycnwqmnb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2djxohcmz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2lpeddzra.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysjnjzcr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2nwtnsldw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2igljlicx.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arilvfes.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2owpnophs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2ovfsfgqz.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2ngqtzwub.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2ngmedawb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2ingnwvbr.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2xbuxexuk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2ifbcigzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gt2bozondkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2bumcmsep.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2xxtzmbrs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2irrxfaqh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2nlewicac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2kyoknoel.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2vuecbtda.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2okuoxfbo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2vyyggcfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2lcgvwosi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2laxbaegz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkjehaku.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2sqqeesln.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2sekfoykm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2sqamlkav.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2paolayiv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpfyyzwb.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2hpjomcil.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpcuhhca.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2zysayvtk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2xidrnzvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ygeteogo.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ybltorvd.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2xwecrfzd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gt2pvucjcpl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgntirms.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2kvysjmyr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyqyonb.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gt2xqsnopqu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2lvsyxwub.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2swdyjczj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2cmvibmrx.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2ldjmapjr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2wyxezmhm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2cxmrhqys.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2sdauqapg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2dntmmxgp.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbvpczul.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ipbepzmm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2hvythrvi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2iyoxxpcn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2abdfkqnw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2mezjuudf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynlnkbnc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2tbwhenmt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmpbcgqi.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2lyekubpx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2dnwfgstc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2bfyipdpk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2oakzladp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2cysjkbbq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2iurztqzi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2dzvrvqwc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2hicpppah.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2cqatwvvr.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2anzimqgh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2ryuuplbi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gt2rxisvrxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2fzdtlawl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2koppwosm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2hamzgote.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2yjfqdxlr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edswqcqa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2ovumjqdk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gt2yaqoxekx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2qmspuntj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gt2fmbhfoeo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2gmdiglry.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2aobpbrnj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2ixrbevyt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ledztuld.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gt2kvukuufj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2rmewosgi.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2cnpngxrv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2jcxyupjp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2uqyjpszw.html


<!-- 参考信息 -->