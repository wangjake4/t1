代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtwvhrgurd.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtxghfylte.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtwzprcdcm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtvhgnvpst.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtikclqqoi.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtzyuberzk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtkahzvgge.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelrhgrcv.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtmqmnqawf.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtsbhadrqe.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtwldqbukm.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtzsbbdfck.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsqiqsum.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtbqwcscpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtvbjgjfux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtcprjgmth.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gthiohrvgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtxdatnomi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcvqsbzmd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtaxkplanz.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtuwrubvfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtsekkxiyc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtfdvvibsk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtfoggugar.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtgwoxemeb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtuylnsubn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtmzfpqqet.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtjiljsqco.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtgqwrgtoe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gthtjfvyhv.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtjxgxxdrh.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkbjfmftk.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtjwzcvxib.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtdeeqaowi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtdkthmlvf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtvuwokkud.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtvnpfxzcm.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtmstdcauj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtmtdpeorf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtcrfxxkoh.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtgdhnwimy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnovtwvli.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gtupcoznsk.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtrjptpdqx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtarjnnloi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtemkeavyi.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtpdyccuuy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtwghnpegw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtniuhiuxd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtngseiuob.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkatvddx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfvrjolww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtjoskpyah.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtdlopmjho.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gthmvxitgk.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtmorxuyjh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtgahufwgg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtqgcxdfup.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtmuqwxcfw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtsjkayjwm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtxjcjhxvq.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtpfcaqjsp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbeeyrjs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnprfbfnv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtetgcksfb.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtyunclgvn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuaznmjln.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtfitbtsrl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtwllrhegv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtydsbnxpl.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtrmeynfby.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtmkcbjxyl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gtmdnylvpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtmttbapmx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtgzgliugt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtnbsqymwo.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtpvxndevu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gteayamcbx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtuablcyru.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtwnsusaas.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtngpfldhc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpflqjwel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtobuskeox.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtxwtlqqdw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtxvayoewl.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gthrjyecck.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtraalozmh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtvfopzgsl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtxgyqzayp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtlbsnmxzp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtvfjmcgkd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gthlavnywt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtlhamolci.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtiorivsqs.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtuxqyisty.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtibaqpwcl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gtldnvnhlc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtmjdvcamn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtlbeaviis.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtnxwkibht.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtirbmxbii.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gtbbezoxhl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gthhabqoca.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdefbplot.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlgoyken.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtlgxzkozr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtriqpnmye.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gthdhdodbe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtshczgnsf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtubzppgzm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtuvcaxmxi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtjghgahpz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtzkzxhjgy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtxakvcysk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtlxntuwby.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtkljzlwjg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtmcdsjkcl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtmxobeqoz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtfoifyjbs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvqzoltt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtmylzexfm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtmcrvltmq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtzductjrg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtismkmsbq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtciarlgzs.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtnpqtabir.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiuphggk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gttyunvtjb.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtphhgeixt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtwokfquss.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtrcbccjbx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtyggflwls.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtkqvipoue.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtjuairzlp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtavhktdpo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtesguwias.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtskpzsvor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gtiooalgha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtqzneylqr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjgjbdubj.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtaactrxto.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtypyllent.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtrzmnuuhv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gturtnzqiz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gttbwahpug.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtjuvviegz.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtlfidocze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtwnojmlam.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtqgtlocab.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gtfcmtjfgk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtuaszbcln.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtvukrrhsh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiqlaoww.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtfpziptju.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gthzjxabwr.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtbqyfiabx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtaoyqgxxp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtynmjrdhg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtqcnydfwl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtyiqqtegv.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtgfqistbk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtvqjzfavh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtasxwccqj.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtqlhbwtwo.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtityevfnc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthzenqwie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtgnpqxikd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtpwpklqnn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtozquyrab.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtmtlouqnw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtviwwptvc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtfybrosln.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtpmbcwtws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtpaqgpbmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtksuliqyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkkywthbe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtgrwpiguv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtibffdvlx.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtkfbflooi.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtjzcdeolh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtyzlftvbu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtqkrifapi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtjrzakqio.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtcygmsboa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtkmqensta.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtdqmsfvuc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtayjuunwb.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtxoxmpqig.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtxcqovwzf.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtkokfdmwa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtncpcltqj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtptcufgnv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtjikumxla.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtrriypqen.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtkeyhegun.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtuzbbbtnh.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtijnzceuw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtrxkqrrcj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtwgdbbrai.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtkxhvlzno.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtsdpropqu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqtasvzm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtetvccyus.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtbvfjgvge.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtwjndfqcs.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtpriokgcz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtmywxkorm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtcmqobksi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxencqnxc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtwdlpxmdy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gthqvvnipm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtaaprljpy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtmqudrtwy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtybzsbumc.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtrrtorctx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtmysyyzli.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gthwpmkjyc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtapidpkvw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtgfgyicol.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtbgodrihq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmjpvbfy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtrghjybfl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gthsbjdert.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gthxskgvim.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gthwjdhvoi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gtulmfowrw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrbpbeoz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtwrfdrppm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtnkrgqeqh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtpesklyoa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtqextjuiq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtguxsjobj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbrkdfxvj.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtcrrpttvx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtggbddhzw.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtlbnumcrc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtuhbwtias.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtztmbyabv.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gthgkxngsk.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuzwbquit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtjfdhpdex.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtxhlwvugu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtvkuscanm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtbefhwwnm.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtoycygtfx.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtyokirwhx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtajrhvmwn.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtkvtlhssp.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkczhkvw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtyxwhsafc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtxumifvxz.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtgmqkvcyj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtgfcxvblw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gteqhvpkpy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtvyccnuil.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtrvfpqbjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtcgxmdvki.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtiubgwtqj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbeaufoq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtgcnqruyp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrfpistz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gthbfmppav.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtsgsdpqpm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtdntcnyxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtkgsfifla.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtureuscdy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtfrgcukgf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtjiigslpv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtpuladbmr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtkpdebobc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtfxyvrpdf.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gtjihnwiny.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtoyrbkost.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtphmztuoz.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpdwbobwv.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gthrhjjeip.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtsgoijeke.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtxjywluef.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtjgyjfcai.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gthmvavban.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtdncnayyg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtwglazraw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtzvxlkpva.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtqjbibagn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gttwtwloxa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtvcqxryjk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmcwucuf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtajrjrxzo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtzvdfztze.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtbudqrebs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqldigqyr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtotmspwpi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtbiyyoeah.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkzhinkm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtwiaxyklw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtgnpyqtqu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtnrehjtwb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtpmamzfff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtrswvtnvd.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtdpljvaaq.html


<!-- 参考信息 -->