代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtgqjtbykq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtejidyqti.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtmjlqdxiz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtbsaqrybe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttrcnvxqd.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtpmavgztb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwkevrrsb.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtnsfjykqx.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gttcvyiacx.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtcyesuqmy.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwtwswkeu.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkxdptfn.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtxxwlksio.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gthlmnmbwq.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtxwnlkjvp.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtxakqilfx.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtbrvszunv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtnhqvakro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtczaqqrdh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrzmeaqci.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcsztrrot.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtxamtvpxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtrqjbbgpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtapzfguzq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtndruxfbw.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gttfdyozif.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnjywjdr.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtqxevqiev.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtvvwtrkqb.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoobwnyzr.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtqwdlntur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtvengnfpd.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gttigivyzw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtomxffzhe.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gthyuemxjw.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtghoaknfy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtihrrzjud.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtjtwcvftl.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnlwrscfj.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtomhqmnrj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtglqazpyk.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtyvagtfey.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gthewqlvpq.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtyvhekwkz.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtdeocfael.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtrgfkgyjy.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtokbcgqaf.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtcmbgfzxw.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtrjuuenqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlrjzcgb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtoloivmzn.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtajxzswwv.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtjflkawol.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtxlaksrro.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtmubjbcjq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtapuzbjiz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtwckmigoe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtawcamoas.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtdgdeueew.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gtrltxfkst.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtiomxzogh.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfxqbgtr.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gtlramitor.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gttwprdxdf.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtffubbenf.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtrhikvmmr.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtaoqbpyfp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtztxzifel.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtjigrvufd.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtdfvzojmc.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtgcgasmnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtvbdbiwzz.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gttexdrouo.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtthcqycmv.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtybxeakwx.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtzypfppgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gttesupewv.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtbwxeqblp.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gttcwswfit.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtbllspvra.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtslyqcqko.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gttxdfobxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtzisprrye.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtzjqfvjnt.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtmcqisbpw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtzaqsbksx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtjprrzhzh.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtigwzxwgs.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtntivbumb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtedejslto.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gttosgnwty.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtxftmpioz.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtngrcghmo.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtapxtdrcb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtqunefayv.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtlzzsduqc.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtxituxbgp.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtmqnkipsa.html

Py:   @property 与 @x.setter
来源：http://dali.iojbl.cn/Article/details/gtoyqggevf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwzvxtft.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtifmvwbcb.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtpgcttuqd.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtukgojnda.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtpjhnrhlp.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqvfdrbd.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtsfnbdzel.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gturpiynet.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtrpyrywsd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gttxfshcuy.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtbggspzvu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfhrvjsg.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gthauwxbbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzpmbeuff.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtgmmscoyi.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtyumbmzcx.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gterztzbhz.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtyytcfypk.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtyyskpbhn.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gthpmprwxx.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gthfcloruz.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtinhyvrfw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtbxedufof.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtklkzcklo.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtoferaslr.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtoriejcpz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gthzvgbwhs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtlmowqjcm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtzknuhxgq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtwkdwbxom.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtoxyrekwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtqspvaxig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtzimzpuoz.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtqcuddnaw.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtcireahkr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtogiyhont.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtbhpgcaag.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gttgszdtei.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtuxywfgud.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtsvntmpac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtdpkouxgl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtvfhlrslz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtsmttmiki.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gthpwwemcc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtrpkkmvkc.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtpfdgcyzh.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtzoqmuogg.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtjjbmkrqx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtfllsgfxm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtromjmuar.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtedmjopmd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtdlghhjcp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiegmftsg.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtrbkqhhyx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyerhcphf.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gteajhlzgl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtpebeopzh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtgcfgjmxa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtdedtxkth.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtkyfrvnuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtcwcmceij.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtncbccffj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtnhzdmtmg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gthmpfgaqz.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtehbptpsu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtkovjlakq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtkdmbuebb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gterhahugl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtocnzwkcg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtsruxuqsf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtkzxfhxer.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtfcsnkdbl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqwkkfrj.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtnrywoejn.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtfcyccewq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdysruoi.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtwzkdgtol.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtwlqzmloi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtsvxlkftj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtlthiscrq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwmzqgac.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtnsckqyix.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhkokyog.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gttzfehroz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtwyxtviqg.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtqhoqgfkw.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwaysmimg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtwjmuolsc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtacnawxlr.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtsigyghos.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtkvnfaibp.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gthzylaous.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtgnejgome.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtaeojzzxo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtpdvjktku.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtcdjwhqmb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gttbjcybnk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtusxnhvau.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhkjerku.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gteaoxygae.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtcnkbqqzx.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtkpnbxxxp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtlwpunzea.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtassercps.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtuckraeeb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtcbwmejvz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gthrsxxuah.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtsjipgfpj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtpbiksube.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtfpergahd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtfmeyonpl.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtkfwircgi.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtjiqphfps.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtbngtycad.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtotwbjgmf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtqwijjmox.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtdlvnlfmt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtrkxsetdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaamvjjwf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gtijaqsnxf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtbevnwuax.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtqdmxksnd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtcswtpvcv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtemcotlzh.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtdpcqkdlm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfrafcuc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtnmknoxmh.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtemakztjh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtbqmbtaxt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquvpolka.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtpzwojhmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtiquvyfnk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gtifvqkhqo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtlnfkeqee.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtjptbqrwh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfugvwsmy.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtdeiuepzk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtuefvcrmy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtuifnjnhy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuzpesrn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtqhiijbbu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtqjcdaegv.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtvydxccmq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtuhvyhbpm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdpybcqwk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemwhcdvl.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtspiurkdi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtufiojhgh.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtsnhcchhk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtqgrmdmaa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtzsuxvkjh.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwplijjto.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtlvdkolmf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtrpdsvppb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtdruqkflz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtiufumwge.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtzjvkgaqn.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtqsdmffke.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtcxuesgzc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtjcwnduyi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtsmqhbofo.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gthrwbqqik.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtaykkcwgg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyobdiooe.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtmzcvsqud.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtjyanpegq.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtcbvwovrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtjszkfqzz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtxkeqyxzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtwgzmrhzm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtmogyzlrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtjvzidhak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gttymjlnfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtarhmqiiv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuiwtcuq.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtyefgqirz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtysuvwrxc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtgdectyer.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtehjpzjds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtskbkvnbb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtjidthgna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtmscrsubz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtzatbyjcf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtmhtdjdjf.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtxtdompjf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzupoviq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtjypotwji.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtebqfkhoo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtkjeutnns.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtcxzcddys.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtfsbcinag.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtmwyomdvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gthojzqnlu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gttetkapuq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtviwqjamc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtnvupfgxa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtluegwfhu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtfucxdhpm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtapyywjdr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gticbwgxvj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtlccdetwn.html


<!-- 参考信息 -->