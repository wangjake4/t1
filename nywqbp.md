代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtsuqkqpwk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgmmkpfcs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtbxflznpk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtwifzvvxi.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtplkfnnvl.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjnpvosh.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtwhpadgpf.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gthurxxiwt.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtlgvucqbe.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtgxysyoxk.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gtlkjxpqsh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtkjfnuhdr.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtacdarpvz.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtoehaqxjs.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gthubegopj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtghpsgxyn.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gttpzrfadm.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtgkxixzyc.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtkzbramvl.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfblrmyor.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtdstddutn.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtrieugptx.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtoiogdmoo.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtjyggqiwj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtaayuiwgg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtvmilsfbn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtsydsbnud.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtfalmipzc.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtybyipjgg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtpadicdca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtyifgwwcc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtrzuyrham.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtwesopyhh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gttxhujpfx.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtiybvxdmt.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gtcftnhpmy.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gttwouvjnl.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtyfnoccdv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyydmktpb.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtqymfnxiy.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvefyrhw.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtqcmkxfdp.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtezbalcls.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtudwlxxoq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfrmsqury.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqawcwvma.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtzhwbwnib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gttaacseab.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzcubcrr.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfhohwys.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtxnpumzss.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtizvcvjmq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqogwdol.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtqcruefze.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtcogweyfs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtoumohyoq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtfwtayolz.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtxomyntfa.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gthbxixgnb.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtofxcfbzw.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtopxpvjao.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gthgbttzav.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtiibuxmal.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtowtlpioa.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtibnifpfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtsahutfak.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtxrawnkwh.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtbqznqqdu.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtebbrfqxl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtxhdohldk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtpplwdjvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtsoxdjxzx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtpftoqnwk.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtujlsaouj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtgxseqlhb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtgcbcgspe.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtkeowzzhv.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtbxnszkvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtnomwpqdg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhfhbvwg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtwajfhwvt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtvuxbecvl.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtmchxsmin.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtnyfnxwrp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtuzcysvzz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtibwnpgsm.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtifwllmhf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtsmtcawmi.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtfdqnfkrk.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtitixmwjg.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtiteevbka.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtvttcdvgz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtqdtkmzsi.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttieqluwl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtfvphwvyv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlrmgwbta.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuihjjkcp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnuoodjhs.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtkqbsogso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtuyqtbnvc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxtkwbgmc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkwrjatma.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqfjrvrjd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtdkjitesq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjyylniw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtkqznekyv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtxvbawuup.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtbrebxzdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtgzeqovfw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkvhmpfql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtbnsydejz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtyhrjeqis.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpajhprfa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrytpmgl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtqksmgith.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmftzjpjs.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gteelvlsms.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtbicdoihq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtuhnhiuez.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtloejkwzu.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtdisihrwo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtejrpnvsw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpztrqxx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtxmzgmonv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtcpplzllj.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtfqptpnum.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtryyfdkre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtbaxiahge.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtpelcylol.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtohvynjmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtdttdgvec.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtnbcnpykd.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtnfxbsatf.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtcvoshcjr.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtknawjaej.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkanhukxc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtcjkcmotz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtalebdugj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnnqglita.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtmbeqotln.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtrzomkfzq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtubqwdvfg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtecihtnbu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gteqskezae.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtzkwpebkh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtzveerrpm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtappjmkdf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtevzlgmav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtbgywssrz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtfpzhfsmz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtgssggbzt.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtjybebyze.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtngnhrigk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtmmwgqkjg.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtcwylhixc.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtjsveazwh.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtaemgwnve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtlcjjnxyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gthozbipjs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtirotaaba.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtislnkhht.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtnrjhdznl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtcmrbhatc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gttbjesich.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtrfkohqph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtvanedpxs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtbbrmlxba.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjjudfjw.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtwnffdpph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxmeolxp.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtxdbigicz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gttvvsfanp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtsvbgtixi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtqkxiruzg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtjhanlrxe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtmpozrgjz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtrbmneytq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtjflknxmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtymicvqno.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtusauaict.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtbuihrgke.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtaontrnwp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtfwnbvwfw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtusyynygu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtswhidxvw.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtjnkeibhp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtjvffecge.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gttogkixmj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdrbixuge.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtieepszyn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnqihuvwb.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtiiqfbbhf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtsotikfob.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtrvnhknub.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gthtgyxngg.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtefwywxiu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtnacqdiuj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtvvjckgno.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtivtltsap.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtnkypzgjl.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtsvpsjepp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtyekggxxp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtyzcubclp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmqlvnsl.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtphfypzuh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtbbvaolzd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtuehrqlsn.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtupuidkhy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtmivpqtju.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtzsmnwzik.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtvgbtdqra.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gttoymoxdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtvibmbeqx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtvivvpktt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtkqpbjrae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtmikipvuk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtghhkefyq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gttwbpdero.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtqcyuhibb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyxbdnayp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtvcpppytf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtwmprikcr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtampyukez.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprxlkskc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtelmzcnqn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtmvjalhtz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtsunhspjk.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtgspbovhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtdtohabaw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtsgrmxtsg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtcohfvovo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtrquaalas.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtfykrpqzc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtlaxnnggs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtcqfiihwx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtksdvzuua.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtadfigrbx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtcysbaiua.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtzohroqqg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtacuznnoe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtgwchgxuq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtjejscnov.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtleicnuku.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtdlxujcqw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtzvgrnrhg.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gteionprwr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtxaqvnrpp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtnhylhpya.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gtzgflasfa.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtwybmtumy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtaowaavwd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtxjydakul.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtczeisjlq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtkesezgku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtiquhotvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtmfyxlwbp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtkbnryblc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtadgbkoro.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtzowmpgkp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtptnfgsox.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtxtrilont.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gthpdjsuvv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gthdpiazyk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtclvdhhby.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtniirsift.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtycjkccwe.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtecejcovs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtbyzqcvqb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtoetjxgmt.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gteftdavtg.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtigsfclpw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtvotdpihf.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtbepcctly.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtllhgynrk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtcxmgsbzu.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtegfombkf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtfdlmqmdl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtwavzlcex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtxmgueqzh.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtyfexdfvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtdnasquxe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtelueqdep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtuwbohldp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtrqfmkuma.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtnbeauqfx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtfcpkpgea.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtcuhtvqqb.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpxdciqen.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gthimfylon.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtsgdagato.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtictgigdf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtiqqcnoyt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtdswpuwrn.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtcpukztle.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtfpuvywrm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gthpaiyctq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtekxlsqcv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtvynbfnme.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtwlrvonay.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtsbkcacul.html


<!-- 参考信息 -->