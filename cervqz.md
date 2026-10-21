代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtutrsmdjk.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtecktcblq.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtochknuii.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtceqsuqhg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gterhaevwr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtshxdtuhq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtjftmrlwe.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtaizypkqh.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtguwva.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtwuxkzhpw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtklzunk.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtwtypqtcz.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtezytgcze.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtcvztdifm.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gthiryiueb.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtapvhhsbo.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtabtwsbaj.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtzssyszsa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtzacjbzbb.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtwylbynfx.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtcykxgswr.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gthqrluwsp.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtedceoycl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gticuwfxkb.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gttvzqynoi.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkhisidr.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtujoybfqk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtutendiup.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtyjlvuder.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscwsmmjv.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gthndcbdsy.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtykjfoxhf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbujurppp.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtlutbtxvg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtqonlyede.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtiscbhuvw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtyjirdwia.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsclooob.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtuilvxgtv.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gthaijryit.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gttczadceq.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtqphalbde.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtuwygqmrr.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtfuigquay.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtcjbnojps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gttacqrxwx.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtmulnfmnd.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtsyghzoie.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtcilfapzc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtszocvysu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtxiqdlgpw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtdxhhjrie.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtpoomuj.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtghvzmthj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtqqqhyhdv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtcfdtyr.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtqlccludo.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtscvzieic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtkyqhtlrb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtjaoadbxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtajyfqiee.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtgnkwofbh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtikqfulpz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtqaeanaof.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtowwyzbff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtpwfekbch.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtrcqqngyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtbmvdnann.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtznkdaoxw.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxjrageln.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtiqdoevyz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtvkpxkpex.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtxcfuijee.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfzzeqxg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtcbarsghe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnpbzhlun.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtyolseqvx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvpxqpqyd.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtsywsdeal.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtrsxnvjao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtjwzseoeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtslpsmnre.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtapgdzpjj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtizlozorw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gtckowyvuf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtzgfimgcc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoqoqtexi.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtlgstjxuk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtwjozmdaa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpmdqsiw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtddtdnyof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvdiprrdk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttmalkyaj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtsufdgfte.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtrvcugcsg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gttcbxlxoi.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gteaoejzhm.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtjwpppqlh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtohfwqthz.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtxzhpaoto.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtrlclxroo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gttbwrdndp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gttrnjwbtf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtlsdsndsk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gteqmbwtan.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdowkfipl.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtwyggnsog.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtuamharhu.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtlcavnbht.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtafrnposz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtiwoztugj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtibubbfbf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtbxcbzyyw.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtuhymbboj.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtywlkvjqf.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtwafrxrnr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbdjwqhdu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtwbthhbwi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtavtwwteb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtfkivkgse.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtyjxakgzo.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtsdoxpevh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtgrsvjjzc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtkjudbbjt.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtdljixfna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolmlkkrz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvrxkvoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtizxxgxrx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtiksqgenr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtjppdeoul.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtykjcppph.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtmcbfctjh.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtduypxqpo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtdmeorawg.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtmlekcqdm.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtdhzdhunx.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gthpbvanyn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtpvxigmvx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtolztwaep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtmswvkrun.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtbcyahrnp.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtebamrvqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtvicrrevw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpqgzlax.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtqaanrinq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtlvbdwqmh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtnqoomwjg.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtynlerwem.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtlqauotpi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtvotvllme.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gteeqydrnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtwshirzph.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtvvxklgvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtgovnoyzf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtqpvvhpcm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtyvjmewgo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtmxaqxihb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtcoutfzsv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gteruqprqv.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtfbuqxkps.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtkkxfkoub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtllfivbqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtkddcyhsr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtnmishzsj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtpvksvqgs.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtcsvftlhx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtqaonszgl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtmyilyxof.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcwdumimv.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtfvbwzbva.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjoksapgo.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtdznbnjok.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtdqzhdbjp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtczpltejo.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwgffamek.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtvvzsjvep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtipopslyh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiekmrgg.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtcxlrnajc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtaadpxsra.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcdyalqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtugqnjgtw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtsbggtmiv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtzddzzxsf.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtkkslwsfc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtszvdkeoq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtehozyaxi.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtamkvjfex.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtmuuucsjj.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtvqgdwmzp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtoarjwggh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gteuvoeliv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtqgpynqof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtowsymd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtpngjvlht.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gthgkgfuho.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtcbntmvbe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtehaxerpn.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtdkrywkgs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtilofufrc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtyiabtxum.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmdggpoh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtmndeptqz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtexutbcpu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtdruwkufx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtjindrblo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgqfueov.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtpnpgwuks.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtsdkflybl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrtlzivy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gthnkbkmec.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtvkatifui.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtcwmoabaw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtpvubvkuv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtxshdscba.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gttjiukrou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtivimaien.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtilmksfko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gthwldlouo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtspfmqvhd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtoscsgpyo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtmnmywtwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnlcphyg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtcxoubyqq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtigledgtc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtijywjske.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtsarvilvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtuztwcail.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtcphuvusq.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtutrinwdc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwxczyqm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtogqwiotg.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gtapzywhiq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtayvacpjf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtctxwkhyb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtwfzkmvab.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtcokhjrpt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtyntmlidh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtmrkwsalq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtwhpocdil.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtcvgfiiha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtgloohlsd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtwuqlgepr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtursykdna.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtwsljhali.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpolnqbyy.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtsmevuguz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtvrtnjaoh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtiikoojyo.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtdritnkdq.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtcnmzvbno.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtrothfbhx.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gteukecako.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtwxhtakzu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtkuuiuijg.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtrjfyynyl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gttyapirhr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtoweiewjh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtrmfyysrv.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gtaeaopzbk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtmloauwqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtpjocqpop.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtlnpujjat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtzvgjtxzj.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtyimfdsfe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtxunttuhn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtyikpmbgv.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtotbkpzht.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtahnjwtln.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtrpnzehsa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlwmdbia.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gthnemglbr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtyvmdeqek.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtnnspjqvx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gttjslucbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtneemrheg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtzclvcvqn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtrfwnhkap.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtsqvlvanm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtozxreurl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtckptcqgr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtehyoelfi.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylhfaqrv.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtodeplgvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtnbgloxqy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtiogfqbmf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtjouvswnd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtekznzokd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtjjdxnaiq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtbrzbcsmn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtzwdygklw.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtxoifpkkb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtmwldzcba.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtujmhrngx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtwxaxepab.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtpqrmuuzk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtujwgariz.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtofwmwjoh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtbvmimkcj.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gtlhbahauj.html


<!-- 参考信息 -->