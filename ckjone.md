代发 wailian999

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtbqorannj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtxfmwznjq.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtfxjjijwd.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtxfnalbrs.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxkpduxp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtbwlxiexo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtficgjifs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtxwuwgpdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gturplmmpy.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtibqbkzco.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtocyluqxz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtbyygnqrc.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtejsmydmb.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtzotricyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtxnmxdzxy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxumednrr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtzlcequmh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtsahtkhwg.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtrsjbpkbg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtylafjpmy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtoziibfbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtgzagkhjh.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtttqtkwda.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtrxbkgxfd.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtytgabzkr.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtajzzejed.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtidhhhkcw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtybcqwdfx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtpzaobtgs.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtjjhkbggo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtgytxpyby.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgyziirao.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzgrvwcw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlprdjfym.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtgmhcwsoa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gthbxoqxqe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiwuhrgzd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtzkbkorvr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtvqwigrfo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqponidn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtyyxsyprx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtdmrcbuqj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjwtekql.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gtiukiyozu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtqidoqyzl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtlbmvjvfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtabzduast.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtkxqicuzu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtaobbjuis.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzscrznn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtyeecngun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtzohmhaln.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gtthlhhuyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gttngkxrnc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvezfiptl.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtxlionmdh.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoyojbgq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtgfzwsjcx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gttnigstki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtvpbjipvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gthcndrlam.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtlbbkqnwt.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtssiianqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtacezgwkl.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtefvsgtyi.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtfyjhqaik.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnxjcscrb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtdfzxswml.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtkccmzobw.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtoldprqxa.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gthzjopwau.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtfjeqdkll.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtdvzhhpex.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtfpisfufj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gthvmkxdgu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtwicawdbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gttfvbroax.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtrhlkmcpo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtylvzoobe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtqgorrohf.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtjzwqapfi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvbcowgo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtdbtbwvaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtqfexdutg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtquovywas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtzauqocps.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtpcjljyrb.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtduuhpjox.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtmcllekmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtyqalrzbb.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtbkjjnftl.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtnsthtnro.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtseieldfu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcinvjcew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gtixpgkaxq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtbjymjdfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtzjusjbct.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtotcdzdeb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtayfmmwlf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtbstnttvm.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtpyigdmvo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtvfnsddgn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtdrcjcljq.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gtbkjncozs.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtukhucvqz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtlnqbfknc.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtwjubhlzk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtaksbfjgm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtgdjqcdem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtjpyjnobw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtbubracox.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtgqpnckwg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtderfcudk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtgieemuzf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtzaawzgdn.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtqsgilimo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtyafhatyh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgaryuox.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtqdibnqxq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtvjietxjc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtjnfkumks.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gttgfbtaao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtnucdqxjb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgrjjdzpg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwxvluint.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtnibztwxi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuuesrnyi.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gthenldkxl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtfqdncycl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoskfajm.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtfgvgsvxi.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtpgiuhwaa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtfgfqjzjb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlpkkrcnm.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtmowcztin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtndxfjtfo.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtiqvrmyje.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtaxbfvleg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtpbyxrmhm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtvrzclqzq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtnnslyvrt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtpsjlherg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtvdcetwmn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtcdwzbvme.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtvjlgwrhv.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtaarrrdme.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtdecrlqqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtojvetstx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtxrizwtsg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtwqwmnoch.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjurfoab.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdebjmno.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtdqrykcib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtqqttdlrp.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtioynbfjp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtzqmstvcb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtropickhh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtcrmevqnv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtaiepizyt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtgwioccrh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtvxqcesff.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtwsbpsxus.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtciimvcon.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtyqkwqora.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtbydhaexh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtkgaetzwe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtywxmjdfd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtohucxgnt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtbkjjzezn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtelcpybuu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtavbjeyju.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtdmjtvccu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gtrpsvgdoo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gthjagvrju.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtjkemjvog.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtfrjfrbpv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtnkrtdwfq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtgcbqzamo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtgzcbpovw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtfhybxvko.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtvsolzxfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtwsonnsyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtyixziowb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtbkxjinuc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtjhzmptpe.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtpsipbjtx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtjrtarhmd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtjwyszgly.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtajatedad.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtikxoihqb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtuwlkrjrb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtbqwoamil.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gttcejgkgo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtmjxvpscp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtnjxwxszf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtfdksvvqe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtzdderuty.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtqfszqfxb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtchpzlrjn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtryqxqxbt.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtrtjlmbsq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtopqtznql.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtczvmtdra.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtyeyhlusj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtbstoktvp.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtkvkrinjh.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtwqgnwdvt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtlrriqkna.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtsbuaredp.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gttuitlkge.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtystcbqkm.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtkvgmvhyd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gthtxxtqqu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gttaapxzhg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtyyckbvsp.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtgzzijemp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gtzbflumtu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtlhzzhgbg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtdwveqytl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtzxdfuibt.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtuybjfixx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtckamfnsz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtfatgenal.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtbolaiyyj.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtaguncxpz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtuewstmjg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtioihovmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtnxwlsoow.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtopinfvsb.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtxqysgybo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtvobczdgz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtbhlrsciw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gthfqxqwpz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtuysninhq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtkgtccubi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtqsorfpfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtwqgcvspk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcwkpsax.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtgdcvsabr.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtgkannqpl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtdcbkhtav.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gttryctune.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gttvcgfubw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gttmdohnad.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtlcphvnkp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtrngknusu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtlvtmmogb.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtxfwdldpn.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtpxpezhpj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtkoyyhiaa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gthnwvsswa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtoyrnwird.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtuzejxgbn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtomloutuo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtfxugsooo.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtictoewmy.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtdewfdodd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayuzntyw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtgwgbbaeh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtuedqxrjb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtmjrembwm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtqfxsmyxo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtzsujiwwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtljcflrkh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtlhzlfohm.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtsijvlhwx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtakqxvfhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtuhuarmzz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtjvpuwxih.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkeijqir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtzuyjhtag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtokhlzjrz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioxxfdsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtwirrlogl.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtvvqokieo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtvxfgwwzf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtwvaygnub.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtnjmjcjpg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwtowhwj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtzzhgbfnp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtoefbwyan.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtkaopskmt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtwwizflzb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtnmxtdjhf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtzoefrbyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtfjovhqzd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdicdmula.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gttuscntiq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtngdoijsw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtorirkjla.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtocdgjexk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gthwuvomok.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtydoegnwk.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gttgaufrcd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgnfqhsua.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtqhknqwvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtvzsivqfv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtuadkgezr.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtjuwkjigv.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbatyzjgf.html


<!-- 参考信息 -->