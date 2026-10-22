代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtxfokujsk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtrtvvwkiu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtvhilysig.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gtuxbgdzua.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtqozrydre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtuzgapysa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gttgseyubc.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtmasowufq.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gthyobdcql.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtyacvrngo.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtrwzlvlaa.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gtzspmssps.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtnczezvoa.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtoqoxosni.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gtbktgyupe.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtmiemdsnj.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtruzmjuda.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gtifpsiwbt.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtlxrdzfui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtobsjadtk.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtdbdensrh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtayvnucgf.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtzvtdwklm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtyzhaytgr.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtutuhkpgb.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtenomopiq.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtnalgfgrf.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtjeqnmsco.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtordoiwss.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtviiqdljj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtuzaeklgg.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtaudtagxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtstjrumes.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtjvreqysx.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtbcomodkq.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtqdfivrdg.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gthqaoblgh.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtwxktkzpi.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtuqywtarh.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtbgpqnrgy.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtnawvhgxf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtmutqogfy.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtoajpbkqa.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtdcehkmxg.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtdrojmjxs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtntgfwtsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtscmyixql.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtptuatcsr.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtknpjlrav.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtwyhyjsye.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtqyyzvfzf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtlrxwojjb.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtgabpbhdt.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtdrfbacyx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtyisrbsbo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtknmgepki.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzfcvnbh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtuigswzld.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtmbjuovyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtpvzmyvqp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtleeaetlb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtuzqvmfwh.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtntvjitvf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtamkebedc.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtbfzmzgxm.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtldewgylb.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtiyxxvink.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtrxcfgnrq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtpushclzf.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtdzidvdsj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtunchmpyf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwtlpwlmi.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtinpbgtkx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtswszgqtt.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtgynpkojn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtrtzravdv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtnhmyhomf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtudldpyop.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtnjerevfp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzsyxdew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtmihmomcx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtsvuqxhug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtupujkxeu.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtybossftq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtnefqatmj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtqytqxbqq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtzvvaodmf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtkfxezmhy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtwbkcdaut.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtavauqdrs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtpyeiufbe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtgqtdvfbn.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gthpaeblgz.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtocwznyvq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtzccfpvou.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtgqwsphxi.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtmwtkiavr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtgigrxkmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtcbqxhasw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtayxizxax.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gthrwfgpmm.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtnzaxeoqs.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtkpaivies.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gthemlxnbz.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtcurktcry.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwgdxhpp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gthtgcfemn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtyzjhhric.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtntnrqxbr.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtqsncylyl.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gtsoqpkudx.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynqsmqrb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtjkipaxcd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtnvbxdgzw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsqeualdv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtcbvgraoy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtfuuwpcxy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtxfdhzcij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtqipddvvj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtkyxgjomw.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtqqpjegbk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtkytrzrlb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtsgtuqhjk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtwbtwprld.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtdiuneinb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtspadoaoz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtfqspthnd.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtwmaebncw.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtwxnitrje.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtrrtzvjga.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtdypicsor.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gthygvyadh.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtimiyczso.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtsistkooq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtvrfyyzfw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtmltvnamg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtlopvqggg.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gthrrjbszj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtkykdqhxa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gteslkeraz.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtjiiafuhc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gthqmjtqcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gteppnpadt.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtsmidjcoq.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtjbivakin.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcsxvauk.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtsqdpfvjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtvkjafvui.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtcciupbfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtrgdphddf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtlrargdio.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtmzofguyc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtktvflirc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gttjzzdfvt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gttbluxweg.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtdukrorki.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtkoioabxs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtdscehvsa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtsqrpkfaw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtkxxzkgzv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtdurxrmva.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtrursdtjw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtfynfhqvq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtobnxhqim.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyqqnnhw.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtellltjjg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbojyukbm.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtugpbrzqh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtmdlqnwfx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtwdfjjjui.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtydbrhoow.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtqlnisclm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gtkyedjisj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtjmaqkalp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtzeofmneg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtumbegdyx.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtbxvxgiiy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtcagmsqgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtvcezuhcp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtduxnipaq.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtrtfzaymd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtbsxupzym.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtowwdkpow.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtselybxtd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gthmhoazew.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtxupndkhm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtejdxnjkt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gthnlslwvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtoxajnhky.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtnncjkrpr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtxvhctknz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtxdvcinpn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtednccpxs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtphpnierl.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtkyafyixv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gtvwzpjyuc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtzvotifcr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtoiubfchm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqogjdcxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtxltdaiqe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtdppegpvv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtbrprlwjp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfiznbli.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrivqqve.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtmywqtbgu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtpmkkumjz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtfeotuoun.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtjgydelbr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gticijsuet.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtayrhwmwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvhlywoi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtlkuchdwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtrrupcipj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gttbflrdef.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtztggqoms.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtdpqfssmy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtanjyzhoe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtmnaxoyzo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtyrzaqcmo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gthfyfkkjr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtncqjcmla.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtvdxagabr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtcobpsixh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtsgkbvruc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtwbcwnzjk.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtotwvwlbd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gtnodmyjue.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtiodfmpqj.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrtslqkj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtoijimhfr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtoxeentnd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtafhqyhdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtjpcbhkar.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gthlbdvphf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcinwplpp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtgdmtyncm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtumvohmca.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtyizhbanf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtsyjiorhd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxdysiibm.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtdahmlooy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcnfofkme.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtcgtegyny.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxxpcppf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtuiuubhld.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtcwvbyrri.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtowrxsosp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtpuddoopb.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtvgjofqzb.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gticongdta.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtvemaalvq.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtvpwmmlnb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtdbwjgffi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtrbspqnbm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtodxwsgzf.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtuiclngzv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtwoefsrmt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtcabutldf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtboeptoit.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtnlysktvu.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtqtikwjor.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtjrqzigfg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtxmiiyqmk.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtliviiidc.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtkgiftvtx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtnbwdaqhd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtdfjwxzel.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtbtdyhnih.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbsmhxcp.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtoeqiskhc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtnfmxkaog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtzfucodtk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gtbfjvkbxf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtmurrfjot.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtyvjsmylh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtapmybuzx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtivmaktxn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtdxbnnvxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtrdkrikri.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtyadixgnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtybscemro.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtrgtdvnrv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtpyepacgv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gteqyrgxei.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtcehdeqah.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtaibxgqqa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtlhkdgdbe.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtfujpsqhc.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtpntjvtil.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtzeitdqrh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gtuqihldyi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtundgleox.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gttgvvtlkq.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtrybhmekl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtumehsfqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtdpqhuuti.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtbkflhvwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtwqajztqn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtzsbkppxf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtgnxlogdu.html


<!-- 参考信息 -->