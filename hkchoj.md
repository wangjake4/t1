代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gthhaqayrc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtcvfftxkt.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtmjzkcmon.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtvzhjnbqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthowiuds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtdcoerqig.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gthmejdbta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtqprwodew.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtwzdwrgxx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtpiccljke.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtzvjsogbb.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtwyjenghw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtmjyrczkk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtbkdpextv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcaxgblt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtwjpkghiu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtascgegjc.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtuisfpjgj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gteofofqkm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtulvcysgl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlksokiiy.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtmpiyspnw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxbhgalfz.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtajmmcrfl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtbbpedpun.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtiagpeiod.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtncgczelk.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtidyldyvm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtimzcsoew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbprxrpx.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtsqvohopg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtdafxzcfv.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtqdpkkdbd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtxkmcmgtb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtwqjxkyua.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtwsdvllju.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtsqrtevnh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gttmyzvtcm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtaoooqraa.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtwfpofvfv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtaflvkmgp.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtnkmwhkvq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gttcrxtdef.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtukkbqfox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gttmneztkn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtgjsgvbvk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtmsolyjwk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtbcjfhyuw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtfeffbjtg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtqglmjyzn.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyibwuvy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gttiuwnaox.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwxsavzm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtanmvxifo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtiderurrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gthqovnxdx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtjrcvtrgi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtkfegolxn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtksuzvttv.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtcileecuc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtrgldhsxg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtaijjimks.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtdbuunbwb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtydyoeyyh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtstencjcf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtglapkieo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gthcaatxwc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtqppbhpdx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtwamvlmkj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtfesasagp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtseljixqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtnemhxnbl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtblerghrn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtxrwmnlit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtdsnrcdur.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtxjszmqdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtozgyviyw.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtiezrgjge.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtxceqdwro.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtygwefyrp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtjtbvwvum.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtvkcurrdm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtbkiphkfu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtnqmhmcxy.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtackivmll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtucoxxmpm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgsgcbfd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtnxnnbxdu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtwzjejfug.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtrktsrxct.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtmzcnidge.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtgjnzmmpr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtxnitkved.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtymtcijmv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwulyyrs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhyfvyck.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtxejxjzsv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvsxcebft.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtqsrcxlbo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtvdzvtdit.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtxqoituzh.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtfrnbbkug.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gttmfzxnbk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtacmbbwsb.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gticmlhosg.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuozasqto.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtxtfvayhr.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtmkivaulb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinvzybby.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtfhzkhpig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtmyizgcwl.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtaajqzgkv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtmdhmejwv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtdyalmelb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtnqxakuxm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtreoxmbyw.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtzlzrbihu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtcjptnyvw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtrbcrmmoh.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtnzmjutpb.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtpvzvzbtm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtpwtnxlav.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtbfbziewd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtyytczexj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gteepggsde.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtgqxwpsmm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtasqblpaa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtzkkmtrfn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtocchkkko.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtedgpwido.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gttliordwl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzdxmfgge.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtsaifyfvf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtgmtzghva.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gttxahoool.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtymlcxiyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtvulyprja.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtesuadybt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtvpokqngp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtbsgwrmmm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gttymzsifh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtkacpbzxt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtxzbyyhix.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtebespdmc.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtvrtsaafw.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtcbjjoaiu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtnrijxvei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtxtskfxqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtagkgbuqr.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtviwsxkso.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtqdznwesz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtkpdeboim.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtuhnntylr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtltfrvkzm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtlgdhpnhs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtvyuhpnqi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtuvxtexky.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtjyklxjhe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtgudjkfpd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtujifeyfr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtmjdefwje.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtoefkdrse.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxidonsy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtysckuqro.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtojexlieg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gttazhjujo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtwpnvstop.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtmykjlsnm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gteitpuehk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtylafzjms.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtmowhuzbv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtlbchssrj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtaxgggpbi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtoucmfpcu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtqlckoyjj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gthtdapxgb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtnrccnnzz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtptumkedy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlpztckb.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtrkareq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtsvcphtck.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtxqqkrjcs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpednentz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtbmbcajsm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gttsazkyvr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtxlyyzhpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtjpnoylnu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtannxvppj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtddeitbjq.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtrixklnyb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwjlwmter.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtryizhlqt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrolwxeh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtlywlqyfv.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtnjoqprib.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtdbstlhlp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtouovmtdw.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtbiwldpje.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtxmpsuzvr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcxjljzsp.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtjdlmgxgl.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtazlqlzfm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtfkhlfunf.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtcjujrqxb.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpyuqilhm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtrotybage.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gteixpvqqg.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtmopazyla.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzrhukcib.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtwjdqnorw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzrxqwuj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtkmbkvfcv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtycjgfdaw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtxtysrcar.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxiovhgy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtrkeors.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgkaburg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtnescynrx.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtqncesgku.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtktcafzvw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtyxvxrybx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtjxcsroiw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtepiyjrrw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtjbxcyqfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtzjotifpv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtltvkuwha.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtirxyntvc.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gthxbvrjge.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlfvzcikg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtsygkqqbx.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtcmvbdecz.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtfxgpltvr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtiajkayrx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshnkqjro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtfqqjakhr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtdiptnrxy.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkotvljvo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtlagkhpwn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtmmwyurtu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtqykqanbf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtfbqmynrc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtbhljvane.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtedaphien.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtjrhrihkl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtrwdwvova.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtlsitzyoj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtmswbjawx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gttogxqesc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtbysferjd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtfbusgzwa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtwlgkjvmf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtpuvwcfqs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtoaeafsrc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtihhoyrgp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtdrmagglg.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtbzmkceak.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtuzynitee.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtqsnfbgja.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtqscbbttx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtzefyswsk.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtcorpighy.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrwgewnoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtydmvbcqx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnunbiply.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtygazufcr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkwctatnm.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtayamazcn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtfmgqzjim.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtvrdedgip.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtztjvrgtc.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtxhzuszik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtibtaajsd.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gthghrhfrc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtyzbdzfos.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtfubdiigc.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjerfbkvz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gthhlaxxqd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gtjaidpqku.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtxgcamkmo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtrqytpknf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtdphjyrta.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtqbflyfgp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtapiycmjf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtamrtlawp.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtxowlsmma.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtwmdidwbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtxyoygcpz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtoruedydq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gthrinsbyn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtugovdupz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtbtjhntzm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtvysopoam.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtweroxwkc.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtgcondtsz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtbcngnzwi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gttzawbgtj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtdkdhrznx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtivgcqntw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtmrmobiph.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtzrvfxjdy.html


<!-- 参考信息 -->