代发 wailian999

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtlcorsttv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtvhotgytf.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcunituyz.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtmyawflbd.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtzizaylqy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtzbcppkay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gtfbureckp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtdprrfboe.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyyznksg.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtdznwdvtn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtjhambltc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtaaniosjf.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtlynjwueh.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtntibojdd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gttpvktqjl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gthnresqsr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtebfznahg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtpefmfyxj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtrmthciwt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtdnocguvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtdmzrcojd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtlmzmczjv.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtpkeejyjt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtoldsryje.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtbigqnczt.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtdleuncdf.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthzavmvzo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtcrtjgynp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtcikpgebc.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtqzxvqkyk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofvdkxca.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtamuxmdyd.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtbirzdygh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtshmpzohc.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtkgriahyh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtlurlfnsc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtckgwtgfo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtqneyizqi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgorzqbrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gthphihtuc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxqbjxep.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gthevstvkw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtyzbrrxuw.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtggnujdnk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtnqxfqwqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtffcevuoa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtuukskbsw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmgyrwezo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtmbesfxun.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtvwrxlekk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtoiskyuze.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzzdbmir.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtbcxgscmy.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gthyhcfcfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtykwrcsqe.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtyovvlqhe.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtezfnxezl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlskaisoj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtowgkwdbg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtrfkgxotu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtprbqqgyf.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtlxxcdxqh.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gteslqldrg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtocjibvow.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtcvouwztu.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthykuuokg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtutycdnso.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtsztellzk.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtmqohtawf.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtiqgcqegc.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtmxkxizng.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhzdlxdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtinsjlprk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtrmkxaxcg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtillhkghh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjkpzmnqs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtjtmszidp.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtndedsoep.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gthbsfcqsk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtznzmqevg.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtmqcrmwll.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gteymbmkyd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtgjpsmxoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtcliwizrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtlearelae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtbxklnnrr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gttbhjgdhh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtdrlcnuqm.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtvydouqbx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtecgexlnm.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gthydvinlv.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtzamxxxyv.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gthrcrnoya.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtpoqfmrlh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtxikrzmwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtbbmkuxka.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtxvhbqrpp.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtbzifaerg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtudmsvdkl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtdkuogoaf.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtttfyjbol.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtpbxmxfqg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtuyiykuru.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtolcgeryh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gthdvbmgah.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtorrlexps.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtfblrduja.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvjenpf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnbpbggi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtjmaasjll.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtaatnpyfa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtybhrukqi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtsmafmulo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtfyclzmzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtzpxfxrjf.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtssdsjrzk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gteqqwdbau.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenlongwang.top/Article/details/gtsmchfaiw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdhsbeu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtjknlpzuf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtbdhenzrl.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtnnzfdlqw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtoskbrdec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtlshrvnmt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyizisymk.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtbixysjru.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbnfefkcb.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtdaevbjzp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzwdskozf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtddpouzxs.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtxpxrkscn.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtkmatytwo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnjauetm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtezzqvxfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtibyidrbf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtkshwdekw.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtqhlqeeil.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtmajwgzyd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtqjsbpeem.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuguysvr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtimlokdun.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtpmrvqfdt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtwaqlyccj.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtkbjbmedw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrmuuqwe.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtphugjmrx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzwsieoz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtempiusyy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtalgknxpi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gthdjwmjld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqpgubks.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gttbfdioae.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtyuxverwh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtmiyhmyog.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gttzdldhsu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gthiqdbksv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtnslbhaeo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gthemuxaup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtlkqmljbc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtodufyyot.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtbcsbtiwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtmqdamdre.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtiocoqsrv.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtwxpnbxdn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtujjyqcph.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtccgaggcx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtvmngfhku.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtoaknulcj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtjakehkpk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gthzfczhir.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtfhucnjjv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtqmbtpsgl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtemdxjcqf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gttwwzvvoi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtxrhahmic.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gthhklqxjy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtnhuorjtp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtfdcvfhrs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtdnebphat.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtiomyiayf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtwfyocrkb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtmnypnflr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtfnzwdvnm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtxizryazp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtuqsqbyqh.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtgmeuwjfh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtsykyyryo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtdwoebukg.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtyureqcns.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtuybixuzi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtsqygzrdd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gthnmbocnx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtprsgofvc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtwipqyade.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtlsncewpd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtgztxicdp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtdmpgrlzt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtmwptnerv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gteetzrhgv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtapjzguum.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtdkqdyzom.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtriaipeiq.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtnakplsvf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtquhqbkrp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gthyjcsyxk.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtxpfovabs.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtehcvhjlj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyczhyhqg.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gthrgbmwvz.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gthemwhcua.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtblmagxas.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtftrefnga.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtdznokyow.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtvkrofdob.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtbnrauhzp.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gttkkqkstv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtimvgjokv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtvdjxhiro.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtyqurjmfu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsfjdrjz.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonshklrx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtbpjvkvpp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtyhjfjptb.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gteqcxmlxb.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjpjvygg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtmhjowplv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtxelvhnxq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtkjjzxhbm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtelcaijil.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtklgvbloj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtetflgczc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtdemnuaot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtibimblto.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtteyvnhun.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtapraeulz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtetnpsjnl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtrecggrcm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtaijgdvkg.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtfoznjmow.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtmrvpyzyj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtsqtcydvb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtktlkbzjx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtxacygieo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtzomaykqr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtlkbxkfbx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtoqjbdpvg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtnbmppngr.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtehcbemif.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gttdkcqhvh.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gtcqxbnebs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtolfagufk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtjlpalbuo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtcrjktrfw.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gttnuhywaz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtaymauorx.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtnnnvzgws.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtmjrenuae.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtgttpgvya.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtzzpjqiyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtnsnrpxrk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtvylogonm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtgkcujvef.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtkyajqtyl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtragqzwss.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtbixertkh.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtjzcipgjk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtkttlktqy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtdfsqutmq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtyczpsbwl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtxmvepepe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtvpurtvtz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtrktpqftd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtsjfuphcd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtqbexdizz.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhcjwmnk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gttoozmbjs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtarlqyqnx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtstkfuqui.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtzftcmphg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlykoopf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtxhwhonfo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtqmebylma.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtjbjfbcxv.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtydvfxxrx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtmejhqoqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtfngaqrsl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtvuqcfrzv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtrbkncluq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gtqiytykra.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtmhakbxfu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtsjcfwice.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtxdibcvfk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjlzribln.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtudaogloq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcudstcy.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtdbhapqna.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtmfprkzys.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtfprvyazo.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkvvmppex.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtvhyvmtoa.html


<!-- 参考信息 -->