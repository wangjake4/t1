代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtdehoktaw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtowejggpm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtohckprxl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtxlbgtprn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwoqwruy.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gticrutyrk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyssmspvd.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtnornvrrv.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtkwwrcfqv.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtmduguyhu.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtojcsfxuw.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtuewijxnp.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjsdedtbb.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtshsprrkl.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtwhwgdfid.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtvbyjfmgd.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtvkiqwulc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtujgtqdqp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gthnqfwttf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtylxzwkmu.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtcbevulio.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtkqzlcqel.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtgeobezbw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtfswyztew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtxyjakmqv.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtbkdlomtj.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtokylvugi.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gttqpzazeh.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtvmxdwvtf.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtttwwjbfj.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtfjfdmmcz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtxraozbpn.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtypbajsbs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtmcscrhyk.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtsenxwznz.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtjinfczel.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gthfozlmvw.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtsxgadoto.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtgzydpyat.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gttwerlpfe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtmeuxkqsc.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtzaqarodq.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtlkdjhclw.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gthhbosjsu.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gturdnxjtw.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtawpbvqkq.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtmpdxlpkv.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtwdusphol.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtxibbhmqe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtlexvioiv.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtawzmapel.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtidiogxro.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtpxulmtlx.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtajhdpuwe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtpabpbihc.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtsxluheql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtvvfxdoqw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtfmubbxaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtpqflljxi.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtxbnqqztu.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtucdkmacj.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtuuhcbjdx.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtchdicxmz.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtoezonkht.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtmpkupchx.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gteplgezcx.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtvtysqsqa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtgeeqyspx.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtvpqkmglh.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtibkwjqhv.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtglevfmnf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtghnqysxo.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gthbhzdoxr.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtcgbzvfhp.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gthndbisoi.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtunmbgqxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtkwodgsgl.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtrngwppyx.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtxzaotixw.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtcfkaktbe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtpbinofqp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtmygtbwjh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtjioxwyqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtlmiqripp.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtjpvzrneu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gttyfxkdfi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtspaixwmx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtonqkrdkg.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtrvyrjgpz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhubnewa.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtdyuvnrul.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gtztkokhph.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtqavskzno.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtqhufoona.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtyduludhf.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtwhxqgtxx.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtkkdavxeh.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gtxornbdys.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gthhgddqzg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtyqtslwkz.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtmmedwqzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtiprjbzoq.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtpudnjudc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gthfiwevkt.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtnqgqvzxf.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtstnknoqd.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gttxdhvupa.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypfypsfm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtemfytowu.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtsrbtkutq.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gteuosbwod.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtxzfnudfh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtwkznlhrf.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtqeeyskle.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gterojgrzo.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfasksog.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtxaoaybwz.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gthblusmvo.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gttxstkwdn.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtznpsfvdp.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtliiocyqs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupdlshkb.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtegcrpzzr.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtlykqrdcz.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjhutlae.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtqsdbpnuv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtpkmpurwu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtvakwbnyb.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtzdlayspr.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gtvuimmrwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtgbtexqaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtydijjwqr.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnchscjvr.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtpxeuxbnw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtigicsadb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtajmfoatj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtpgcpostv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtirgwfgmr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtgtvwojrr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtgiktjdzw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtniydumai.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtxeubhkyw.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtojpeikyr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtqcqzmocm.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtcelbbnmx.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtvowtxkkj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzjxxybdg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gthfzolwvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtfmoyzzos.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtskpqwqpp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtyylwxqzs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtomzltdph.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtnsjvplyy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbnkuzppf.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtvchxophp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtlzephqwo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gthggziqxy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtwwvldoeq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtphmgitdy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmawzadse.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtumbabvdq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtouqluldt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtligigyxp.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gthxsezemw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxlimfgv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoqfhflvy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtasovavtb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcajkkpdh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjrfxslba.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtktbubjan.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtyedyleig.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtwlagiqqn.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtnfxcxzcm.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtlcsiugfz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtkoplpews.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtwjdcybgy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfjpjfep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtcwixvqli.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtswrguggj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gthbuhkdab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtivtvnkjo.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtogsbqlez.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtepdksfww.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gttiolknog.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtcjkhbtcm.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtyfmuvgay.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwloeyeil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtezioalco.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtwdcxkzmx.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtjvashpqr.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtlslyqftf.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtcqwfnayv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtfsipckxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvudxeikd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gttqdrmjpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtomgpvvwd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtuqquzxlm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtvsybqdkq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtwdgqvrgq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtwyqlixam.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gteotcxtgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtndzrcabd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtybbejbfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtdpapnqpe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtsizikkgf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmnhirey.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtmtsanlah.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtnolpvmdy.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtdbmwphzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtzgslacir.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtcqyjlngq.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtdmfdwftq.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtjncibfem.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtmitedeec.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdueujlwc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtpkkxayxb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthdvpfwio.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtyoudewlp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtdihfiuri.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtphhrvvqk.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtxvcwxonv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gthatirtdo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gttlciievq.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtihbqvwwm.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtmeoubeaa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtqtqdygzk.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtsnwxbrki.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gttqmmqosj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtbohauuxh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtzkeecrqc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtmepcxnpf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtitpgcfcy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtrkdndjsl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtjwvvxxtp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtkthmomkt.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtmiycnjwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtghadxxqt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtoqlfpklo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtxdbtwwxt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtmbiepyaw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtaxonwgud.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gthvtcelnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtgywmlvva.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gttrykdsuc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpbysmugp.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtikpycayq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtuckhpyuj.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtbxdckfqc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtnpdxzzog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtkklqgngd.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtavokicde.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtnqpvdwes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gttgjhjeda.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtrhauzjph.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtaaroqelu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtadcqqtcc.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjmdlumjj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrwkuyrdy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtudyeqnxq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtwgxjtixx.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtzxrhmpmu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsezbivvd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtkkfeqvxw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtrmshekyk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtfbmhvvzw.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gthvwpmjwq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtswfugydc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtyhwpskck.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtvakctemu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtdkgrimxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtycnaluzp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gteciibbas.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtzwppjwmn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcbvrqme.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtuvitncxs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtwmkehotw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtgfgvacyf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtgjekqlpr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtuxqqqepu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtcjgwarzh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gttdtyhwju.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtvngmaxma.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtkmnaldiy.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtjaymwwnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkujmyfss.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtrtdcuetd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtwiawgdrp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtxyarbcoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtpbkvsfzh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtcvhokhyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtryxssdng.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtakoxryqt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtkpedeuhe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtspwaqcxe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcexumzvw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtsluhqqer.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtpgvgaahq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtoefgjuky.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtycriphom.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmflmffgm.html


<!-- 参考信息 -->