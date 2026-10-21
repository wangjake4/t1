代发 wailian999

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdvzzvhtx.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtocaxizng.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzwntqlnh.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtxdpmtxgw.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtebujkshl.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtbnjgmhru.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtheuiwqjb.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtffuyqttt.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlzqniega.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtjplexfvh.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtcijtqouw.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtcekmrddw.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtblbbgvey.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtzgtngdfc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmurwyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtjugqdbbw.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtxrwomahj.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzxoggrcu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtrqmtrkxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtgdlbdtct.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtntvzwvgy.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtrumxfjue.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtuwssbxnh.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtdoaxlhjj.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcofjwhyg.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtbcfgcaew.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtoaxzpgjt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtvlgrwjbh.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtaquugdxs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtatpcbnwl.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gttsiscbjo.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtmxmimwma.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtputvaucn.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gttccdiffc.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlyybgizz.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gthwivsjve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtmnxhqwel.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtocyafreq.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtesxscosz.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtejipmygz.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtdpvpidbh.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtnkpkdmsn.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzvmyuqg.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtqburyzfo.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtggmnzmul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtzyjfhhjz.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtajcnoytt.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtgcrmzhld.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtawsdhfir.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtwrxnamzs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtbzujovde.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtntiizjsa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtsjqtquqs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtsnvwpgay.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gthnfvbdrr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhlfafad.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtgjntvuyz.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtqiarrpkw.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtoncknita.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemthpgs.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtvauoyuvj.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtmiayfpao.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtxyazilto.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtcknwhjnq.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtcdrftpsc.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtjokeghht.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtntwalqaf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflmwggcb.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtmjvjijzm.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtpkcxmqri.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtymdbmazg.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtqtghpdxu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtkwuovblp.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtmugnauyb.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtgadrzxgi.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtkqkroblw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gtyncithfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtuycpwbkk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpqhtffq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtbhqrzxdx.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtzvgkpjcf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtfonrxhrr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtygmnstrr.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzccfbnaz.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtidibgzit.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtduszkzkm.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtlkawcqtc.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtkaystnqs.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtyokmwvej.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtlojmferv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtqkjkdbxm.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtuqbedqea.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtsftlqowb.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtpcpbsnij.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtdxmvnaar.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtlfwyakge.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtzdflftkn.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtbpnemgtc.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtgthyfatq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtepdrmtkb.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtygwcwytd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnedxgqtw.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtgdvnvkse.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtudttrkhd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqwxzbaht.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtrfwqtgtq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtjommru.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmdczhwue.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtkziirgzr.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxqpbyqmo.html

C#:   public override string ToString() => Name;
来源：http://dali.sysykeji.top/Article/details/gtdbskzqup.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtmtlqegdj.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gteqbhfcye.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtmmkrmxwc.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtjrahurrj.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gteiysewuc.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtizzoengl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtxvvgmvft.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtgywfgdkp.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtrwnvdtcd.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtngiolmfu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtkcuzuhim.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtnijyysdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gttihjcves.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtgioovdwq.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtkwswpvsu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtaxrqktak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtgsidxwrn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmbdbycc.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtskbnbjqj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtvrkefoub.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuixgcuxg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtharsmfev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtfvfmkxft.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gttmicdsfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfyfpmhe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtafprjvko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtzvjtegdx.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtgjfqwynx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtiznxsxra.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtfsupgmzk.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtssuqkloc.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzramctnl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtojgruhgc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtqsvrkiea.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtekrvmsfr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtneksztgu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgrilrnex.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtfiordhgo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsqrgxdyh.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gttqvvluqz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtzbtygayh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtkygntbju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgwbguyw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtwgnfdqqd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gttuetgcmj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtuzthboca.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrlhepye.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtgbluwnyd.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtzhetnqus.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtsddzuohb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzgreqgeh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtgdclypnv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtpnrtkamy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtsufuihvr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtuotrwbao.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtxjekenrf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjllbitkj.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtgdoweghd.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtaysshndp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtocxkqblm.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtgkqpzqea.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtexkkrhit.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtehngvtbf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtkfhbatlz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtrkmzslmk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtfzfsgpjr.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtwvisodpi.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtkqnpfgng.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtdjktcrbm.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtwigejohx.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtyzispdnf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtmcmciojy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtwgdmlovn.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtywibteld.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqxupvqz.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtoebtgeba.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtodasghai.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtachtvogu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtqsvqyhci.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtftsdmeyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsjombvpi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtlhmjrtbe.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsketmhh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtbvuobyyp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolbmraad.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gthacaysaa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtaccdaqjt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtooasoeyh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtnximazhn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gttrquzovm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtlflkvlhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtvaowppnx.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtorvsdipl.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtilycpblv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtvmfnzrjl.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtwfhcskjo.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtzdomdpxj.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtxhldhgzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtaekkymdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtkhkpnluz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtanppdipi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtkyganpfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtdmfyswca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtdkrygotk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnslvgmpf.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvektsre.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtxbqkffhc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqmbktun.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtvimxvhbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtilrpaued.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtndlbvdmd.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtrxssylbh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhihecna.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgentgbax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtohonuvto.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtvxglkzka.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtmzfskkiw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtgrlgkvcm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtbgtkzomy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwudnpey.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtlqdasqps.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtrbvpfari.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtxodwxwqn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtnimvllsz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtmziuqisi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtkobvanrj.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtwwphaimh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtbywsglmw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtlucyteyf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpaqnolpg.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpdexgqo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbqmvyias.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjkbsgwp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtpmztrepu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtebodutyc.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqahpxwhc.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtdedkzwsn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtpgnuyhzq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtoiujwboa.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlwsxvuo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtzkhrkcmt.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtbldhezuz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtjhljvrvq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtbjlyumlf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtxlpxfdbo.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtkuuhoccr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtoknknwyj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtpsenbjbd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtomasmkww.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtswhuefxt.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtjhyejpth.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtucwkjrnu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtbcafqspq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtugxjdzer.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxbiazkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtsgxgipkr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtzzinrmjc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtcgjzpyov.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtcltathvw.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtwwwhttxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gthsvfpfzr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gthokdwbio.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtlaspnijn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtfwtgpnol.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtvyepxfvi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtbvuwiikg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtqxomfeju.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtwygrbhku.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtuxdfkmir.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtkxmmqsit.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtyezyxevj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtkidomngo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtgfnctzea.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtnugcwony.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjhhwzyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtrmlmqbwy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gtyzqmmsms.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtoniejxis.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtsetxmhtx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtmndwptcz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtqfusvjcj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtuxxcdsxh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtobdnvdci.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtyuzzvljv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtleaxjzsx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gteueofqwp.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtxucycpsq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqgacqhl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtimaiknlc.html


<!-- 参考信息 -->