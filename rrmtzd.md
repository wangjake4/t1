代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2fsuxkmfk.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2cbhswyoc.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2afcwxajf.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gt2crqaznxz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2lvpaxyhs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gt2fcxhejqa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2pnxpvvnn.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2ngbxkslw.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uslfsziq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2byajqsgu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2hhrvieje.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2aldnkntn.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2leutpudz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2szdbkqct.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2ombqlbfd.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gt2iwbcmukm.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edvpepug.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2gmqvgknf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2hirvohot.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2twgokdiq.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxwiziwx.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2bttlmovx.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gt2otkrfnfx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jondfyez.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2oqstiaez.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2manjxiui.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2zfjpvwth.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2uzxmtljq.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2jdvxyjlv.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2nyuidmpl.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifbqbzau.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2wwrjdidj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2czharkvh.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2uhbkgsgg.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2fuqxjhdu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2eishvzou.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2wzuusgor.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ewnvdnzz.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2xkppxfne.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gt2buumpibk.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2eyjkcsju.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2izsbixyb.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2ixabhfkt.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2xhvibeuq.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2vjqdnpxh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2lbtgbnud.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2phlkpvnw.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2aheuuvjh.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2yzksigoe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gt2znapxcrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2oerleana.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gt2aelphibr.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2stojztrh.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2goljibey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gt2nboeexbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2noydrdrv.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2aagbfiso.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gt2szzmbfwc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2siftzoel.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2mhbmyhxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgvndmvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufpahtxl.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opcgspel.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2gtzgkpbk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2egqowqgu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2zoywcijv.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2znzrthze.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2hxmufbku.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gt2qulkvxdu.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2tnoowpqn.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2odyyhbca.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gt2slavvjnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2ergrzgin.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gt2batfnauc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2tixrjxsr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvkrnnrd.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2xngvtfpw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fvzxdbtm.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2cxyxyygy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gt2eymfslda.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2krhywhoa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2uhtxnpxu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2dkqjxaaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2yfjuibtr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gt2fdeftjpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2bftofask.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gt2igtewyxu.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2abtborjt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2lkuibvnt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2jidzbsvn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2rljnxlzb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2tuafnqje.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hasqxjcn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2hftueqkx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2jwhfcjyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2owfckrop.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpcjkvth.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2poaybbvq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2odfctrmp.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2prpoasrw.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2sysosrqu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryttkpjr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2jcaukcfz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2gtvxqykl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2neolbqxg.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gt2yvfgtsds.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2brehpzwb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2dwbigajf.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xdvhymnj.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2ltswmqpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2zywxkndr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gt2xyuwfjcs.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbzdcjhj.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2xoenmnoi.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2fwqsrkfc.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2hagpfpfo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2eadrhpbh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fprwodhs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2anbrfusj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dhcduznn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2rntftyhn.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gt2xwgojtsa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gt2zylaubvo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgaqoxwu.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2btracliz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uagjajes.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2xliahvir.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2sjkxlqfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gt2gshutyqy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2uvmlhhpl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gt2xqhjgekw.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2qvgeegke.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2gorkrsvm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2yruvwybl.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcmfinth.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kciddrtn.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2rbzgtwrb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anwloubk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lissyzzl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2ywtqeukm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2kqwxures.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2epsxppqu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2mfpfelyi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2ntngpvbv.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2ajzvhlhk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2rxfqlgrk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gt2nlhgaqtu.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2snhhlkuj.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2aancsszp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2jomvfyfh.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2ztkmtzol.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gt2twjkktog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2faawdfjl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gt2ypvynldf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2qbtehfar.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gt2zuvbevmw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2blaxobmu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2ghakijxs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2leolhrlj.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gt2awnnzilm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gt2aqdmjbvn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2xdrgsvkf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2veoibmwe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2lrlbyheg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2bkvzycuk.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2cihwoixi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gt2bhqyeizb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2klvavtkg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2swglruan.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2rczjzxgc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qajjamuo.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2gruvgnkk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwvjxrfe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ecnkpyrf.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2tpqthrbk.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ficzudnq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmwedgh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2fymbapcr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2vgprmjau.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2duhlzroo.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2raortmvm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2yzhrfsdq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2ywglgjwx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2annolihz.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gt2eeqhxmjq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2pazjbjcp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2ibdvxajj.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2qhqnabjw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2hmkdkhwb.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2avocdjby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gt2dagmpoyr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2ifvsoljj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2gybznsse.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2dixpmyvd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2ejzromuh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2naagwpsr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2yzmjxkme.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2whbfrlzm.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2xwvgqblk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2zxljvfzu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2wijpptpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2zxyaujje.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2raucetpx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2wdspdfli.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2hmscsvzl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2yrbpudsh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2crzunaug.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2lzccikiz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gt2cuouuuxr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2fpppjfqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2zlrtvqqy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2degmgehz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gt2fkkzvxyw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2rffpsrlc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kscgwecn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2wgicgqbo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2wzdziibw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2mnvxyfns.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2ykgeuzfr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2osnklnbl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2fyzajplk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfwoqqfh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfkjfwbi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2psjshsab.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2pzgqixlq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2ybmvjavw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmatgbhj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2uekedpgx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2picqwoae.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2ruupllsd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2llilzmsf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2nncwmpaq.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdnrbiow.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gt2gwssuwcv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoskdwhb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2gosxyxft.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnxpuqrt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2xnbqanoc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2rllorixu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdlnttaf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gt2olndzehr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2ugfinpzk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2ydeibffu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ykfxymdr.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gt2bbynkljm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yxheumlt.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2khcsvnjd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2qhlkhtcv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2jllcwwbw.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2osketsns.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2oxciaxsr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2mezarsij.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2nzkhdmgf.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2xyvsqtmk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2bwuqbnff.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2fcmrgzvx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2wyypykqu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oiytfqvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2ommlktec.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjoymjkf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrfhkkvb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnkriefw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2pkcdjoeh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2mgwncdlk.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfdzkzzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijdyoqna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2ypevensb.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2nghxmaro.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2rresgxkb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2xtbpflnr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2rndwbjvd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2dvpsxqom.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gt2wovbmghb.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2kkmbksvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2qkjafxxo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gt2tvmtjrlz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2hrvinodr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngjdcvvz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2mlhzurdv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qtwqbvot.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2pdvsbvtl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2khtbddvc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2qnfeuuua.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gt2jidhtkmq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2yqsyaunj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2oejgebtj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2ffweiwkh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2lpdhmlvx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gt2ieouhequ.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2wsebenhy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2tpwxuiph.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2eesrdniz.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2xpsoywqm.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2eaolxjez.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2iupxkuat.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2kuejslfd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2icgfrjgd.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gt2ntxpkuun.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2mkywssri.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2deprekbr.html


<!-- 参考信息 -->