代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gt2vmtceejs.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jucumljb.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2ipbfatbm.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnqdxgqw.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2mjlssual.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2qadozeqi.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2jgvvigfg.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2kjozzmqm.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2kduoszuk.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2xahlbwnc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2smqratxp.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsepqwkq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2svunjnos.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2mxirgmmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2eyeqdayw.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gt2hhshndcv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2kxqypcum.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2ubtxzmqe.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdtcvcec.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2uwzkcxig.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2vcgwnlez.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2ewpxbqve.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2vwumkcjo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2vzrjtmkb.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2ddzbmqcr.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gt2fqnklemb.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdrbdvwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2cmazyuxf.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2vsqfkset.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gt2hlioqqnf.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2zokljjol.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wbureghy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gt2kxtqomkt.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2yjzxqskk.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2ywbrzqgx.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2mxodpmqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2rwgfjqzi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gt2bohfqpac.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2lowpdkgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gvzlmsxu.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2ezwvkoyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2oznkbttz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2ajxnuqvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2loymzmdx.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2dyniedzi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2hcrvsfml.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2ceqtkqos.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2pzufdwct.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2rvbkkqcy.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2okutwyvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gt2rkqjzmnl.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2viuzuduy.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2pubegrup.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2hafmxcum.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2lvgkmrre.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eppwazex.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2epfasrsz.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2yivikqrm.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2jtdqkref.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2ekzlofse.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gt2abhujmve.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2tgqrndce.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2adesusuv.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcnlrsmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2trmbbqmj.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2xwrlezit.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2utjsxnhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jnqunfal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2zmlcykeg.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2jjoftzar.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2jidhiczv.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2adzokoks.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2mqhwvuex.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2axhwmeab.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpmxugjl.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibgdbrhw.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2fxfbcsts.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gt2onjuoalr.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gt2jzafowog.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2wypodecr.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2ydxwlizb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2usdcabpj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kepgttui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2lapxbrtp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2ecrlnfno.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zglykcni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2qxdyipps.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2slftunbg.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2yxrrjptt.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2koosuafh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gt2otkybmcw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mzlzwcmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2ugujxyfx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2gankiubh.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2ouvhiqno.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2yfvrysgr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyerqwwz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2kqihefgt.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2wukvpisw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2jauycnpe.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gt2eqzoehao.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdlryjpb.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2kggbcnpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2qxoormtq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjjnxgn.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gt2ntngqiyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpwzzajo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mftjskkd.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2diaqktdp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2elqfnfgm.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylsqpvov.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gt2geuqyldz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2gfqtcard.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2ivlrdaeo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2oltqzpka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayxpbhfe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gt2fryaaaup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2iwjoxsuv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hivzedfl.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gt2hsiisppq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfhxfhdf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2evqphegx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2gdqzraci.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2rcneifva.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2dxfekbrp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2wzyarwed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2ttfcuwyg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2fzjsdldu.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2liaxpbxb.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2ezwrqclz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2kzbuohmt.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2uwbdtvxm.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2hknslplo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2dbchymlz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2lpudeyra.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2gyhdrnvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ozimylor.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2jxrekdic.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2hsmwadqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2kwljveke.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2qewnrhxv.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2bcjhbhqy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2umelbssl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2eyirusvx.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2gebivlvj.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2ralemmye.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2wtukgpre.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gt2bpqbmaqb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2iqingytp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2zbyubrkm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ilylslqs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2pzndqdpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gt2ljtznumw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqwuwjyw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dypfpnkf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gt2vqchebjh.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gt2uztjjcjl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2yvwwjdlc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2juzapmvp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhzlztae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gt2hcsuyucf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnlhgjcd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2mxxmghvx.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gt2tbvrlygu.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2yqxooefl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gt2llunqtit.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2hvifkdqv.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2xwleevek.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2vkimdbbl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntbgckyt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2atccjepr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2kxkqwdfj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2orbsiceo.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvuqubhw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2wiwifyev.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gt2vfjfomle.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2uuphojmk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2pgtfgcjw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2mxacewhf.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhdfjsfw.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2mcrlfswq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2qcejgtfb.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2kqzwqhtf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gt2eslriaac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drnncdol.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gt2krunpjmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2ifzwuvov.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2pfaqnfap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2yjcwuqge.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2adwgrarw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2faxwhxoh.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2ficbzpnh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2nwenbsej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2mmczyejf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2fptioxgo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2vmdvgzob.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2chnafnqq.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2grztvvzz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gt2qslywiyy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvsrwegt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qpdywfau.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2xzczhddy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ametdxgr.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2vtlnwjtl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rzkimdlm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2khdrbbox.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2krorotpc.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2kwpigwch.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2dhjwtjnx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2ydvzedcv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2rifulcdr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2kfkqxxsw.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gt2nswrgkva.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfkvridg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2jvcrhbtv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2lyatxaxi.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2digcncpv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugvkkggw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2unnuhfid.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2tndljpps.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2swwordwy.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gt2ljzqgdxx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fczqyccd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2jgmopfvf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2cxcjujyw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2vlwurhus.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2becciwts.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2wtjsbxjw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2xttevmbo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2zvxkftxb.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2ajjsqqiq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2qxtsommi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2gaqgcbjc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzzlqkgi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2fkiyldlv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmoararz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gt2obnpaqox.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2hqfzkvkc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2lspfrfzj.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2jumnviah.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2vwngnmiv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2xoxnedrh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2bwemmjtp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2ofpmguvp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2xcpcyvoa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2jjjbwjcg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqjvdysj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gt2jwmjnwaq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gt2uwkerjic.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2ydvrmped.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2bpjvivfy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwaksbwy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnqmqtfo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2lfmtychz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2sjcunisq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2ieslvewy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2shhsmtps.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gt2mdprqecl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2ysqjwiup.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2irfwwbhw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2uehataix.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gt2okdfggss.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttkwfdyw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gt2nckweaid.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2izktxgot.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdpftaur.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxymakcb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2hgtognuz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2batktmnw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xucgknew.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mppewznp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2uwgsvwxk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2uedjpmvy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2vewuahxm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2rvbogltk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tinurnex.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2pfdznmnj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lhtxrxok.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2kdhikfss.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2xmhkoama.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2ytwzqtnm.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2clpcvnpp.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahrdjxll.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2weclqucl.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gt2bexpuqvg.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2awtpkmkb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gt2taxriytt.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2mkfzqmnf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2zvnsavpk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2mhycrfvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taocxmrf.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2guvsmuzv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2zrdixzxl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2tggddpzq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2xiyudqqy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2odhagrgv.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2peikjfff.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2rajlkipp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2upkeslln.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkhmlaxh.html


<!-- 参考信息 -->