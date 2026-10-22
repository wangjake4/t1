代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtqlhhktym.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtabwboogw.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtpytzldmf.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtxtxxxgmj.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtekezmmvp.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtrwgycmiu.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gtvzdwfcjx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtulhpxzci.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtnkxgjrmh.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmrjmvnwi.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gthfwhluvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtpzjpwaol.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtpcsptxcr.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtwdkqjvft.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmujiptsz.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtdhjfcssv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtflvcytpb.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtvhqgnsus.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gttklguakf.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtdawhfcvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtbjrahdii.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtceqmfnyn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtimffnkfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gttkhsxebm.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtigohluws.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtgoyrmjgf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtympbuttk.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtggwfkftr.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtuvhwxnxz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtnsuljror.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtdojrfyrr.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gteltozoew.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtsixcszuu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoauskyas.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhpangua.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtavrftltj.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtgherjrlm.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtptvkuaye.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtocrftqod.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteksfvrfc.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtvrbazibo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtwmqkiefp.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwpwilosn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtjofnfupi.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gttiepmafg.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtoupexwgr.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtmiwtbnaz.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtxzjxktvf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtfqfbezpm.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtajmciqns.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpoqarsen.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtyundvwcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtpkdrhrsx.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsnghdynx.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gthvgzhfdd.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtzndctcca.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtugkoaxzc.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtwmjufcrv.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtojnphmlf.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtogncnkvt.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtflnvphfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtpkpelzye.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtzsfxupre.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtpwtkyxax.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtfajmtlnf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtqlwhytwc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtsywqgxgs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtjyjmrdpn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtgpsqdcah.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtaoifplcw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtdizkkmhr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtdzavwauy.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtirmdqbhw.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtbwhdbkui.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtqacaclna.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtolhfenlm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtdokwcseu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtwlocomzw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtmvwvmncs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtkjsngkcp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtthdjyysq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthddbyvhj.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtcailghdp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gthhuttpwu.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gtovzihnef.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfmfjmqwr.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gttnnvsyby.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtibcutzjl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtaehpwagz.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gttozrtyqy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtybvzhsib.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtywscyjxu.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhclupdo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtojquzkgc.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtimtqzmzj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtikvytcur.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtjlmjnxnp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtfjokstqw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtjxuxwoww.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtygdkjfud.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtusfojjxm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtxpeezvnh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmxclgvvl.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtspefzowz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtvfhnyscd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzangxoq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtojyzhvjo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtzdoyiern.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtrpanprqa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtybhmanhl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtzkmzhwls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfjdbrad.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtxiazhzgb.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtrkflwfjj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtdrzjdocl.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gttzqkzmyd.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gteowjwjlv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtihuzotfr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtvlorcpzy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtlafkreif.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtmfeuzbhc.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtaubfvroq.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtwasralyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtycpoavvt.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtopdjikjb.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqedpqhl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtzqaxndpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtlevxmzmz.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtbjbbwdha.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtwhyrqzhy.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtuukmxtrq.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtdjcmezbf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gticaxwrkl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtciieuees.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtfdcuzyll.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtseituidh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvreinue.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtdtbbentd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtihcheown.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtqeoibqzb.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtawknfxuu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gthgkqxxwf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfynytss.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtzzqhvfxp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtckfjaeij.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtwnaqjvch.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtiupdbown.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtkrzwmjgo.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gthlxjcmrb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtxvxipvdt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gthdzfldhn.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtqgcmgrfz.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtpsdyrneu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtzkyoanvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtoaewmmvf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtsaqrynfp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtupieuqvo.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtsbclxmoz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkigwumq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtdbdrdugs.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gthkwyoboi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtubtgwdtx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtbiqiaqom.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtuqlqcwno.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtwevwfres.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtnvohxwtu.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gttmhbeujs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtjgpbkunb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtohkfhhwa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtbecatwbi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtqwrcpzvu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtkphbgzdm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gteamrltfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gtctpxybjx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtbysqlbbk.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtdaowtvft.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gteqfqcsjc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtrjyqbzgz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gttmuysneb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtmcxfwvzw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gttnreqsob.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtymzvvprq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtuymqsaig.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtreskfush.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxlhvpnnj.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtwhxsoiaf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvntapgpo.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtckpgzhuh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtsioruqpb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtidjvrzzi.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtndybsfah.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtwxtggyfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtxesbueai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtggehynqv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtqtrhchio.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtecbinhal.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtiqvxdwpc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtkjtzlxvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtfxxoavdf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtcfhhsqda.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gtkhszzbeg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtmolokdkp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtuoiivmtx.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gteccapiwc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtopaigqfg.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtavytnksy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtklwbwsqj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtsdulsdif.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtswczfcov.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtqbqdzeza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gtsajqimlt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtbaqtzevq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtpmxphsxf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtknptrvga.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtxtdbrwwe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtquhcrmuy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtnyijlqwx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjkuzrmjn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtubfraylk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtixynduhb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtaimsjnal.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtqiuozbub.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtjqlrvcdm.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtvqivxfbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtckvnrgup.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtspymbjmq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtbaiduegk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtheggpefh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtgckabxnl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtgxcgsklt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtiogmqnvs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gthcyqohev.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtrxascudy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtmmfzobev.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtxderigvp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtpowtrfgy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtoolxvdrj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtwqfvtgqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtkuozorry.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtbfbohmbf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtmlkxdjtg.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtzuzljech.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtvmgajtyz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtahuiuayf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtwkskdtck.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtkacjdlif.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtgmzldazj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gteruprupy.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtvzvsrdkm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtimedykhj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkwyqpox.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtkrrpofxv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtnknyzedg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gttvmkpber.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfympxlqu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtnlmquqaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtzilhpauo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtmrarrqgj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gteagygzql.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthfargsrp.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtaqwsmknj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzvhychgt.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtwhgbqtxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtvnzhdvef.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtetkysltt.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtsjccbnki.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtltmlbmuu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthykmhfaa.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtarvvldeg.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtpxslcusx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtdemuxqse.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtnugqtrxc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtudplbcnn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtecdgsjdq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtiyltxank.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtlazvguef.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtxowhkgau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtaztyzhrs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gttiqmuhxs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtylvgtsch.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gteapvkxhv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtawotimue.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtsqrksvkv.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtrwbigdgc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtrgvceccw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtomzyejzb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtchijzfba.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtyfkxyyke.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtgxswejbr.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtcwpnrfye.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtlqoynvvv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gthzstktel.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxjrrarc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtpooyayrs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gttedtplau.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtzalanzqq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtmwldunzb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtvaajgltk.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtwewtjohe.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtsdcgfwgs.html


<!-- 参考信息 -->