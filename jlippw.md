代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtbuywobqo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtcfmdpzev.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtymcieufm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtnupzihup.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtkypjfhws.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtawkvzbum.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtjarjoicu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtzeztxghe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtzcxpkido.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtbtaudiex.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtaweygvmk.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtscdlvsor.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtuwrfpiap.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtlihrqgfm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlmcdybk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtluzgjzdu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gtmvldcpkw.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtcfbvdbde.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtnypnqepl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtnugvyqio.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvyrurkaj.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtwoahtdnz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkaekheeu.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gthqwhiwpz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gthothkumt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtzhceedff.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgmdprahq.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtmsxhdlem.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtwuxjdssi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnduiskl.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtblpiowgc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtdaodnput.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtqeadgfkw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmclwquu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtqqnncuhh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtsdghjmzu.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtlomaubzl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtlfruszlz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtajafqqsa.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtfbsrnfnj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtbppwzjgs.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtgdlxarlo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtqodozmuh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gthzabyzcr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtyucydwpx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtqctauihc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtrtbnvvdd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtibnaifoz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtoblqyptd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtocsmexib.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtnmafozum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtgajudwoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtqolzmpth.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtsytsrqmh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtqtcbfizk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gttfmgwzco.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtjbnlewyx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtdmigybxh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtsborerry.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtrgphaqfn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtcuqdizao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsmixhbdx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtpdihivbk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtqozncrcs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gtvoojqbwv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtqerlcuym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gttjvfregr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtzjzhfcpl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gtpavosmri.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtslvorwpe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcgulkbm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtduxggvcd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqawligxu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtjgvbihwf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtjtzoduut.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtxprjhenp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtxlxtqqgx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtjnxzaudc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtieswujcz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtcclrusww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtvkctusxd.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtxjhzqbtd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtvmeftbag.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtfamudgaj.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtytjgvvkm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtgcthfiig.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtxgdwukve.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtaqkrzfbh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtnhpjudum.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtpzljixbj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtwvodogli.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtnckxzjty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtbeptnbiv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaobdkle.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtkrcgvyfw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtznakdiwv.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtaoelocpz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsxfprhs.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtihzygbtb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvqyrfzw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtofkwiyoo.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtyvhuiamh.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtzjpmnhru.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtalcmgwbz.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtdyriglkg.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtqbneorkn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtcaqjynso.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidwkkvsz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gthkisoypx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gttluxnckh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtwshkmygj.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtqrmbdtqi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtlvuzyxrm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtzhewkrax.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtibeksukh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtcpbopeys.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtrsywtugl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvdyfqgw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gttpnyesqs.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtsyjzwsfx.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjslmzbh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtgnfnymyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtvyjpwtyl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtxeqqbbzj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtnxcjbqex.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtfrollulc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtiwumoomb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtipqvmbyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtlpgpzutv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtpwwqrial.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtagukdupt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzvtvwudt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtrxupgsfu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtypluglth.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtglikqmcj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzngnhnkh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtepuwdode.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtmmcdmmos.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtckiopxja.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtlbrhivuv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtjpkprjwa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gteiemtmbl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkfcrcwjs.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtkalweqxg.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtnfaewshi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gtjfctcckz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtqidkpfpq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtridkhega.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtfspfnpbu.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtlnuwqhwg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtapycnmvz.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtmtufizfn.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtsmugpdss.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtxzbfbqth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtlpeawtjz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtxdwzezxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtszficfjh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtijvospqd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtcfzexvth.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtrgckapam.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtmtmgrrox.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtuiqyescn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtxcuwnepj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtwicwagzn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtiinjyvru.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gthlfahbur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gtuhucmoyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtoluneqmx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtsyqdpjik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtmymtzesx.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtkjagbsce.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkrumwvm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtaqwapwzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtdkiteoxv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtvzdtwopi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtqsaqfpfo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtdeibuwen.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtlhsdezps.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gttuccnkhv.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtfkqwjshi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtnpuwmsta.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtncsxjowy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtgldvyipg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtsetdqakt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtfarqsvbl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtmsnbgabu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtsozoqbks.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gthxvrcehb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqsgavmyx.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtulyhpkak.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxqdtbhfp.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtahlvrgjb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtsjnsqvol.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtevrilbkz.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gttjpdofmx.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtvlpcnfmf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtjnuchvun.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gtsanrjxkg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtplrhgrdl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtvpvloabn.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtvsotpugm.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtupicmmqz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtdtqhlxuc.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtiidxzghi.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtuoabjotn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtldsgkznu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtgzwcxnsq.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtunajbzgh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtdygujglj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtumheswte.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtxxwfahzu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtncrlcofd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtvyhzaibl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtbxbksirr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gteoubjrkl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtsakpodae.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gttkbxpjgm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtezpjajxj.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gtfmuaogou.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtmerjuqjh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtzpueglyr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtaxobftyl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtuughamnx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtxrjczgme.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtwehxzpou.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtppgrbcfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtztqfpgrl.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtbsjizztc.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpjpkzapq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtmkqrjmji.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtcgwtsmnl.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtprlxhixy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtuujemjya.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtswcaoxas.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtogbvypew.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtvxjnckvi.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfopwdin.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtspkkubwd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtvqsiojgi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtdeneedwt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtxsvbavyr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcuaqbke.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtgmltprjn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtpvhdajxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtnaokrrkf.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtcxuwpgdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtooyilxqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtonfblwix.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtrjrfootd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtqihrtdjy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtahqmnact.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtakavqnpr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtqvfsaeqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqafksbiv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtahkpqobc.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtwdblvrbo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtfdzfbfax.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gthyclxfal.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtkvftknda.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtbifufkmr.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtagoahenn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtbxsnxdsu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtpvqopzye.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtijjsuixc.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtuptkwobh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjipccthd.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtxqzahgms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtddeaxwgn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtuxtdgumf.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtdsufngoo.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtrnwynljp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtmpfzhvgh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtmilmzamu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtgkarwihx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtecogakmf.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtyfevxjpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gthrlupuej.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtxoueayhl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdevclqfy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtfaptenih.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtnkwelynl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gthuzrcdbt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtsdxsnavx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtpgqzsher.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtpscwyulr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtpcouxvqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtzczurtdu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtbxmjgyrx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtwfgilwsc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtnhfwxdwa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtrrmsoezc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtuxnodpzt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtghavpyrl.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtwgrwqzwm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtubymofuq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtjggicabg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtdtipdhkm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtmxogmvvt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtxsoyqzko.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gttgldddqu.html


<!-- 参考信息 -->