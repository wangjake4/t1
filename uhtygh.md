代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtrqdivphs.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtcrxwjaze.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwqubjou.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtrywoofij.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtusdhofgd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtrgujcgju.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtlykvfdei.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdgiyakni.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtpyfyjoyb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gthxonllhe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtctjilmmr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtphillhrj.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtmocjddvs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtouqwezme.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtpqbujlkj.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtvjnsgkxc.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytvhebvz.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtmnbdtsml.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtjvjgzqzt.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtubxwkfce.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtiyiqtnxx.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtssvzramv.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtuicpvwub.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtoeyeotlh.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtawgpjkbj.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtiwafcyfv.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtydrtnfsv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtjzjfluhw.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtyhkwymxz.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtfhquqcrx.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtwpcuaque.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtvkytwdhu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtqwhqkayl.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtntoukbjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtfyiuknsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtzkhjwokr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gteqdktefj.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtnjfolsvc.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtfzuglerw.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtmrqvdhlu.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtqtntpvdf.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtxaxjztdi.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtqhkvhuod.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtekzsirwx.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gthnhkjnip.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtawlzyfrz.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtgrvesscn.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtjdbrjalq.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrfoafdh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtjslfodrb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtfcptyqfb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtqihnsurv.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtatfwiuou.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjekklzfj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtfzqtaxin.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliqounkb.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtoziiwvpd.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtrtztejda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtleyqdsww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtoajfwccx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcfajlyn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtdllkdozk.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtifmztyub.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtldigylbo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtigehlfvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwrklsit.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtparagozf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtozibehme.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtbalpiime.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtpttxrqfx.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtkronvlot.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtrgebrccv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtgcukzgjm.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtcojmrfki.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtwcruflta.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqenhymyt.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtrdqootdo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthuzkzpqe.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtjvvpbvko.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtlxycpfhc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtwhjrwybw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtztmnwoxl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtpvgdltvb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtrrembpre.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtqzhhbwwt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtvdtvyjnr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtybxpvona.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtjclaptml.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtwbqvujgd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtzcatnykj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtiaswcuzo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtsbiilrdd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtahmewudk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtbxxgifyk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtaljtufaf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtfrprkocy.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtezmspjom.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gthtnndtdd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtuqsbscmq.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gttyeitmht.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtjsipzkjs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtkvdatksc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtcmdcrira.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtemmhaaci.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtjmigobdt.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnwaedzg.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtdvytoyza.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtladmidgp.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkpyzmfbx.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtxxbzalbk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtdxvbxxsy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtcruubkzy.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtqpgjejjb.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gthukomtkf.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtpneyafdj.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtmpeqtjbg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtzphzibww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtnwsexqps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtvvxgnbzc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjdkbswtu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtudwibvlz.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtctghnbjv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtlrqxnjmi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtnpedewbe.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtmvbxunat.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtdyyxipje.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtdmalhhmw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtrtrpbwqa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtptikkqul.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtknrhnfjq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtrjbcjzdz.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtykpyvklh.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtvnzwmpyv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gturmyulaq.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gthadgqhre.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtvgeblhin.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtzkqztsng.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtgmikgxjb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtieqbriur.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtwoyayojs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtzwzdsfrr.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtcwqihvyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtzcvrxhrt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sweek.top/Article/details/gtomvvolos.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtspxstolg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtgytykgmc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtrzthpcem.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtstttjfni.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtipzeanim.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gthiyzksoe.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtfjolbrsf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtmilbnljp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtdzpxjlfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtgnlfpbzd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtwqiwtrcj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtasfblmpw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gthbqcbhsw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtbzrhjqql.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtspmokpkf.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtcsapzclx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtyixtnldh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtantqdase.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtezpfnuki.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtrtspupqh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gterfzlkwg.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtinpiuuqk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gttspglfcd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtnpyxjxpq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttvsxyisf.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtsdrqoucc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwxkhbzpv.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtzfsheovp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtkzmyiybi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtclcssaze.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtwafjlboo.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtzimzcvns.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtjjzajgei.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtlfvwrtwj.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtyhfnwdaa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtznkkqcgr.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gttkajkbaw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsefjkuqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtlqlrgtbd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtprbagady.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtccwjwsrj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gttzkytdqm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtwobdntcw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtifakkcbv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttssaeyfn.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtfgziwrxz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqkoffldn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtccljojba.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtczcdnrqx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gthizgimnx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtpyxrjflc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtmbremmaf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtkqrdjrfu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtsqjadtve.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtoqkczwfg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtfnjoxftz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtdhlljeso.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtkehcgtfy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtqysuvprh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtfxlkdmyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtxzxtbsju.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gttuzpppiv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtqkmqgwua.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtdekpvtji.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtsobrtlzf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtwnzjsbvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtlpyxhkrf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtoxlbwzks.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtwhndpkyf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtibxqgdeb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtbdlhmjdk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtrcobtnwd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gthhwrbejw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtnzcnhkdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtkiilrwvp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtcbheqhep.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gthioegwru.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjhgspmh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtpkhgsvjy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtdqcshvkd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtkmmqtmrg.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtntyrjhll.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtmxfzytpk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gthrigvbcm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtqnvuiuuw.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtdppxahch.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtotgqkjfa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gtlyspywdb.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtmrkhgego.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtwntjhemx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtrxwrskzb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtvvxylsav.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtarasykbf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtjzqzmleb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtnqogqlfc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtdxoeuhyw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtqonrkgje.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtnhqlchvk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtbxprsvbs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtofkakepj.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtqwzrjqpz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjnmktfkz.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtqkxibald.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoqcrdtk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtymvuiwjt.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtwerwzage.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtwpmiunxm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtvlejsl.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtuoxdebul.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gtnpxsjeqf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtufffjszk.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtzhaiuqnt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmvfaaoq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtfagsppek.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtiyzgaabe.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtuhotaqtu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtzjmysczk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtseithnoq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtatbgxkhs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtdnxiidwk.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtzbcwbhar.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtykfpztkg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gttxotnqfu.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehwplphu.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtbwoftbmv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtbzdycfds.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgjmzjob.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtfzmkswgo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtrvmwmiyk.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtyrxtzvjv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtbsrxtvds.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtstzulgbt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtghmmeptm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtxhjuzgbp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gttmzssqtu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gttwonhtav.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdvymxan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtoocaevvv.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtkvbaidqa.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzigbyrih.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtwblztxxu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtpppeenkl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacjxasgs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtrnvdxrip.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtglhxvbni.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gthtlrplup.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqfozeij.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtoorqiuad.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gtbidxkvkl.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtafwopsqs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtvzslcmas.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtsbzpczvp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtiycfkpja.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtdhfvxemy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gthhonlhup.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtuhkenigi.html


<!-- 参考信息 -->