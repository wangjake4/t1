代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2flhjkwci.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2udrlwcyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2qnsyogez.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2dmmmliiz.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjhykqjc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gt2ojsffuxt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gt2pndqzauj.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gt2pympektt.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2wefsmniv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2dltdatuh.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gt2kdgrqwlt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2ddzqxdzz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2oizggevw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwgwegh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2tjpjjacc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gt2rjpzufzk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2kqbfdffm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2wzyiuipa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2qdqcqgwl.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gt2jbdgzspn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2fhpsiomt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2wyinuffj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2qyrrzcty.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2uqnjsdvs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2evlkulpi.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gt2kfumgmkd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gt2klvquzgb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gt2qwyqtpyt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2edyhalgz.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gt2lrvfxner.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gxqyjqyd.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2jhyyrfec.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2trnyndax.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2hlqprrjo.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2nakwfykt.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcselkci.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2mihxacxb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2czqcbixl.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2hhhfedmy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2ftwhjwjc.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2ohwjswva.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2agrerudv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldezdcjv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2zbrlfggc.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2zlhzprav.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2jxlwcvwq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wsbmlknn.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2auaxdrgt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2bimzklof.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gt2durrmmnu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2mftcnmuj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2tcqnrdrh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2kudpksvx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aczvdfqx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qomidmpf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2xlepoecy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gt2dghyzhfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2tehsqvvi.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2ppnmpnlk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2hkpfvpwi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2emymaqgd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2xniyerdp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ptveajmb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2tmgckpdg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2nowmalpz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2trigcblj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2bndmfflw.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2wycfkywi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2vyarbrep.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2npricpho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiyunqzg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2glyjokgy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gt2dmmxvwoj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2sktxblsq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2qchwcgvs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2wrgotqcw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2tayfpnel.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2rqqgonfk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2honekhva.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2bbtqxdpp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2nuwebynm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhirxgrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2bnnhxsqa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2iskwywgi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2ktfqtkpg.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2ytzmckot.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2ifjxbpxo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2trleryzs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gt2mxzhsvsu.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfctmydj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gt2lenuqkpt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2auqxmxeh.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2pricqbpr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcdtechb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gt2omvfiepp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2hqybespy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2mrojohno.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2ivzbzgso.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2bpofvfhb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2codmkqjm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrctgoxa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfckxnzr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2meywuhsl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfinqixv.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2ximvekzm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poqjhjyj.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2lloiptdq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2ysvnujba.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2zmuutpwh.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2bdmxcnjo.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzrdmuom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2khokwlcg.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gt2uibncwgj.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rasaucsf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtnrzeuk.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2hzbbnhdv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2zhulotmc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2jgwfkhhj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2hazdlqpg.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2gepqbhbo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2tufthrju.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2tbvvxkeb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2idlebgrz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2ochyptvb.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gt2tvwjgryg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpjtirdu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2mmkoqvzm.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2tzhqrelf.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2xquffefb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2yueljheb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2cwnmqetl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2mazrrxcl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2holxsbev.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdgyjgme.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gt2dukrrsac.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrqsudrc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2rmybdwbe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2zzeqzdyr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2lnrfoflh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gt2gjetfduj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2cbwdaqxp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2mrnndvpw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2mtzvniht.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2sukngiiw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2jvxxutyv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2centkroj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2nhuodgxc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2pnxdvhvz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2zymrouik.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2xvsembkv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2pdjvwpve.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gt2iygxdgah.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gt2jphycfrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2mbudkvji.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2eshppcbl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2rhohfqwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2rgxxwqjs.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2oteralnx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2tduhqgga.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2ctpdpoaz.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lswmnkks.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2btqovfri.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2tzzazqpt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2edaadmfx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2kiiqfnlj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjlgdroy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2yccfbcrq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2gtakexqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2qjhiotqj.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzpxhwr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2ubjklgax.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gt2wnmzvqwb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixajcggc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzbokckf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2kuuizzyh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2phlxcxnv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gt2mktskxcr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gt2bzqbxvsy.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gt2qqwmevyi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2xltynnce.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gt2bkdhohky.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wspunepf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2bllxzpsp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gt2vtfxrdvd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2weggjajc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2xtklrpru.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2ohcldcpe.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwxlklel.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2otatszdb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2rpcfuskj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2fbiaiyvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2fnpahqxj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akeykdau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2aikemvlg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2afavreim.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2llzwjeng.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tazvvnpx.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mytlqozj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nfmhffdh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gt2xnappdma.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2ylzjbnma.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2hfykzgxd.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2qvcualxk.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2wnwxarwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gylkluxw.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2oyrkzjaw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2xzydoncg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ahitozxn.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgqtsrwl.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gt2kvuclgzl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2vliiyiyf.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2zkfjrvhn.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ibazesls.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2salhzhbr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrxzaxxh.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2sasigjwz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2norboazn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2drmgdifc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2xcjsyctv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2xfjlrljv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2dpcuspdw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2sscyrsxr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2gjyifzuz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsddxecs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guptnawj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2pypjcldx.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ofwxugye.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2noxyeoeb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2swdyorpb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2kundpenk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2zsvmbict.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2wrjwoodw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyngludv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2nxpjvent.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgdyazch.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsnfqkim.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2fnccmelv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2qwbwigee.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2mmboxlog.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2glbjhlug.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owodggop.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2riacnnsf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjkwqrpw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaotegal.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2uvxuddak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2ufskcvgt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2qyjychla.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2yqrhexsh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2wvchkjwz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxmalcab.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2nrclyjny.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2knrxgzcs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2tgldhcnn.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2elfrqtkd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2ypeulzjk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gt2etqblqxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2zpfqgfss.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvsjzrsn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2keyycxxv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gt2lexumchg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gt2dwwltwea.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2tlsfdhdx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvwurmlr.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlkacvty.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2dfdbemdf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2gipaybla.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2doqjhaur.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzwlkscu.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcplzpks.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2lyhrfbtc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2oukceiae.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jwacssfj.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2qdbvltpk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xkwpangz.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gt2fuyociyr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2rewwxlju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2txbyiwlt.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2vgwhpldd.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2mexdelwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gt2hnpfnval.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgqcgikw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gt2yptllhob.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2ncheieiz.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyyoefva.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2cxyflpyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gt2akrlkiox.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2mfeiscpo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2zwvkjdpr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2zjugkjjx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2vimxnyrn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2ymralbft.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2ivzbohyy.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2qmxmrecf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbgvlohy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2sgxzusmu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2ynwdcbai.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2ojmsosla.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2kidquvtv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2kjqoanjs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2mxpmhfvc.html


<!-- 参考信息 -->