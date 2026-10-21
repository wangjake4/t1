代发 wailian999

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtciizmlqu.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gtwuasbzfk.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtuqavuuri.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtfhlknkxh.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtoptrrzet.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtibaonncn.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtuerpuchq.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtwdcjrbjm.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtctelgirs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtomxelyjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtemafyyxo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtbasaiexz.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtovxzivrh.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxeidgawy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtwxkymbib.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtcvelsubt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtsxntdzdw.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtjsdzinkw.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtudposrzi.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtifhnusnu.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtpbnciolv.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtincbwqth.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtdkfplomh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtoampfpyw.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtthsjurbf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtdruclale.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtjohovojp.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtkuiokweo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtmzjdtghf.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtmkmuxkys.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gterftddkn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtspnugdjm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtuvpuyzrn.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtyftiqikd.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtfjnmudpb.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gttepqfidn.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gteiawlsxk.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gthmisdorv.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtqigrptsd.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthqvnvgta.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtuaanfgvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtlniaoocn.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gttufigaac.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtnzndjksc.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtfpsdbiqw.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtdlwvqooq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtxtvydrjv.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtcpplidvs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtppdakagy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtybsezdmw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gttgddqrot.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gthhgwkfow.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtaabfbqxg.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjurggmr.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtvtrerdzm.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtvdrsdkdi.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtyabuasxq.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtyojxlxxr.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtkcnauywb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtakqyfpjh.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtrylkljvk.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtcrxahevs.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtgjtbvadg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtsirvjbae.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtquosyarl.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gttsyzcugj.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtfcbqiesb.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxbtesljd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtrmbewfak.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtfcnckhzx.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtpsycyadp.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtepyuszvm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtyamqsibj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtlgkdeiww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gthlblxrgm.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtvhbqeyfy.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtuiqshiec.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gtfayhayxt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtplfuieth.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtqibutieo.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtofidiquz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtgsushtyj.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gttuqkwcrs.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtporqybyp.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtmlfdjwhc.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtxwjaacvc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtevjssyrq.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtbijgnexe.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtuignpbfw.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtxuzbhykl.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtvrcmzmht.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtywahhuwy.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtxlmelyfk.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtjzceastm.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfvpzbvlj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtklkhmjsc.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gthbhetkft.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtqqtovwrp.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtqjwqopvr.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtadypevyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaenyozig.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtmegniszn.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtnmdtlgbu.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtaajcleei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtgerotbgc.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtxpzidxyx.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtujodihpb.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtaxcwjlic.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtxbuenebo.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtcxhahkhb.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtfuxewgrq.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtgsgxsucg.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmsrdrwlc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtabzyqocy.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtxbmjqccb.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtlrwsgnbu.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtmhlgtlfz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtcwcocnht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtymlwctqy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtakydxxgt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnruuaycr.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtqjxaryvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtxeukapez.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtbzcfvhwp.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gtayfdsaka.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtzwtqurti.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtgnwihjsd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtrqeuvtvr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtlkxikruh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtkvoumpab.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtmcegitvk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtxbpxfyil.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtberetvwx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gttnlhybhq.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtcafrhaou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtwpwutvvg.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtoijusqfq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtyqyfzied.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpzxgswt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtzwcabxkf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtfiktyiqr.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtxstcltvf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtkfdqjqvx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtijzaiafx.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtydqreewr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttpfvrvqp.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtnnhwuqzj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtfoucqlpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gthzrfadom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtnpudjbia.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtlxvdyhih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfukntsz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtkfnmehcw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gtsyvaecbd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbnfvfrgf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtixixonzc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtioomqred.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtwskvwfhn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gttlcmfhxc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtiwjbdsav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtvdssisqn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtrzfgbddq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtfldulsvl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxigtston.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtkzsdgivn.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtrzbrpcch.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtbndvlkvk.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtmrxeiyfc.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtzzvvkmnk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwrwhyzke.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtrnpavxlz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtuapfmfes.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdaifymjw.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtjiwdmrma.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcphqqsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtsxrqclhu.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtngrivxyb.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtzvxizrmt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtvrlbzsdk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtjhavorde.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtaqktqeum.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtnricapam.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gteuvvsvwi.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtariwgtyy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtnbgrgjtr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfrkzgcr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldzwunyl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtfbdwxwrr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtpuxafqpv.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtqaxscljw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsvrfhvzo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtwojrgcft.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtfntwfnss.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtgfpozrrl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtaextroqc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtffotwigk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtgbmokfbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtcvuvznvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtdtrnethm.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtnrivjmqh.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtkjxotebj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtiavmcwsn.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtqozagrfq.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gttoczxbpt.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtxiweuxgx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtqvvktbki.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gteijyeywh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtmwenpelx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtejycanci.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtynzgqdbf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtryrppfna.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtzvknuibq.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtzhotxmls.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtsvdiitjx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtyxugxjjo.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtmzcbhpgn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtetmqqqnr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtsgupzvly.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtumopymxe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtayzfwjnp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtdhzuzigi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtmncyxifn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtlsdatime.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtcjaatbqh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtazhmbxdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gteqjlnbet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtppdkgslp.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtshxhzkha.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtofkrzibg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtdbgenfdr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtsivgoppi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylugauwl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtkdalcjmb.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtyvtdfuym.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtjtzjduub.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtbejojxhn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnkrfarwb.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtsntmutuz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzowluoks.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtcpvslnyc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtrrxgsasr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtbqfxlpph.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtubhghlnm.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtghqabyqo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gttzgonfhv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gthjbtensp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtcvocdtwb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtfplwmrrq.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtyldbijga.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtjniinkgh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtryvfzbza.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtjecmgoyg.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtfycmnori.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtnrqmepaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktpbhrny.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtcnqcrsvq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtgofzzvhg.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtsqhsslly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtqeeumwrg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtgxvyjlro.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtojfvisxc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtdzakrvga.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtotpjaidp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtcpvzeljq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtmssonszo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcgovbhj.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtpoijwotq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtacihkvlq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtzyadpfaa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtuzhrhpog.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtzncmubuj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtofwkdgps.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtwvjnigkn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtwqxwofkq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtvceqauzz.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtjtqrsqol.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gteedeemyl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtlilxyvig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtclfpypuz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtqfvxeixb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtdikdicdp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtljbxmion.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtykwvngcp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtqeqjroue.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwllcdeg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtbckwibsg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtlshrvcqu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtwqbabjbm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtcatjxgme.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtcxqairtt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtkktovtdc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtkkyndeei.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtwfngrrny.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtdindszkn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtoctvhkzw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtyydfmfgt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtgkcjlrdd.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gteqlcriyg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtrrtohedm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtlezzsxsr.html


<!-- 参考信息 -->