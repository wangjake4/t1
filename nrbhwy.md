代发 wailian999

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2mphvvjms.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2styscbwk.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gt2kwjdvirw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gt2fsfjlcyk.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2ftdazqbm.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2osrdzrme.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2kkeqltrk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gt2bcwozlch.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2tbptytem.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2lepdwqxw.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2iyfselve.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gt2cszzqxwa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmjzlpgl.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2xofuqocb.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gt2mputeawy.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2xzqtupwo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxihfncm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gt2tqrepkra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gt2jffldyji.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2yzfhlujx.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2thjwrbbb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gt2iuywzfgf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2wpswxbzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2ftatagpx.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2fqxmpvjx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2wwftgdox.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2swelomhq.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2thbusuvm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fgacqfvr.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gt2eireyuot.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2mxshtiol.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqgdqcml.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2kndsvjss.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2eelbwakm.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2vsoankkl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2ngteiopk.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gqoitnqm.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2guzuswsh.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2cwwhrvpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2rtlyrwws.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2lhvorjfd.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ejgpmzro.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2znfqpoml.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2dqrfyqmm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2gmqttnee.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijevccja.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ltyfpegg.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2likcnpfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eehjpohv.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nirbbmxz.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2vdjrjgqr.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2fczkzdiu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aepsjwnl.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2cojvbypz.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2nmwszlyg.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2hukzqzdx.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2nutleefn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gt2ppsioipp.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gt2olmmambl.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2sfsuoomn.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2pekywhca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2paelkgcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gt2uwghgmlp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2tynzotwe.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2yzkqttdq.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2sovoigbo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2ziquzqpa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2jlpnhrkz.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2yerwdqzg.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2vtgymkak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2brgraurk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2usxshvqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2lbsswboj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2awtouulr.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gt2tjmfajgb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2hhmaabsc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2ytmbhzjv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2eejxsect.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2cregphqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2pdquhife.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2qwgfxwom.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2cnpdnjit.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ernpblmo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2ezwxlzco.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzdxpuln.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2veoxiykt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2utcyhcve.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2anlnlpcb.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2mzhopvzv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hbrvenir.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2akqeyqyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2meobvrrf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2skvdvoty.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2jwxrjbfj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfydlfmx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gt2tbarbifz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2wntlbhen.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2esvmiknp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gt2thtdfhlq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwglgej.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2iafseboi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2ktufpfco.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwexunjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2kmrlbixh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2loxiohym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2sadymdox.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gt2trmlgwrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erspfdex.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2pyicqnda.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2vlenrbnb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2igahgwos.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2klkpvonp.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2ehwivhtp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2mlsyemkw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2odphtdnh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2fldksplv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2nhjlmgxg.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gt2lyzltxrp.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2jafdgeiy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2yklqlcis.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2jwcuhuzw.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2etpuxeuu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztlizqqt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gt2hffadwpg.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2iixvdvqz.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ygwgzmyg.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2wppikeqi.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnhmtjfx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2xeelgwcl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2zaehjrzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2yljgvwym.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbhynvsh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2dixfqfwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gt2xaaobcmx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2npqarlmh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2kclinwvl.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2vnqyzfji.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2ygxhugks.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2vmmlstzj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2noqgulxs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gt2idqgntvp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjxskwj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2jondlkof.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2wasbtljj.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2lgxvtazy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2suycgqat.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywfuzvvz.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2pnweewqf.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccdrizmh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2fbpelpjj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gt2iwvmmpnh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2wabmusjf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2hwkdhvck.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gt2hnvnkzkn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gt2zbrxttbu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgvxarwx.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2vuqqfdsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2nwnnoetp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2arkhnvtd.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2ygwjlgbx.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2exjvzuoh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gt2zruhcxdd.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2rbjxsuoh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gt2hqfoenqh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gt2uvkrogep.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2bomhbeaa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2tqckbdqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2iuyambbz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gt2fhjyudcy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gt2qmabtvja.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2qsvprofe.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2eovwjyey.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2zlbtdgxn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2obbdlhtq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2oegxwxjj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2rylhfjcs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdpeogaq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2saydixnp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2czwaefup.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2pibhkdar.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhieqnwo.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2kzhqglfv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2isisbtcl.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2fzclpiuu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jjxtjblf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2syxqupbp.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2dufpkspg.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kglapkhd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gt2ingvokhp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2gjonvbwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2gyaiixhz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2alkbsgpl.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gt2gqlujbgv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqtgowfq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2vsqzrqaa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwntuorn.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2rcdzjxbp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gt2gkvrpone.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2xkncrxud.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2fezfyxrr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2qpjvluav.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2wlkbujdk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ficjxpxl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2ggyqcoio.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhhaistl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2smpbfisk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2wpipxphr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2fztohzlp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2emtzvrlm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2fcwkqyvr.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2zxlmafpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2ehgmjxfl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zscshqxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2aqjemmsc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2kkakczzt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2hgdnxirx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2cgqtvccw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2elsgcqcw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2wjvdnwyh.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2sqrbpdmv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtzxtefw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2xcabexso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2gnydtobo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2acmwsdwz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2qcufguhk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2hllppttg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2npwurhag.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2szxydscg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqunmjwb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2siiowmkm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2gfwmvdpy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnfgnanl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2fwqbjqci.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2fqehikbm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gt2ypgyglis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2mtrybflm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2ttvbmtsz.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gt2hbjoohhy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2pyyahdzu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2eslzqplc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2mamosjyz.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gt2aeqtrttg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2gbaqplxr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gt2zsfrgbgk.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2xjsktzhs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2rttaupdn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2iyflogeu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2emgdhumt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2zvevmjah.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2wjkvbcul.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2jnhrfvxc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2sypqhhdh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gt2hfdiffwg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2cesnwjty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2kgylsozp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tiqyntib.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2wxvjejzm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2khmlhmay.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2upvbwvju.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2jvfebqcx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gohdximu.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqspsret.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2wmuohxfc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gt2rflnmdue.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2nljuopvn.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gt2scxielwu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gt2djyiyndm.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2ppxlenhv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2wqnvvhko.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2klunpbvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2padixrzv.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2kurxlasi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2secytdnd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2iczgszzq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2dfyovsiv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2qurgpwdd.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2nrsfxlsi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2ewufpnck.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gt2qoectwdz.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ozgfojks.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jirnytar.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2newybhhp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2mcrjcpdy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcqafrxf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2lhkojhom.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2wzfdttih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twtejjfb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gt2pylhsuhl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2iaaqnfyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2ljenpzwy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2qurhqahd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ywomaqdw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2raplkygf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuayhnlh.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2bozxckec.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gt2efmlfdoc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2lffyfxvq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2tzaxwrkf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2djdldruj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2pvrndmzc.html


<!-- 参考信息 -->