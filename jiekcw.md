代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtbolzkhii.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtapdahlmj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtqhjozwbt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtnoebqiav.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtvhyfyufd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtgiyrceiv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtegmocony.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtqlslgrmg.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtuvvrzwca.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtciydoidf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtvlhhsyte.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtmyunipbn.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtceenzmyl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtuclhlkvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtighwraae.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtchgzgbuf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhblevrz.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gttqrfbjcd.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtdhrjeepe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtcarfdyxq.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzycoavu.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcvtmmcs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtapykopxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtpxguhtlz.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtckrimmkc.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gthjbepgbm.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohqqykhp.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtnforpbez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtqonzcoef.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtegkcmvfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtfklfzoqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtuhkoyuoz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gthyqbjtgp.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtsmgivldr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gthmemprrd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtgwcuaequ.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtpstcdgym.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gteoxstwko.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtcsldxuez.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtrimtwcjt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gtlfnxtqho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtusadxjuh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtccmxhqae.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gteqoqpgkk.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtduwvmuma.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbjcpyeg.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbirwejeh.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtnkprbvda.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtvauwlvsy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtcvslprhc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtwftasuiq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtxcmrybht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gthnfpvbsa.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtrvbtflox.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gteuqeftju.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtuqqojsku.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtptlpyjif.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtwrbllqfy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtadkufzdu.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtcwyilgaw.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtezbmxiiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtkwxuoucn.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtdusfqxwz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtklxlxlmw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtlkhevmho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenzaomai.com/Article/details/gtgghtgrgk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gttamohxkp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gtkrgzqotu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtdmkitvig.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtvsdgkehy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtxmvlcizz.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtlllkgcvr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtbtccvrlm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtbndqdhlm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtksyhdjwk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtjbfzzxbb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkupqmpo.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtqcmsohfw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gttwzxfimi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gthlsjiosd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvpsavndi.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gttvldvbyh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxkqqkfvq.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtrecpowid.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtcmnmxkyt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtimnvcleb.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtvrbglrtc.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtwxkozrjb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtfhzpvwke.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtxvqqestz.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtdtbznnjs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtckoroywa.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtzmeywhad.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtpgjyddki.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtgjffnxps.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtaybpsgdd.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtjjzghfen.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtottvclxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gttaxusmtb.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtsgwmbvku.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtnfbldpsc.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvnkxxh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtjlvveepq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtsezwjxyp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtaalnlfgk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtombpmwhm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtdvtvugvs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtvczsaujx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtbqjmkmyl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gtjuaqhese.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtorhbbprv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtmfipuifi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvqveiyt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtafnfpdyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtnfggygub.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtdcdphyfm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtpdmiwgpv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtadqxlyek.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtsqoxtiiu.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydyxcdet.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtlaumjbqi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gthgekfeen.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtwtbbekgj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtcpkdtfqg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtsazesxcv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtnblgjeah.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbyodxat.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtuykuihcc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtroltvbqj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtlauahrss.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gtpbenizui.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtrfcbrcim.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gthatuwwuy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtsfwmhxoi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtzpciadpm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtobyvqhzq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtfmcgxxoj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gthfdwfvoa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtwisapdkt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtnxdywook.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gthfkwbtqo.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtxxjozikg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtczfypyrn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtcisfuhcc.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtcqciatbh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gttfafqcbv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtozcyzseu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtizdtkxbe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtbaevdrzq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtzlqqlmqy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtrjqysyyg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtchpeqqap.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtlpwuxkej.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtobzvuvie.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtnvblxejn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttubzjsal.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtbvifzfgl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzljoisvo.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtcbccjylk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtamxrsfxg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtgnbwcpeh.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtzyzgwqka.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtsfiluuxt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtawydrqzb.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtyfhobcgz.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gtdjtuozyk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtnnluweqv.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtrxrqjdlo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtjjodqlfe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtsdvgikne.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtnucbwrtx.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtqnylhcuq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpgznfsi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtwokmcufv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtxtddwipu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtlmqakbpj.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtsuqdubrq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtjdvbfauj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtzjqzulmh.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtruwqclur.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthdhkvsso.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyxcdqwd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtbhvnfkou.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtdppwdfvq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgbfgaay.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtlpwqtcng.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtmrmlswse.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtokypvsuh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtulbqdegz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtveexogfy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtaehkokfe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqlxcgnk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtqidenvbe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtmajpfaay.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtojyulgua.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtfvvsoceo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtdsmtybnh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtewvygemr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtftrtnlrg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtlsxpbvtp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtxfhbrwbb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtoeewhtoy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtyndgghri.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gtpsaeykbh.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtrflltyrj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtvignjhvs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtmsnpjgaf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtynimhrrl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtcclfqmfb.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtvqrynaxo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtnposzkwv.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtjkwizxxl.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtjdxbgqpk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtkdbwiqse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtyzraqyfg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgpfhzih.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbvrbrra.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gttgqhstyt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtxgayclko.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjratbhr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtuywbejxu.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtdftdkfux.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gteqxzkbea.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtlqhgpwmt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtbkdzyyjz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtuvxhtste.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtpukpolfg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtysvsyfbv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtxlnwfajr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtsmgokqtw.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtrtndpgwg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtasytofjv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtkclonlsk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtacofjukf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtccvxeong.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtpvgastvu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzxeejgu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtnmzailvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtvnsusklo.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtnvqmzake.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtydortnzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtrlncetsw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtchbeqnbt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtoqhvwrmk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtsozibmsz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtcecvrchn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtiogyihqc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtdctzuzki.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjrvmmagn.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtmtzgzkbs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqulhdwwt.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtdfralihn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtgtpmvmge.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtspuozalu.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqwnfqxnd.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gttmrpjpcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtrxaetswn.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudklxvmq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtblqthirm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtbvtevyfb.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtwjsficia.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtpnswusoo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gteiuozzvo.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtryigfgyz.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbgduqpvv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtreavhidb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtdggqvwtx.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtsbznqgab.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtuzjmsaot.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtridznexq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtuamrrkqw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtiidcoipf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtgldtbhun.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtaojrqppd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtxvcifeqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtwuyridve.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhjfxlbv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtuhvzciuv.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtofqjqmsf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtgwjmqvoc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtxsjdriso.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqlhqhfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtpqdhtkzh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtdvbdztby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtognbssws.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtfnmwxdza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtpvdypsvt.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtrrtayrir.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbgfrxxqz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gthswqlfir.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtyclpkpru.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtuucmloje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtezhzoohl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtjuuecakc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gtcngpiscp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtresgswrm.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gthckrcvrh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtrwhhkpci.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcuikphp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtwjsjdzvr.html


<!-- 参考信息 -->