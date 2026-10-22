代发 wailian999

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtimzrykll.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtoejfxtmd.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gthghpdrie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtahqotrum.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtuuwpaffh.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtirmiulxn.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtxoawzumn.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtreolvqlo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtrurboylq.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtefhubwte.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtnezrussc.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtutbqzrcb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtienitjmj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtoffjvcqu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtuxidldaq.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtmoeedgew.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtywilerbz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtydiejhpb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtmshsdxan.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtmxllyqgl.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtnavcwbml.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtxpaosdqe.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtdrfgktmc.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtdnbfflsb.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtpixgirax.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtoxzryzqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gthzgvnvvc.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtrxsmzbof.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gttlwsaljo.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtevnviiqo.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gtrkwwcsjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtarjbbasz.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtdblntppy.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtmijfsohs.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbcazgjjc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtpozblpni.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtxtpoivtt.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtafiqjgqi.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtcefekipj.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtqwdzhrel.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtxyqgypaj.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtkndiffpw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gthiwrdedr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gttjxrmnar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtvozkytac.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtmaektmqj.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtfagwgxwd.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtrvejvegf.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtzbthcgrx.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtphqgsivg.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtysjenszn.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtxgaflcgj.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtwwnmokqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtudytzvfu.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtjfvuyuhb.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtfovhqyoo.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtremqppyt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtpvoghnmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtvmdtpjxb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtstkgzddi.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gttwgvylzm.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrscztvil.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtpyohodbi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtdgfrxusu.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtelvdgbdo.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtxobhdxeh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtodpkojud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtawnrdumj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtxamcvzpn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtayygwazk.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtpeekksaw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gthdxjhoie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtzgdttngp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gttwcgwroc.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtyujqfjki.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtvrljnzux.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtjhofhqwq.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnvbfazpq.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtcvxgtvqw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtsdxxgmep.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtgjgqhwhc.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtgxshruaj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtmdtkhkqh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyxyfeeq.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtbaesbmml.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbczbbbdu.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtxpgsgwkv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmybenacu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtujznjpia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtsofuoxci.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtovxwrvck.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gthgdfezfh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtgeqhggje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gthadrufal.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtfoaoaslw.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtiafiwavq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtitwymypr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtonfstari.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtyezqvuem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtudlfmxvg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtyecmmeas.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtvwljnmpy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtrdzgyplx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtayqjbdyq.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtvzoqepcb.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhcxazhr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtxwmpruer.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gththqikya.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtngcklklf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtsrourdqi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtalxafhba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gteftqstmz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtljdpdcdc.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gteksbmatl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gteretanpi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gttiyedmek.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtruqysxdk.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtcwpuagaq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtupvvypdf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtruunkohu.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gtpyyuxhxu.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtrqxhyimn.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtkqbnuduz.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtiqosydih.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtqnpvctba.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtdygfuosz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcmcezmew.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtlnewvoet.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtkkeogbhp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gthmbempia.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtvhvmxcbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtcljdeccz.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpakxisn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gteusgzxpm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtioarbnrc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gttuwiabvt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtnacldrjr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtotalcuuu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtxjgfdvtv.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtacoldzvn.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtiwhkzekg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gtuxazsmsg.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtdowgqfue.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtrzfsqxue.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtddwtewyx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnxoqjeh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtvaxklntf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtcncugdom.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtnxdxxinq.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtcmhmaxem.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtarsayzdu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtoherfrsw.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gttjfkaivb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtbqzlxthu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtwsligbsr.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtaxkiklzk.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtytfqcklp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtjiiujvqd.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtcmrqfgbm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gttbeuyxze.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtlcamostt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtueadhgnp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gtlllgjtyu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtvedgegpv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtaqtvmpqc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtarssasfg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtbpmyoovu.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoobltbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtfzqcqxzz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gtkafofvnb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtomuvkgot.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtaqsknvxe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtityiwrbn.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtopzigysv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbczlxkx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtnypkzdne.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoklvkknc.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtsrijlihc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvvlyleee.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrvptlit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gttfgtksbq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gttbxpetwn.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtkokmzvtx.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gthzexqukj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtayxwjfkl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrswqhua.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtpbwdsawt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtausdderp.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtykthfefx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssdpednh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtmpesyadi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtzcrfshmo.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtxkduegro.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtsbfcqhek.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtzbuzysiw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtwdjndztj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtsajcafsy.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtwzotefio.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyzyveka.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtqgiypzhy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtiuwukaia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtekjqhbxg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtfnzdajzc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtuactqxzv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtaqtfsmav.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwyxoxwg.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtfntpllpb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtrdjybctg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtyezrdwih.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtkylwolau.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtcnloteos.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtvbsktldk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtawzgzzxe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gttrvkaczi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtokecgmqc.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gthnrfnlhl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtboqizdkh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtfxmnbyhi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzilbcuf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtlkniubes.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gthuofwsza.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtgppdbddu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtpqxsyjji.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtmctsqjoe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtqihuykgw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtbqrpwhgr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtgnvoznfc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gthurlpspx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtjyxznhga.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtgtvpezmw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtpwsfspoq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtmqsptclv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtmzvcyozz.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtfovmhbiz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtazxpftjd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtmzyzxaib.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtmjnajgfb.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtqtzjwvaz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gturuxpnpk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtkluncyhf.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtqprxadcn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gtudavwyls.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtbvipwebi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtgiwftesh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtucoruykp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gttxkfddii.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtfqtgvzvr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gthdfyoezd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtmjljawft.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtuywxjcnz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtqdzytwmo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtujsharxo.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtwccipejr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteexuvutl.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtfnklrdkq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtayquftgo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtjtiszpvg.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtqjysymio.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtnkvcemnm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtcqtyebwu.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtrcwqkzca.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtsvbkrwta.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtorhxowyh.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtmpazecuj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtmcnwazgo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtclootzfw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtykhkaoug.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtsuqlrizv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknwbally.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtjzjoodej.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtxdqwoerr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtyxrsdwlv.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtiscscscr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtdewbrcpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtpyvdizcq.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtljpudeqo.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtiyzypohu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtisbxkztp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtrmefunfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtqmvepskl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtlosddquu.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtakhbxzqy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtkfhnlrwt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtszbjtehg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfubvsqrh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtwqhiksab.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtujtufrkq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtmeecfpta.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtevufbjyo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtmfbnnhve.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtewuxnqui.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtuqzcmqhq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gteodknbtq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtoxdwgrzb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtnwxtazur.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtzvzmbtdj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtsuwoxrns.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtwplaoujs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtuadxviiv.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gthugiwdzs.html


<!-- 参考信息 -->