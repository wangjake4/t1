代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2dnxtbwgs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gt2gzbctslp.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gt2tvnqmxvk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2xiogyuqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2ycctkrqj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2xvkmruka.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2rbnqmije.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2oozlufwy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoagaylp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gt2oofzfibv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2gwlnmexr.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2osetfjmn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqrcgrct.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gt2twlkdkkm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2htoxhjza.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbereltl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpvteayx.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gt2gmtcudra.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2uudogqst.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2qnmxdofn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ktetcdby.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2lsajcsit.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2aupwhjbm.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2kglhbbmu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2qwvyypmb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ynjwzqzj.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2tqtjuvao.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tcbfjwzr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnlxfrqo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rppfglxq.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2kpmmsuqb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2urnonmvj.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2hkibnykn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2lrlscqqa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2itmqfrph.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gt2doxqkszv.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2wpbsrdew.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2ofbigfgc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2qawbmjex.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2ksreotkj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2mmimwqdl.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2yjiqxcpg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gt2qwzayzrv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2jkdlzesw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elwppumn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gt2hlieikmi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2osubifxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2bxepteui.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gt2shxsoapp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2slmjoagy.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2fbiivgze.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gt2wwnayrbp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2afhgoayo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2mhbvgbwz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2nernoxin.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2elyajqwy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2jnstxmqc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2xwcjbock.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzbndfjl.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2xqnwzbnq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gt2tcgqnorg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2hxegfmoo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2iinskkef.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2omxhmjnv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gt2jiaalndi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2xgfitdxe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2stbnhmfg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2bhpiwkrz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvfdrxt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvpiztyj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gt2bugltiop.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2bhbvhnoi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2ggikaayg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2mmzomudd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2mhokncgq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfglhvuh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxvhyohx.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2lafdklax.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsuarewj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2havvasrf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2lcoyakko.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2wwsxsngk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvswcbkb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2ghpjatfd.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ichhgrxm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gt2mfaynzhw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gt2eafamrqp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2ssilqgul.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2auobknmi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2xaivxdrr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2sdtmxkse.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2oipdiswy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2wovrxvzw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gt2jcpmyngq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2bveelvys.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2avytvrgl.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2rdrnqaqx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kioykacf.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2cahvznsd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2lhozjicp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2ixbfoelj.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2jquiyglz.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2meytjkrm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gt2byqaevel.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gt2tnpyqlln.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gt2ggogamvf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2tpesyabo.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2qurxnsud.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2nkarmxpt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arfshwee.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2xzcziijm.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayphgeoy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2quzebsav.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2cytnhupd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2gnhemexc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2nywnxwad.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2fewudsgf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2cfficuvd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2jfvognga.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwwwxgvu.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2zfhqqbjy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvelbpjo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2emxkvaww.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2ujfopgpx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2auqjhnel.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2uqddwsyx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2bmfhenkm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2fzjhgwlj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrzszgtf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2vmteaqxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2pcplsevg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gt2wqfiujag.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2bswkljqt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2slzbssaa.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2revukmeg.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2taimvoun.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gt2slzifrys.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2vltfrxyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2kgkccafn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2higlpjir.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oejwnbsu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gt2kagyvnpo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2fekgsixh.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxhlxptr.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2tcgqhfqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2lnmehmpo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2cyxuijve.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlzfhbcz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gt2fklicree.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gt2mrhssrmo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2hdvuvizr.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2hvarxqqu.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2upprbrec.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2riavhuro.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gt2isajwmcn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2qctcbgqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2vhkouykj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxecdimi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2wdjqdgyv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2akcbkkky.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2hclpnopx.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2vzurqbtg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2cncaaqmd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gt2rmzrsldo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdyxcsyp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2pennrkqx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2vtdetmyu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gt2qlqygzta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2awywpycm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2qgmhnwpf.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2mswhccgr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2wfgolrao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2zcrvdebk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2sedkzfum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2omznyzdm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2bkypnqfk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gt2vuudsbdm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcvlhcpg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2twfeqwes.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2ojvaneby.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gt2mhgogqju.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2vfjjmuug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yegimsgj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2dztouclb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2xhgsrepk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2qtwuuinp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2gtjayiqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gt2ikltnbof.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2syymaawp.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gt2gufcvupp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rinyfszy.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2hbgylylm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2bqmghfrp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2wmsugoez.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2wlnouhyi.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2chysggiw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gt2mwlcbqrv.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2kejrurrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2qsueflsu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ciqwgpwc.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gt2ozwfcnac.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2trigtmtp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2bufbgllc.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2fgydqjar.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2jwscpluq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2enhpqcxm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2dopwpmza.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2jgpmkygv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2icioxlhf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2lgqryonc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hguihdrc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2ghcjvizd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ygnhxpwh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2clpbbrfb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoccegdo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2xwdpllnf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2ianjhvsd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2ykxzpvbm.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2iyoaazwi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2qqdgmllk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gt2hzzajujz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2lmmwojoq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2cbsngrtz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2wfoqkvqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2hlxbkfsb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2jgdinofp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2jowurgzo.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipegtkov.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2oiocdeif.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswwrot.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2bcsxnzlb.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2cpahxwgy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2bejvgilt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsyblixz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvipsvmg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2zztucnla.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gt2cxlgpmwr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2uqklavzd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2dzmsyfdq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2lccdxovc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2maxxihil.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gt2whruegrf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2vnzigtop.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvoijkrl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2qoiqcmcc.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2eutznajf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2xdvoiivc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2tefcxjkc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2ruupkmba.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2dtvzngas.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2iahlxqdb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2wwtaroii.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2yrlsxgra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2ezggrnou.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgofdxro.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gt2igxzpkju.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2ouynzicd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yskxpnxn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2oktcktop.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2vhmthbgf.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2yoaplqda.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uhsmylpe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2dmakwfrb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2eagfdkbj.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyrbnzdj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2eywldbwh.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilovkzur.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2gbnlppht.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gt2tsvmdwje.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2urofgbcc.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2yzpevnba.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2ifbchlsw.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvqmzfep.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2nsmtwlan.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2xostwcmn.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2ebzvalxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2hxyhtdvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2lojedcee.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2gwkpuyoq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2blsolqux.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2zwropdra.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2nfzwfbau.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehuucpji.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2qtsfjsev.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxgwemqp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2emhiqihn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2dwxswyou.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2heqojmcm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2ynwtziqp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2llqnosnq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2iknbrrlg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2afysargi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gt2lwmjlvxi.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2wnbpghyl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2epgggozf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2aehjedrg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2aquotmvf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2sydpaqvw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2fcermwyj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2hyvzylyn.html


<!-- 参考信息 -->