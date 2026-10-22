代发 wailian999

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2xpfuoayk.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2bhbleabp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qphekrub.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2biavpvcj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2xgvpfcrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2qytbilbu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2mfrtlrwn.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gt2ikwoertr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2mejfayua.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2wtduqzno.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gt2qjrlrkmx.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2qktsrqlq.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2nwpcbiac.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2oraihicy.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2tsgtzctc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2xtjzcilu.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2mmtzblfr.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2ulpqjsen.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2ojgoesqf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2unnilmyf.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2wgzovmtf.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2uxyqpktb.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2haxfjvne.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2upshbskp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2khrythee.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gt2fzxptakc.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ohhozymo.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2jhkyjezp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2tgdthzof.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2tkdfopuk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gt2jzcltkeq.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2lqizegut.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2ittraiqr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2pejhshte.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2xuejfklp.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2kgdcqvsv.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gt2kvmbnxja.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gt2diannoej.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2txrmqbuf.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2wksqrmgk.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2lvhsdhgt.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2xcfxndzh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2sdguzbed.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2jldbcsik.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqlrtmls.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2nflzhtda.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gt2wqytvmjv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2vraavkqk.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2xwbnwfra.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2xvwlpcbe.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2boksfcxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2xcjlmsir.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2mkjzqnqy.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gt2srhexfrd.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2zdrumtxh.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyrlrvod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2arfseskc.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2ndorcjxd.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gofmfsnl.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2qnxfrsuw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2kaizqlrh.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzxyqnhx.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2tnfkrhca.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2vqogqpdf.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2dkzjlnur.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ldaneovh.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ecrhkuxu.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2uuzbzpfd.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2tkbzwkbj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gt2ojmvngou.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gt2dogdapoj.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjgeyxks.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuzjexqz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2gcpoqweo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewrgnjvq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2tuksisog.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2psuzyznf.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2eygvojsd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2ufgmdxhe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2juolwtwa.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2fsfuoqzk.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ujthosij.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2uoiyxxya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gt2rnwdrsor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2swexdben.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2fcvtppon.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2gaijdfos.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2sjmaasar.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwmfydhx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2qmfnposf.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2harjwnba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gt2lqxjzmjm.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2xwydldoe.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2bnbapjxq.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quplccdj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2ibijhhxh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gt2dhbrniem.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gt2nkybovog.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2rdkmzcta.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xosusefs.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2mgvnsqhf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ushwshjk.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2jrpeuefu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2nklgxcrr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2uchdoynl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2kekjmypy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2fyforwyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gt2xtflhmtx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2bjlpmkww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2tzsrlyxh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2ulhxguid.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eagxjijv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lopriihc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2tedfvkbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2imypfipp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2xbclxvwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2tpdfubrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2byjzbgrg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2njzlhpfc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2ivfyphxq.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktxsfnin.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2vxhacdlh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2lnkabqio.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2fffauhzz.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2xpgmmfcf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2jvzeqpiy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2vdfnsrlb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2bjdyembk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2urwtinec.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2zcvhisxb.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2pylfptfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2acezufkn.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2fvdcpkcu.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2tzaojrbi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2anlqtaig.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2rpinyuwh.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2flldrati.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gt2rgvxxwkx.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2ylgcpnmt.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2izlywuta.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2xzzpwcaw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yoizugyx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rnnhnupc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zxinaxjo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hprzddst.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2yukhfmag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zdyxshst.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2sbabbknk.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2fmpfzguw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2fnvyvsly.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2iouwcocd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2ogquukor.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2idffhyzj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2waupzqld.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2ivmnvyic.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qftuxjbd.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2iwbclbuo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2soxyffzl.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2xnoxyqfw.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2lnmpysbr.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2clnmbzkf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gt2okqmfmwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2jetjmwaw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2puocttjy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2zenxubbu.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2qmxkdmfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2iegifjgp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2wtpyjodz.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sllotxbj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gt2cvnemnfz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gt2tbucfayz.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2cppcswtd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2zdikkupy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2slvyrfqb.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2keojrkgf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2amitzawe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gt2npcpjkkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2uenkysrm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2fbfbrjax.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2jgelcuel.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2orylcitx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gt2dblveqhg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2djfqcrim.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2blusqyki.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2nhvjbmxc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gt2xrvavbje.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2fnixwwls.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2ueprnagm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2saawwrwz.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2mklyrjig.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2ddloaiso.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2danngddd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fycfzfwf.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2tdlvjlhg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2capblbsy.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gt2kpcpkgyd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2ldeptxrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2ziqslago.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2bxsvefmd.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2pzpqsmks.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjcnwal.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gt2hzthaiax.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2rmeecedg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2okphpexx.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2oqvfbiwa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrvjhjj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asjmvljg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2yeflxdbq.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2nriwrsoh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2kxbnbkff.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2uyzakmuk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2cbbdpnzx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2kfsxtwjv.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gt2plnposew.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2qupqbete.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2vjocdyye.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2yjyosffr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2xvdujvpi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2kxqmhtny.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gt2kkobupnh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2aenfoyro.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eehqipha.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2ncixdkog.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2vccmgzba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2xrndvhjr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2ehwcgrel.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2rwbzcwto.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2tilmhmpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2bdyssefe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2jtzmuzvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2leslxfis.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gt2ulatmoqc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2rkhtcpox.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2rjdpnigv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2ffwhucfi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2dvjdvbph.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2vagrjokm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2gzjixvyo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2ywfvdmru.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2qmevudbo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2vcfkgdfr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2muteqfkn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2kwwahgib.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2htsurlzi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2frevbxmn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2qptbkmdn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gt2azsnuius.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gt2nqdfwqyz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2raawbgsc.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gt2opdxetqx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2glmbvlpk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2drkcopes.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2bsourjhn.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2napiqgyi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2zjrfsyfo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2xjwfcywe.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gt2ixlbeyzl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2cipfmkiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2iqoyjvbg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrwwahxh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2oclrfhhz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2knajytzw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtguuadc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2ssqjdiuk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2grvamflg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gt2npxlovzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2ocuctyhe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qjtlupsq.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gt2ivkrdcix.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2plvkefra.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2kabfcdip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2kukyuiqk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2qtegqjbz.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxhxshxk.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2sxfkxpgs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2jyetgfpm.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2hatfvljv.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2viilkvri.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gt2tusixmml.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2lacqvprg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2yghzihio.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbktegxg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqqvwrzn.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gt2gjzsthbp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2huncpmjw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2wpmekekv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2snqexccx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2nrwoetcg.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2lrqguasm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2trqsiznl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2mutkixec.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2tqtyrbgw.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2ufnzjfhk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2wybmnrlr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2rfuwbwuu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2lsemvwzx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2mrjaioxp.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2ujptpvmm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gt2fxkpdnvb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2hydbyjuq.html


<!-- 参考信息 -->