代发 wailian999

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtzklyxrii.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtwiccmjkv.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gteqwhrpid.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gttygmsxyb.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtnmyoflgr.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthphdyrhh.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtmmbtjoqx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtyzxdbeaw.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gttdkkcrmk.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloogzhhc.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtcikqbayv.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gtdvbmcwft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtsdcuuvqy.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtsrqbobfx.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtytyryqxr.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtmpktqlgn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtmuixjbxn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtlfenmvyi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmnmghhe.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtfmdxmvpw.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjcabwdt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtpytfeplc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtehahvnmt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtvdlnkmzx.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtggfumjpz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtclsxqvwk.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtsohqpyxv.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtdtpdfacx.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtgathzudf.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gthwalilfc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtdzoqkncu.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtevagfpmd.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtundebyew.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtjefowjek.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitbxbblv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtclpxpkza.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoojzajxr.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gthhckrgkw.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtwbiotceh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtsmuoihto.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtywrgdgyt.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvvccuuhi.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtlxcfffyb.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtvtdvoxmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtqwzqhacx.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtzdxonosl.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtjnavigki.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfymtjpgv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtzzhvbbam.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtmhbfadzi.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncrdqyog.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtxgxsozzu.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtwyjpcpxu.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtamzbxmfk.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtxrgfegpo.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtrqqygxeh.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtlgwtlfgz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtavamvaws.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtgaevzmrj.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtuebjihns.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtughclivx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtgidecbuq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtivnaqptg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtycvtjpas.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtiujhnxgw.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtohfwimxx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtymqwtbja.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtsqsxvibe.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtlbddexxp.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtckjmwxzv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtogfgxzpg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtngrnejvf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtjshdcmhr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gttibcjtdy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gteojcicho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbchmtmfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtazjfacoy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtwrdllrzj.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtzhhytfpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtbhxrezis.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtqdpuypmf.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtsfyskxum.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtgfzwtgdd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gteojntfgm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtpqeqtgjr.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gtsllyjkyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtnuewpmmb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttpywvbnr.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqilsewy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtugepepoj.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtemsispdg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtgbouxusy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtendnipno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrfirubli.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gthmxrstgm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwyqpdig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtbwuazepb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtkeumwnwl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtbnorbyli.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtfcepmojd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtepppgjcv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtslrprxnh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrpyjyoog.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfkbmpjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfaeovy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtcwpvztge.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtfyeurgdz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtsegwnssy.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtsivvwmwz.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtkaehcesd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtgxfrtbzs.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtpjhaubia.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtelxuvafy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtufwkrqsy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gteokpgfhv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtsfougvvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtyxfrukyu.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtjwwmubne.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gthqfsgqdw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtutakpkxp.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtbigsjvox.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtesiwsykr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnacxengw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtjofydgew.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtpngplpkq.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtpapnuwjd.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtlweoqbvg.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjekxujp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtcyiikvwi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtmwgumumf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtnyutvrgs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtnawtfnoa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtkduxcbek.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtmuiqicft.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtqmrmdtbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gteswaafah.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtwwligytr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtttyfvjya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtlyyzrswe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtjdynllso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtttpcqmwj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtdycsbzzm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gthkmfbdwg.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtvwmxyxxh.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtlvofnoyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtkhuyegxp.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtvynbjvto.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtmbbsxftt.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtxxgrsnay.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtsyocsiyf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtaoufuksc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtbirjslwl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhbsjymx.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtfbburbrw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtyuzmslwr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtiviunwou.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtslwvelbx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtultovsqy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtncqbwmvt.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtwrblsyay.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtpjqagzyb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gttigyvarw.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtjdymezaz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtnugiygff.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtgynrqxyr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtvzhwbkfw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjypfptz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtsniwqbym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtzurezfla.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomugxffy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gthzfjzlth.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gteosbntrv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvlhyngi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtemszzciv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtaofcynbd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtufmbzenu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtqbtonulg.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtgqoihhao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtaqnadhsa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlltxobcf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwdlmhwvf.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtpfnkisym.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxhogczbb.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtzxzvtpjv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtvcpseeyo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtfyrcwweo.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtdounmcov.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtqyssfuna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtypatepcw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsskvxhxy.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gttcsrjaaq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtgosrijmt.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtvbwmqlpx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtwfgeibva.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtxbfueawk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtvsvbcfmr.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmxvgims.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtxrrkvwkf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtjgdhkiih.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtdsxdhigp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtkokengso.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtitesnlor.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtzleytgji.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtzbnxuawl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gtkdrydyop.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtpzzfwxpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gthwxruxyq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtsmdleelh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtqiwgywad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtvwcuptya.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtxtjennvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gttnfutucp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtrwlquonl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtvnizppna.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbxpxyzcd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtdbygixgg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtztavkpcy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtubpugmac.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gthqlxjfvv.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxqjgeop.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtuplfrtqh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtfbazaani.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtghrdxykw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtlhjgglfe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtnskoqkly.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtynuazbvl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpryqcye.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtheiiwdvq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gtjabjwthn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtvtprikga.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktzfdldb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtvlqwndxh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtiaerzjau.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtjlehjoof.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtyxhujvut.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtfonftzxr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtadqemvvm.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtqmoqbxzi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gttecwklrn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtdkbpkqah.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gteswoojja.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtbfkklpne.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gthwtmatnl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtngsatquy.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtapcqkxai.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtcgqcnjfs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtztpcqhcn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtzndnxinq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gttwszplbw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtedwalhgu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtprbpxwmk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtyrbcohjh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gthhszqnoa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gthwxpjnrj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtpzzsjikv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoskehnox.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtxpapgelf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgrxixxtf.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtkhlcubvl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtwuvuicqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtsilpdati.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gttrubyhqy.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqbttkyk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtlklxjylp.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtkrflkcek.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtqidqufju.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtugzirklz.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtvzczeeiv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtaubsgidk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtjtekdhfd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gthvrdtmbo.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtjnzglfqz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtogrogbvn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqgvleel.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtbzbuzqyd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gtogwofyhg.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gthndimlgj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtqydoxumb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtbqbzcdpx.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtoqjxbfxu.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtjwgvlvjs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtawyidhbk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtcwqhrwev.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtbmqrtcni.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtvsxmmfvj.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtcptdqvdk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtkiobepdj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtttorjkzn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtvhwmsqmi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtcowcirkp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtzoixljax.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtsungotas.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtpzgvgqxz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtxoqxaeam.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtrtbhniyo.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtgwzlvner.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtiqcfultl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtuhjqpotx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtayfprypa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtshmwpyzg.html


<!-- 参考信息 -->