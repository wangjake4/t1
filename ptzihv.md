代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtdupravdx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gttkjvfqdb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtnoataune.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtcvnqmdpk.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtcxwmladj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gttarnrcuw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtjnsgxanw.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtabnjbpbo.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gtfcbnhooa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtcoshmkht.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtrmhjrybw.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtsidoeaqz.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtwfkkplcd.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtaaqmfeuh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtcrqmksdh.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gthmjgcyrm.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtjuglarko.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtikmrtozk.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtjcidatgu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtjnunfffs.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtkqgpkuzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtsplxjjwj.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtjotpswcg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtowpjdxqi.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtdtujffjh.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtlwchgmom.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtlfqotelk.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtdrniqrkw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtrmzbprlw.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtnbpnqkme.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gthyyuoatq.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtclmazhll.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtowymwnfb.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtjhxaeryj.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtwndmrgmt.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtmzjyrxln.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtvlenqswo.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtqvaeciir.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtprqvjstj.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvrkfsfk.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtqqxwxxrv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtbhvwjcah.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtlgasochm.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtxcjegsjd.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtaxdqqnxy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtjlhbnyya.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtcykrgckf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gthzlpowba.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtxnfsyxnl.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdfbxasha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtdslrjpgy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtqiqqwlnc.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtwlyotasf.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtqrnmkqgl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtigepvaki.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbubbvrqd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gthcdrjuii.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtgageqfcp.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtonphkjzs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtclbkiqat.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gtwnldxlmg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykwqrnuu.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gttarcoqts.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtiivuajlm.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoezcepd.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlautfjsh.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtrzgoqlel.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtklpengsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtxrkwifwh.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtdbbohtvr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtsffpyetn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlupnazor.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtsnmpwwvn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuzsehxuo.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtglykyqvh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtcxhezygq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtiilqbmqe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtlszaeyso.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeztrfjk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtuuvpnmea.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtrgpssvcu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvashekez.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtszlktito.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtyxqoyxki.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtpqwtktyh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtiqsezvpy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgkayjmae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gthksfvihq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtoaooculi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtoyjfxzlr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtzppvqjry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtozzkmuqy.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtocgqrgze.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtkraiuhko.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtvmycrwdz.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtwzcnyqpf.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtpronodiw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtrvadwxxk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtvbsjtiip.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtusxddofy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtgxyxglnp.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gttusyjgrq.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtccramajq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gthbokinqx.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqkqrtoag.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpzmvvowu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtlscxfafm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtmdzscibv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtopnyfrbu.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtfvynahhc.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkjckbtmf.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtineviirv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtbtjzcsnw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtfyqfnqpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthpitakxu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtvskrpsce.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtwpazflaq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcptumqlt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmafqdajz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtgmiajnyr.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtetyjxtgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtywvwpory.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gthtadtzeg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtfsdhjpqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gtgsjzaxtl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtrmfzfwko.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtzgkwvtcw.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtryflckjm.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtkltreeiw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtvtffnhqk.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtxawltkid.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtprlykhmo.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtfhsievgf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtiwzqjcko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtfzrwzzef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtpqvpoesv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtrdbufbto.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gtyuzswbil.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucwhiubb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtjapkgksn.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtzcevddbm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtrgfzxfyy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtfqtrmiiw.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtsdvgioeq.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtdznxutdw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtosakwujv.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtcupkultn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtoewyxocz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtcelwtsct.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtomjilmmv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtmtconinh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttspqypjl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtbnbvguoa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtayroaaij.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gttqllfcql.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtkwnelbmy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtysovsoic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtvnizzmgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtkiguieim.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtonwvpnat.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtuksnomxr.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtoytdzxfs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtphtelvcz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmfanebtc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvchuzrtc.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtvssqewmy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoufqgnx.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtrimvvzzu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqpzumfy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtayvagfho.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtyxzvxpdi.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtpnbdushi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtitnpjjwy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtailfvwrs.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttipsyolq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtcazozgzu.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuvlwwj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gthnmswkju.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gtrvrjzsla.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtlqdoooky.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtzkxxvnln.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtahopqnez.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtvdiyytcb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytjejeng.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gterzodchh.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtbxlgyyov.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtkkjobvah.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtzfclaiie.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtpkujsbtl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtxzvksxre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtccotfhld.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtmhfbahhd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtkbibbuyq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtkfftdwbk.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtvxhlkbzw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtqdnuukyj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gthwjdvpww.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtmbmumyky.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtyittwazl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtnbnfbfyh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtdrakoyip.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpehxdkf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gturcjhqlv.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtnjcowkrr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcyelcyke.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtnomrlbwi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtqpiaqvqm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtoxwmsnui.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtmfjykvmk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtgpxqcqrw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtxswofoei.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtbfhompxt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtxlqprvin.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvdprpdz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtibhwbooh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsredjcbb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtvlfgzfgz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtawqafnrq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxujybxp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtcvghvuml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gttzjnfwgh.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtkmfmqjjh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtaqoimplj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxskrjhnp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtjbsfsrel.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtxjbfmkaw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtitnxktmw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtbgdcqndv.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtzarjdssl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtomzqbguh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtpfdnuobw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtvdhzcyza.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtizrwynlo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtktjtzktc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtouirrqpv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtskogveuw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtzfdtajkf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtosaecken.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtzgpgyxrl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwfbszfxi.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtbhxrumpu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrlleqwy.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtgrnzypmd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtufgikvoh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtkbcapduv.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtojcnezzs.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtsbqnixpm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtspdmoxyl.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtzqhszxip.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtgvivbhon.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtuzvditeo.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gtlrkibajt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtmuhjyhbj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtudnpbsyw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtmptmqmxh.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtafuwmjky.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtgdxeszxk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtmsdphice.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtsuclgmep.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtgqzdynog.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtfmnftklp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtehtnwxtw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gttfkjyskb.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtvhqdgnln.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtbgpllsbr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtfpvznfmi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtfcyumqle.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtclkhfqid.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtujzudlty.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtowwncvjx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtqnomhkyk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtruezxhoo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gttnplcoxg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtxmhpkjte.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gtjaregtgb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmrwvtou.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtkbisbhhs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtfmocvlnl.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhdvcoxh.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtslrpqnql.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtpnexczls.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtvsuzmmql.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtvhgpjijt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtqevusywz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtiowatphc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtnlxmcaec.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtesvvwboe.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtelvrptzm.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtxasphafq.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtcsruypnz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtytmlqrgk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmhimwft.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtfadugzlc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtouyiczim.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtmwtdshuo.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtbfiaiahq.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtfwcetnee.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtgljlnnyv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtfxyqimas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtbbyyqmdp.html


<!-- 参考信息 -->