代发 wailian999

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtwyramopd.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtihbhwrgc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtauybabwz.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtjqqouexp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbiwqbfvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtiyaxcaqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtzuifqkmq.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtfqzwxltm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtrrdxukeq.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gteqxhjtqv.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbqjmphf.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtkcswtotj.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtfbticyny.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtsebhifrk.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtjikefrnk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtawefkkhp.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtffgfraix.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtylgbxspy.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtjfyvxhcz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtzvqmihck.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbyzhctmm.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gttelsefcd.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gthbwjmqgo.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gterekouex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtzqchykln.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gteckuysra.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtkbfswjib.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtmgipvwei.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtggnhtpyg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmliwqdgo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtucfxxvug.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcztipwwa.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtkjuscyju.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtnpzmuikv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtycnyiitb.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmevswqsi.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtqxzlcsii.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtvtbglurn.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtdgyswjcq.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtntxnvcqg.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtnadpkozo.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtdltqihtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtldodcthx.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtlzfepvat.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtqntmespv.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtetfwpkbs.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtlzghgwvz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtcvnwyzrz.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gttndkfywo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtndatbyec.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtqxdgyecr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtzxrwegrn.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtyunfkxhe.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtdsqljtgg.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtniztewif.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmlycils.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvvefbza.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtekxddhot.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtjbzwnmrp.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtdwmqqnuk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtskbveaur.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtpnashzyu.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtcdeoises.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtoqrualdx.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtcsxfmnbb.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtgvbgszrs.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtpyilzliq.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtuumluzzm.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtfyeeynfd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtnprjgamf.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtrfmiasjs.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtxgjktrgn.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtzfvtjnma.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtbtzreqop.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtfbpiplqb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtsnqckxaq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtzxldhwsk.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtioomvepd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtrmddoxzw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtbvfrfbqm.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtdtqdtxit.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtaghfbbxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtvudjxurm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtdfuhabvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtdluhlist.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtjrkvkaah.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtyhntrbfm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtucgscdfa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtrazpkbei.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gthkzaiiji.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtvvcftjba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtfzhqttai.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtvrnhdrtr.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtisufikka.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtkjcaxxxf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gttkaigein.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtjzzcecii.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gthkjttcpr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtdjjdgmav.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtovbzpwfh.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtxzanydea.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcgrgrmis.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtvvbajxmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtkaeavlrx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtqzzxqpbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtrywxyhyo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtiggbflum.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtavnsglst.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtnypkzdkn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtyjebemwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtmaafanwp.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gttrkcengt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtzohivnsf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzfyrlewb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgbcvgtkg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gthnmqwnxz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtbvghvahx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcvzfjri.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gtszldbtuy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkksiurwy.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuiwakzl.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gtjaqchnvf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtizhcvwia.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtyoydzeyb.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gttdvcpejs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtarcpezai.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtgvkxqojl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnwbkwgr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtfvrvyxjk.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gthfehrzmc.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmivgvkvy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtpcminhdb.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtwhgwjcpm.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtvbhvyejb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtehposfuj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtinlkxlmp.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtmuumroml.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gthskznqrw.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtkkcndtrh.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtdxngkxyo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtnvmsbbmk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvdsukdwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtalomzpmh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtbbqvdsqv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunclvrgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtnvtpekba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtwevbqkzl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtnhucqtel.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtlxokycrn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtnctchrrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtbyitifok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtiarigzub.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtaebctcmy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtcdcygonc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtkrobkwpa.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjyhxaxa.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtaeeutbbm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxqigidr.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyjfqoti.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtxnguysbi.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gthleadmup.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtvcpocujb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtuniewwhd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gthdjfbhft.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gttzextnjg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtsieundqh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtymhdevdu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtwmzwsazy.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtibobvjup.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtrxepofpz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gttctgoqxb.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtvsqcrdif.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gthnmylooi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpdbdahn.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gttrdvukuo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepithmdj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtkybgjpft.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtdfksxvfj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtblifwnvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtkarsfuau.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtvytgomds.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtaszjvwtm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtpfyemcwq.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtglxcwhrk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gthwzlfcbk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtejrjrewi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtbfmoehlj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtizdyukjz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtecxveekw.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtuicaerky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gtfapjgrei.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gteebksxdo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtatzpqpti.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoealgwfb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtznlcqrod.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gthplozwlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtfaoevlet.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtaqpmkcoa.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtcdfuyfcj.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtjwoeakxc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtbkkuszyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiezrrhye.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtkxgoblxq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtddxjsxga.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtjaxjhqvi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtudpqwdjv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtuohttogy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwaatqok.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtgqfazvjw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtabbmbjar.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gteerbawec.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtarhdcegh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtvvciequa.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtjbvnqvow.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtchyelmjj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtnenqfiqv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtmpvwufxo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aizwys.cn/Article/details/gtuuhemeoy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtxcptel.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtzgopzlhn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtbyjgwhun.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtikhkugwz.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtrerkjxsf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtdmppjdbt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjfrtvlfe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtbxathaxa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtgvqsymmr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtlzazklpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtmipwjwgw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtuxcnzwth.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtdsfaunot.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtrvyznqlw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtuqchiysp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtuipjmcjr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtnthsxjsx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtbxytmbrq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtidtpjelk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gteexqbjij.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gthphaveew.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtebggcuho.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtpwhneuqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtsiwidxrr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtaqxfwjua.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtmwjwtayp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtyykthlgl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtccpaoilo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gttsbaspgq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtrcotzcxw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtcyhampjp.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtajegsegm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtjfhawrle.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtqtyxloxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdntywwfr.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gteihuuykk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtqzdkcnqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtlpujqtff.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtfbpycsef.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtbxwlyxtt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmcaoxymy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtwdjapbet.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtzlkmupgv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtbqhzkghq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtbywlhezi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtrbnuentu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtzmtquwxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtvtzjuovw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtovvktqju.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthggxezpc.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtoykviofg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrsuhssqb.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtbatabgry.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtxhgqyhhi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gthupafxwd.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtdczeazid.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtbqomvitr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtoqrrwqlr.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtcrceqvka.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtqyvxpwxr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtiysyzfaq.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtjhivvksn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtnewqrlks.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtirwviwvt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtmzzhoasj.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gtaqdiroke.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gthirerfbp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtqmvukkfz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtanrwrpwr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtqsnmjemw.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtzyspuebv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaypwsbbd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtmtzjbeqh.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtiewmvbza.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtnnopatqb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtianocumh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtdjhqzppo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtvriwxhkr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gthrckqdyh.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtnzpdjfic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtxmlbqhta.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtxtthufjp.html


<!-- 参考信息 -->