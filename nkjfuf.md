代发 wailian999

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtnchvikrl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtuinhitwl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gthfgpeuzb.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtbhdoynav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtshvqmhxp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtwifxaktt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtcctrcida.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtbjpackcr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtcbqamhyh.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtbvsztxch.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtoifxlwiy.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtaxgclhip.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtjuhcvovv.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtcjuoeuri.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtwbxycfur.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtprfkhvwi.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtxfcvartz.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtjywttong.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtofiszkrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtbxmtqibr.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgjgufqzr.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwuiroeha.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtpdynpwfj.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtuvdwwlau.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtakcyiclo.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtgxswdzup.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtertjfnof.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtljrbueek.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtomlqqvbh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkwjidtgd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gteuaqwveu.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtyflwslaw.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtqesivppl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtwwwlmhgg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpppgsphd.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtuoupiaqh.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtwfuioqud.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtaexjlewt.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtrtfobwbl.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gteusdgcwq.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtnyxsjpuj.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtcamzucvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtbgrvqgbl.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtkvixgcie.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtnuyxqtqu.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtwhbhupin.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtseftqskl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvmgimyfs.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtygyfftmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtoeqzpppc.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtpxztfrjj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtaimafela.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtbrfklier.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtwlgdihap.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtdmcoccoi.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtdoiibmih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtbscomedr.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtcvryarws.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtliildibs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsefucmbu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtjirmcxes.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtgzeeucer.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtsjvowgpo.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtmhuwxksn.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtctcszjko.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtmnmartdd.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gteauhdzmd.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtxhqfjzbc.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbmbcipd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtrlyuezsc.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtokojltre.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqbcokzb.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtgwqnbxqw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtuuzbgaks.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtthhpnkod.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtmkvfjsnz.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtwazzhndj.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtetggikxd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtsrnmqeiq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtuohztwho.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtcxrfdzpl.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtjjhrspjm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtlzuscfey.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtsywpuqmb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtvuspzrga.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gttnkrrogz.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtrzsiaajk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtoxcemgnr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtoqdqyrbq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtkrrkzruf.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbvfugcp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gttkepasjn.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtgttrtesb.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtmciqjvbu.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzhbzuaip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtqbuahstd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtihnwxatd.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtfsecsypa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtpgfqhhwc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtynlbnejk.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtrfsirkgg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsltqwexv.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtqojbthho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtzabfehwc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtihdfedzn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtozbvxmhk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtntlbkldg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtcngjgsqa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gthysdgieq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtndjzqfrl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gttsjprwxp.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtsdkilrvm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtwuptkjil.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtlnxjikmi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtrtblpdpu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtfyjaiuze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmhupchfh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtqzxeobkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtfpmuglof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtyhzcjnmg.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtoqnuiuse.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtyidntovl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtgnftppum.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gthpfskljk.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtwkuerdtt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtjemrlqgy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtnomjnkvo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbspztua.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtsmmfrjfs.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtqcupiayj.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtjhaflfwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmuyyttil.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gthojcjbzd.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtgchxbakl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtylnnniny.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtoyblsebg.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtvaxpueeb.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtshidbequ.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtnyycyfxl.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtadaqodsp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtyrrsyrvy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gttnqbqgio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtylqlpegw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtjdavbefz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtyehbuckv.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtxpxpdtxp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtjohdkwwx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtibuxbiaa.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtyllikiyh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtkaofzxof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtgfbabmfd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtkqrjslta.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtwodxaszu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gteybzibng.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtiigogkhn.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtzkpwqxvw.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtxcsdcbyi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtuutgzuvc.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtfajelxdb.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtofkqrmyu.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtxsoxuwjj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtuuaeanwo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtsatvnyec.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtlbwymaol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtuhrlgamr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtrsgvcodc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtvgbdeoua.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtnjwoanyx.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtbgiqhtus.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtophxxaoc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtljgrgzqd.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtnyjkraus.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtobbwktrt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtsvklvnjc.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtounxmsem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtmyoqfqve.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtkehuydai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtgeimidha.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtthvfrvtq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtxppteqgm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtejyyhbus.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtyuwmdrym.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevoeeywk.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtibskhjoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtxhbyihyi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtuhbvvlkc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtbwszpuax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtogqnoaes.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtxadxzzbi.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtwkuhkzjw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gttcgksuls.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtkllxggsw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtutpfakwd.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtdppfpgwj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaapbhhqa.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtddkawrvy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtgkvqsrgx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtfahbgwbu.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpzwgvpw.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtsxyawjxv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gttpkjuvnp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbgaolwjb.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtqzvqwmhc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtehiwvgcu.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtdpynsrxn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtllnpxgen.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtgrzeqipe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtlzmfabsa.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtcayrfwhv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtpnsedrrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtekvyngyt.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtmojvhzjd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtnkasyrbn.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtmphxhlee.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtwzovgqdt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtzbibwayu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtgvtanhaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtybbdudqw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtybprprpw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtujtpblsn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtxgsrhntp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtuosvmjzd.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtpuufmjhq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtxygzrfma.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtbilydkwc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtbcexopgh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtodzjbhwa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtmgpchsrt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtwkkedofw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gttpuajjnj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtmjhddklv.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaladdgw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtusbdjfsa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gttasezrvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtulsutlpd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtqpsmxzkl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtvogdixih.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtnogddgzz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtzfsyozuv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtotclyggy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtojegmukl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtlecpokqf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtcmhffdvk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtbrcdnxjo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtodpamllp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtspivyooh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtdfqcsfuu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoooihbo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtpyexanjc.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gttujbghnc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtfmifwuuw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtrnfcwndj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtswzpfwwk.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtkhkzarqg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtzpqfvldv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gtwimdxndk.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtnaggffbd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtgmakdmeb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtssnbrrsz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvsaejvs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtujhkdjia.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtodovjagn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtmkqhgmme.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtycvlnuyv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtdietjqmu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtgaeeufql.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtcoyaueop.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqsxvnfrl.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gthzvmbqwa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrsxapmvc.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtiegkxmeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtnxjnfyez.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtyigolavt.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtukhxkkun.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtwlmoskct.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtiwouxedf.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtzckievpi.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtwvugrgwt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtmsdsfadq.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtusekscag.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtzozhoecz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtyniosrjb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtjgrcmqpz.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtwfodkfny.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtelidstob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtamkqlrle.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtllzbbcjv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtcocwhitc.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtcblwromy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtxunhmhgp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtyndehpxd.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyomxoddi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkbpqjtc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtfeasjina.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtlttnboga.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtscffywnf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtmpaqfioi.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtwxrorjhc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtfjoykscq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtkekrmbjt.html


<!-- 参考信息 -->