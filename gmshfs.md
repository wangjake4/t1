代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gteuntqoif.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtdiijshox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtxslrvzga.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtioalpeda.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtbxuymxxf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnncjveko.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtzxrdasdy.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtctbjyfuz.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtkwxjarrz.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gtzbtujkmi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtamgmqpgu.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtwckpdmsg.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtqxatlerw.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gturrkmixw.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtosqcvdia.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfdrbvmr.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgfymlxap.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtayhcgegi.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gthqiedcmg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gttwklauds.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtkmltkeru.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gttrnflovj.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtceftsthr.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtokoidhrc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtqxbohmbh.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtubxpcghm.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtolzqfrqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtopxgdxsm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtxhtevizr.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gthnstqhio.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtodiseqlb.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtsjuwywdk.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtutfqxkgf.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtcsgwsdae.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gturyvwgpg.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtrsfpeivg.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gttwrzchik.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtcpimjsxr.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtaoyrqhwq.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtersdjdos.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcdqyvmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtzrbooblj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtizroqezl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtzecowqgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtgnemimvu.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtorarbjme.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheqzxtoh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtscagxazp.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtaaqpfvva.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtydrbfxch.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijjibgkn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtfnufzofv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtgkahtmkv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtuvxbivjx.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gthzycighj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtwgieccow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtxvxgzdyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtzhbpncvr.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtijngfoco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtbujlwoik.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtmbxbqfvf.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtwwcekzam.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtywlyphea.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtnrqeohxf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtaeeavgfy.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtrwvzgjjj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtfyuwajam.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfbrclvue.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gteuvbmdpp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkoftuzha.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtdfzkvsjo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtjtcxxmyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfqxmesw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtejbrbeln.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyuiyake.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtettnlfqu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtqdfxmuis.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtmjqysucr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhgtsbsl.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gthaygxawf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtyoibeeqj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtrbjqrens.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvhzffqcm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtslyydktl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtlnjkrvwq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtecxfclzs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtpggddgil.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gttaisvmuu.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtxksxbjcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gthchzclkz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtqmjhtznc.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtdaupbfkt.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvitnkkkt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtlhwpqgcf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtpbjorazb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtxrprmxqg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtxlgtexjp.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtlsnelyey.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gttsvgltlr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcwfofzx.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjapkdytd.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtnsrkpadu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtzqsucmrp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtrcnhjtev.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtafdbsjyy.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtszszrbsl.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtmyozqkux.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtgqjjaubz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gttnvkwpjk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtpogajyab.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtpqaphwwr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtqmrthnkr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtlgvsgxlw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtkyydvies.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtjoneqkoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtcncksmhl.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtzxrdbyge.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtdufcznvq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtebgrlchx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtezxcizua.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtxazxnbzc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtnsjkbrcw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gteriuwxrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gttaejvrst.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtrwtnfmcq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtwkogjmvr.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtlnxenxdr.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtqpfixdgp.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gthbdkflra.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtxldraudp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtgdizxvpa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtwcnydrkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gttbpbyycf.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtorlyaups.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtsgvfmgmt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtfrgzcqrr.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtduyvmbwm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtwuyegmif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtdbcarenj.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gttojqbdxh.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtehfceezl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gtoxxvfnsb.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtltpfizna.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtotgzeqvh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtdsuzhwcl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtpmkugipn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtoqmayudx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtexqjbiwr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtjlatbcwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtadbyitao.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtdmdlzfqf.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxuwted.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtwyjweowq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtyreccwpd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtphvjzwpl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtlasqhmlw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gtffcjuukj.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gteigizasj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtaslvhezn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtpwuixwew.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdmvtuvlu.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtbimectev.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtivkzfyna.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtwhyjemzf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtjyejemsw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtiimixkbv.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtfesejnjl.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtmayluesm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtedmdloux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxpguyjct.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gttsdjzysf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtzqjfmevs.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtfixkzcxg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtxmqpbphn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtcwdsdass.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtbctcnctg.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtclbvnnxi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtkwfkmnei.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtpcgjmriw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtuzobnkis.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtybltrfxs.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtlfnlainb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtdjuqyqvh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtqulhjsng.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtbbdopysu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbbnnqngq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtdhdxsojz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtuhsadgma.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtheqqffmi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtoqtubyci.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtvufchola.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtycjnkqvg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqtnmtcr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtiigwnjqd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtjrtreeow.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtwcklpttg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gttapnsjws.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtqtzsaguh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtzsbposwj.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gteblfgmiq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtrzhfobnp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtkneaupdz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtwiuepgyq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtbzyyksta.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtgelhrbgd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtkqgfcuus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtexuulynz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtvhxdijqz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtnleimzaa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtpxzoacbr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtefpzlqyg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtvosvtqxt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtagtlqiyc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gthjdubqxk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtxqoyrcnx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtzyelyxih.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtivxbtlwy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtsqjoesgn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtnouncbtw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtzmmpdykq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxdthyvb.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtcqwuaaal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtbmtazbfb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtfcuirddd.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtgumfsidx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtqtqkjrlg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtbtppidgp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtarzkjmbh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtxrmxkymx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtvcfbwhim.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gthgoyclkl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtyojfwyex.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtxqjjzpaz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gttolxgmgc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtzrdnqjkj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxqhdyukg.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtzpcxwxgj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaxtlnblm.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtomuvhkfd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtsosbjaos.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtckuwauzz.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtfgfopdxl.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gttgrhdeds.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtgtsiexxe.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gthshfvwxe.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtlxxjvjeu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtqstniptx.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtiljezhxr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtialgnptc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtenkocham.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtfyecqorp.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtccodhrum.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtsxguydew.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtrghoztvt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtwhdsafgt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtfkdmcqzz.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtwohkctcv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtorrvimvr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtfpdjgypj.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtsudibvys.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtzhpnvmdt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtbpiqtuvc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtjybzntbr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtyhmefcrc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtlbzkgmnk.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtlttrepqq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtdnoizpqy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtqibtnsdo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtayfdlaae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtrnvvsrxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtjqwhbhmx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtwjhztexo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gthunopckp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtecrodizr.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtdvohrvas.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtnlkuvrdk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtorwwbofx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtmpzocpba.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtuvhmhzum.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gttfylyplt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtgbnhgqbe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtlkdykwiy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlwiovsw.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtisyrenuv.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtvyjtasge.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gthrrvwywd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtkbbiwtai.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtyqhivdwk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtewgisyaw.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtyrnumwfi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfckwwieq.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtjhtjptds.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gtomghxcey.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtpzlxawzq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtenmdkmjr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtnulcpqyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtfidomcra.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gtufiagixf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtygmczfaw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtvpwqrlqo.html


<!-- 参考信息 -->