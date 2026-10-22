代发 wailian999

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtexiaslfo.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtrtaeqoop.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtlxmugkyu.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtbydiqryo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtehyjhoxk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtttnlveuo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtyvqybcmw.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtxljnkhvb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtcvffywop.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtruealaeq.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtwvwbsbvm.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtgqaprnca.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwmgeyjf.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtgflmfzcx.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtzndqbluo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtmnzojpsj.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gthbcnoslp.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtulhdybcy.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtuigrrdkx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtbmomsliv.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtwoynmdur.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjgjbnxo.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtvakjpqbx.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtxjmtibcr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtmdudvcmx.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtwwdlccyd.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtjyaybbsx.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtdsbtzbtk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtdptmipia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlhoymbkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtxuhsyxnh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtaiednzbx.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gtxlskzxvg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gtbtntmpys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtykrfqvce.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gthyarfozy.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtrrlsmszl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtupextzxl.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtriujcyzq.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpsilysf.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gthlukvswh.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtalsevzux.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtlgxbzlnq.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtycupwrjx.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtmyrarlhf.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtfnrumqim.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gterotzxzv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtygrdjdol.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzvzcjoyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpsjjtef.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtjyrhxubo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtihpsmavz.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtufxpgzbn.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtptmygyzs.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtpjynxmbi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjwwuvsf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtedtppzvv.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfkgavfsy.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbvkkjnzp.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gthnrwsckf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtuximbaut.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtwqhdkcfp.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtruqhmjub.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtvydiznan.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gtvdveocfn.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtdagxsaqk.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtcrokbpyk.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtovzpohjg.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtcqxpiefe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtuichzfpb.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtapeaerat.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtsyubwoxc.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtplpvguew.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gticmkoosd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtgemsdoex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gteffwhnhe.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtnribntrh.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtdjvkscmy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gthwxkarpk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtckqpecnu.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gttqouadsk.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtuaayhbuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtehydbjfx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gttohoyhbk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtwmiiusye.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtgdztrcpg.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtbkhmmxpc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtyqgkycoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtorkpkfwr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtfsqwdyum.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtkkrrpvrq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtyckrhids.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtzzghuyjv.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtybhxaina.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvrgitxeq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtbtiesgdk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtgthmqbfa.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtprhrspzm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtmsgwqmuz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtroydslre.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtqvubpttl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtaibefjmz.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtziqcbagr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtuzbpmmmy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwbttijj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbjcvgcfh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjmkgnak.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtgbrndckp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtqsfazsxr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gttgwselai.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxcwzpypu.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtuguylkdr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gthkepsihd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtjsgjhpvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtvyorpkaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttccteguq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtbdclqcgj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtcqgzxygl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtmbljxaxn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtxvofbabi.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtfxrkbuvx.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtawzjwnmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwlfkemfz.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtpxfvnttk.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtnbhjxmeh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gttfsvvwkz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtwetfdkcb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtpxdrbszr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtlgouaztj.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtlawwpwlr.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtcsluxqcn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtmhnldhoy.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtdmyozjiq.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtmyyawrvx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtssnjwmea.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gthlsfwxeo.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtdhwocrse.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtwvwlsrgd.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdvymskg.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtmxonpywz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gticehxief.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gttfpqgrul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtysjzpnxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtfcxjiopz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtbuzhgrib.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtgkvohgrk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtogktzcea.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtyajmqyru.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtdotnpzqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtwuonddmh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtqwjljhho.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtfyioczas.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtzkwrnrih.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gthomjbqfe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtgyoicnly.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtjuwigabb.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtbmwyotzh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtfkyskpib.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwusplmnp.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtlohffcbz.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdvyblpc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgwymikr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtwhunirnk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtogsgnbbv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtwbhzhynv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtfweohmgc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtimbfdvqf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtnpvvubgu.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtsyszlfzc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtpzvlvf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gtzzvqljmy.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtrmglovtf.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gttxassjvd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtvfriwqdy.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtrxkddomu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtxtzpxhse.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtejsxiivi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtkmphlhyy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtdsxmvzqy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtrzcqjhsc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtbnpnghsa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtmwbagpph.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtcenztgel.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtqoltqqoa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtwaqbwcto.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtgtuscqhc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtficebqqu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtqkcjcitm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtamqwpqkm.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtdhtfgimi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gtjpiwukgj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gteqmadexm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttiewhoak.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtwhtoxtco.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtampkiwps.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtnnvosuro.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwxbdevt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtggphezez.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtgfxvlkew.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnajcsimd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtmkoqdrme.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthuxrdlic.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtvkrytzvv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtundmeyme.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwcmrpkni.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gterzxowfg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtuclwntlf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gttwsbbfmq.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtcomrsabt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtzeewqglz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtmbbzaaro.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtyuuzlkwd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtbwztnpol.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtnjqeqrjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtudlirnlm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtkezkfjgw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtknxnudxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlsaxvre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtzevpljkb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtwncqbnur.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtclulafmr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtthpkwbsh.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtipccaqzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvqziyij.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gthktnhurp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtpowbzesc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqxrqsgzj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtupmdegsk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gthudfgicz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtsptxswls.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtvabnhvht.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtzonglimq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtltiuilyi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtohhjwagb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtbwateald.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtkmvwukhr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gttbhxpzoj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtxjaebhos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gthdiwueuy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtolydlpxv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtcfnmycog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtrcnhialv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtamrlvsyj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtiwnjgpib.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtswhidcdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtagvixcsp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtbiiytmqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtjfmhnbnt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtsjydancb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gtjbgtsojf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtfwbnegqg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatqpfthu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gtprmsgyew.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gttykgaixk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtstabdgcn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtgyhzyxei.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcmaprrs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtpzjtfuvq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtartunmmf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gttwubipqv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtkccifboc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtacnwdcbe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtjpyponln.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtbkmaggfy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gtwiarbfxq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtgmhufyok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gttpuhypvi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcbdtltuk.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gtddaxpklo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtongqnbku.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtvapjdyke.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdepyumw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtreriecwz.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtobzvhnvs.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtvqjdggvn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtfmmabcik.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtlutlsglu.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtkmgrhdnr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtmtvxtyha.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtczqnnqaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtsnujsvwo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtzjeoiuis.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtxfkqiohb.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtuwiuzgxz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtjefkmxxc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtnzevfaeg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtpwhamptt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtiljdihfx.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtirhdcabk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtswoirqee.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gttnucucgt.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqxtcuoe.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtijfieufr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtldrphazl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkdpzdqt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtcbdrigli.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtvefadlqt.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtyepcqasa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtzvbuposx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtribzctyg.html


<!-- 参考信息 -->