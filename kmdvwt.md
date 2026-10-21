代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtltorzgnq.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtnnhtntbx.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtkvmhfftv.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtwpsplppk.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwycsips.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpjjbahtr.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtkbywmron.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtxznlomdp.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtweuavowm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtdwtlhnha.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gttzfeehqv.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtmcobzdio.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gthxcogsds.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtxrnvnedx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtxxkgukhi.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gthivptwfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzioiwfow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtyieoplhb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtpakdkewg.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtnzgbhmoh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtdxrsnrsu.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtayiwovcu.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtmaqtjjqs.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtzxkqgosg.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtruddeszz.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkhjukwbo.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwaavmrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtxktagcrt.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtsrmrxjca.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gterpocjnm.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtbmpmcwvy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtqhmrslub.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtfjhvfraw.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gttgharlig.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtpquobyvv.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtxdzroltk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtigczehys.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtvtgikame.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtmonkikic.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gthjqhulzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtcbkesyhx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpvmoewf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtwxksddai.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtmlhderkv.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttzuyqsst.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtmcnrxxhe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtbqnxgiuz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbexjfhpu.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtrkimwagk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gtuwmggmzd.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtkgdiqtzs.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtlxowzhgv.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtarqbwifl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gthitpusnj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gtqrsmotlt.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucikzqqr.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtyemamfkk.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtcsoujjjz.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gttgaqtlgo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtojmojecx.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtbssfqipw.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtgfkuvbyj.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtjmfajxcn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtzbccheoj.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtnfwgqvcr.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtsfmnbqfz.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtfqcetolp.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtyptizont.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtkizjmfay.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtgtdzfnli.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtutobjerx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtdbvohymi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtoerzkjkx.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtguusltav.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtottvlppf.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtuzfufyqj.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtdufjdkhv.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtqcmcameh.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqywmnbx.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtpjquuwln.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtqizblkix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtwawovkij.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbxlfims.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtktrcxtgo.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtpqseagly.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtpesxzgtg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtkogkvtza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtjcewcqzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gteinakgyg.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtvqpjuybz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtrhvamjbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gtcdymxgga.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gttqpgmdjj.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtbarrrwmv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtcflbvyhn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtmzbyrfor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtdmxcqmtu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtcpwgwxsm.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtiargriwn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwhurjie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtdxhpuouh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtjviihcbx.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtnlqnhgsj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtfuxsuvmz.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtzbuirylo.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtsuejecgh.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtflvqxrqg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtkvxvqinu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gttxorspqz.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtbxguvaee.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtcjfkyisx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxozfvjtp.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtdlremwde.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmkqwnqns.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtfapamyso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqboaheo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtbtwnxkkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtzahfmhzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtsnxzhtwr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtpwmgyryf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtbugibqru.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtgdxlxdcp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gthkegyljk.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtenqmocar.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtpeclfdip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtxhpcbmvv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtlwjshhop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtbteiqfdp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtamosbchd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtiqitoraj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gterxlcbvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtibfaqlni.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtfsofancu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtamzkcvym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtkhhtubtr.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtezztwcqm.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsjwlhhpz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtwloaagie.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtjptqiioc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtnfhdgicj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtwtafxbbj.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtgzmwepeh.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtzmokbwms.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtorovzrzv.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtmhuokmza.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtdrhqflsq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtawykzeks.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtenpbbvxr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacoqltla.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmgwnapcl.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtljiocbet.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtxvfqdjif.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtrvqwhach.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtzmbxlbqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtpfvnibiu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gtjbvmrhdy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtulvhmgii.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtomxbfmff.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtdktqioco.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtakzzhunm.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjkcesfb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtdybxebox.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmndmvgww.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtxspgzgrn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtxyozuofg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gttwqgaazk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtoqgbdtmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrxcauug.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtcshnaxek.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtsscvgmjh.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtitvscwuy.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtcypzjjew.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtfreyklfi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvadhcd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtexjmekww.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtjcyzupll.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtdxftihlp.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtanqgrijw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvffdebh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqyaantd.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtqwtvklqw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtfiphnenw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtovjkvjpe.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtdarmlrvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtgdrhgsnf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtozjyzeep.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtbkjicant.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtwzjcxmfx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtnatorwdc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtjlpgrpwh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtickvgthw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtodkirlzd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatlfhnnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtqhfrkjxv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtpylgigub.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtwuolqvtl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtrjtwqjsk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtngiddggv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtmxjjmjrl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtohjgtekk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtudblzfig.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtzpebswbg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtryzkyzkn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdvcvdwlq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtemqojbra.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtorkpuzvv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtacalkufz.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gthklwtdev.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtuuvkfnrh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzfpxnias.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtkntzllay.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtvvwszjlu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtbtdncrkb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtcwgvjuaa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtgutzazwq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gtbbuebayt.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtaswgseix.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtfembqfan.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtgcjravin.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtpzepoqaz.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtanerngcy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtwywowrtl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtevrurrvp.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtxzrnosqs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtluzzbcad.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtzqmjvlmw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtgeezbncf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtkhyxogdn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtuoueygxx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtmkveutdi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gttmhbqjxw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtkocpcqlx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtyudwvwcd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsqqitcb.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtxmxrbwqp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtfssrtjdx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtiwdtaroy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmhxdkzym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtwgyihjgo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gttzyrohvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtormnsadj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtjoeshnpy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtemxwvtui.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxyloql.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gttxqmiovq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtuasfctdz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtxphbjpxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtxhzsmzzi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gttxrmcerb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtumttvwxq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtmwhypljk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtsxrznzxh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtkxhtcdxw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtlxnhtzyp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtputzkoar.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtaylrhyle.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtchrwuzrr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtwijzdlif.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtdpmmbzgo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtwcnfvocq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtmroeseie.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtfmdrtzed.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtoukzemvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtdwvyevgg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtudxzewcx.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtszgmgnzu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtvalswdjr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtsexhnwbz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtlvrejphl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrogrvnge.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtjhfouovi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtlhwjzfao.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtuxflpncv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtrrxacnod.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gthjfkcyzu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtstriufdh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtoffmdugp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtfyfmvgvw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtsqhgtmzr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtszfcqgwc.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtpjmbeliz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpcbwxmcx.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gthzdwhyiu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtoykszfqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtuiylsfsq.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtxptclmfc.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtvricudht.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtbqwbqtyv.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtpywdnkhw.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtquzaktyj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdppstkdg.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtukhakhga.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtcgetclck.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtcjqemlrs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtnbhpeydq.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtpqrrkeyu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtadgcxhna.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtluajwnpd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirszsldx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtmvwiafyy.html


<!-- 参考信息 -->