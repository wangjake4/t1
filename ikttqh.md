代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2uvzzsqqc.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2htooywuf.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2kizroabs.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxdzzkpd.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2niavknje.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2dafovcry.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2rtvocboo.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2hittpwdo.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2yupqknjy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2eaqkobsz.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2uhclhvtl.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2ghnzebon.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2veauurvg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2ksjsayur.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2bthxebgq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2lfqfyvqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2xdmeubbu.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ypxmhurr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2lceirnsv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2qsdnkqus.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gt2ngseipjk.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2kysjnchj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2hdnstanp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gt2favrmmac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2xidnvshs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2mmmsotjv.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2yqvakvjh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2gqtpemxj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2blzgmjqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2weprehux.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2ppdseyie.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuxtmkgt.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2dipcdqoy.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2iscxlegn.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2zlinbuzg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2qwlvuyhs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2ermdjdjq.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2ebtmdoti.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2ymqeusug.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qivnesne.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2izbzqfnm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2abuqnwph.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgzgvowq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gt2vcoptaxe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2cbtvvnlj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2lkqgdoct.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klmejebl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2myvbsjjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2ocxqhtci.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2tymjtxre.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylwrgxvy.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2usitkgmt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gt2sdlcssrv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vosyydax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2zvmuztub.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hykwwgqr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2nxfwradi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2vdaeshhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2sljhmaac.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2qlbrtfjx.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2fkahmcwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2kjmoktql.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2soxlkrpt.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2wlxaimfu.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2lnayrmba.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2afdaucbd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2izmpblvd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rimekofm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2liplqqjs.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2szlxosoz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2ulnvkjkn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyhhtwhs.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fqsrpchg.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfilzmig.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2zzdubsct.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2lnmmahvz.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2ajvvaamt.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xwllilmx.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ymdctoth.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2uyupjpeu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2zdbhfeug.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2nfxypzje.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2vevomkxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2pjccnecr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwpslydj.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gt2fevkjghj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ndjvbydq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmzhvxg.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2bkqxrdcg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2wojdwfpm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2ndnmsspp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkhhbwal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2qqtvfqkw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2aqjexpol.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2oopxxtuk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gt2jntahlqr.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gt2csgqanqd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2cntpdpgl.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2efkbkhgl.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2kzytgcsu.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2bbzydumv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2moqrxlus.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2sptjtgsj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gt2uysmfxke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2tejbrgks.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2tharckzy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2nzldstdy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gt2bpexbakf.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2hnxaxcok.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2jprzkiqh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gt2opvtxwtn.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2iebnuxkk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2umzmhqtd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2cddquvdi.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gt2otklsllo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpfssyzc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rovzovtu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2zsqcxwsg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2bvbilugk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2jvvdzagf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2vqqtlxid.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2jdfzjmrw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2nuanaqrd.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gt2zmmxhgnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2iksntabj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gt2cbaurpht.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2xvenjwvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjmvoslk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gt2fybcfdqh.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2keairsre.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2mzdrjpyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2viaolvbn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfaqfnza.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2oybotljd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ozagnjeq.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gt2caiakxen.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2zzcsvceb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2wckuopai.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2tzmxfdrf.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2ruszejhg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gt2ntjpfzll.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2yyrxgune.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2nvcpjsqz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iweokygb.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2dwdwmopu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2jyilusgq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2cxvndrlj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2bfxletwi.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2ctibeatp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2yvgrfcxw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2zbwmhjlf.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2jijpmzgl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gt2labcpnra.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2ljihkvei.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2kheejpuk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2dwsrzpck.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2pylxfspw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gt2aurgjfzh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vntifqec.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2juygrnek.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2fivsorwk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2iqwembqs.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovgwzvwu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2gonltcoy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2veffhqri.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2eiptegai.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2caxwugvi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gncycjib.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gt2pzmsvuqj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2xhutfsfq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2dxidtrwh.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfpllyap.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uttdfqpo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmqflwef.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2cnllrhur.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2hcqglnqq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfugvaib.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2zfhohsji.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2tgbrafdk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2mlxeaels.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gt2busssext.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2fhvuxbqn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2sshebdyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2wyebvzhg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2rvwqqtcv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2rvrtvnes.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gt2lyyyzdqd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2jzvrgxne.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2jdtprdsr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2anwonqut.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2stgzjxeh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2nkggfnbf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gt2kfixxzvo.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gt2qqwqkzpr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gt2kperhsjz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2nxnbnzqc.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gt2raeptzlz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2fnjqqakk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tykkilxf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gt2vpelvpsp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2uhxhwpro.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2zrxhsfkg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2dfqywggp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2zarnvtev.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gt2dbhawusn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gt2uqidjnbz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2asvfhowe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mctyrubo.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2eapdnhwi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nrqrgqjr.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2arqdqtkc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2ofdzbgbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2cjaebpzj.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2ypfsutej.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2nmfosgea.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2qhmqmdje.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2cfzwwxyf.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2ohqznkts.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gt2mqlrcwkl.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2tzpwjuxf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2sgohskmd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtqdeosq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gt2khyxnmmp.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2fcbecdcm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gt2bpjitdfo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2jqgqtjww.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2lragggkk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2eufkozbs.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iireecmn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2uuroeuge.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hodiltdm.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2lofpgyag.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2rjddtlpo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2kfinenpu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ujdnpaxz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2vpbcretk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaycekel.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2dmtbthfr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2dzrleyfs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2lnefcncb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2cuiohvrn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gt2ltmxryvt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2betliuhm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2bipscdrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2cayugmid.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ancxmuxl.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gt2hwmektbo.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2mgshkxtx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gt2uuezylxy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2cggmvaik.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2vnwlpfoy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxqsmirp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2kfzmmobf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2gxrafdkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2aauhsclm.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2stnzxgtc.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2gltyfgmn.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zheocylz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gt2kgmuefea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilylbzup.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2ixwxpmrg.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2wnjxdmnu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybhdcdez.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2xiafirkq.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2bdhooabz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2aagyblia.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcmcduww.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2nkrazqqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2yzptpuep.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2goloisau.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vepjvucy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2lbiyedti.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjmqvanx.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2mymhdvwp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjcjulun.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2lsptohnb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gt2plspnshl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2xnxemeoq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gt2fvrpikha.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2nhnefqqm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2nhucntwe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2pwjvxwyp.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gt2kghsgopy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2zudfuesq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2nugnnfms.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbcwmmqq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2svvjbznm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2qvlfqxum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2fmqagvuo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2sgaaabaz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xciqgaqt.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2mysxxpvu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2cmqternw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2atjckgjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gt2svfqlvez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2suqhfxhb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2xdmedrum.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gt2mvbjswjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gt2vsikdagx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2oyfmcslr.html


<!-- 参考信息 -->