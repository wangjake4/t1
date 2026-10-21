代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpinebjzk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtbkcjbrtn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtrdfisxro.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtovyxzdpj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfezhwloc.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtmlfupkxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gtobtllydn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtgmtpefuo.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtcrlkfysl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtmjuperuy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtywuzuuys.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtbayjuqhv.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtkkpgrkqm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtsueudtpt.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtoiaweqhn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtuqwhsekq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtdjynyjyt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtsnyafryy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtnpammzgx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtiexokesl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtvdvrtplm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtmuiunvuk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtzgasurbz.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvxpqoet.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtaclcqoqd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtkksceejc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtqfkhyogg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdcwezca.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvpmpuel.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtdtiynaov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtculsfqpl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlzpexhnq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvziycaad.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtasabmvjb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqnbekijn.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtpadufkot.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtglblxzwc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtnvrqdpez.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtulebrivd.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gthdzwutir.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtvlxehhpd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtdmcufmhy.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtgoxqosgi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbczkhggc.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtrxzxtutb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtalnydtgg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtkhqmvwcn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gtyxqkxsig.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlhxykfz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gthoggetoh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtiduopxat.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtygxazdpy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtapudohnq.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtjggeumue.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtvlpaeagq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtwbhxbxht.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtufkroldr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtcplurhch.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtaiqxipkq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtpwjpzwdp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtetbndcmh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtmpinyoox.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gttfdeopyh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtacxyrgge.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtfmlpvlqw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtuodxioaq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtbsxadeoj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtlyanggyb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtcizxhmvg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtvvgirkhu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtffdffeeo.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtqpauvndh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtdopysztw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtongqsjfm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhimafru.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtawvqsvmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gthbamnndb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfluqwjlj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtosxlgkjn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtdjidmspj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtwopjfwnk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtvfbzbomy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtaroyebnj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtaimeqbud.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtmrppcvzo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtzohikgom.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtrdlkklmw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtxqapnqro.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfftwvkiw.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtqduvvclp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtffjjeniq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gttfwodbnc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gtipvmqcky.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtudoqjhxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnvlgonm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gttfgojjgk.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtvkbbfqml.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtuucjsjdl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtwjglciof.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtvtumrtqa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtrhuqamxk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtedbsixmw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtwdgiqjbj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtmcefuvsg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtdfgabrtq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtkyjkoqfs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtsrckkkid.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjwrlttu.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtkudkgigp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtstfdbybo.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrayxjrq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtqmiapboe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtbkrppkfm.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gttvtsfawq.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtjsooaqri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtkngbayzm.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gthimhzdcp.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtnpiqvssz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtomvqzruo.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtdxtxmsys.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gttomlngur.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtonuyelxp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gthxzoeoes.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtxnrzenwh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtgnewjdmw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gttsirmnlh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtpoiaiwro.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtuovfoogc.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtbvcmvmny.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtdhazercu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpfadonq.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtxbgepvnz.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtypomvngi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtjtkkxqnl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtdlkgyaai.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtcmjwmlng.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrmnbacx.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtplapcphg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtrxshbemh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtqvxbqzgm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtrbpdyiun.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtfwnrfaue.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtjvrtemiu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtddblqxoq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtpodwlzid.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtzrlcqxjp.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtmugcgpnh.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gthyencstw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gttvlsmyaa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gttjdurgld.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtxcypkqat.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtlpwcgbbh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtgmokzzpm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gthxavgbop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtbblhgyao.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtikkuyzai.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtktzwxxga.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtzelzazcl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtirmphxxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtcxuocatz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtcemgontp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtjmpecila.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtsslbswqf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtueqtllko.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtoppbyumm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmcwfoza.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtgysvldgi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtuxoumyhz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtdgkjxsuv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtowybeafs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvdzfllu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtbpvlojqc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtkasqwdas.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtmhbwvbdm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtetjthzzx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtgflajilo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtmxzbefik.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtkvjmhyfc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtpzeebbyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtmxtxhwbj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtgbsmitjc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtqofpyiln.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtypjkmijt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtwwasishn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtgrwtgsor.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdbfbgvk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtkiyufxuq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtqsxoyrfc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtdnagbfhg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtkypgqxeo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtibcuhdxw.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtiwnfhyej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtbjtcgoyb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtuhlgeaeu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gttyjpeqbm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gthvdutarw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqrrsllan.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtmcofkrfa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtmoaspqev.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtmrcxjtmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbwnqrjil.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtanzjwaoo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmcpilkdw.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtewlsayqr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtoorpbdkv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtjnayxbfr.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtcbsakolv.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtdzmfsiyn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtmqmzkmqk.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtxysykybx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gtdtyqnlgc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtwqqzckru.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtdmhchzge.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtehotnjag.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtjpeltsow.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtvlxnfalm.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtcexemcru.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtmrrzmucm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gttixyqrqe.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtbzpvfawo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtynlxkwud.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbrpztrb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtvboyykba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtyldizait.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtteboypsw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfqbxbkp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gteknmbdse.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtzpnoacyp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtopaltvoz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtjfvosezk.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtfkjnbifb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqkcsgap.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtuyqzifrn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtbshxsnde.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gttxepwisc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfeyruhc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtupykibti.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtmosjqall.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtblrhopzc.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtfmsqqwas.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjzcbahu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtsopxprkv.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtsjgepzms.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtfjhnkibu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtnybtbxzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtirngadli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtcyonshfg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtbzdxbude.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtkslubngm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtufqzhzyf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtrcdpivrj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtmgtdromm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gthutgbnhc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtfnemsmoi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtxhkrvaco.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtyrgmdszd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtrlsdupqk.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtabqljhbh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtkvwcxysc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtmojukngx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtlmgpkuaf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gteebesnhz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtgdffylpm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtqwmmwqaf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtymxhstpg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqyaiwcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtxfingstg.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtjmydqkfg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpyowpwhm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwzphaok.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtrfrtfsbk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtetctddpt.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtxbavyxfa.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxcywdqnc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkngnhpa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtijsnllcx.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtepiaixvq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtekmthunn.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtxlqsdryo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtjvkbrrhd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhmtglcq.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtrlyppdyi.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtcdujdfvc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gteskgsarp.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtbxwfbzgs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gttljitlpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gthnqvcycy.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtdotdjxey.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtcruwnblo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtrgtnbeip.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gttzaskcjq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gttzoiwddg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtmjxhkxfm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtaukymoxe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gtewygedwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtoqugeslr.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtvvaccrap.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtgojvyfdc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gtlbwoqfgu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtanhmlueg.html


<!-- 参考信息 -->