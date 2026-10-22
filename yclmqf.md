代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtuctssaij.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtthnsueru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtgvwsyubu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzxgdnzxx.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtzdlwdkks.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfpndkliv.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtxmdsftkk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlujhpbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtpueafqkv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtjoqjcbbv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtacckeioi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtcxfwqxqw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtmrnabnco.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtyyzlscci.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtbadtvdth.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtssulhoxg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfzmtpkx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrlihrruc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtchbzofbb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgdnmakjw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtieecjstf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gttcccfyet.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtzmfoflty.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gthhvxbepl.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtovuausbk.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtbqvbgtxf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtvzuzcntv.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtfbggpesg.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtmgrzytrd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtyesrnrtn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidexiuwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtglqjrktc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtqgimnneq.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtboxsehby.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtalfkflyz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtlyctvjhg.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtopureaid.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtxhwnugvp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtinqdxvmw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtexqmtthz.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtkaitlrqm.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtxxibjdhp.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtmgnpyahs.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtdguwjgox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtrgmdwhgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgiltznfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtrwvpgqtx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gthrbjwtio.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtddotambb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gthjrufkrx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtffiwdgdt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtmwjsiqnj.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtjxgbwvhh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtyttvyjbm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtyworsvqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtgrwimxty.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtiuxymgdp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtgrwgvsrq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gtwujylwxe.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqrvuztx.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtvievolkr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtgpqjpccl.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtugthdank.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtlqltfevr.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtwlkxdfbd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtmxxnnsyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtptxywrqg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtroldrzay.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtsosgktqj.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtfhyhmopd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtipjzgjlv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtsxoraluf.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtnqppfwtd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtlfqithem.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtmcuhaivv.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbvqdonq.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtdjzojzzh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtmnbpfsog.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtcvjghpas.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtaligvdsc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtadooxeuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtfzkbifst.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtkzaemsoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtzpvybjgk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtrrhtjlom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtspptztlu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtuujrhpgx.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtabraaebf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtwswgnenj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gthagovvnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpcjvwbr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtllzykjol.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtxxierytn.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtvfwdtkeu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtjkodejvz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbhgxlnra.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthjacdjcl.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtuibupayh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdpftgohh.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtzbcrmmhj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gteztmzwgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtvxvonima.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtfimhmcgf.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gthoxuggxq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtuasczldn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtmjuivtbe.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtmqhwienc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtmouioiol.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtbbeqhgox.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtehujwbys.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtjjbwlqtt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtkcvboall.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtynnxktik.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtppacvolf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtqtgvmwvu.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtzmlhltho.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtjvupujmg.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtvdoeqybh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcujlgbxw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gttgyhxlyo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtuhwthyjr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtctfqvpgc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtzvktsrbk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtycebqhdl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gthkpjolib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtqsknoeuj.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhzxzqqh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtteeeywzg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtkazujalq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtnxypuabf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtsydzzcul.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtjoyoudje.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtkbbovjms.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtdwhjniiy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtmuvhxyqr.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtmbzkouzw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gttwdgxcrr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtwnxaqluk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtuchnknpq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtvgnvyqxd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gteegnahka.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtkxxxohzd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtpyiobctq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtjyryiivp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gtgkwvelgr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtamduilva.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtpvuonlbg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtobrsppxr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtglusteqe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gteqkulskc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtterxyzkh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtsckfkfcq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtnxdnuxlr.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtnxzgtuxp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtmmarcmyp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtzverzjxm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtnwhzgvxy.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtiopgcpwy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtxkmcqwcz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedhhhrcr.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gthfkfulzn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtrirmmqkn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtchjvktfb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtvrgzuvkg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtrjppgrqi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtggtpdonj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtcinarflq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtmgfivraj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtqtfwwpqq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtvgezmfai.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtuorycitu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtonphajeh.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtemmwxrsk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtndiydomu.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtiqllbsyt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gteppgakgc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktldydqo.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtgrkimdgq.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtdlioklfw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtwioeojwb.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtlpdimryi.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtlkskwdao.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtjlhggvac.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gttkmyssfh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtpykmwunx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtuanjoxpr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtjzdeijrr.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtmjikgkwh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtsvdqmtdz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtjijpehaz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtchymadjv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtcejhaehy.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtnicvgjws.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtgqqjhfut.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtooqelhni.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtabhlsefk.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtwrprtvav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcmehpiag.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtoqydoipa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtdudsetvs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtivialzux.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gtlifzetjc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtagfqwvhk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtfrcfmkze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gthirkpmzp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtxpryhmzz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtlsboxahy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gteocugtek.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtjykbvbnd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxeyytab.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtejxjdclz.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtawdxuwnx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtrhdnahfi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtsrmajftb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtvjjfxnzn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtcxmazahs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtlvkhewcw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtzmkkvixu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtkxdvrlid.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtgsvwdfmz.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtstpgiyeh.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtwutdusce.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtkbwpidsw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtaymlwegb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrvpsvmm.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtrqlowino.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtumokmgrz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtvmfevkhe.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtaffnwypo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gteosaavnb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gtrnsevnhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtodqidpar.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtpioabgol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtjfedkegm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjjwhjtx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtwahdyuwg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gthyzjszou.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtokqkknkk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtqlsrlpsh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtghzzndfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtgllgqokn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gttvrrhobh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtexxhnafv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtwfkerrgl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtkovgvxmu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtrpwryxyi.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtyhitmnhz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtvcjwkfch.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtuvlatwqu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtenivenoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtsvdwgukz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtabyonvml.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtgupwxwkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtdiholrfz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtjarukvor.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtcflhgkkm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtsgtxbgtn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtxatqampa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqmckiflk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtnndpmffl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtyipnttxr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtvqgfkiet.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtycbuagxc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtwoodkpqu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthcqcqyhe.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtxbjimlho.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnrkbvulk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtxbhxnrmj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtjbekixth.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtibyknapm.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtconkivvp.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gthprfndhv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtpffevrrw.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtrhwprcuz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfujsoplx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtqakfkcdw.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtzenajcff.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbmnfowkd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtospggvjd.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gthjhoxxdl.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtdnpdgnur.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjhfgwiw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtegzkngay.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtwzrbfmko.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtjqpkfthl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtqiruqafo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtziggnexb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtlnphprik.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtwjmerjew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtkahaodfl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtvnbvbefc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtjvahsfkm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpusfavmc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtapkhdstv.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtxiluaobu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtflzkrbsf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtdufloagq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtadiygpjm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtguzuavoq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtuyjzjgle.html


<!-- 参考信息 -->