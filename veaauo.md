代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtpqslhogr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtjwirlsec.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtrefzendv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqnpqofx.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtnjqzcfqc.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtpwcohfvs.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtpbgqbxic.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtkpohmzjm.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtdpulxpld.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtdjxiczho.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtbbswgfna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtwzzpyaph.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtixtacutj.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtrwqcvozu.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavwhvrol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlbzyaoc.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtpzzfngbg.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtvnhwvjxj.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtonrmsokr.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtjlrvmcdv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtmhltwfzd.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtbfxlwmfh.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtozmghkcs.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gthezzqlkt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gtlbxgawrz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtowcxuslb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtssuzzklh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtqxusmmnr.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtfnpmdgge.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtqtsaqlzd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtdqzbfqwc.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtmoaqxvxv.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtavyeqsnq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtjjpieqfx.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtrubyljhr.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtyiztozyj.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtokkezdsz.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtbarpjyni.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtdnllgmoc.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlqjwmhb.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtmtsqedrb.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgncisss.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtwbryzakf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtjguoxiih.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtivniiqfp.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtlchelall.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gteiwjcphi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtaaffyzvp.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtihdpnpmd.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtfloqvorg.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtlyqrgncs.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtkvibozpy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtcpcegcae.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtdcevuehv.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtkvwjxmwb.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gteiaricva.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtnlwuzfou.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtmkwqxtma.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gtbdgsazeg.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtcubmsmze.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtdynoaeja.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtjkyasdlz.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtjyzufdws.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gthhugsxde.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtaqrbmpgh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtyrrhzgcm.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtsiaqihla.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtdjktvnxx.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtbprhgndd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtnaisnpwv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gthczcnobl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvgoqthn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtrmxpjike.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtzqjpopsy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtktuhaalx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gttromtcqy.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtmnjvcjja.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtruyldjcy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtuydufoqe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtdtmdzipz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtsqbknmiv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gthzaukyup.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsadcksk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtdswnztpf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtfadvvjfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtaqhvderv.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtdhzzwnmp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtnxcstqye.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqedeytt.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtcatpkuwz.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxpbjfhou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtxoazajrz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtmqagjcuj.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtckuowufi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtwxcpcjik.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboruosyo.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtlrksbtjl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtholevtxb.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtnhdbtibj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gtkwkhbwwx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtxfbdgowc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtaaodtimh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrewefynr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtcivnxbpm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtjwakwskh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtjjesslch.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtoresfazp.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtkaxhvkju.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtlnywrgct.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gttfdhqjkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtcvejhefk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtudcxxjyn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttnufwunw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gtfhgyibfa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtikxwmfpl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzcxjrubl.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtvyrdidge.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtvffwilns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtadwdmyuw.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtvlakcago.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxmyeaywk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtyuqssxde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtjvulgwco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtxvuzuzmc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfhycfyn.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtagmapobw.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtpgazftxw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtafdhnwsv.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtxseowwtm.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnggojcz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtzoyuaokh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtiqnzbddp.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtmmsbqybm.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtnvvornwf.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpneffusq.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtkdzuiokk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtqrjnoihb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtammqtacy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtcjmwuijx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtuqvjuwlh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtdpdozizn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtpesexdfe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtypcoddbn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgunpegi.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtrhticaxe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtgoixlvnh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtsnmvrgpk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtpjevwopd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtfwhbbwak.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtoeooiezi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtxtmaukib.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzboankg.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtsdzkoedy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtlvsqnynt.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtpiiscmka.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gttcqdkcsa.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtctrdvsms.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtqzdoclex.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtsxhocsol.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtaytxovie.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtyjymrdct.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvubgykd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtcnltstcy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtzbtptxvq.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxpfrxen.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtvsjjudzy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtgfobaluf.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtgotwezza.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtvraugyox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gthpafpiwc.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtnhanfinm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtgcnrlcss.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gttwjgzvzh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtgdpdlngr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtpypgpkbl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gtqiqxymgd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtpxbiopft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtzvewvssk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtfilkcogw.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gthrjxapye.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtytktbpfn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtdhsxxfex.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtrjmznksf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gteweftwac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtphpyjqyp.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gthnxsmnsq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtcaifmvup.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtszppffhc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuygjxnsi.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtpjgsvtrz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtngxpkepj.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtmxyopkow.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtbotnuake.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtrymrfwik.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtvdlvqoxq.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtnyexlygr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtkjejgexk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtdvolswqb.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtqjxollof.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvbdpmca.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gttspshmfy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtlheskceu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtxugthfgn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtjaksgazl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfbptufs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtzxzpckeq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtugczaowg.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gthzamujbc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtxcdbxfmo.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtkllzittq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtuzoaxrug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtptoatzzv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqlyfxwy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gttnckshlh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtmhqmrvos.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtfpyhjkwl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtvpiyhqun.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gthufewwcd.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgulsxduf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtlalozdxx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtseefpqex.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtcpelfrvb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtgqmknzdc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gttxmwmrcy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gttpcxtvty.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gtswceacmf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtepabifaf.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtteoajtou.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtebdorbgl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtzdoagfnq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtefbzpuee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtxwxeysyu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtislruvyl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtbjkunjne.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtdjqkmpcp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtqcuzbtpi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtdiczpcah.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtgutozqws.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gtdhhbrvgc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtlmvqvvbe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtphxafdzt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtvjppzqtf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtnwezvxdf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gttqwzaenw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtpwovrzxw.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gthlxqbcnc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtzhxkufrp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gttiiuoald.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtohbbakzj.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtdzwjbnoz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtfyjembbz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtumcektdb.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtiohduqqa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtvzxhaglp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtzipjbkbd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtvocflceo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtcprdoazg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtxwgyxyuw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gteoycwxwp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtdxjcxmrq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gttrqstpkq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtmgnihmum.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfooiwbm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsyceldoy.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtghunfaud.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbghvhrpd.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gttawnvqgm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkxujkxj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtcrsuryzs.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtevbevuwy.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtpqphxfol.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtaskihegz.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtxtsfyfui.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtnqqaikrv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtqacnuomb.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtqqslscrw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtxuvxdbnk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtdhrwhxvd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtflbsafit.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfyvvknm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gterdfpssj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gthuolozhu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtwphvubeh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtlqdbmniz.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtfijyegyc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtpncqckob.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtjmndjuem.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gteiqqygdq.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdztgehvn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtuqswdarn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtlkltlwzx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtcybqzbwm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtzyjfyaxf.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtbfxuiybc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtyxzwzhyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtognkohba.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtxaahsqqi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtkngalxta.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtvgnxyhze.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtpvbvpwbg.html


<!-- 参考信息 -->