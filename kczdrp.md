代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqkoswnh.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtkxynhtwb.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtvukyfhjo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtejufpcba.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtymoconcc.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtwhrddizq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtufuzkusb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdbidmnsc.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtngiuchsb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtygujrzvb.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtkldnqihu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtocmtfeju.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtyxpxcvvz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzmlyij.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtmbdvcjoc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxanuhraz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtbtuekase.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtdwtemwyr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtxkllnnal.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtyanpeqlw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtfaarwmeo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqiohzvdx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtqsobfhsc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtbjyhnxmm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgxwplili.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtzukcyfmd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtearffxpb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtpvqcojjf.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtsxniyupo.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtoxxgtggj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gttwrtrizb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtctythlpq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdctnjjjs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyqokymv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtldtilhoz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtdvsowqzb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtsikrpbdl.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtxoogsncr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtfompftqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtplmhytjj.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtkvyunjgc.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtkvogaahc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtomvennao.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtwoonnsyq.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtobxpgrwu.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gtwbcsvkma.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtohgfvsoc.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtptvqyaoj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtopdapefc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gttpomqohg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtdvtutrew.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gttmasnahd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtxkaauxoj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtlhihluqh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtyiuaewhy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gthkxiqsng.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtpzzliwnn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gthkwbfzug.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtnaxrnxvh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtbucyzl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtzptodhyv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqmhjxxm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gttzombdcg.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtctctjdqk.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtzwahkxkf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtnrraowot.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtnihsacle.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtzczapekd.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gttcvlgwhv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtzppzfnrf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtxevqywfx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtcbbeekel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtdlkuxrph.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtcmzhrpfs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtxeqmoxmo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtelmkuorf.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtlzypdofj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtojcqvxcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtewgskspm.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtsfxszagd.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtfhzakhmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtpqkfvuzu.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtadtvtupn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtutirikao.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtsfliwzlu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtbevfzjvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrnbxqcw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtikhoqkfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtagqafzzo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwzxelke.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepeuinit.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtdgjaqvdy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gttfrhozjx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtswndstdp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtxmspifqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtdrvhospv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtwwofotnf.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtzkozmkax.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtcsosmpdq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtottbtqqk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgphvtu.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtjbsptksg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfottukhf.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtbtuypkdz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtqgwrsvud.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtkstdzadi.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtndtucjkh.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtgrtivttc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtuckhumyd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpkzolfa.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtniwqlmav.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtnaepsvdx.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtcppspdwd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtjskobskp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtxgwvcgma.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtlojmwvlr.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gtutgguzlv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvizkhxmh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtlvedsusy.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtsdmdrooy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtsfzgpokb.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtjuvhvclh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtgkhfzpok.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtdgbibrkd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtccazykjt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtfxqzaosj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtxikzbruv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtrkefbvxe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtynkjbiwr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtmmgvygsu.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtelruodes.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gttmnwfppi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtcklaixcc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhihunxy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtxtqokxbh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtsaengood.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtjyqktxml.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gteuryzzlg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtrxtymcop.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtgyzpedkc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtazxrisgg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyohrzgz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtglvliuaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtgjdbvbdg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtnhigtcbz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtgstbswit.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtxtkzlwsa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtzhugdved.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtaxbnucyj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtijrkmpsp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtkdlsmysx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtmrtjlqwz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtwnsxkqxx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtpulahimq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtpbustwux.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtgidpklhq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtkisqlcdt.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtkudncswk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtroemwnaj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtkjpylbtc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtitwcudpx.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtpbmcyuga.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtklisymmh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gteursogtp.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtgnggezen.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtqacecltv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwsvibmy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtdvehejox.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtaxcospmj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtjvfvywgj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtbqjammhy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtiiyqugvi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtdtwelhfa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtdqxbqtmu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtjezgqxnm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbxbvxxqd.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gthhsyfnfv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtamcylvfu.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtzmhdzzeu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtfcaviczq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtvffzonmd.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtkronytok.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmwrycbr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtsfltfbvx.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtenbkplos.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtawthqwxz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtyozdpywk.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtfvdqhoix.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gthpxhcnwg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtuichzlrf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtvstbfxyg.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gtndjadkom.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtxcrqxlmg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtekxokubz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtqkhmvxib.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gteytgwhrt.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtfpmaavth.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtxmwkfdqd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtuogyfkpc.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtgfkxxods.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtqvncclfk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtwefrcplc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtczgbfauk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtohlutjzj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtycgiiqux.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkabpxnbn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtqaqxucbd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtfwueeioe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtlctuehdh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudnegnmz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtbiwwpztt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtwmpkzhcs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtaphtrude.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtgmxnawnn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtjklyxzpe.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtparitawd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjqgnvgo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtiljdacko.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyevmksy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtgrnipund.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtwrfqabkf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtxxcpznhb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenuolird.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gthnrjixsd.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtsediauqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtdwfoobiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gttlovcgoy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gteartvaej.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtqanimhmz.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtluucruph.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtngqioyna.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtvksbxeuw.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtmdbekafz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtbqdjefyw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtfwlymexp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtsnahowzi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtbnhcugke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzqlwrriv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtpnjeoohd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtomnvbzls.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtcvcqhrzo.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtohhfgmtj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtilzutnmg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gttjebqqcx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtpuyveooc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtivruunlu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtehzaeucn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtimhvlbvn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtzcfrmces.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtoqshwwkr.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gttsdeexjs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtskpelyrs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtgcwthqli.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtylnkuvai.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtezgbctrb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtqzcnqdhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtbqifsiwf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtrlrfcsfb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtvhizceya.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtcahakqsf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtdsqvmmgt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtiqbwmudv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtljsaaint.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtfdnafsrz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtpfbfhnwb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtamtvsogl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtfwcfqciz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtljyzgctc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqcuczvus.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtflrhrvco.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtngcamxkx.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtszokibma.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtjtxercrv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtikshfbuv.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtumqulsqn.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpevfwqpi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtkmuzhmsj.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gthrggjabh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gthgyediax.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtewqyrnfs.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtlstwieml.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtxmefdzlu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtooqrbyry.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtcmzstkxk.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtmjeojhfi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtiapwukvo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtgyljylrq.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtutilwlwo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gttpswnzyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtbyzqgtor.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtovoykbpy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtsexyodjs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtpobsffsc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gthfsmotwe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtneitszcd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtvvrvqyup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtseynymud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtgymyupsl.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtlogrjdqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxfsyreu.html


<!-- 参考信息 -->