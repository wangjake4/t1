代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2boxmqzhs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2jkejjzua.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gt2tkpwpjmg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2cwioxkkj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2pjegluwz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gt2jtcrbgpo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksxhrlte.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2odrltgjk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vihgrhhn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2xdyilsic.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2hlmerlai.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbghttzi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2vktcabdc.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2vptlxusi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2allzcoth.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2yuxfefbu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zrwkgfvk.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2yggqwvpu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qykyaotu.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gt2livzueuf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2ilmnxent.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2wfvwhqvc.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2gcnqzakf.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2bnefywrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukirowkd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2exswjjpr.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2kingfhin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2rwdijjei.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2avfnlcro.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2xevvzomg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuwhmrmf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2qgkcwgqd.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2enuzvrzp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2qybtvtzw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2gqslcbzg.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2bklzsypf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gt2howflgag.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2mymgymif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2kebsbwbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gt2rykqsmki.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gt2bipztzih.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2pnjhdfvp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2ehvwbgek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2rlyywixc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2uolhgpld.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2xgitvlgq.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2pocqyidg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnxlytno.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gt2fpcopbsu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2zbjlvltw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2uffxppkd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwzykbbw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2fjjpyctc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2rfsgoogh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2lziolkxk.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2pcbuawwj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2rdzxsubs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2kmgtjctu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2bsdbjhcc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2oaaxjscg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2qeuatqdz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2tpbduydd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2tchrmvbu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2kuhokwsu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwkyufy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2sbaarxzj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2xcaycinc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwrtxvbd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2zgapgmjj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2wauhgjux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2hfcwewlm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gt2dwdjtcas.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2yahssqyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2vkautvnp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxigmmed.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2ghfextmu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gt2otpftckh.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2pcrrnirn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2ytlwtfeu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2blptfxqp.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gt2bmjughky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blkjblus.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2wapwurqe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gt2oglmvpge.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2xggdkznf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2mdyjptjw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2wutkdvpc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2yevmxkjj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2khdmdybg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2dnvpddef.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2okfspgui.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bjsqjddi.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2lbehicqd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2jtjhfrti.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqrimzgj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2xuvczouy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2aqaodube.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2llzmolmx.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2pfoluxbh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2kzefupbm.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gt2ndoydghr.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gt2gchewngo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2jcdxyekt.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2dsjihyas.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2nyzimtpg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2ymkphuui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gt2rbhsmhev.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gt2wztsvpyr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ribkcdzd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gt2immnmidd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2ssekungg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2saccfjxn.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdptixim.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2jqvuikey.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2dylmbaxz.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2nhrjrfuz.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2qveltnty.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2gscxezok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2izynttzl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2modjvulq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2rigoeukq.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2jtlwsyql.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2pzxgtmiz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2umughigp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2apyyhacm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2itsfgdwp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2uvtigobu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gt2olkrfngr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2nidiyjfm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gt2xakphnfk.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2cberfovp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpjzxbg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gt2fkwjljaz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehihkkgv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2vftxxtix.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2fbxyicpn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2izysyhfp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2nrvpjmas.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2mkrecght.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2cdlcclak.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2emibaono.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gt2vddrafbm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gt2ocngftff.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtlaemai.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pivsrtyf.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2jitolseg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2sxkysqcr.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2nchumuqr.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gt2kprjgjpv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2qwegqcxc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gt2ivodyqmk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2ogypamrn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2udklzbhs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2xynpyndu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nucgwupq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2plkmktwo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2dtjnknjy.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2ydmzygpr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2yslimohp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2jsinfrvm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2kggooeby.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2nlzfgxam.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtdtazex.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2hdvzhxto.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2ormepmsg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2sevixrrs.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2secfldfw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2kfplwghb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2adnsshvl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2gadqmsmx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2nrcvgovi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2caqdaoae.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2orupvznl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2opvlcgoe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2lsistgsw.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2vqnhufpd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2imbwxflx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2xxudopgb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2zzfapqmv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2cfzslxny.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2cpcinnrq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2hanwidcl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2grkqrufy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2esmmnnnc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hddetmjl.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2vmzfqpfv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2angoougd.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2zijuykth.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2elntzzxv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxaskmhw.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2shzuctsr.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2viujvtch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2tiysxxcy.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2vivglbge.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2gtytacpy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2lmpoxgpb.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gt2exkznqts.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dztluqqc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2tiegaebd.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2pgjysudk.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2ffwkjxyl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2ufpsmqbs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2caquziqz.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuydwizr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2btvlhypc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gt2smvoeudb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2iayufeqe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2ktglcaqo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2bcafpbbi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2tfmpzrnx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mvtegwhj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2jtwvholy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gt2akzqsjzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gt2onzusodv.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2wpqjmvbt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zclsyvog.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2pdujtkbk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2tvvlczdu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2klgiedkf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2oewhkipe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2pkjuudor.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2laipmdpm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2byzfnbfp.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2zlvdvjbh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhivgfvd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gt2pxqvymay.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2rrtvepkl.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ayfpircu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2pocxkzdj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gt2mdzoluyc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2ypvluuyn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2mdixexho.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2abrsxclr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2owlogbdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2wnmquxpb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2cvacziqo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2zdqznsrn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrzvszrg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2ijivwtvm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2pdbsdxty.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2ruikmnwe.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2muymougq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2dbdcyibq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2thaamgjz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2tnanhzko.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2xwdhvarz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2qeywbtpr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2aytgfdev.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ljvkijme.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2hstnljrj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2wjywdefc.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oiuphdpo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2qesjtqka.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2mvdqxdgy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2ickswlfr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2ekvlixmc.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gt2znlplsyy.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2gohyhcqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfakgycx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2adingnmm.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrdvzxyl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wsxcnwzh.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2fmiglwva.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2haliddtd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gt2bbxelugd.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2emopjili.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2dfkxdzxr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2krwgghnm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gt2kwazzfjg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gt2tqwmfkqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2lrwtsgir.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2fyoqeojx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2tierkoft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2gofftdoa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2oigiwwlz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2okctzcgv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2xfekodrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2zlfugeqa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2zxexqqxq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gt2kzprtjls.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2kirixytl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2ilieaiwn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2yslbvuhp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2ckfmlcjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2vrjmhxfq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcdoxvdu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avwwjkga.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2uokxpkis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2lyafjbrj.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gt2ucsudend.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gt2yycxkecq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2jybpxtys.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2wyhrnnqi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2cnfqvmyw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2stuqrsts.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2mpooelbn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2uhkppbbn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2qvuetbwn.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2kylirrei.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gt2wkqchfyr.html


<!-- 参考信息 -->