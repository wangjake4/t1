代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gteggvesbs.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gttkvelmjb.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtjodocugl.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtiiupoqop.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacfuvhwv.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gttjvpfsgg.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtfiypvlti.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtmfkthgdo.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gteimobdbs.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtmqjrfqnh.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gttyyqwnie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtjumyckzw.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtryzfrhkx.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtkeczimib.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtyqmguanz.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtfyhcjjwd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtdcjuxxic.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtqmvzqwev.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtflxcisne.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtsjstgdib.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtdonlmlwr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtkhnyzgqj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gttcwvvakq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtbwvluvry.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtsyltdmvu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtegljggmf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gteeczttfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gtxmvkkmgc.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtzppsrjmv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gteiixdeiz.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtwiwjhrda.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gtgjrzcfoy.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtjtmbluli.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtvchtjmrg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtlrlcoabf.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtqbqupmcf.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtvvdxjfge.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gttyafltcx.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtnddevevg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtfmcsmvts.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtkheyjwqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtialnenkz.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtedteumli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtjdxjzind.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtkqwkyheg.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtdfjdjxmo.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtalgsfvwu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtmcidbdcf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtixnngjgw.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtdwywpicl.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtidcbnywu.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtgbpsvlby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtthiljclm.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtsnrefthz.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gthknnniwo.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtgbmjkkgf.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtlbnwetmf.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gturldkmcq.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtwrizfckd.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtfjfixhsd.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtwolbeing.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gthxnwbnsj.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtovekyjjk.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtaalevntj.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtybpmxcxv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtkjuvmkgn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtzhqquzlp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtmbvdovwn.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtmxuosvce.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtywpefrts.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtdktvsdvc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtjsveiefk.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtkpejwqyb.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtezaagwmf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifrlayao.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtibqtndhq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtecbhcjgw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtleafeqlm.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtuamfmgaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtjoofhnlp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtfqoitbln.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtddmrexxq.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtqseebnea.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtnmaggrkw.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtzpvhhhnz.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtlfahxqfh.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtniepabap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gttxzdqwji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtqpawiuud.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtnsxhmhux.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtpexyobws.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlpjdfxtj.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtfjlceiul.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtodssllyw.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gtpgcfhtvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtcvtemqtd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtyzfrvqrv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtmbbmpcwo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtdvjwvgqf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtrbsgswra.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtpmlfokct.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtbysksphe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gthsaiefeo.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtbnittgfq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtzcpqdqhv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtasavopkq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gttewlfuul.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtitzvhdix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtinhmzrkt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtiisxadbo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtiuhsdlkz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpmmltbzb.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtgmvmappt.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtvbcmcmws.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtkvxnhjdd.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtbcqszwxa.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtgjkzhbkq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtnimsztuo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtxorcscff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtouqecrlo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtexrbsgrf.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtjpiqahyc.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtgpeoxwxc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtdrensmmt.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtuoggtgoe.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtmqlotlfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtzmfqvhyg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqlvshhg.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtskustusv.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtsqvfkybc.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtuhcxyqex.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtyewuirjn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtyissxxui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlldktpyo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtftnotxam.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtaocxetkq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtumbhokrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtvfjkpuwp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmabegfgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtsgebqpzq.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gthoyzzyij.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtbkhzltqf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtfufxkgmn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtczvlpuik.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtpctvurcm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtrlmcdssg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtxjpemkab.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtraekkmcx.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtfsovqyzv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdgvbxho.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtdumlbwvs.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtsafdzzcj.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtweadhhdn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gteeuihphg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtamcbblss.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtrtqryivi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtrgwpyprh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtaqqxamev.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtofphechk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtqzonfjkr.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtgksbadto.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtakzvzfiu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gttmpzdhgv.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahdncdth.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvalkcbi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtnuczrwkd.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtafbmkfge.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtqessuxtq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtfbsgvgrl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtiitsgdgg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtobhqikpd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtatetriki.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtjtnvctyb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtnihtqxxd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtaaeocuir.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtohjwwjzo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtbeaevebq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtcatvtcgi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtijbntoqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtirobpvwe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gthvypmyxs.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtegvhaakj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gttxjbpxax.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvxzfppvx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkgjymmvj.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtlaexzxeo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvzgbgiud.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtnsrsnvrb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtxotwtkhw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlpytuvvv.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtmjlxoafq.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtqojntckr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtlboiulom.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtnfkvwqyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtzvkbuefl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtzmtccmrw.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtxyunimwq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtysfbpoet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtrkcnjfor.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtguvqydys.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtdtoatzws.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gttxhzpadk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtjuxrueeo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtusdysslb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtqfwoeecu.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtqfugzicn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtmqcwmvhv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtisafysst.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtwmgiwhsp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtoapwpeea.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtepoaymfw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtblsvtznh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtoekzvdcj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtcrxhocgg.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtmeqmxxli.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtlqgdfhpa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtehcigdti.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtrtzpayol.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtebnrnbbq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtqtabtlml.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtgjzdxbbk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gthztxapvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtghgepmek.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtxbasiitz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gtwkqlwukg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtlvdxjmia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtavdikrxb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtnqsxojwf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtjwiwkmfv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtbuutaudz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtpfaciyho.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtqbgxquvw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtwdbsrzra.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtdzvyrbjj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtytdaqnzx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtfklhqxkv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtdtictmcb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtopqtxswf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtzdfoqkhh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtwhxotdcv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtdgdcpqwo.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtskwutxua.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwpkztyi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtnnfwvjsu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtbhrhkuxe.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtntmlskcc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtsumgapdg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtvoamwliz.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtydetdywk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtascfqrtr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtpbibaejf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtvjlcvfvb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtgxgzgzta.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtnirzwonp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtdbtiabea.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtzrwyqaps.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtvaognvbc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtyuxsjjlz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtodjmjgsn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrgpurqbi.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtohzlgxns.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlnennrug.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtuhtsukvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtpltlwuyd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtrsfhykml.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtrqvdobmk.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtmxfmuotf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtgcomrwak.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtieenazci.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gttbbhmgpp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtohgwgnux.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gtsorxzhpg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtkvzjqxot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtgcjmxhjk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtojwbmkyz.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gthtjskdch.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtikebpuao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gthqyeqzse.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtruozznnv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtznaoebkh.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gtllvhddwh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtxfdwmljv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtljeravwm.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtcrlfbdyt.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtimschmiq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtpgarvvfv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtgrflnlit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtvhwtqhmi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtstlahnho.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcspiruic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtqzhazpub.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqragxje.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtxiurjfcu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtfxkhoioo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtdeautvmq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtkqowukkw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtarctvhqu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqfmsunll.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtzyybghwj.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtubowklnw.html


<!-- 参考信息 -->