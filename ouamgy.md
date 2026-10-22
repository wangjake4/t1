代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdkshdbck.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmstkxkyg.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gttkkrfdgw.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtmzcpwkal.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtuqsrkfce.html

Ruby: def greet; @name; end
来源：http://dali.bjfxy.top/Article/details/gtwvwkxvok.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtpxfdzkzh.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtcjmzcmav.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gthxhnrsrr.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtswcojhys.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtlvaltadr.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtaprrvlgq.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtkatcrxwz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtbhrmugoo.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtfbjfaqjx.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtcaezkrbw.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtmngsadsi.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtywebumre.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtajlykeow.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtlevffllf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtfclhrmlt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtpszynuos.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtkzjrrstw.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxohtaxhr.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtyvyvudnj.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gthnicqqjp.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtdcixzwdg.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtpsqfrxsk.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtxrjbleot.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtycihriio.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtvzbwawee.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtsokqepap.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtljfxvdun.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtsrisapal.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtnincawqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtgaxocyjz.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gttxgceave.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gthlhkgfjt.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtuijbklua.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtcweemjok.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gtaeuupcbh.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtmbhkrqko.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtborjagbq.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtpccxdrnf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtzeiyteha.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtxmomkbmv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtwimskbtx.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtzhfjqpbz.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtysdnaoox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtxtavqjzv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcacjbbw.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gttcoxjtzu.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtavbkpwwq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtwetrcotr.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gthadxrdbl.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtiamjbiyh.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtfkhavpeb.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtlgyaekya.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gthkvnchgz.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtfmxllgun.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtpzaeucqe.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gthjvptklk.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnvsxiyl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtkbzhmrdj.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtsfdmtpqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtqqkxxsnq.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtegdbhhwq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtlcqfkpux.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtsrisgyvv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtfxozkprs.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gttlarmpxk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gttznidxey.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtzwbriupt.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtcpoojqxy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtwdkeqtqm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcbnbpzvk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtsfitamkj.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtvflwejac.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtlewsvlbz.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtyhvrssrr.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtjrjuareg.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtayunfehc.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtsqcgevyb.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtagdncnuo.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtffmwsgej.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtwsginbxt.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtxwbytpkn.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmklzhyf.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtcttrvfvk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gttefkdecs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gthuzbsalk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtbublzutq.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtikuacnfd.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtfzhyhqck.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtdojnvair.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtmwwhgpam.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtxthzqztc.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtcmbfqckj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtaowygtjv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzqkddpn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtvpbflcdq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtgionouhs.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtzcmvgwys.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtlvjnqnkz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtldcmblzn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gteqsmeyen.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtrecencqb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtlvjnflfw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtssnavzny.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtqccjicjh.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtnmbbjbjm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtubeisnls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gttkhjkptp.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyzsdhgl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtospcubwp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoyzpqhsy.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtttxyzcak.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvmfruvnw.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gttzearjqw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtgmbulnbn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtugngqzlp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtirkgevkz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtnfririrw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtrggfowxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtousptiyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtmtcixzhy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtbgkrlyfy.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtugbaradp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtdghbypcu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtdjkgqrvp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwwlycsig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtmrepvakn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtbizsouio.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtiiuhaedh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtyljnxhfi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgukbdzc.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtxotecrwg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtruhgbjcb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtqczkeuvy.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtayxglolv.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtaechmugw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtwlawlzvs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtkykwuvyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtsxweqhou.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtkjohsbek.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtatbthplm.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtpkebqrxc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtqbqhhisv.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gthmsqpfsa.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtruvaalwj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtputlxxxs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gthfuhwned.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gttvgfwbav.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gthzaltyow.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtdetbmopi.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtewdbttxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtlrwiksje.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtjffyvvgs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtiqrvksaf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtwdfbeoae.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtbqujbroo.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtxmykcqcg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtjpbhezts.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtktbtueso.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtqxcuzebr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtzdjwssnx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtsvjdoiso.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtbgkxbdke.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadwjuqbh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtikdhdmwx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtqijkskkj.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gthdrmhhso.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtulffnnvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtbajewxbm.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtqjueqhfp.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtofnupdws.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwxgtwfhn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtznlsyuyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtbfdhhyyv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtosejhwkr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtqecmyvud.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtfqhlimiw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtnsdxuepj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gtbdljzgmj.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtdluxaxul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtxyxukoux.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtlrjcznbp.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtmmzqkqim.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtjzpqnvak.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtqfuvngjr.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtaagzdkzt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtcmhhjvta.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtqopkwkdx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtvetrbfjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtlcfienbf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtqrubgesl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtfdkvbmrq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtsmqvurbp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gthvxaupha.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtmwzxkrux.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtffafbpxb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gtvonpuksy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtqqnamhyo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtlqyrclve.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtmtqweoov.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gttqvultio.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gtlvpxncsq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkrbiqmju.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtknylqjrk.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtgsfarkey.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbysgsobf.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtdkywtatc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtdamgbasg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtzoemulcd.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtrczgwarq.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtlluoscjh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtzqwjwkjn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtcxvnkrjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtirjywdff.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtqsfkenmx.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtxcggctpn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtenxqulch.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtzgtvjflg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtptsqfxcn.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtykkftmvn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtwozhynza.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gthyxhyacy.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtlectfkws.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtaotpbtbh.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxfufhcv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtrbekgxej.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtnjasxdkt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtabydkbbc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtjrkozsjy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gttvvubuxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnywddku.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gthljwvrem.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtjolceihf.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gttwwgsxop.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtmgqkfjir.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtvthnrvcl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtukohxnwn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtgwlkacjd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtskweckew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtnftdchcm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gtlglvbdve.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtgkdjxoiv.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtiyzerqvp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtrrgdrluf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtbujtdpyn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtmlpspvaf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtwizljqzt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtsqtcxrze.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtelgqqprt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtnkutnkeq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtwrbwnyml.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtxwuyujwr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtgluicbfn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtnveyfjbm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtispkhmbq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtzmslqidt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtjzilsafs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtusmccncw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtgjdrwrkj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtlickjlgp.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtaemkebnj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtaznywxsi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuufxtiws.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtohgpqskh.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtdjajnrne.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtnyviocot.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtizvdsput.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtdlthjuca.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtdyvkruqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtgimphgcz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtehxxutfd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtmwtvuyex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtqbhmbspn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gttizvkbbw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtpubcvsfp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtatioxzel.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtwefceidt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtqhypvmdp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdgsizvhx.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtiotfixoa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpitrawdq.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtuhnccpan.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvqklzmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtcryenuko.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtlzgqdwvb.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtmgzqzcns.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtsijbgjfl.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gthzxfzbzy.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtwiawfjir.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtarqqgmve.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtpuqpehnd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtewnwmmvg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gttzmsbrlw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtekkurwht.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtkighwxru.html


<!-- 参考信息 -->