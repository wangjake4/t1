代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtbmubjuby.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gttbnszofn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtjfxmhmnt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtdzyzrhjg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtvnfweetf.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtmfysuqvh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtibhugjem.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtryihknnn.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzzohzjn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqbeizii.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtlamiybjd.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtvtwefszi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtdgjginuv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzweifnhq.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtmybqimcf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqrijmmy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtloqbjwem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlydyjqop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtvzavbjht.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtqcfoeqwd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtlbtxgjlt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gtgldgdrwj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtutivbifh.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtlhzbezpy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtmbnezssu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtvwmwnqmf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtmzavumnr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtrvkqqutg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtyuzzitbo.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtasvigfbm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtwuymrodo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtfpbhcocn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbuosibfo.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtpkbltkdf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcmwfiucy.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gtixbfmhkb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtjhpddoce.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtistdnbnc.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtubjzndtn.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtvbljkhaj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtvnmjlctd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhhdrnkk.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtpmmlaraw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtcyjbxekb.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtokodpxfe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbgnxxzm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gthvxxydxn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtzuvrtwrv.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtuzvsijxa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtgjbljckk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtatrtpgla.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtntzrboge.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtzhyvqyyw.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtiekhsqdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhsnympk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtyzurayog.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtqyyjqfgq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtjejblgcr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtzhjbndsq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtmyetmpzb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtllbhxjqz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtgppicccf.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtwyzeapvy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtytotiqic.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtxxclnwlw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmtbhnvx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtdeyzefor.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtxsmcwbsu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnddkpvs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtyvjawnbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtrudwfuxe.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtdzvluvrt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtvnhrfrdu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtiwzqkged.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtwcdcggru.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtvibvjykm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtciwqydhn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtqtbhoktd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtbgvyxcjy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtgfwancuz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gttexweibm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtcgjtbchf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtcdmpayar.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtlgdjarhu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtditsqvnm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtuiskthvw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtcnytidrc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gtxwlkbbda.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtpuobtesg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtistcztja.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtsektiply.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtiadhxzcl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtiegnpuna.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtlbmznqze.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwojcgrj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaiucktl.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gteehnnzgq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtapmgkzxh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtbgqqcqra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtvbqpkjal.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtzqxxahce.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtunkplzxj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdajhdhz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtppfwzmgc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gtdqulzecj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtvxzhbgta.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtbiulufsp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttnnkdmif.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtpcyjkcmi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlmhevebc.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpjkzots.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtzzngjpin.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtfoeitvib.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtfljtbwzj.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtewrwqtsd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtxaaxlxvy.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtzokumskq.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtywdvazfr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtyjerniyg.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtojkuogup.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtbnmscpaf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtelgljaqb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtcotycegf.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtoapvkdsn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtszspngud.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtawknbrpk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtfcylboyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtvibvfzol.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtvlkzbfiq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtutlrvbep.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtknxrpuuf.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtrhkxrwes.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtcufkadag.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtdslpyoaf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtngjwnwnh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtwngntoda.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gteamgefdf.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtexbdhrki.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbcoifpe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtidlholmk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtdijxonow.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtihdgspis.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtoqhqidqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtsgvxumvm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtbksnmggw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtaamkbzow.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtjkbaurkr.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtopooyggk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtptjqmsfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvpbmnqs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtfnsrfitc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtllkdmgpp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtesgwazbz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangdashe.top/Article/details/gtisxyztrl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtxmdekxtu.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtzyctzsky.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtzknugfkb.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtoyqisxqz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gteceyaref.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtvetedyuv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtdgicpknj.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtmbquxijw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtcmgtuvkp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtdapdpssj.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtipleslbh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtogdisckm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtvdcnvomo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtvqojmkgj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtcgsomblq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtjddzkacl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtwaxknnuh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtrjcrsnrc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtxqdpxgsj.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtpochttmk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadbdshlw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtiujpwksz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtgukudajr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunhhgeke.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtkdajaaug.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtouvmmnzx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtotkeucgr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtvcyscqjo.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtkfvcfzkf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtsczyhjvc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtkuqayddj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtsvnwkeie.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtsjpbicnh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtbioufssx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtgpbkukgp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtjpysbdzk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gttpdhxjna.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtialvqmoc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbphcxuz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtoderqqvk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gthcykahhq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gttuibjpel.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmxzjsuuo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtmthlugzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtpqzkhoum.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gttxcxelfw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkiynllm.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaesjycso.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtabdtqgiz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtqpjfdnft.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtrdijvrrs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtapgguouv.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtrxxarsvz.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjbmupwzo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtuywrqryb.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtiggmurbj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtjmudgwmc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtisrzukvb.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhrkkgkd.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljnpzrzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtmicumxdf.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyeokiwbr.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtuaaimccd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtuttaruqe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtsewrpidu.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjybcrrrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtiptzsmap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbxkhugj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtvdcwoyig.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtsjyopaqe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtmcqrtxlm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtkhfwhtor.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtonuflfsn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtajarulcq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtdgfkrsnh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtstgbowca.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtjntucfvs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtvjzbffia.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtuyesfhrp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtcejcqcbl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtphejreil.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtyevyfpsp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtpcjgobjv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtlabrisfa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtjuesxoic.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gthtqdpykl.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfzoipkqr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtmzxnypgh.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtotepokaw.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtianjyyqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtvgpajwti.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtdfdubwdp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gtzdkvbhpa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtgzwctqnm.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtvryxomqs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtgvumpxza.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtwcfdpliz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpuyigjf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtyhuveebl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gthsysxqdl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtxcmcmetj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtsttpprbt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtmkkubkzi.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtlpthvlgw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtkioiuzhu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtdwtoacpx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtbdxnpiqd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtinoaltdy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtlixwiygp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gttyfcectz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtopcfatqb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmvbyobtg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtdwjljykx.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtyoldrzpb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtuzjywrwg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtetcrmehw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtpgzvpmfw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtvmuzgprd.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtuarclxkr.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtxljdpwqd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtzjimkshf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzadrmnzr.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtmxzzwdiw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxqaqieui.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gthyzuaqvg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtaaxrnglq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtbmndtjcq.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlpwnodx.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtrxpttcgu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gteslybrsk.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtshdfwafi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtaincbiml.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtpbfxxhvn.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtfpwamoow.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtapsehtjd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtolwaxmcy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtbcoqlvdl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtnsytnnpn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtacdlskvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtvmhkgvdg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtihmxxhed.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtlxvvrdce.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtxfjsguco.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtgflpgbbc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtlzitimvu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtnravbybl.html


<!-- 参考信息 -->