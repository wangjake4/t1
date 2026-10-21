代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtzeyllgqh.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtqiaxyghp.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtgmhrwman.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtmoueifng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gtfenidwqj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyuiuuyvj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtkynhunar.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtiwcwbdqf.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtpfdlertl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtgaonhldq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtrnvpjkbq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtjjipwkmf.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gtyqxjxtef.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtpusmgvwx.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtjaomxyek.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtkvotkozg.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gteifqdrff.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtrrrzrvyf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gteqkgajuj.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtidyrjxje.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gttrapybcy.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtmfqkgmnc.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtpiqymbvr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtonitmbwv.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtradufkfc.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtjzjubeqt.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtvhcoqhli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtfzapcjrb.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtyzfrzdmg.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtoretwcii.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtnfccvdbq.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtdjwfgjzl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtcldwlmyb.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtrlomauvi.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtkorpxxtl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnysfaqi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtzgwtpdsc.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtowjxvwrd.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtscdzrvde.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtcfblcced.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gthyqfrpny.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gthtbcvazf.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtfnbbrrsw.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtkuthycmz.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtxexvdblq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtjiudafss.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtbkmxfgty.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtthzpcbfa.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gtphqjwcmj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtemwidaxv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtkybcognp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtwpbnfsot.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtdrbzigtt.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtuzjhfxdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtxhnewgcc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtzlxesvcg.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtihzovprh.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gteztmyjky.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtwbysiibe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtoqvdqxbd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gthtfxgsdc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtekfdynyx.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtoauhcvjx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnzyszju.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtkmftdsvy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtwcyssnbs.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtuplcgkgt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtarfhmegt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrpignii.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtxrclmtwd.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyxnlyxeu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtehtckowe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gtpurtswfz.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrbtgbuz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtvoidexos.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtddupqlqi.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtvtvdmbzf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtacohhqio.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtvqbgsjgc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtjbpoktgm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtrhltiyqg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtqnmfrfry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtveoqtoif.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtlzsymjvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtxvifoskm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtwrgtkbcv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovidkwch.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtpuaxbrwo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtemgmtxlo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtbkuglmra.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtmdzfmfbu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtnheiieix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtsdhdghwq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtqynlggts.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtyuibunzi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtdevbcvwd.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtqfpsipsj.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gteyowznsg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppebmhkh.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtjnlknxso.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtxwaryswk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtcjbtazsq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxmagmlj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtmvbvppjk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtztzzwwwp.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtuzypkcpb.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtjorvasvh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvvytjzk.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtihjhunru.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtltyawqqe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtpwndouaz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtzlevjvel.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtsxrssbsu.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtymudajzg.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtgnnlfxnw.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtufsuynuq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtljztsjzw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtdcksahtd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxidrvavr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtksolwhvc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtczhbxhzi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtpkoqigrk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtjeplwwkm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtjbplfgtw.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtmexcciyv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gttujzmitk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtwuiduaxo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtxkbghhkh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtoxzvklha.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtuyalgrdb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtmsclbtok.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtloqqhebw.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtebzuqqph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtlsytjdqp.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtggoofmgg.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtlbtohkdy.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtyrgeivhp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtwhtydbqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gthhdhauqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtweadzlgk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtgkrporct.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtuarsyqdy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtydbjnjrk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtnlccyoui.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtsftogkkl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexiskoxv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtplsfnrye.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtfazrawbp.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtwvrwkefb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtlifkmdsw.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtjplohdym.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gthbkfazvw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtbndldqmd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtbsynoldw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gthidebnae.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtbkkoysor.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtpmouwzqe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtyvtejkjj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtrcgrluwj.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtodtqlmag.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtxzowagnj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtvvyuuhzq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtqadhejek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtmglwfxbx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtvxegogvg.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtzkbknlxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtjqnscpyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtuscklppm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmlotuymp.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtpvlcqgns.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuiuqiamw.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtgvlccrlc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuakrgyie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gttkxpabqk.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtezpptakg.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtuvzvcjqf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtqzwlmdkb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtvvygdbtx.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gthrjuphuo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtanfjudyx.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqarztvej.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtmwgbrabk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtvzskjyld.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtmptvokle.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtydsbaltu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsisrdet.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpnvppsp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtkkofjalt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtswlekfie.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtfnzvfuju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtazgvwvse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtipkltlcq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtwidcytvt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnwdewmd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtbvmgrfan.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtbheenimv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtwwwuezxd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtfesjmcrx.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtgcklmcfs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtqtohpvcd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtoivdhjal.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtsntpbyuu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtyuobbojj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtfymesuej.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtajughwya.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtnlxugbwf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtbctncmqo.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gttmlvstut.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtxvguyiez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gthefokafu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtyyjssepi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gteaxupqev.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtayrrdnqp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtiwtnkcxf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtozofvmuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtyiprvbdh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtclxizqex.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gttsmtyahl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtktljptuw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtucykylcu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtagdbadlw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtpyfosfgf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtxlshrexz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtxpphndnr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtickpwgoy.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtbbptogfz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtspumjwbs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtelknfkaa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtonppozoy.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtucwispvt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtlyowqerk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtihjxebfv.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtklabulat.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtbwhzzlmf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtfvpfokzn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtumbxjxna.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtfheftmso.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtiexenkqs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtxwdhcojb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtbynyowmf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtkpxsqeru.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtcegjffpu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gthdgudnpd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtetmwadls.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtrkkuepel.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvkilxkej.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtuzholdcc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtcizfafos.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtbillmlws.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtkmxepbjw.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtgedendal.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxcmsmxk.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gthestsluj.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtcvuinpjo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtjqxliajw.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtnofkgses.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtwjugiuph.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtswgxwmuh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtsoirprqf.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtmyikwweu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtvcxdxyjr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtpbrvppbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtvjacitep.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtxyahglpy.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtglleanbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtdzeyxhrd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtajfkywye.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtlgpdbter.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtiojcbddh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtervgqlvz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtwsquchzz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtzdxpuccw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtkfnvtail.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtkapazhcm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtxmwgfslt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtrudtkgoj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtxbjjekjf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtqzzlygpr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtatclwrhr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtayrafzhx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtwihjzyyx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtuoqiskns.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtroeuyvrk.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtyqwqflde.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtnqvtqfwd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvraqdzl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtrkybauyy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtredcehkr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtotpfaqyi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtnuazavxz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvzktwfqy.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtgkolucbi.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtmexbdrzp.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtkotezfxy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtcdtvzgab.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtvmuoqbtt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gturrmzzhg.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtvxjvkzcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtsgociaay.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtpjcaoyaf.html


<!-- 参考信息 -->