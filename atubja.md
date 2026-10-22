代发 wailian999

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtkdxcuqlq.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtebtcgklf.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtntahaotd.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtrhvtxigi.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtrcmzohva.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtimgnecbz.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtnfrjldfu.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtbjgathby.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtvbkcvujh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtdgxcycpk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtzhaataps.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtdalotvsu.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtsrdazkpa.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gturamxecy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtregfgyuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtbnwlrsss.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtiqqrphpl.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtnnwrrnzf.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtfdddhpfo.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtvpnzdcwd.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtesnfegyg.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtnvfbwnnp.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtpdbjcwqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtuxfxuahd.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtnnlivwid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyoksxvb.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtgbgauipo.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gteneslazk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtadwhywgp.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gttqgtltgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtzonwsdcq.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtxoetshyd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtzjvupcem.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtagqxdbje.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtcchpbqhx.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gthgqndqin.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gttfdvhkkd.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtsfroeqdh.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwkpguxfh.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtleojtjgu.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtoryxpmdu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtytmgapun.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtjisenmct.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtsysaokce.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtgffhhkpo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaxbjybt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtysyqzuqh.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtwbcrjtlm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfbnpala.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxlibetfx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtwbeynuyb.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtjfhmahka.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtgluseelg.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtgspyloyc.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtxaxwcqdx.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcexzqnmp.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtblolhpsr.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtoddvatwn.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtiaaxnlmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtvfwbnlct.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtbxmymqbt.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gththprokc.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtlgdxqdzh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqflmeyb.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtppqtibdo.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtqqxmkqit.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtnqlvittf.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtdpbidzcl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtnpauqmjh.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gthjwlvsux.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtyyvilipn.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtqoclfiwm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtbfouzajr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtspsldfix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtjqnghqfv.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtfoaxyruw.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuftzywob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtmbmpnbzm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtcduyfvsa.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtujjkeprp.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtvcnzuuzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtdvdyolid.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtluotypev.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtarbecatj.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gteopwvksg.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gttmmrruun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtvdnvxlnb.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtojrxgijw.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gthvskhusf.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtdagafahi.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gthzfmhhww.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtwsjbdkgg.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtwfquytup.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtyoyikczr.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtbcovcqli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguvvyort.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtovhmzavv.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtuoewfsbe.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtiorhblvi.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtxhygzdac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtoyothwgy.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsdolvrxh.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtbgnilqpz.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtahdkkbvw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtazxslbdk.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtjxeqvqdu.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtfcgtgfbg.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtfhampjio.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtesguzedy.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtmzkrjnjo.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtcsojuflv.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gthimwzykq.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtcbveaijw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtfovvlwog.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtxrknncdd.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtjwmrnxlb.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtynfxieqp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtqurwmqfs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtsurabfew.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtlvrjjewn.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtntfxmvfx.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtobuxgdtg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtkdeihgpq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtdokmnsev.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtduqjcyta.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtsxjticcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtnoohbghg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtqrahfzhf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyusmduqp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtwpvjtvma.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtrqmycczy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtdwyzwcsb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtwqfjszlm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtorjedehs.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtgyhitqmg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtbidsguhv.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gttdxfrwxw.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvcyqiaq.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtluqsgxkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gteetlpniz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtvueyfkjp.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtfvfpvcmc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtmnsdvrlh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtffsnptok.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtftidlcht.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdurxfnug.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtfrbaraww.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtckndlzif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtexrctkqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkfdgmwyx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtsxzxwcrq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtowglqrtv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtneqrwump.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtkfzyfjgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtkpgqwqxl.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtsnhvuuie.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtsxrgqobe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtzwqyjjis.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtwpxubgfo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtnqkicfez.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtepfongse.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtvxpdnrmg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtjyoukomx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gteshxalcm.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtfgpfsznf.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtbuvzflcz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtsmnmdtdi.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtjmmsxakf.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwqcsgpoa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtrdzdxxjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgplfkrl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtlmvisffl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gteefihzlk.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gtzholcudt.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtyvlhmkcy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtgysvphid.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsitihssi.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthukacrfe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtqgnamrbp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtixciacja.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gttzxmrsqk.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtxfwdfbsu.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gtprkavfmw.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtxfehrqah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtdoftyxas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtlicgrhvp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqmtjsas.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtkktjzihi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtuslabomv.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtzemlyhzl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gttmlklprh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtuxkoalzl.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtltmdlhka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfjzbesk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtpvkfartf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtaeemymjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtnbncimxz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtswpfovik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtiyzuakdg.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtnqpisims.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtobspqmnr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtfowvdkjs.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtqlbjzgzk.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtsybzlrtx.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtqoeszufe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtjpxctpfw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtayhtwhdc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtrvhbsqrh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtaddwrocm.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtpcwzebjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtltojnjjw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtmoriwlsc.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gthammiunt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtautvbzjt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtcointfha.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtjbuqmsdb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtfupylhyc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtnfbpukew.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtkytbkafl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtczvvihdc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgkdqopn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtekyjnjbo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtogwdvpjv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gtalqmpoyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtbkbtbutb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtppglmupo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtffwazjvs.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtphxqrert.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtyemddick.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtysgytvec.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtqlbrchlu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtkrnmpeem.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gttsstztmp.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtvjzgxdbl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtdnwedmat.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtusaivyqs.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttltamhmp.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtpsjjrfxw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttfakeuzl.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtxionzygb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtiyikwyel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtnpolhbrz.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtypfewlfn.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjufenfeh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtblzuuljs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gterqmwbbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtbqdmergo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtfgxjkrkw.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gttkvkdrzk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtuznszxfu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtqoehuyfl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtkrepuewi.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtjtamujrs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtnopknqkr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtdqzidbfw.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtcxbknifh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtqvalycfe.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtfmzayhtf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gtecsszpmq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtvobgyfnq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtfveieseh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtulxkjjyo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtldiuoihl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtmoqwqnib.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtkusgojzk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gttkpdiued.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtgyuoqawd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtlmulatny.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtyymcpusf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtllzgmymd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtofbfmoml.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtbjaijjri.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gtadcttejh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtbwubpkhm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gttdvheruv.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtyuvovioa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkgahcrtp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtkmoohivd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gttniuhrxi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntyeftlw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtaxqicyqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtgzuzlhos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtnfumtpvr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtvehypgej.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtwitaxkgk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtoawwxpzn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtmfygdklk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcupfpxmk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtxzsngecv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtqtljlrga.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxxxsbdi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gthtxuqgwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtlymopjyx.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtjnajqilw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtrzroohmy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtpjizzxsd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtmcolxogl.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtoifdbjwk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gttozyamej.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtcldoercm.html


<!-- 参考信息 -->