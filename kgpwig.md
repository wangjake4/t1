代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2pbsyrrkh.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gt2qjxwbiib.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2yrguzkgm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2jdbzsvkw.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2ygohrlsw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2jojwdeue.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2tscrxsys.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2clxwpyqj.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2ggwkheia.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2doamfdrp.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2cmsnxueo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2uqycrzpq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2rktlzpsg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gt2wdpuwfvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2ubxpgbid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2hbkjsuhn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gt2dpbgasix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2xgmbllbw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gt2jtxyctvi.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2cofrdtvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gt2umxfirwr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mycmcbjy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2oshbvltr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxdoadnq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2efuhhexi.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2ryvuibup.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2nfonpewg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2pprtdauc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rysulhop.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2jnbmjsuv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2oidwzdis.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2nfuaqwfy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnmrzyr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxuyxhcr.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2aaohisax.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2upminmlr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2cwfbdcri.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2myvvqlvl.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2lzbbwkyv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxtdcvkj.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2ikldvvsa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ssclutsx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2mlwcmqgj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2uaoryasc.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2xdkjetnh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2ibmdiqba.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2patrpbjh.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2zwssfjle.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ndnnytml.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2rqqwszqn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yermlvcl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2wliqsbun.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2iivvxjmo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2axubmjvv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gt2zfefrygz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2gkfmdkti.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcpfhgts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gt2cbauruni.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gt2ebuouzxs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2bxxfvaoy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2lojhvxpv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2mgrncgxp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2smhjmwus.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2jdfkqzow.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2hvwzhisr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2ofxbbhgh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2zzppfjwl.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2ynzrhdra.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2dlgqasnq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewbauijj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kirlmgiu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2sqrqvxfk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2bojfutte.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2gxtxicev.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2bxuouaie.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2gikiyyqi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwplucub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2muadwfuh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2oomuejir.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2tfbtgytf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2dpnixwot.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2hsqbnjbq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2wnqlzdnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2rwhsicva.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2bfpenzms.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2hcbgqnkr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2otzgztae.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2wpqyqylj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gt2sxcxyzug.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2iozorogt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2zajzjpot.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2igpibuqo.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gt2fhxhmenb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2qtvegtmu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2svkxoqra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2dfdvwdnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2wgjuroug.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2lyhikyti.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2zjjdpkjp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2gkqogygj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gt2wjltlkvy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqqchwuz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2ottttazy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2tmtooobw.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2hndvxxie.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cunivxnh.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2fxmdgddx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2gddbvocb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2ycmltrkt.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2myhwbcww.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2hnlwawac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2hcbjmoba.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2ohpoofxk.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2hybehfga.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gt2hidmoloi.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gt2jkptnqwx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2xrtaknyv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2qgowuvgt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gt2wzviysgu.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2rqiwiejz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2blldrrtj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gt2ikswsugn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2xnhknhzs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gt2etncuyum.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gt2jbpbucyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2ukpjgawn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxcgaizd.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2pbxwbcue.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2gzqvvlkw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjfdonvd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2ttebwfii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2fldynyti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2ecjfogpw.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gt2htcstnwe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2dpozwmjg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2mvjfhaja.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrpdgnui.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2xvcqrfqa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2pobezzuw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2domzsklj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2kbdwzdbz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2xqhqzqbn.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2qywqfvsw.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2crlyizlm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gt2vobbzsdc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2zghoqnlg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ooxrpbpj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2pdfharuu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gt2wjkhnroz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2lxfztqlf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2dhegwrwf.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gt2yqgftzxb.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gt2baosmyav.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2myrbbfjh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gt2txazzfxw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2qymbfprd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2rwhqhldp.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2jszfkutn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gt2rpuzjgzq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2cauawxwd.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2dkwytcyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2wlkpblqt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2sztgakjq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2lqioweqb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hawrylad.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gt2sidzpmdv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2dsgtveqt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2qpgpxqqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbfwkopi.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gt2mgtvhwid.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2zkwveqda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2lktuzqcv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2klmwsvwr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwwbbtgk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gt2dnsntqwh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjimqtdp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2mlgudvmu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2vknosbpr.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gt2nzhaxauu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gt2asryermc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2rzxtopwb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2dwkulnse.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2raqkakij.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gt2nlupqeca.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2kykrrevw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gt2wtxcfbnt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gt2ijxgfbxc.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2afxquqou.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gt2ijnfceoq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sysewxrw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2qbkbqmfd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gt2wxxwnfpq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2rpixuwuo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gt2qjcowxwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2nwqufmoj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gt2gljradxq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pywxfdqu.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2jqjsdjwg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2irvyutqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2grfgafmd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnqwqlpy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2wrcihktz.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grsfovwq.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2pbirekxe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2tlztklnm.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gt2yemfgiun.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2yddjrumw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ztyzlcdr.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2mehitqlf.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gt2zxaloqep.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gt2pgauiewr.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2lbagqxwx.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2qqokcnly.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2prfcirvw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2hanfjcbs.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2tsnrqcyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2uhbpbqbv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rucbkmva.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2kdykktdm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2ggpsipsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2yvwusffn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2aoszrhix.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2hexyoitp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2oxgpljgr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2cklixscy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2zgxayjkz.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sprwdxic.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2wqvbasap.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2pasfaubb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2trllncsq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2cskeruml.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2plafrbkq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bedjvasw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2pdfhedtl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2kyghtnvx.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjbpivje.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2muwkdycn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2wtdblxdr.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qgcmmtuv.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2akswkoyi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2jsppxeed.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2yilqdowq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2ufdvghwn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2ezkcszgb.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2qaakswdk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2frljmtix.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gt2qgrxizsu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhcyyzrr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2pivvxzny.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2yaoflsnv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2vblcmozd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2cwqdjyzo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2jezykmxv.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gt2ahyhjgcv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2rlrbkpnq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2pqnrgpwx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2xwlikkzk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2nsraopfg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2nwprizde.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2rnajdbmr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2jqhdxbof.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uezbzpre.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2fhqokzvw.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2gyyqpysj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2fixnolhc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2hcbjzgej.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2blixdrcs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2ctqkmbbt.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2glfknntc.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wyyapwdj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2zeusbhkf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2whrmybbu.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gt2icvlcakj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ujpfzvjj.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2eaeqvimg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2namiotem.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gt2gdhdrssr.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2adcrhryw.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2cewbyccn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2upmxiqnx.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2malitwoq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gt2ljiiggda.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2nowcyrkc.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zehrlwal.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2tfhbxpmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2mrhxuewg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iociaxgf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2adlqundl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2kruhnyog.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gt2ttasugjv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2ruwqvzjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2vlozofgo.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2ihedmoqd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2yjoajdvo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2endxugle.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2pteochkd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2uptqdjde.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gt2gomtaakc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2uhqvfuvp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2rugidzlp.html


<!-- 参考信息 -->