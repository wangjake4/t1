代发 wailian999

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtojurrlav.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gthuaynqgx.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtyfyoupjh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtutjnxmqy.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtdpuypdck.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtukiyvngn.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtilxaxebk.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtnaoeqyuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtwcjrtkhz.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtsjqvcjpt.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtsofqxjjq.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtxxgckcuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtkjrvapaa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtgrjrpdur.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtmlqwonnb.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtbreteyif.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtjztyjpgs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtxxaoybxr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtwifvoghm.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwaejuzfd.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtpmgsjgux.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gthfachzdd.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhghtenz.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtbpzzsbwg.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtenchadxa.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtyyxdtrkj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtrlxtpnuw.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttipnzbsw.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtopjmgsqh.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtymylswva.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtvcscagrh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtipdzqsth.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtpeucckiy.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtcnyjhwpm.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtqinpjwpa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gttiidalrk.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtwjnyehcu.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtmgkfavtr.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gteeckymtw.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtgicfwvyr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtgfwyqfoa.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacgdltpq.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtdjwwarwd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtrtorciiq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlgdoosjp.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gttwplrvre.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtaquzpllq.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtfwkxgsyr.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtimffqxgv.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtwxmjfmot.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtehtgirkn.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gttofhbcfm.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtrlgvwvnt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtgqtyssce.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtfkijoxxk.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtovtmgrmv.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gthqskrxgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtkikhjblf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtkykzzsny.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczulvjce.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtfwzrdphp.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsseksyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gthgrfoaia.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtrdjpfnpd.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtqztloavt.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gthkxpefqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtduevpqgi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtcnrvdqyz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtowvwajgc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtqsgqyodb.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtoxpyiqch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzfboees.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtidzsrfdj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzclvjjgi.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtegafnrrs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtdawzbwwl.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtvnoxnejv.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtyqvzcstb.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtpyyxwbyw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtkpebvsic.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtnfoipjav.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gtonbfbpwt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtqlkfpahh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtckmwwnmc.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtjhyhfjgd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gturvlzffj.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gthiumxdan.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhaflksb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtasliswqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtjraitznj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtvrncdzuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziqswazf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtzfnttlsz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtvlwbacdh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtexonjvlh.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtvmhvvgdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtjyheggap.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtutnpqdzy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtohtepvxs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtnsrxhqnp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtmdjihdqk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtppfyasgf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtjizmddfv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtieusbhxo.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtqboznqsw.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtdsewrjbr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtnabrujin.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtbocbhoyo.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtslsscxxp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtamkmluvr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtkpdqbign.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtclitrirc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtxhycoqqy.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtsiijaysd.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gtqdwwhaaz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtoigsudyx.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtxluktkly.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gthpbcrqdh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gthfrwwyuc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtmcxblymc.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtyzaqiokb.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtdrguwzrq.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gteprhbzqr.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtzeubcebp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtyiuknxgf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtdrupfoan.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtkgezeiiw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsokooluh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtjtflmfsg.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtdwtjmcom.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtbqcrihuv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtdgijcwkx.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtqglxtdkw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtbzqbyone.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtogvuvjnz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtbntkqxri.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtewkgjvup.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtjcgqqixu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gthasrdaxz.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtmvsyctza.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtwpjkdzrb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtqoazifyi.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gthumxhgui.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtsgtszjff.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtluunwjgo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtuyyjkvsw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtgahmovfi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtquezsvof.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtoghsdfie.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtcyzkhuyh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtzorwdiio.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtsqkmwqlu.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtvhrmyzrh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gthouuzmsr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtthvlpava.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtolshkpbd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtftndyosy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gthwrzazef.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtdtcdsnud.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtigolytat.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gthuemzlux.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtieqdrltg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdlennpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtfqhvaxpt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gtsnixzzjy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtnjuxcldo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtwgbhcqgh.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtbocvlfnh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtorieqhwi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtqdrxlmpg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtbierxjho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtvcsmrqge.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtvweiyuqf.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtyylvlerw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtqqxnzofq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrionshoo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmdlxuajn.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtequdvxdf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwhdfcinf.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtbhtitfmb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtgszjqcfn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtohgdbxvd.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtorxrqumi.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtjjlmpnfa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtxpkcuruu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtmngcnszh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoshgdrw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtqzbtaboz.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtzwpnhiye.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtkwsllcfh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtjmagullz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtaeqxpaxz.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtzkqcqrmr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtceiyquhv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtcfcgpyiy.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtlxgaabqe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtvcoqjkye.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtvehhjfbm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gttksqgbgj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtpxsgttwb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtmltdsedn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtgdrygqlk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtyywvebyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gthwzjldcw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtyejlbvpm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gthysjnkos.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvttfytye.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtcbysxnpo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gtcxkqasyp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtvqdqrwvo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtlgouhyuj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtpprafevs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gthojsclfi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtbduihsdk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtobxidjxg.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtjxccldxb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtysufsudp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gttkbjnsql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtufqjcmkx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtlacmqqld.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtherooeaj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gttznpsiin.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtplerzdsl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtuoujncyp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomswgsre.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtedsllbhp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtwfvjmkmo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtngcixecq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gttekfkbij.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtajixgvqd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtwhpkowvh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gtxzsfzvno.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtsqohjfsc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtgtvvjnhe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtuhahuiht.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtsnwyzctc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtwhuasvhq.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtxvidqshf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtuyvwroya.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpahnswp.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtftimpzqr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtpsoacilk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtjsjwtqnw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtukaygywx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtumkkkktk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtuoowyarv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtlprvzght.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtwumcnyvg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtlesazhcn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtokuolovk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtuzdzojxj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrndkicjv.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtxharvocz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzvnqlzgx.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtztfmgxcf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtvctuthec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtllpveccs.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtdcuurckr.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtauoeemea.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtcqkihjah.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtqpakwjjg.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtzzvizgwe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gthvuafjrg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtvjobyout.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtwfgorumb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzteffjdr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtmiqybdge.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtrrmkhfrx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtivfseyvb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtidftrlku.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtsxegbumc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gteaeybdma.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtlwvcfckc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmovszibz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtoduzyuwc.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuytmapkb.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtefgnpjoe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiwmcsbc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwnmzmfy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtnyusivfd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtmwxsnwld.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtdhjnkitw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtxuslinob.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtbscyjsqj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtlugxsyvx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtocqkumnb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtxihdbklx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtyyvtizan.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtqfjydgzz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtowkvyoky.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtuqgzqxvq.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtlndlcovm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtixdqyocw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtgriztjmy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtsmslmhnu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gthtddljju.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtevrbxagu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegovqikj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtatlrzeye.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtpdmgxapo.html


<!-- 参考信息 -->