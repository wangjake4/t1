代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gt2ykrqvtzk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2bnbbktex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfwthmjp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2csbjkvzk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2vyiejuoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfxdvhdb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gt2sksixmgh.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2rqrztnnc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msqtdaay.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2mhsawbwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2doedrxtd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2ohojizwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2bgyxnqmq.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2keeotrcf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gt2goqnvdrr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2fzrfcxbt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tdhqfcmz.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2mqzdtcwa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wgrzoujc.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2nmjvjtdk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2noipyiiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2yxojsupd.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2yeioymqj.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2klalkfqi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2zwcwhmqf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrjboqej.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjntgqpf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2zazhzekw.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2wfhmafvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2pjgtqeup.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gt2xiciscij.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gt2cmbvaqvg.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofbmtojc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2gyegzpyi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2rlwznavj.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2iqmqmqat.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2ibqsxfmn.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gt2olmzqaqm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2xpezrjja.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2cacugixe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2fmsxshyo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2mtgwozua.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntdemvcr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2xtnypaiy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2auzlccfb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2okmevpde.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2unjptano.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdfztegj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2mcncnvyv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2cbrulcpg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2mlcyyuvv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2tjbvbynq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2erqtcmjz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2blntdrom.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgrvuuet.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2yepbfegm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2lebwixso.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2usjxfumo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2zarobliz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ffptkxyu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajtanmfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2kgxhnklm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2wwocpkco.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gt2qaqwwkcs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2icolzmiu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2jkbwxiws.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gt2tuatiphp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2dqquxzpf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2uaotkqxq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2xpkvnaml.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gt2detrrfvv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2timkowjp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2tptkowot.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2lymcsgdk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2upuqlxrf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2fjlaixpy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2tgmkjiji.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2lofmvhes.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2oiplbzrj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gt2abxokxpu.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2araltwnr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gt2kkiwoaut.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2lktfmcvc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2ffwlrxnt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2pmuuklyp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2wirgljiz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2klzkvlpr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2gtpgmabn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2dugzwbqi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ottmrhrl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2irjmlgik.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jwiiwivg.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utesgddf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2rnbtkmmx.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2lmgbhesw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2itxepszl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2enyzlttj.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckcnpqgb.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkjzudfr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gt2rqilorvl.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2swqikplx.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gt2uclwomya.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gt2acibucxv.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2wkycoulr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2tbdlbxek.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyryufmk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2iqgmzzok.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2tntgljiu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2esdcexnt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2imribphs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2itfpkkwb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gt2jwmoctqr.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gt2ybgttwsv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gt2vkdrylsh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2krfjrzja.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2tudeqhea.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2hzmbmvkt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2ifbimiln.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2dmcykbua.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2ephulovi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2ybcfmcoo.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2roczdyvx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2vjwvbrww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2oibhiaqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbovkmar.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2gzqtekxs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2iusubekm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2cclkcldz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gt2liruvxqg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufehiqlb.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2vdfzuvvo.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2xzwyjfyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pndigene.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2wffvlumn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thskfemf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2jadrjnxd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2manymtky.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gt2pznjmijv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2mqkvctcm.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwtskslf.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2svjytoma.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2smjjqdzm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2adyjpojs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2bzsukqss.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2onnimmia.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2igjtqjea.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2tiqcpfsr.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnqqdyna.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2fbbjknpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2cvhepspb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2ebkuqlor.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2ejdognfl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2knikbpzl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2zkxuozxi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2yjeekyfa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuwzphjq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2towrzmwm.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2dtveawjq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2txywmeje.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2vxbtbmon.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2odgwqqnh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2qzlioale.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tokcfqpy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2ncvjpguo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2oywlkmgg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gt2fzjkfdye.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gt2jfztpicv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gt2mwopdwwo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2pfkruphq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2qexrfkkh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qobftfta.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gt2lyfqxeol.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2vpytndqx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2agyqzzsg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gt2dkmrbiac.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2ekyzpuji.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2uywlcgze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2inlhntux.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2zjnvuuki.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2bkohsoso.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xyexkueb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2zajwlxux.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2cmjjklyi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2lapooako.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2saycadzj.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2yarlfbqk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2spigdhuy.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2dagbcxvt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2hxtmohbv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2plgdzjbw.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihvlwtcg.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2lwmbagsa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcorditu.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2etkznaqc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2jskyvful.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2powdfkwt.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2vonluxsu.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uknzzhcr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gt2vzzomcyd.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ywkjtbcx.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2reuopquc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2pjexcxox.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2zlnfpfub.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wftsmtud.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gt2womvrqmd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gt2xqqmlqrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjshjiqi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2dsbolfnm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2qrodyzsp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2vclvcsoc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2cyoqyqvt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2lboikbsl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2jzvlfqxv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxtnmklc.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2wueyuntk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2nhfyymmm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gt2nbqrkbux.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ityamoyf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2nnhzuqqn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2fkfjqkrc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2dmpcorws.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2qpftrhuo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2hzjuedzd.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2zjzxztwg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2jmjhewmm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gt2hffqnedl.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhcsolhx.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2aafxwksc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2yzxdhqae.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2qtaeyavb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvfxnhms.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlyctdba.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2aakzlxfb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2chablpko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2rgdoutwl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2kwwqwoyb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2fouthgkh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2kjgqaeje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmuremar.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjbwcujp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2qtnzgtsq.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsmnffso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2xayvzwdw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2dawaxojf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2lxghyafy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2fxvdllvf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovsdbzct.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2xgpxiskj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2fsakbbrk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2neoporzy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahdozmab.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2vxanigow.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2oysffgbc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2ytewnvng.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2bzuqowfm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2rdpyjvvo.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynngjjea.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2rxxvdecf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2tdnfaqga.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2uylngiaw.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2enebnbtm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xolbynsu.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2sxbprftu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfujytrf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2fbqfbhte.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmslezih.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2ryvsntsr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2hinptqzc.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2pcmplzju.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvkpyylm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gt2acoouyoc.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gt2mywdwmnu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2wcrwquna.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2ljdwmcgi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2ppyxratk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2cbhaukfq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2vjszkvlc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2dbomlfdp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gt2rgfxutnj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2jeakxawo.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2tmuyyscj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2rshiyqlc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2rxgrzmfe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2kicpcqcd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2ywnzgjuq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2aywvpckb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2fjkunczt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gt2baspzeyg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2inhabcjn.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2rhfpkamp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2eebomzdq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gt2qvzgldgs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2normstah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2zcfcmdef.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gt2pglwlder.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjvdzwlj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gt2srrvuklj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2tfejapng.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gt2fcmmszah.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gt2jrgzppmx.html


<!-- 参考信息 -->