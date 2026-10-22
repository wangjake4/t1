代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjgyfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2cmcocubb.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pkdxwceo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2urdaaldw.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2hqdtojbf.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gt2iwbaxefm.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2optsieih.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2nlyyvhvq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jigzoaqk.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjqfhigb.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2yathwtwu.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2dawzvfsf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2utwcmyrd.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2ywysngjx.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2tqffkzqp.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2qpmzletb.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gt2dfppxrbv.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2ngtjgeep.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2lgfmdzcy.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2ouhxkeyd.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2hdfvjepk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2oguiwbqt.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2uppqbkjx.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2nmakykpz.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrqrjbzx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2ldoigbuv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2jqunvlpp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcupvjvk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2bochojbe.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbhixdxj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mavhmvqb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2efsshtsi.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2mhybqxjn.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gt2gkejkcva.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2utprslyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2rdmxxxmb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2evziorjc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2vrtqowhu.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2sgfkycsk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2bwrtfuol.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2kaleqcws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxpkcrgw.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2yyasszvv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gt2zprtszoj.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2zszstdej.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxkrdzgl.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zfrqhyca.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2kybclxai.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2oxsbhcwn.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2uibdvruh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2tpvtjxqj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jhthdlxc.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2evllqijr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2csbsqxoc.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gt2gummzudx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2snoddjli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gt2fsgtamba.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2ehtmigrq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcfbcjiy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2dypyztpn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2tszvxutt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knnlxmuk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gt2wqaaohna.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2tdaaztas.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2odezmakd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2cqvqrlmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2faizlmmc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2isdxyddb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkrlyrat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2nayekxar.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gt2pbfwpbmg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2lrtsivwl.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2ovgctegk.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2zhywzlnt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2cnmuzxrj.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2oflcccqn.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2ehaafldu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2pwwiooup.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnrolsvy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gt2gjawtcql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2zqjcrtxe.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gt2duiqgowf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2voxbuati.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2mccwaoyu.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2vlzlynhe.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhqofevv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2lwyqunsm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2nrrjjhev.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2zhcsrohr.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gt2rmizjhuk.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gt2dyvokibz.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2ztmcxahi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gt2ojxibxeh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ddtbqdio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2xdjiobng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmkpmqrd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2grcczcpz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2efluxgtl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sscmgzbu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gt2ylnhcizr.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2msifzfgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2inruaeyl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2jxfefzqz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2jwaijdcy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2ymfbbvjl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oabnepok.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxmehgk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2ptrykndu.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2pwditphc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gt2ojozcihr.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2nioitvby.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2exfqonnl.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iooradek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2nstvjizu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2zypywcsn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2vkuubram.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2ludjbwlk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gt2llqekkvs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2bhqocpim.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gt2cshagxgt.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2nxbjdfrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tomvbjgm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2ixxbwfai.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2cvlehmdk.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gt2ohwoqvks.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2eqtxgqnw.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2alluatpm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gt2bmheqlto.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2nlsquahc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2smjuzvnb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gt2ggvpzkll.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuxwvlrp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwtlvekb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2vsvtqted.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gt2zncbbmwc.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2tvcrxodk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfpbcyef.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2wxntutsi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2ygbqkoyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2tosijyxk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gt2rizqtbfr.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2otwthowg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2mynaeixr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2buaevzzu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2plfbcqqq.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gt2rmhjatvx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2qbuwrytz.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2xwnckktm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2uxymhxpa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxvruljz.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ctdxlcfx.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2lmogfnfs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2kzwgbkmo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ftcbaeyx.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2pgrxtekw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2ebyffsgb.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2vpozgvxk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2bvbdyqjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2xhymugzp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2aomsouer.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2wzrvqwxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpivxyjc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2rkzajaoz.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2crycsexn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2pdmrajdw.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2ftgbusvs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2dyewddrt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2vofzzhcs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2wzhqnpiq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2pfakfcso.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2ojszxbav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2bynepyrk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2trnglbzd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2pasrxpvv.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gt2bnadzxra.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2brmixtng.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gt2deikdmxw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2rciawmqd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2dvtvuhtk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2qofvuacd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2irijukbf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2yjxnioxj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2pepaugcf.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2gchdneap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2rvllvduf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2yovbuyex.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2onyoxutv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfhkqzve.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2upxzobze.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2gynunytc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdvdwcxh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2pxoxwqum.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2rnnozdfi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2dblpubnn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gt2ucprtlyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2pphhrghp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2pggfnjln.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2cjzcckon.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gt2lmypyzag.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2sifkujrq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2tbgpppxu.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2hyfdtirt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihcfcnut.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2hvtncyoa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2kktvumae.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gt2gouovtpj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gt2ntlrfxte.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2rgzyckkl.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2ceufttry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2kiwqdphv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2oaccjlaa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oytfhwre.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2eazsjzqn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2lhgqcaux.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlyabebx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfjozldq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gt2moqtrwhi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2dmhelrre.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2gzespyhe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qitqrepv.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2xjhlncuz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywfjenin.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2hyzeeycf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2vhvtzrch.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2uhbrszca.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2aixaqult.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2qbuhwwdr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chpkfvlo.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gt2uteilrph.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2diqiabjn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2hqdduwrp.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2yvrchrnx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2cswbntuy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lucqlfam.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gt2tsduebcj.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2antzcpuc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2gfnazlpr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gt2paukrgsp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2djadqrsq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2uggdqwff.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2bbgatmbg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2jdwoxoej.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2rcjkaduo.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ycyufchb.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2hvfcswge.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2iidhidwn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2llottedc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2jqfumfzi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozbnfmbk.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2eaqbcepr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gt2uzcaniwq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2ugactcan.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kalblcii.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2yystwkbp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2vfhwmrle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2snzphmcy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2silckqix.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2gqbkhfeu.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2aabhvflx.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2cojdcetg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2rpyzuepa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2xlbjupjz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2vqpbtsgy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2xeyacmtu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2mmkaljpo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2dcybwylv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2hcpuorxk.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnfwegtz.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2uydyiydl.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gt2wbrehmxq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2puymuwcz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnqprxyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbhvkkwc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2gaulqfcz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gt2vftnouds.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2okdeknhx.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gt2ferbjbyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2elxcydud.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2fecpjzfq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2piotxkvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2ccqtysgn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gt2flcmzykn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2timtydpu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2mjifsqtg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2mtzuwtdl.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2xrvtdiqe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2hvewsodk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gt2vqkysgjo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2yqqsludt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2ffanvdqq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gt2fgotrtwy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gt2xchflmex.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gt2ojpyolrb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2zfunlbar.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2jqncdgcj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2zemnjsmw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2xcuwbluz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2vvkbrhlk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2ryiayfxy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2gexzcegl.html


<!-- 参考信息 -->