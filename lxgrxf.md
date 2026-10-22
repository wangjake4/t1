代发 wailian999

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2ivdzetim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2xcrxdwnr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2uqgwrpso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2dbcaeyef.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gt2wplwmowk.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2plwvfbno.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2pqdtkwxm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2xhfoyqcv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2uwwlvoei.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2ykygvsbb.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zmivdsvp.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2gjohcswo.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2mxzuprhg.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2invmxdhm.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2adcqegla.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2lkvibqkk.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2htgnobxp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2wnyqfljt.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2vucdiena.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2fwwimcmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2oehvyrdt.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2dxubcryq.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2wansgipf.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2hunvosub.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyqnqfxb.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2xyjcpgxc.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2bhbxxgub.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gt2lejqoswn.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2lmnckvaw.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2dowzpdep.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2spjlxhid.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2mfkxhysu.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wodbgdiu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2kytgbhbz.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2wotpflbk.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2ylwmmpol.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2svehhitj.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2vulgbdnt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lceozvzn.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2plvnwlie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smwtqpkq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2sqmrnvrw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2ruknasjy.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gt2ilbsjavv.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2fvuqufdc.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2hqbgypkc.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gt2hhazgbuf.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2fcftvmfc.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ymjvhbul.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2mownwvdt.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2jucjhros.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2rauttvlc.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2ckwobgqi.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2zimzngep.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2lazhttje.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2rqvlbffz.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dngrjryz.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awonzolf.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2hpxcbkwv.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2hdewqppq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2jkzudrbn.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2bvqnyxwt.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2badrreqa.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zipibbfa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2ycgswzlo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2aodmlnou.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2irmrjxgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2qhzwuyky.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2dapcawfn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2agcppcpf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2xabqgzpo.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gt2ypsleqzq.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzdtgjpd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2uwzkzhgz.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ruqvrycl.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gt2vrxswpja.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2pbappzbb.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gt2tlovdvno.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2soveupzb.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2iyuzzxrk.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2utoachyp.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2mykzvpti.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2dhkbthrh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2pxfrsybb.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2pqyelsml.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yzewaoks.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2mrieiotr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2crnquuzx.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2geentgxc.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2kbzqtltb.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2vftpketg.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2mzlalucw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2aqkupypw.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2wafyijwt.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ddbbaizc.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2tvhfglcj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2iuesoiyw.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2uaruzdwv.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2wamiiyob.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2lmntrucs.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2uqmyqvfz.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2iojlvyzd.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2ehwlxqom.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2pxggfxqg.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2kbkebebk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2vjnyiqbx.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2hkmiisni.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2pilgaard.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gt2aqxhianj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2evkoagdv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2zezdjhqs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2kglhzbwq.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2ozszodxs.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wiytegvx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uencwdll.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gt2xeyrgrru.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2netruclm.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quuopmfb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2pnluyclu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wbktilqp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2fdcunpne.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2tmytotdj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2wxhxrgyl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2syilwvmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2lnxbyhxq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2sqgwjlil.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2qwxwbcoq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izjyoudi.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gt2htpzhcby.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewzuztvo.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2zdyvjwer.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2jnsjlbsx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2losiskvz.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2lakzzwpw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2waqlvzvj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fiamtrar.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2scgvrmlo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hoiqlrmt.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlwjmino.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2tovqzieu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oizgbcmn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2hdtecion.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2ucfxvvpk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmujrgdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gt2sircoujl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2odyywhhm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gt2plzjvcoc.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srjqnefh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2ydqltlfr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tyrurnkn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozkuzyrg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ebbhrwzz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2grhlcmsm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2rrnblrtx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2tqqrmoss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ngwalbqa.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gt2jxxggesx.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gt2iansluwx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2dngxmvvc.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2lklupiya.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2ilcjqzod.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkncddkj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gt2wovlunbo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2wyvmtyry.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxshxxpf.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2kvzjfemd.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2ylxffpmu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2rrvtrqxy.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2fdrqmqxt.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2aolgeicu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2iwqxmgah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2wcangljb.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2xaqmzhcs.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2byrzgkqy.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2qedjumci.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gt2lsqbvtbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2dzactmjs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlrjjtir.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2ybflnkjy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gt2jwcnjtmc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2ezptqotv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2teqyytbo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2tubrjnve.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2ujisopth.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2crhhgfkh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2ymevqtwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2abjwjyzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2nrnkomkb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2ioprjlat.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2inkppkhc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2otvdujji.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gt2fvoxrdea.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gt2vxhjvhuk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gt2yfytkckf.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2zxctcvsb.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2igqlzbdy.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ugpnqrgc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2bydpcyza.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2whfbesrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2wrfemiql.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2rixvgskm.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2lguklsyn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gt2rqbcredq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2ulrtfdff.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gt2kytfbxky.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezqrnnjx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gt2qrhznrey.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2usewswgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2uxtjixgt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2nphfvqva.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcshjyws.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2lggrfppc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2bmwhuszo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2rmwpsxdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gt2tdmjbqom.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2fepwejhn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hujlnbuw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pryqmalx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2bcakpoxu.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2xkoxuqpd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gt2gyxtppyx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2klfvcxld.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2suqmyibs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2uigsexbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2zltmzxmf.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gt2beueekbc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gt2pxrbssec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2avsbfnka.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgbqhpto.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2pwdvnfsd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2stsmzgim.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2aaxgvaph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2aimpjnwj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnpexpkx.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2ccacmdom.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2ujonofvl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2xexinest.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gt2rxvmpcgf.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2byqlumgg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2tcaukrsb.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2rclkdbtg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2ppeuimxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gt2fiupvvrj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gt2ouybjbfq.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2woxoioap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2dccqxcvv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2hbuojahb.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2osejvvgq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2rklkxril.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gt2vuuzwpja.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2wqvikoiv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2dzrkxlpt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gt2omtmpmrl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2owbgrlva.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2nszwbqcd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2anyxqiol.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2yisjyweg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2jtxoblok.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gt2aaieizrv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agovmuqz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2dgtmijnm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2ihpvaqsa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lptlczbg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2wcrvbomn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2lqiyxzgp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2glxzxcda.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnksojfs.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gt2rhpnrmxj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2zyoqvfdb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2qgzommrz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2wwzxsaus.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2ivkmaneu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gt2adxebnbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2ohlbzumb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2hvqtfjzg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2pgpqhwxe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2qjtbetls.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2kstszpee.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gt2malwfqrw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2astjlvsk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2ggfcqizx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpujskdt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrlkhmjk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2pmlwbkvg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2nikuleuq.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szpytxor.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2nkdsfrti.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2putqfiwu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2bpendrwc.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqzlzefp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2ujatlamn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gt2hucnyctx.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2enhcjcyr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2wbuazhtg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfdyovpq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uknidmfp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2rlfluslb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2mobqkyoz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2xvmmwdiz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2sgjreqtk.html


<!-- 参考信息 -->