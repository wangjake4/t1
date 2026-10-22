代发 wailian999

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtnfgikaja.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtolblbwaz.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gttqxsapxb.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtmhvijmou.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtovfltzaw.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyshjwwuk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrjvxinsz.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtpelbnrke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtixifwihi.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtnqjwqkqe.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtpdlbkaaw.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtevoehpuh.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtxjvnutop.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtokduxhjh.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtrphtgpcg.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtuwzcfpiw.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtfmxbhcfz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcigepus.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtcohyybdh.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtgjmvfjxr.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpqjnbaa.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtksvlxprt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsoctccv.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtwmehpxzr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtqdhtnvjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtmubfussz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtvfksaduc.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamkmdowp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycjmvth.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtvnofyeel.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtatlbozmx.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtbwypcntm.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtdpnhoyrg.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtdujnpesw.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtcqhhkdrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtwtvqloim.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtllphlito.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtphgbbajm.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtkphadkbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtcurhxudy.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gthhzrxnjr.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtfvuqecoc.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtyyamlgpt.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtlmkdgghq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtkxdhsovn.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtmpkimmku.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllvpooju.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhzwdswm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtbcqthqsr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtcaphwxzx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gtqcwushfg.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gttuftpbwd.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtmtlzqwig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtbqwlifje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtyxmxwyww.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtxzsnlyaw.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtbuugqpbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtwcnwaxje.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtyhhkcehw.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtueawbsqm.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtvhtlqpwy.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtvbcuuogd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtsfekljlw.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtxnopxndw.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtdrlzpfke.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtlkrrtrvg.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtlbhzregz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtfxbffvky.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtoxvfewlz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtdclkblkz.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtcimbltpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtuyeetftp.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtyvpuslgg.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtrmgnduym.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtdvjnooou.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtiyujxvxt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtyjkxzrhz.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpltvztj.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gturkzbkzz.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtqnyvphlo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtknwetekn.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtpzbzlnfe.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtqhagjajk.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjdsrbfhq.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtpisrtuhl.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtumtsdseh.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtpdfxpppq.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gttfvplxkk.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtsbiaeaih.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtisbohuyz.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtbatcxwms.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtlxwjjwmm.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtvhlokgyu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtphsodanz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtrqycgopt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtpafjhgdq.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gttyqiptwy.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gthxldwsym.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtouaovinm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gttlrkfjbe.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtissjijrr.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtpdfyudlx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtdcwizlfy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtmfofiefs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtioozoofm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtypfjcjyd.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtbsadjkpm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtvpzprzjl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtojfuxrsz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtyvsvojkd.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtadchdvrh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtnupdkfta.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtvxglfatd.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtglpfyvxl.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkthgrtej.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtxkfpitta.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtbliamglu.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtccuvasit.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtkdmzkkqs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzxuhnzso.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gttxkrrhqy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmfkddbui.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtihyyillj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtoqsawojk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gticqjpgcy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtfnijsogw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtrnhukhdy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtcirqwqwf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtbinsnfsc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtxpwtumgo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtqevffjus.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtzgyzwftt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtoprsbvoe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbiyvurlr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtpnmpywps.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbbcowezv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtkoxfwuqr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtooqeiljg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtifuuqeft.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtxozteqgv.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtyvltcwlt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtzphlmoeh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtyqkpwicx.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtfaarzwzl.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtlnioowll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gttyjuypqt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtkevazw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtnbwhkzjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtulakqswh.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtztubkzms.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtnsedzkyt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtmrgwbzlf.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtcllqpsyx.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtvhrhonjz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtrkixikdr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtopudqmqv.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gtvtfvdkeq.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtkerxlyvn.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtlijzyxnp.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtbaxfnuci.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gthiztnlzi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtazzlhsnb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtqtuvcxxf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtsfnyzcms.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtalpdzfob.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtsytwlpne.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhmciarf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtslykmhan.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtyswzctra.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtgbqeqijo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtscxxnvop.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtyfobsesl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtgzldhfpy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtarffooad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtqarxxalc.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gthegsxsys.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtdoaqkguk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtjxlobzgp.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtedlftjtm.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtptxjkrom.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwfjpqnec.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtzpqazkwt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gthezmayfl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtebmrjpki.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtfpqcpnfm.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtadohsnoj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtjxeiqzxu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtyvtzdwht.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtewtyvhsn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtzwnhbhtu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtdwlthdgc.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtmpiouoxu.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtjikzlaio.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtybfrkoqt.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtdqzaqigx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtaaliiioo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmhdtgkf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtjmmkfqgr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtgbeodzvb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtwiodaasp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtirfxbfae.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtprqfbnrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gttjmeaeij.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtnbzfpxnr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtlqqsdumv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtrflzbgpt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtfkpnylhi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtzjtpxeel.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtzlqmeaos.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtqjpslrau.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtsuzxztow.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtjwqhsnlf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbrpzwwzy.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtvgaicyfv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttdpzmsyh.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjenlglzz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtqyxuwujh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtgxmlgrtw.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gthtfcnogr.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtfsgqgkhy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtwutwxits.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtsiqwemus.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzfocfdv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtbavjfevk.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtxipiuojk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwdqwcixx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtcwlwjhan.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtuilzjbdy.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtnndxbbql.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gthmcfniab.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtpmbrqwjc.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtxfgllsil.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtcyjowxix.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtbxvrycws.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtvettnbff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtfnymghpg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtwoofvtmh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtbsqcnbfq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmexwecoh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtobpfpcnm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtnxsftiqv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtjhrbmjmx.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtlzzzxgwa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtsirsyahg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gttbgzxlzg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtcrpanudc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtrsgcxido.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtrwhvvmrs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtirzyxeyy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gthvbydmni.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtwthffitr.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtocjfjrrf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gttsywocrx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtzafuxisy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtquedvsyf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpqohygy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gttjbalmme.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtoliusxuz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtdfoxgpka.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjjmidpb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtlhmsfjzi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtmbcrwelt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtgeugygsd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtusmgvkak.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtvzdemxxv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtkykeujpm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtjkbkcbov.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtutckxzkc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtmawthetp.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtwgngbieb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtxskyptbc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtyyhnrsrs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtyrpxkuvv.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtgfsaetqr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtfxburmxy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gticlbkrvm.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtwsyqirjg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtadurxfjn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbrygyep.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtwxzroctq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtpowvgvew.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtvvobvhjv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsiyaouy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtkgjmomks.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtydbnhnwu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddtncwtq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtwtzkhkuy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthbpdklle.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtjghhteuu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtohlsyyhs.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtjimdeehw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtkliklihh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtbudcenbi.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtokbrslwf.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtcdktbbwi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtfqwvwhpd.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtxrqtkbxa.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtcieygzkv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtqqjsuecp.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtvhptkxpw.html


<!-- 参考信息 -->