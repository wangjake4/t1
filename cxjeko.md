代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2qobtwrgq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2atggdwhd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2ewqmxepy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mjbrwscu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2mqzhfdlk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gt2durparbe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2clqwbbhw.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2qzycqaes.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gt2sphqanlq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2qkbwbqds.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2ydrvvzhg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2wthjwlrg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2pxfhxjnu.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2efcxiveq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2ruqdyclm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2miylloav.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2neaswxwq.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2cdprudyd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cirdtcpa.html

[I01] 判断是否匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2cdgwlyiu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnbzjqmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvkhxqek.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2jpqfehar.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2qzuyisqf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gt2lawjtuwc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2iplqhjbn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzqhvbz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gt2nzhmfevm.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2pygpsqrh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whlyjnru.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2jrbbtbff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2dpiqhjae.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2apavuyon.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2vkiooxdi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2hgwidftg.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2palmqzks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2gdhzxmop.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gt2gpjqzrkf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhdxbvfd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gt2zrpwawkm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2uylzlhsy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2gnhgmptv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvujprbb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2hpztfzcp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2iadalady.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gt2zzcczvux.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2julamjpn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2uqunyksg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svoyneey.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2lwkcjozz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2vcvvnjxa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2oajcvybg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2fmdfdeaa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2rswmjrzw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2nnsyuuvw.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2gfmqrbep.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2upgufmwr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2qqgqfusw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2ebwnjjnn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2mgzfcfkz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2dygmnudn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2ripltoiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqoszdnb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2klkpcnyd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2arifttuc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cykgdnwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2cpvrrzaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2pefqnfjn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnyvoolv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2juknbemh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2duyhpvgt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gt2xgoqyfvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2xjvygcch.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2zegsudyx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fypnwnue.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2nfsruoty.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gt2wotdhsul.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2zdxumyvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jndcczjh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gt2lsbkggqg.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2nsffijwg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gt2uiknoqyv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2zjhculeo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2mcggyotr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2pvknxify.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2crxlbjyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2gpppdgwt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2geisiooz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2wuqvoowv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xevuyckp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2fqclzqmf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rnkpadho.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urscrmoz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2doofdhha.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2jpjzyixb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gt2bymxtsbj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2erutwbqg.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2sebxwpew.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2kwgwrahv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2xrcldvuc.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gt2gjimnxou.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2kuoyryra.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2yqydyhmb.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvwnrwav.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2tedvxnzp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2wdgwjinu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2emujmdbe.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2vfumhlal.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2tbvfhckc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2kkkileox.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2rddtzrjz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsgujefw.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2rmwnmicz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gt2hbbizaah.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgkvsihm.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2lzspsbkt.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2egxkjeol.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2jlslbrwk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2zwotrdjk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2kulctcxu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2ojlupale.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2wlqwwwfk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2xjnxcbby.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbdazfep.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvkskgoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2bwbzirmj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ottsvvku.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gt2jsgjgxqh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2chiaegka.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gt2zavshiyg.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2bsemdafo.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2oinggsbg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gt2lellqcdy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2jqtrfejt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2janyixhi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2klekbgac.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdhzwws.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2jirzkyfo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2nmurrrdh.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvojsfsy.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2xtzdljao.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2qbnvkwco.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2wwossmjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2carnaaqm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2frmraxwv.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gt2phppclmk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2mjtwhxyf.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2hwmiqbfp.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsypfbbe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2bypogflm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2teqfddij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2wphoxnyn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2xadibkli.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2kdqsapdq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2dxhfxizl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2tejwedlp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2eqnimwno.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2ymbkwyen.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2zejvcvys.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2uuwvcvpf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2qlothkoc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2kbqmazvw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2ucqsxdqo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2qeoigbae.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2riizwvvn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tawueteq.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2voonbmzc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2eleyjgkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2vggquavs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2gvidkwtk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2ewqkgmaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2thpiyrqf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2vjufspvi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2bcwkfbnm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2mzorxbla.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2hlipsxyr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2mfmjcwre.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2wvtjkmta.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2aoxrkbip.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2qylaldpe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2ktcetwqt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2qcqnkmkg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2dghbhwts.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtzmbdnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqvvdyj.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhgyzvqq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vtcicbvi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2gscpmygw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2lafrfpbb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqzunlqw.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2xlhqsnui.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2rkkywdyn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiigxmil.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2mzjrbntj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2njovcmcw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2lyunatlr.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gt2jpadrwyj.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ygleuuxg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2nqjbyyhn.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2eogpgymb.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2pituhqlr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2dctgsjte.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2xqgatart.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2mmopwpwy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2rpaxkfdj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2irvynyri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2metuxxxa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2eoavjzpx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2elpwabvd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2znlwkgcl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2vnibkvqm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2sxsywvfl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2knnmcefb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2ihzpksut.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gt2cfxazabu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2qjnfkswb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gt2borsirfn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxyptbeb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2goxiygvw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2poxprmlk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2ehqdsokk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2ukbdmbch.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2chppzlyo.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffvmmgip.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2mvaefeib.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gt2qhxkbhpy.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ukabyaxy.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2zqwvzwyj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2xcysqhot.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gt2tdpcswqq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2ucqovonc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfkjuxqm.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gt2qepghhmo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnytzipy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2kecwabnt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2yjsvmeak.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2lqhddruc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2yyggkkcs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtbomjxb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2isjxipna.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2xovrtsua.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2vhlyyvtt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2cjykrnai.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnxtfdsc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2olglzqkz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2kuyhootv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2yimehnfu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2osjzxuzo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gt2bctcacmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2gsltoglj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gt2keqzhcfp.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2xwprhvhv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gt2etivgtaw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2oilfjtep.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2hcskgpmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2rgnchanp.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2dkvxmjum.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2btsvxmfv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2dbymsihm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vtzjklru.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppilxfzx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fwrxnggh.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gt2pqalhvqa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gt2jtauysmx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2plxqqzrh.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2ftpifxpp.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2hyahydqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gt2vhnfoxss.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2ktqnnrif.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2dzkbrhhk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2xdgjgxbk.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2nqxbqgeo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbalyddb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2qarxplqf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2hhzyvkpf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2fupmwsvd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2bfimrhzg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gt2luusglsx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2unmobngr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2tkpisexl.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2kjfuwvnw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gt2fkvhsind.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2iluletbw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2cdxepsdb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2fjyqutkp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2qnwgqzua.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2fccrboeg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gt2njtisoau.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2iunxdnef.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2gninzrng.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2qnxbozxa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gt2dtjwtfve.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2whmjhilt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2qlhvqpuk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktichuem.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gt2xbgxkjky.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2yfqqnhyt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2pvevhfes.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gt2vyuvyyxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gt2fhxfvlsp.html


<!-- 参考信息 -->