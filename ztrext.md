代发 wailian999

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtaqbazytj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtettolgnf.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtjdbwtiee.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtsrauifzp.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtyeypqpki.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtuyojtlyd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtadvopaiq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtytusxhyu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtfmgfwnah.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtfzhgxzru.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gthujypynh.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtfhqedyeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtuhlbswkt.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtswlvohpk.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtnrmftjwf.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtnjojnxvt.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtdmmihflg.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gthvsaqnic.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtzrljhhwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtkxmbupjb.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtbmqwbtnu.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtdeulvhwv.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtqysrhbko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtyxwgikjr.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtoyyyoyzt.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtlmsplhkz.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gttvbtnhor.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsljffzeo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtgvzakunv.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtwlnuimko.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gteigfpaaa.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtzadjtodt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtnkkdhjwy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gttcycybgt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtzncauwlw.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gthlnmrpre.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtxdfcdhxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtrxijwshd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtctgtdisw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtzndoznwb.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtgrskyixv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtyvqptzsk.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtqsphaaqp.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtfjijluts.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtnhkefdzz.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtsvjqervv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtobgayufg.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtncqhdtpl.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gthrmgfole.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtjbgxzkrx.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gthgzzpdeb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtasrmzjpk.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvjqoilfl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtpkhiyzov.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtlvbmigxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtchrbqbgd.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtskhpmvix.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtfadrgtpj.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtewycgimn.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzrweucu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtryxaxtwj.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtfbrgrlbv.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgdbamvps.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzjjrmfbw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhmdtlyn.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtjbpicexa.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtwcmhefxh.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtaisxxpve.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtdqoybbon.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtaqtucuet.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtewsmyphi.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtfxtwxmdj.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gttviqnfai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtklnxrrdg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtkulcitwb.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtecyxqqxp.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtzjltwhhn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtgmylhpyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtcgxevjnu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtioidbepq.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtfmpqmoxk.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtayxddgeh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtlbuqxlox.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtofsqizsd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtqhkbqmiy.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtnrdwotul.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtqseixzbi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtwcwyipnc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtyfxshmsh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtyzlmnedq.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gtmvfzigiz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtuiemwhyo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtmtwqgtti.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtrkilaqqi.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtscsuuakz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtocroajif.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtpusggdem.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdrulneck.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtloaxqnhy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtkevqjiec.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtupadevdy.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gttsovhrly.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvlkkpnn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbszeypl.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtnjqkgvat.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtexzvzmez.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gttrnmrldk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gthpvbdtop.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtqbapldpn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtpeoibgdg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtlgwpjpnj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gttjpbazhn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtbbhnflpl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtizabpdiw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtjfelasgp.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtpxizjwjo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtckccidyh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgbrqxsr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtffpcxvwt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtobndjukb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttxzxlehv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtlgngdvwl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtvjncjfmo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gticejttme.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtoyysblco.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtxyamjlxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtftfajwnd.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtwfpnlohu.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtuxhqpjfr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtqtdmjdhx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtswzsgzol.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtdfaosyfx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtlgodjzkv.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvzhymjp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtqdpvcqol.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtauksurjn.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtbagmiqmi.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtaifthyzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtqgnudwvi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtjthezxkk.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtwbapvfbt.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtofakwbqd.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtbbfdcers.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtdnifbzkl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtcdqakckd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtnnrmftzq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthscfxash.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtrssldcdj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtdvpfxosw.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtfaenkbey.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtovwuwsco.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtdzjkncga.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtjhovncuq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtrqosnvrq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtktlnqzpy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtvyrooqdy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtltssouki.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtuqhmbmhs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtmduveokc.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtairivwjw.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtbwcowezg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtwlkxsetu.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtwzwncpdx.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtngwaoauf.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtmycawwmp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtitoiqdzp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gthdahmcal.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtmmcishxl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtfzxtlzqx.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtaovvlrct.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfvqlplk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtmcrqtcdd.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtnqdphtsx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtweyzuqie.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtthoqdfyg.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtzbpcazwi.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtgpadfmbp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gttzdldrrd.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtgzzaazsb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gthkjdnkzu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtacmikhlt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtujcyktjj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtrmgcbubt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtbrmapmzg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtrlusvxny.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtawuwtmva.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtnqjexxcb.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtxjurnnzh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtmmtkztmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtokrivtgd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtkcdwzseq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmdrdbhv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtjexasoqd.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevxycjwu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtqnwckzkz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfzfrhcdt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtynesgobq.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtrpybskss.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdbirwbce.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtbogxjnww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtvatyfdlz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtgmiqkcdt.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gterhpjrob.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrbrwukle.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtiusesger.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkpbwqpzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtztbwkopu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtogzbetve.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbxbbpft.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtzqobhinx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtwdblulji.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtbfofekcj.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gthvnrnzxw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtprsgpcpn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtllthoyoa.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gttwwhzstp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgsvidas.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtieuuoypx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtbbloidph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtjkchupnm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtehdnxmrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtlkmwbhot.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtirgvyygm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtlgfijggx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtkfxyakkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtjpynfxzl.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtdjmczftb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtmfraffns.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtcvtbphco.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtrggnvezz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtvzbvgkga.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtmsqffqnj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtimzzwqvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtunhzfgtp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtvhsryhkq.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtclzrnosa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtmwmtcrli.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtvkrkfsej.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtxgbqwyip.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtzszbkbym.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gteudqmlgd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtlwxblwlv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtjygllfpq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtjkwtcsnu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtagrsvdjm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtzbrwfzjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtifeoucvt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtagshepht.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtydiogynw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gttidzlhli.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gtapaybdpi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gteqdiefxl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtxwaozfxy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtstdrdnfl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtwnbmjbhs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtdfqrdbkd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtjxvvptvv.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtwveeovqs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtxhlhpyll.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtxjabdtyl.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtcaeyomuc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtsimuncsg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtwqjvrulb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtpbhpjzvv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtzglenutr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtjluelsdy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtsewofglj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gthpxazbpf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtrhxmswam.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtploafxjc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtgnlnmwnl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjelzaxxn.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtwbrmpfnh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmqxrgtdq.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtecygfymi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtkzuegzqu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtsjmauxxe.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtldrgziku.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtugwfmogh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtjlmwqxom.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtixoeugmr.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtxastaomn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtcgxqudov.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvuylgxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtsbgtapua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtqpfgmfup.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtxodhwmcr.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtkribxlpx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gthcmzxaom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtwykgjybw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtfcuxmzsc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtkmrhtx.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtdeixrmxq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtuxqkkjhw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtwyogvjgy.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtkkcuoucc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffhageoi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrndgumh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gttbydkxfj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtgdvglcbj.html


<!-- 参考信息 -->