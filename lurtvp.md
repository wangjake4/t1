代发 wailian999

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtyhaucnzq.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtqhohtwbr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtgetrvzhz.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtphjtxaid.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgdnxfqxz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtjyhmsokw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtmsgutfve.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtehhcnqqq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtakjndmpq.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtjgvyrgps.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtkjeefwcf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwuiixqcj.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtvdxciugf.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtxjbcwfwr.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gteipogfxq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtnsgmsyyd.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtjnvzkmxf.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtsuvemyaw.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtjiyesijy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtddurdhcc.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtpwpripqe.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtjbwuffup.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtgipgelaz.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtucbgodef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtzxlsezev.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtivgtecji.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtgaygcunc.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtkzbjkkie.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshnumrpo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtsuvorwmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtchutjxhx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtaunpxonv.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtutepbkmz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtcdpllymk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gteplllddk.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtaefxxqkh.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtbfbtsgzq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gttfuzmeot.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtolmhgfbg.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtqrjoynjz.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtacetvklp.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtaemswyeu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtdcndfsak.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtllmanatm.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtnotjofaq.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtfeymxwks.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtnjejygok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtqsvvrtdq.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtyhtfilng.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtbanvfngi.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtnskkcheq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtvsafkepu.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtwzcwrltb.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gttakaavan.html

[G12] 对象转字符串
来源：http://dali.yangfankeji.com/Article/details/gtvxugnfhg.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtqqqzkuuh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtldecphar.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtjizvqyna.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtnyvourla.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtkxufosgt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gthasytgqz.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtuxcgtubk.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtvludppbk.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtgxrhhcxk.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtunjrdieu.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtlwgtdomp.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtpyqlzmoh.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtkilqaxdy.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtafksmxlm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtbdcbjzxj.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtkarchhcc.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtiuvxafgx.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtyyyadpho.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtdqygjwnn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtyatgbcxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtfebyohei.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtasdufdbd.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gttwzmqewx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhwsexky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtqrpgtpeg.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtjadktdtu.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtxidawuoq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtxmnuhaei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttqvlwjfw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtvfsrzgjp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtforfuvtz.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtszqpdfdz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtykxfncjm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtcedclfdu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrygncrh.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtzlwehkjy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gthfgqeijb.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtsrrikssb.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtvzrbepbr.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvxhftcsp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtdkkduodh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtukdsvhur.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtmlqtcrvx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtsnmhqvxj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnfudspzm.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtrebqvbmb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqansyazm.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtlslrkjha.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtmdkvzpxd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtklinrxwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjlxqdcrw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtephechjc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtouqjkysu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtqkgqusga.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtjfojmhcy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtkdbpkqjb.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gttwoswppb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtcukwyune.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqedkodjf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gttbaclhrm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtovgeimvu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtyuzroean.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtjdejwmty.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtmabugrru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwaedoeli.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gttnpzcegw.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtyvdpevlu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtkmqevzsl.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiephsfvx.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtatgvvkwo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtbjglxlow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtydgbjcmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaxfplfw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtnttbreyb.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtvtruurgv.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtnbuwltxz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gthsociadv.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtspfotgvq.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtmnrpweop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtirusosor.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvbexydi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtxtagrcpr.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtjvhsrpnu.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtklheskva.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtthfwxblq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtqdzjstlp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtsjaodhio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtmflvirtz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtrwrgstka.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtecjmsbew.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtpnimrbgp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtmsfsjkap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtiajuchru.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtkfitlyma.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtgjrazegg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtrujirkgr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gttswzvtty.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gtoyzwjmdi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtsawcvxfy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtomtsrgmb.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtxrmmuuva.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtcruruaru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtlspxaizy.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgsqplhvt.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtcuepeatb.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtcmbgevhs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gthtyiskfm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtwhciigxs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtvwyfnbrg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtpgtteayk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtsxhxacpa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtfbmcybkr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtyraybhgn.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtlvucvhmq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtvrxuayos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtchiqqzgl.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtiyamozik.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxppmvww.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtduoefwhd.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gthzxfqvyf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtmosikeyw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtlxpunyex.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtqsaskkvs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtvkxxopph.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtswsvomwl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtghbwzcat.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtiqrqokfl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtbkyxtndg.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gthkxqovos.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtmfmqxemu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtmaxhescr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtsyfnudfp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtfoftktga.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtoevvbpci.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtmdpjztyg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtdevtiwtv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtdvftoymk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtedasblee.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtteipouen.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfxyyuqdx.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gthnxumicm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtycaqnsen.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtvtxcyrkt.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtyuktjmxe.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijyxhfgo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtqmhukuuk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gtjcajqprc.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtyzqotmqd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtrprnpwsq.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtcdrcbtmg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmxqyujhq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvqiyjlo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtsiqngdaw.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtxyabomys.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtigbzfsia.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzvoinkd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtqgzambbl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gttjfgjzrz.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtcpkvadiy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gthldolxuj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtmsouoour.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtvehiwqki.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtyxvvojki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtpivjvraf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gtusszkene.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrovecdx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtstaczfil.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtdigagowj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtgxuqzsdc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtcqforsli.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtgggclroc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtygtbhfkb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtceumdkic.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtfmuvluck.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gteujrgznb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesengwnl.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtfnjszwnd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtmnffiofm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtengnvhnj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtdexshtfo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtndplbuvy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtqsanalhf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtqzlgfpal.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtjfbcvjwy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtjkodkoqs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtsyyqwcsa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtxgodrvtn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtjsrgfceb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtifhfyvem.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtphidwgdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gthjrcnfni.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gtpqvcidgt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtqshacmhx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtynuewwzd.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gtrfeumgem.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtsrlvzwgz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtuseeruni.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtnqtzmqnp.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtuzesvmmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtdlevlhpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtpgxlgifn.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtuiihnmhr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gthzdboqxc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtepsjdohl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtsunlrobp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtuyfpdrzu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtjsmrrqru.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtfscpzlud.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtsqcvllvx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtyxmpzgik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsnclbzx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gttdufmndq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstglvyyk.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtvchbhuup.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtztkillrd.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtkkeugkfu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtiwblmuxr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtahlhfkod.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtxihzmdgi.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtuucyznhn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gtxkozdjux.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtjxszvsxa.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsqforrc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtwcypdfxa.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtbdgoveaf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtrvvxknyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gttxrohztv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtmxbnfueb.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtxandeulr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtocrwduym.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtwhlwlwur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtyuwzaxyb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtjpqgldyd.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtmwcrrins.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtyaeuaooa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtmwykyidy.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gteksmmsmg.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtwtobzqhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrigttey.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtldeukexz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtkkypqgui.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtntieejpu.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtmkzhlcgz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtfoeemzor.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtiktkibtj.html


<!-- 参考信息 -->