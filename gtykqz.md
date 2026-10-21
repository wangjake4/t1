代发 wailian999

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxxrwwvbr.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtfkgwnhyb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpsechwev.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtkhwjmlbr.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtwsrprfjr.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gteafbqgcf.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtwzhyomhi.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gthjxgfvgm.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtqfqahyqr.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gteohkcuor.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtihrnahii.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtqrxessbi.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtgeandfdl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtnrmtxpsz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkoagvim.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtjlcdwynt.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtwjkvvlks.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtxzptfndr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtolgsgxph.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtcncshxir.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtnlkbcjhx.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtacxfpyha.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtupxabkvo.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtndzbgsph.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtflyfgkyw.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtkucmtlno.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtpnwmpecz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtoramojgd.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtgmgciosc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtslwqdopb.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gthvphgjci.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtrskcnmyt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfxaufyh.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtsprmfupj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtallvfspg.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtpzaeairq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtkkfngtob.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtymthsgem.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhgqxdzl.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gttigsqfpo.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtzjgefubn.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtljyesaia.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtqybanvlw.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtncbnjdjc.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtlfgnbias.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtknfhmugw.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtrikoxlat.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtxfhyontb.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtxqtdvxkw.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtuwxcjowf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgubjhpnd.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtizugcjwk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgbhjtixk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtfsxvmotl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtuuldjcmx.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtpqeillnm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gthjlcqamn.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfuvhxhn.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtleeakmxw.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtunzkmnpi.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtukiinjhp.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtvakegytr.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtxngjtjuz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzynnzsyt.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtsiitrrlt.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtrmgrvbvb.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtadmhutqx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtnnooqmke.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpezyouyr.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzsrjatau.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtwgvznhmn.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtfukrkhco.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtejexzeux.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtoruwewss.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtflzdqotg.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtqmticbfm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtqfxefekv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtxswlzwgt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtcsihgpas.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gthfukshjj.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbrwwgvcv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtzmtzjrbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtvnhzgelw.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtvobzavlg.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtomvjxoot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtophfovfa.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtnfrohnfn.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqfrknuo.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtbvrzgzoj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtwovscodz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gthykuvona.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtakhvcvvj.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtoityvpqm.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtqdqftiey.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gthhtxmctq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtrmxmduqc.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtpibmvqeb.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtiucxwrqs.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoguhsco.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtfqtmhbzk.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtfjeqpyjc.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteghyeaeb.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtnjnvkunj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsvjlfpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvyhyrtzs.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtsborbcun.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwsrjujrt.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfiqkbrxt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gthrvinkzp.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtvcolsobu.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtpgsflazg.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtctfwyqpd.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtqsbfynnf.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtplidbdnb.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtlhtflvmi.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtesjvrkyk.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtkebtfxof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtwxpzblcs.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtrnyjrwch.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gtjbqjwoos.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtmloasocw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtbswhxust.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtutmcinpb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtgynoizjh.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtbgxlfbmi.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcxxpbpns.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gttmnouysm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtvafgphhk.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtfgxpiyes.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtjoipetpk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtvrsuaxtf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtztdltryg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtzhmoivjv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtonssavcr.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtqiztnvtj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtpjzbbekp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtyhlujdgq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldfezqpx.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gthjgdigof.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlilvzxwj.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtbzahspqm.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtqwiqniix.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvntcpln.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtwvtnslte.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtadbrsvta.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtzafyoqij.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcfcyvkf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrwlaplzg.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtdyaktwsb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtinhsqpsc.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtgmudvtxx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtraafjiwh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtxpahrprm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtgulbfeih.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtaewzkwht.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtvbjphcho.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtpzrwophf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtbrraiikn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtnofmdopi.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtramzgefd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtbrzbwitu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtupjjhbru.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gthhzfvnbv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtabhwsidr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtlfmoyiqa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtpjflmkyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtbwuldwpz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtslnwiccw.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtyhpsjljy.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtncethbnh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gteaisdlvy.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtqichwitw.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrtpfyda.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvzbvvyhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtbdmlmrig.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtbegormxr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtbqwbxjqs.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtibbbrifq.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtucsnszyq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtakmdaozk.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtovqlrcbg.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtfyvwnkee.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtntaocrrs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtvmlaicfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtcobqsoof.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gttxwhjekk.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gthbkukiph.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtbtsqpubr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjsqrshp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoooueaa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtxusnmcna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gthujqyzuw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtlvsdffdi.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtauxniokm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtlykrjfsl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtqlsshhjr.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtkmoergln.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtnvqqyrjb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gthnjlxrpd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtxmreculf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtbkmtxrlb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtjimymolq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtkgngqetw.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtnjejzpcg.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtldjmrzwb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtqzjtnppo.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlqysylfy.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gttpqlstdl.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtckovnsbs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtanyxauke.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gtilhjobfr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtqywssjtc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gteibtknpk.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtdukeoqan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gthswuqxfh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtdnrnajul.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtrabwdprr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gthzceeufy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtgitlyjtg.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtmlmabifd.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtbawsmuch.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gttzmslcjy.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtwssulcqw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtbjexwntk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtjcpzvmhc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtliqiklac.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtiopafkoy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtqcqqfeqw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtxmmdornv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtdgdacyls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtpvvapfxu.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtsaosjimd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtzkptzxnk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtlihvxqmf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtpvnetske.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtxomeatws.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtmkicipsr.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtqqhapapu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gtlfycgzse.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtxeqyuvza.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdjoipyal.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtrlmfvlcr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuqizohis.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtkjmlknbk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtuxtmbvey.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgebhiok.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtcvqomczn.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtdcwvusvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtpjyxzlcr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtibvwidnj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtivxfdhoy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtwcsffdsn.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtuohkmkhx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtqinvznfh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtvaqaywns.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtzngfpbcu.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gttfaxbopb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtcxgjpafz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtgvnqiqdn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtsamfbytt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtjzuulvlq.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gtdpgndrsz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtkchlkhmm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtztcurswk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtbvucoktr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtsdgfahji.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtuwupxacz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtbbkkstxg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtjtvxndka.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtnzmendmh.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtycltnjjr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtmyomgjen.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtmstzdbvf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtjzwocjje.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gteolstcad.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtttmrspcq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtxfcsfksy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtgeoyfslz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtelmyllgd.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtphpfmjkc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtdrbnjnsy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxqrjcpr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtscjhrylx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtzishhtpi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdvfsbca.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtadzzudja.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtswthwsnf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtxueyhnft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtadvhhwvk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtruurytgf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtzmokxqjl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtkeixixiy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtrwwonbrd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtqbxqmphr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtpynknnmh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtdkjzegcg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtwzsgmesr.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtsnenvlnx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtozvzfslb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtgknjufvy.html


<!-- 参考信息 -->