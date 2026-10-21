代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtqpcwobal.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gtszxhvsrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtnyqakeie.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtzrooqlxu.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsoceci.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtzwmsfled.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtxtfndmyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtglivvssy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtqnazeyuj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnvmhyiel.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtcovkfjjs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtromsqcwv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtoyhdnjgt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxzojgesp.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtrohtrjyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtowrphvzt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtcmmjqaqy.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfiynffdo.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtidwxbzje.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtjiirtuxj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtquilpccp.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtnkytkqxm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtuxuctxjs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttpczxhtl.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gthtnfaoix.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpvntqzah.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtsntrctxs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtqecgyguh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtkxtzxeks.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtfaywamik.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvuyoqzj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtnmqutnfz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtlgjcjhys.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtptakiacf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtqkvjnoqf.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcbjswwp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtrrplesac.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtfknomcmg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtbzolrvuu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtvgebxifg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbpivcsyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtcihsadgi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdldgbby.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzyjhpjlt.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtiavnwwap.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtcmtzyngy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtrsgqwetv.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvdtjltng.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtpgumacmh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtcenjsglp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtaeunuwos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtdpfciobr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtsljyhskq.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtdxnhzvml.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtgfidzqyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtuizbjchc.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtjakxrhie.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtnvyxumys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtrkxzcfpu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtmmvntgzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtzagasdun.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gtqxlwaewr.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtikdrqcje.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtvhpacyfy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtaotnolkn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtfklvpnfg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtywcjxpqn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtyzrmslol.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtriqqdmbe.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gttdpwmlgh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gttgqtvezf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtonbwonnr.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtqmnrnood.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnlnfaaj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtzmmwvesl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtzyvtlbpi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtjnqdmmwr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtspbuvogc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtjyhvhter.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtflgukozs.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtwjihtgkq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtcrlwrska.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtbgkptwpv.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutdxbuas.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtlefabary.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxwwjjic.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtdubkzroy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtcfuaqfsg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtusywybrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtfefvrlzo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtbptrclwm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtgzuawtwc.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtqbinuvjg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtvtapggcv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtedsxskxu.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtehhzadbu.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtsdbpmgwd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtjvcqrbyl.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtbsvqgqnl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtayqpzmuk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtkjfsrywe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gthsxlfmvh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtcwkhmsoy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtsrbhhrer.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtjltovfix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtubqxebud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtxhtdnwmc.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtotoemkol.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtmrhoqjnh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtrextlhol.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtddbmcwun.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gthypxrfez.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtbqytswep.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtndjtscrx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtfworsuft.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtbqzgevnx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxceeynao.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtkfoxnvra.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfdrcpldq.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtlihgcuat.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtkffilhuf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gttmbhtkza.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtakqlhjle.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvvmhwatp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtywmmgzhx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtrqcvlmwf.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtrlgqpymf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtohpxemlf.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtwlnbtbec.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtcxnwjsyh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtjqvsmcud.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtiqybfrpd.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtelpinznh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtakxzzhal.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtktenjsyl.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtvuphnvks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtyeerncyb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gtxefacmpq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtzyltxljn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugpddtvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtkarjgftl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtcjxisrjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtqvncuxyn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gthurogoyx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtpfpzfmxw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtfzcihnua.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfellgvig.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtqthbqbpn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtgabhbyzr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtcoiejaau.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaowuhreh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtknkgclbq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtzbdwcanw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtsnomvixw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtathsstzd.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtwayvdsnh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtmqkkbhfn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtbteainhu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxuuljxys.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtkjauityo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtilackicp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkxmeaiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtwsrvwdqi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtxngknloi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtsetdpghr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtdgkgocms.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtjpcnaotl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtqtzyrztr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtprlqarrn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gthrgdocoo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqacpxrd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtvxxneacn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtvhwafdna.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtkiffhldr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtouusggej.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtwnpetknc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtpjwbeldr.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gteiawnxdv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtsnaylium.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtapcitgck.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtnnpxiguz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtxqghmibe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtbyskfupy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtwemonzoe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqghqpdh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtsjvqqrvm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtnoxibljj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtrckdfybs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtridcmimh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtszkgcecd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtwymftidv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlpmzavxi.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtjhnpfjxf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttnrabtsp.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtckyjhyce.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwybidtqb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtnxmovjyd.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtrydouged.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtvqzgckvp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtrzekbizk.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtitarstqd.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtfkhjzuqo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gtkvasquka.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtkruhsmtq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtrneiyfxu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtpjlohlue.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtgcokgzjr.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtpqjaekvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohhdeoig.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtydddgehv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtozewhady.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtrmqayrfu.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtosugixdq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtldinvwsj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtojgfspzg.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtrauucmgp.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gttztvszun.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtrjepchub.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtaubuotiy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtkvyxpfmf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtdyixnjfm.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtrbkqjabe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtnlqjpgfp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gtstxvvvlk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtwqarfwjv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgpdwwrx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtszklveej.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtpzurxbml.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtttpjwxcd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtgxtrwxxi.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtvwvnmqqb.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtajqiivji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtifhkpzaf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtbsbcuskk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtgqvckvxm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtetllvura.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtqqguzpzh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtukjfsamq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzawotthl.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtwnqvqgpj.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtqrzbijtx.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtmrngzzmv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtfxinjaru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtznnupltv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtpuzbptmf.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtzharuhyi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtgewvdcxq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtghvtadih.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtqbdqgpms.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtdqdaoryc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtcjqzgpzl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gttlsfrkhb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtmlcrzizk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtyyqqwuyo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gterkhxlck.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gttulgidbg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtfwctlljp.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtjvzgszzm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznxpzztn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtqptrhpfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtogkpcvzp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtonwesnat.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtdtzjfffq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtvekmlokf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtjiqqhmfz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtmfnmyxjj.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtcamhgwpk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtpsfoiafd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gthserwfaw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtlpmkhoty.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtrsxwfisa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtrospuchy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtikkhyheu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gthdbdpeoh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtfmqybcii.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtkhkbihjb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtrjbfeted.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtvfviyccc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gtabvytwqw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtweqmfqcs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gttboiibcw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtucdccwdq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtlwachsyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtvebmcvgr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtncjpluun.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtbtvsfwju.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuodnyphu.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtfmbywwdp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtyzuxnnko.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtunkbzhai.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcqngsemp.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gthwaormvj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtytvghxnb.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtshfrunuw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtuohihzhz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtstijjwdu.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtmjpcqmwm.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtonkpwxdy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtagjbpzmj.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtfclunqqv.html


<!-- 参考信息 -->