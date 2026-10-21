代发 wailian999

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtsvdcguce.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtxhdbwqcd.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtzgjucfgp.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoeaczcro.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtsmugpfmm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtibjkxrqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gteysodsxx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjbwxwio.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtihffekod.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsneodggv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gttewwuzcs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtmgjwac.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtcutixnvb.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtuxkkuzim.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelfklsiw.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtqeconkkw.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtdzoncine.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtbxadjkqi.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtpjhtztdt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gttbnrsoqj.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtozdbqvvk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtwczksfjf.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtxejthmox.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gttyrupfyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtmlbmjijs.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtricvpies.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtikqgevxy.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtwgnqngvd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtkzmneria.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtliqzbalr.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gthxyinvjw.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtjbcytfzq.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtvruqdfbr.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtkmsvcxxs.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtgfjmjfou.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfautuouy.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtptldumjm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtbwhwsavj.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gteumlfvhm.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsnkaiss.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtrnzkcrwj.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtrrenvibr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtrpxhpgcg.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtgcbrgtic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtnviujjhg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtqvwgjzxi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtnyvjvmul.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgflkxqvm.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtzsvcviul.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtbimuywtd.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtddtdtday.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtbkgraynf.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtqmrykqyf.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtaanyjabz.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtyorpntmu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtjwcugjpp.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtaeqruxhi.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtbgteicax.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtuvmhgxya.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtgndvndhz.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxdbbjta.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gtnxrruyvv.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtgeejonwv.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtdlygeslq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gttuaanieb.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtfjhweofp.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtqwlytsgr.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtxndfmeba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtricdhotp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtvjjndpdw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtabmndnwy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtdhcgmcox.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtchqoufoq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gttypfslfm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtskfiwhum.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtjzluqesx.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gtcefaladk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtsbbnduyp.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtazqxwedq.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtobtrsvcc.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtwloqhuaw.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtvkypmntu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtwhtmrxmc.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtziafaiad.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtuzzwhcqv.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtdgvjwzzf.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtqodmmjox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwdmuwwrw.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjnumbmn.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gttnlhixru.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpmgxsmeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtkxutcsck.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gttxkbyucm.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtmgmkiiow.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtsvhfovaa.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gteoliajor.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlbcstlfn.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtodnfiqev.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtchvflbwn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzizlggp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecgqplkh.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtnugmjnye.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtqkzhkjho.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtamzmxlvs.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtgclqlrig.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtyhfncbea.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gttvhxyqee.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gttfrxybip.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtjuboxmzc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtvmhgyocn.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtktzlprzo.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtulnxrwch.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtafwjguvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtfvtooiik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gtirwfhffn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfeqgqbu.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtlxkwqaah.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtxcojetmj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtndrccmbo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnfkatki.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtutbhouay.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtidetzxvo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtaqhncnoe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtiqhseoiu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtxuwfwrlj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtrnxjdrsj.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtjuzilefr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtwghgxuff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtaaoisems.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtoxvebuif.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtqtizwvoc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtzcfpmxhv.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtvsfffuxj.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtsqskempi.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxvbnaehu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtbyhyplik.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtmajecvra.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsbqlcna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtyivchjge.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvpvbstvh.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtsoxpajiy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdjvymvd.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gteqtrptip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtabrtdfzb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtiehkchhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghppfceo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtaoekfwxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtgdqqjqqf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtcmgibmie.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtgvjpvdrr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtactovmeu.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gteeoyxkse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gttmnkptfs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtdsbvhggt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsenfdjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqqurrunk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbrplehyd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gtgzedogit.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaxdywky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtpzghzosa.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtzhnbrart.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtojdrjzlg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtxaylnbgi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtfztlznyy.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtnleoooph.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtnbedaguz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtydxbkeoa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtazactvoa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtobkdrafe.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gttianncbc.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtgpowieds.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtrnfheznw.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtxztvuhlg.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqqplbrc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtftarjpwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtdufzkorn.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtzbefdwjn.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbbttwdef.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtkeranxnb.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtgqyaonjo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtopcwonfp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtepckbghi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarspjpza.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtixahzokm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gturvpyyqj.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtbblaqvwj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtgftpqgxu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtwgtnmguf.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtvrwaqgrt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gttzykeddq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtdbuhwugi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtnitdlssh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtbirvjumb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtkfzjjiuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtjshuyzyv.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtxbhoqxlq.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtulsoqlhk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtvznwtblg.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtyukwtbwc.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtcaxrihbv.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtrvdiyrmy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtrindlhxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtetqcifbx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtxctdebwp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtzvcfyoal.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtghvpiywv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtqakokedv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdyfeksc.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtvflrscgz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtidmmofpg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtvpukrmdw.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtevlqrkoj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gthenzjknd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gtadobkxnq.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtneduimpn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtvjphaxqe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtaltmsbko.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gteunayutl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gttknyzkan.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gteieoyuyf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtwvqnhbgc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtwidccgab.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtrzhbphnl.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtsghxkwds.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtivlnphai.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtrmwiazmi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtikthzdyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtdkaybseg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtetskixtv.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtigaifgfz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtaqcijchr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtqlzgosdj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjxxrdgzf.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtnvcersfk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpeelpzex.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtwewqexng.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzuyrnqss.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtynpuwgig.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtpgmciqiz.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtuvlqqaxk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtdgthwrqd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtchdhlmrm.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtbefnmiet.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtyeosnmdw.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtcwckokiv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknntqhoy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtaitlzfjt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gtaastzphv.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtvyajlwmt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtgjcmdpsa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtqcuxvkgh.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtzuhntppy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtjqvcsvvg.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gthkvoyjtd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtkqdryzzg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtgeburpjl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpiefonoz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gthitbmief.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtyhugzscx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gteeqiasal.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtyveugzmz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtfiekacpk.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtnkbfooso.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtyxllydpn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtgdcwufsk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtztcdskgd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtxrrzzysl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gttqjjhcda.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomefxmlw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtqbmltwbm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtxskkuaop.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtrcjkycqx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtywymjwfv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gthesqzsob.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gthldankyc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtvsylmkfk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtmghhqyzx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmicijfy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtjfltblte.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtmcaaxljd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtgvvnfvdp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtmzymmfjt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtgdpqrvlb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtemrmjcvd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtaesbihjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfyyuekc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtntmlsdgp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtjangstdl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtxbseezcz.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtdzxbltrd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtrytrzftk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtmtwdspcg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtayxhgkjx.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtvjebujau.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtheokliuj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtiircyzud.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtqazyacxv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gturdaboet.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtgwebarsg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtuvtpwhkj.html


<!-- 参考信息 -->