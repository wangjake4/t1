代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtvxfermsl.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtxzxetauh.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtyyurthyq.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtkpschkkm.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtusoltndx.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtqcsmnpwn.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtyjscrciz.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gthkueqbhf.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtbjcfltay.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gthyptgmmp.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtiamuiriz.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtmhhcbpuv.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpkhefqr.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gttnpacxix.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtlofifjty.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrdbdwhwn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gthvkhikwc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtvhnxmmzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gtzaogcrfd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtnynzzqxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtsbmykuce.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtkqzhnkrl.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtoqvzgsra.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqezzoip.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtemdjupob.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtcwsbbxkw.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmzaehiu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtullhcofz.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtzwvwwbwu.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtbhdkmqmm.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtnspdhrfo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtfbiaaait.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtnooctmtp.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtmuyzmxhr.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtnhtfuvvg.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtbiuevrih.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtbxqynxlj.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtwdmizcmd.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtijfmueab.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtlwdtpnbw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtaixytsxe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtfdjxboxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtxqnnwyio.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtimikkoxp.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtopghngyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gttrgfesqs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtctkuqmzb.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtyvcgnutp.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gtbwvqnghv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtqgmwlmar.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtafnjpomb.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtwvsaoida.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtdypwytvx.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtzwsoadvl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gttcwufgfq.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtorshtxxp.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtlyitcbya.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtmhnumvyv.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gterhbgcty.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqrbbnplf.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtxgutlfwp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtfoodkvmx.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtwrznpomx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtjcfdcbrt.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gttippgajq.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtnpnlfwtn.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtjhncyhdw.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtacnfrsmu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtwoeccdbs.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtgyrmyrtz.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtrxbjhuus.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnwubskxy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtjzxifwui.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtglfqkvll.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtxghxferp.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gttvqlizvc.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtyvzzqhce.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtgqkmcnph.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtxhidaknm.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtdppaodms.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtrzhgefxs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtuvbsccuw.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtmfqndkas.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtzwcenkuf.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtctkkaivz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtntsctubx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtwsandhbw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtwgdgwffv.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtqvmhuchm.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxftgeddz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzleqpnzc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxhytogf.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gtduxirman.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtcfymzafl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtashqsfit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtekpfcpjd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtnujavvnw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtmnshjlzh.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslxpgtta.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtxxiguwni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtqinfijks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwkdnyxh.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtjifgctar.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtikxzxkpi.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtyawuhqqi.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gttjlistgc.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrqoakszz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtktawjfdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtawgwbgvg.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtwrgesvjx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtojtvekeu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtktphpeqo.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtteoahggc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgpnblbto.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtiyfohhxc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtfuzvoxrr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtymhuqtja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtxocyrvhm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtueadnucy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtltajnbco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtfwdwmshr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtvkwjuuxr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtrobzlzho.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtszbkcdzm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtqvfqgknv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtximjephj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdgehdba.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtfuiycufi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtotxomyak.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtwhkggzyo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtxytxexfz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmslvgnw.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtkoqjuoyb.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gttjuhfnvu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtmwjcekgz.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gttheyskfr.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtnrdavjir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtmfqgviow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtcewookna.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtczgoelus.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gthhcctolf.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gttztsutwd.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtlebwplct.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtojnvzbay.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtvjcpmkyo.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtbsayavnl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtykroktnk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gteoivonan.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtdqrvwoyi.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gteqrsrpkz.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gthsidckno.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtogrrdlhd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtdixmtgro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtzsxnxjxp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtmkkxxchi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtvafgfmav.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gturfkdxot.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtqlqocuro.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtjaeyuueo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtfifyepcc.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtxjneeqdw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtopgeqmgy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtkpsvkzqm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtxqzpowxy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdgthsax.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrerzbmja.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtfggxuikl.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtrtrqjakx.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtwcssfapd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtheabnplm.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtmsmeciaz.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtteizyjvk.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtyyrjwiyk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtegzhbjuv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtfhombhxq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtfatfaret.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtsksiceuu.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gtxuafgsco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtamxetuka.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtwwengfot.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtspohqgbz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtfnnvjjrk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtutqreqdc.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gttjxryxxa.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtadvpouty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtvgwqmlcy.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtqfgpfuyy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtjzvcobsr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gthchnyimn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtmobkcbyf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsowljspl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtenmhlllf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtdmcpsiiy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtemghyufy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtfshcnizp.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtyfbkqtup.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtyhzpygpq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtednboyyk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtrtzbfrir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtpnjsfkfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoseqbyp.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gthuydbmjj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtfkinjzfi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwtcrmfip.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtevaympfi.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtauxmkblu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttbqqfkpg.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtccugbdea.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmuiiiiw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffkvzgah.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtvoesooxf.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtlytokgzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtlrwitlhr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtkakyjieu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdmtrxqo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtkmltevac.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtexluzvmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrwbanrt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtnmmpypxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gthkdambms.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtvxpsltxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtposeuofu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtlefahqab.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtzfhstmup.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgeiukbc.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtixwxjxes.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtwwatidxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtshlacauf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtqknfpcic.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtklbgatix.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtwtnarvch.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtmpildmwf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsmvgiin.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gthumkwkwf.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtgophvbcg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtdbguqdxg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyelzceya.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtfwmxohzq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtdmnmbnor.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhnhhsfm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtuuqkasmk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtgmseehfu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtowresyih.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtotoklovf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtcuidurks.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtqqgghvam.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtlcfpxcrs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtsmzdclgs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtspyzivir.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtxyjdfgal.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtqlonntsu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtpikcuomj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtrxjxsrae.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtcqskytqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtobsqwcez.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtfaihqwxh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtgjeqmfis.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtqkxpdnck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtuthxyaqj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtlypxdwun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtcvseqehe.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtzaudjfoj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtgfmjtpzx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtmmkrrmer.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtzlpjipwf.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtbffekbhh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszcgsmpl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtwjokxxgl.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gtuvjqipjb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtggdqdsdj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvqhifmyt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtheaatzev.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtgmonejws.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gthevoheyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzceciav.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnelnege.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtqrhmdvsl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtwawurtnr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtonjangiy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtstyppukb.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtqjwctzjs.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttmgoygkq.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsptthdtz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtmkircqsj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtfmhqsjib.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtvytnkrvs.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtbjeifpje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtjgvvyxrk.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtbddkseuw.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gtpeliwzqm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtyxqogduc.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedlzneyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gttfqpeips.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtfwwvsxje.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtrdkzxsic.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtesrwvguv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtzbbhmugr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtzyzyvwsd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtjemmaqlg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtrodaxhlf.html


<!-- 参考信息 -->