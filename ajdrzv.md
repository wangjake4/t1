代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gthohusrvq.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtvfjqjabg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtxliavgnu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtpgjrftmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtfayeanrr.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtvsughtyq.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtjfiepqya.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtrnpgtuay.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtsuyosise.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtrzagnhzp.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtrvpgibdt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtjibfufvt.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtkcdxauof.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtuyrdyibm.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtmioonvnm.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtktypvpyy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtrbhmnprn.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtnukxpuvc.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtqzahzlqp.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmcbesjhu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtokkuztsi.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtxdljjgvx.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtbusrqpxa.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gteaiqyrtw.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtfspcwgdy.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtondmcvdm.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtmbltocnh.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtklinwlum.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtwxxfwbgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtktwplvhy.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtwgiguwuo.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtasywqtsc.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtlgthcmfc.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtzkqucrqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtvqnqslcw.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtuupunmrp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcxacmgat.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtegubhmhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtqqoyjedt.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gttigtgyor.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqdeziyh.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlsrahcj.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtyrxmgrva.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtwjcbfezs.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gthgvklaux.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtrqbhugkg.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtvcogtdxj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtvmbtjeya.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtiouijhid.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtegempoea.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtofkcrtwb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtxfsraygl.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtljwpsyrb.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtffjhnewu.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtsjywsuky.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtluidsrlf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtdbutpcnq.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gtpqjprmoq.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtqgjxrjuk.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtscjmqaaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtaqwhdsej.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtcyrugdxp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtadyrcwql.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gttbthjpzo.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtkrgeqgel.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtgctdbfqh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtsnoomjhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsjeyhpac.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtenofhfnu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtcblglnyq.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtjwwvgalr.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtfkakxlzo.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtfbzkbrpo.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtvpyrqbfi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtlvodvxly.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtewsnpqsl.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtfawtizab.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtgfoyaeuc.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtjnzjwrpw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtuanpbesz.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gttxvgboxs.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtmlxqbepa.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlkcfzqyv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtzclfurwv.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtwrqflyil.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtjeoexhhp.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuevozryy.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtzrnycuip.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gthpiikriz.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtxpnwepaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoqzjjxc.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdkynttga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoufdeuoz.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtdibtbood.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtzyynndpb.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtmlmxkntg.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gthdarrnpj.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtkaftkzpf.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagioexlp.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtzlhvwqnq.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtmsxwughx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtvnvmerkl.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtocriyxbw.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtgvmhatvh.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtypedwkyj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtfnhvcayt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtwagvjzvt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtrcouufst.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gthncmdoca.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdlrxlyez.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtxjghuzbm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtbawbmlhn.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gthdiwowhz.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtzsoueonw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtbqlznmkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtktumufag.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtaimkrttu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtjbsxflfe.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtrzirifbc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtqhfhojva.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtjrfiauod.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgdbltoo.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtqtpcmfzv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtskluaiir.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtblccxexg.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtizoazlex.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtldmuaqlo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtohajbbpz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtvkfsbwjs.html

Ruby: obj.instance_variables
来源：http://dali.havefunace.top/Article/details/gtkqjykyfc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtbqmnjllo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuoxnsnwv.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtfjziaggz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxidwnwri.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gthrqjieit.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtlmywqmkg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtfsyppvrx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtzqgchkfg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtchhdddka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtqleafitm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtckjhhuul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gttweksiwp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtmmqlaktn.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtvyzbdfji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gttlzztmku.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtcbbphtay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtqaduhnkn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrviopjve.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzaskzzpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtltbgdsvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtoogqlxbk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtoqqixeot.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtgduvecmd.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gtnkdfeglw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtycedciqm.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwzqlxpi.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtfenbixsn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtwwlvejkb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtgyjwoaup.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtncerjzdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtvcbufzcs.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtcqzfjpmt.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtcluwptbn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtvbrkfbse.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtkrqabwew.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtusztzqjk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtuygydmef.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtsbgctvde.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtryxtzuxm.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtirvemxao.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtabuvigvj.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtbkrpnkfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtdrbrlrwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxmqvjjvn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjfbsqgpr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtldtyeszq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtwcffognw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtcbscygli.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtoagnnpnj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtgjwwdlqn.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtynqxmgvj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttiomenz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtjjjgnwzn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gthntwqeum.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtbrzavrul.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtugaqeoto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtarmjbqof.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gthedlumif.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsaqhgvq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtkklfgemp.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtyqxpbsjh.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtckyqlfrp.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtovhdivwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtqkqbozha.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtyacowcfy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtlcahqcvu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtnybgagms.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtmblpxfke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtfjnbtrje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtjxjhpfpx.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtfhkesyyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtkystqhxt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtiwfjfndl.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtyhscbfgq.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtjjdmynge.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtobxzokvb.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtunvdfyso.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtfoumqtly.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtaxajjqib.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtiilqudbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtpstnramx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gteiflgelm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gthighjzdl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtqiccfotp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtjamxcbwn.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtsfpkouyg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwbiekhw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtwhzbrckz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtpmwomzlr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtbtdckgqh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtdnlqfofv.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtukxyfekj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtuxwnelvz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcbsjvbq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpgfmkqht.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtycfunxyr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnuuogowd.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtlfovqnnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtombovtyp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtanizsefu.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtxqoazkoj.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtydzfpapk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gttniauvoa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtjxwvtoyp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtvpedqame.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtrocaylsr.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gteuiraehh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtgsgyfjcq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtosyqwdhv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtzfwyhunw.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gttokswgys.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthaiecjuh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtmhfdpgtf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtadssqudw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtbwtqemqk.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gttpufbtzm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtqpvffcpk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gthxsndffs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gteydemrvz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtxumyhzca.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbdtamxt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtbbyhwykg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtrtgkzgrq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtpvngcenk.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtfnuuvqxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtiptcznjv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtbjknvicr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtiodugjhe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtemgykkaz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtktgpfkrg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtkhzsnfrn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtqrgtrnuv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtjawmtyfs.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtvxyhexqt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gthkyekbpx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtppgcfnik.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkwgljwj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gttamabelv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtarrmhtuh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtqhcyjfxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtlgjrgvth.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtxwrodqez.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtwgavozmz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtbtwsfvpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gtufkufsmf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtypumymfw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtgufjufgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtcidttjkk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtoeyykqbz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtdhuzhrqi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtfnkekhvr.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtbnsfpvee.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtixmvcioz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtnawuubrp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtrvdhlkzc.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtxncwbifg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gthzohjxon.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtfsciihhu.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtnhglvdik.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtmqxarlhn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtonmryeow.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtaiiyoxkv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gttepjxqar.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtjpjhchuw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtknisdivb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtneglkuae.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtlwqejjgu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtcwtujlbj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gthdwybxzv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtawcpfogu.html


<!-- 参考信息 -->