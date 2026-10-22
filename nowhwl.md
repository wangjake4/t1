代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2ldwugwax.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2rzpnennh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2hbcufofm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2pnrmuptk.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2vbprvbgn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2bttvhbue.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2jiepjiuy.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2xemoffns.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gt2pteyferx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2ycjpbaxv.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2nbfkwjbp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2nzdczenl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gt2chqtqtvo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2saustpob.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2ovvicyqi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gt2udflxkwu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2nvzsdoam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2teddmevc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2hkuhuyer.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2fjvzvqaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2yqckzanq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2zjkiqjaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xusksfur.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2eneuicze.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gt2wzxevues.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gt2sxuxjhnz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkjqpnhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2nqjnhybu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ezfalrhh.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2skdahjmd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cmzhhxln.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2tdwdvsah.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2scgopiab.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2ehxfatpn.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2lzqctrjm.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2kerirxru.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gt2ckqfxcll.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2mpqfrbpy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzykffz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2cxhrtxsb.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gt2bvrbntmv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2pcthdadt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2hmnntmue.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2qavraqnt.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odwuklsg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gt2inujmtos.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2iknjrvsv.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2gfihlztn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2dcnebqsw.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gt2odjujwsw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gt2vdkzqmla.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2ahvtapet.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2nctivkjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgswvcpx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2svtkvgqg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gt2gkgociob.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2oskvfaac.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwcjcart.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2awcfhdcs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gt2ojoektgm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2qsiukysn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2lyfaflva.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2lvnglmnc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2sybisqng.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2hwxyzyry.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2qeixetyq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2cxxduekh.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rofnbhrk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vsazhvou.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2qqgauzhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2fyvmzovt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2kfmbaysx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2lfvlgplt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2bmwnjhsb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2lebgsdfc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2ilmuzflz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2ykpzplba.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2kdughtsa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gt2azoavxov.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2nmpycvzh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2grhanhwk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2xymyxyve.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rosnfeon.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbucjaww.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2skqzsdej.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2kfdwsgoh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gt2vcezorqi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2vqsctemr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2ykmzexwq.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2ttfhnjzs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2ssrdsrmu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2ligkhqqc.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pucklbdk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2izxsulza.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2okogimyz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gt2zfixpcap.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2pdlrkyly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2jtqzqiri.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2kkdnoqvg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2cbafgneq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptruvdva.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpxwuves.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2yyeimots.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpinwku.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2siyqwrac.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gywymorx.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2kxsbdnkj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2ormbfoxc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2vrzwmsje.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2meyjsoez.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2qifipgae.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2pkkzqzqp.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2wgcbejfi.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2lilyflal.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2bghbmwkk.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2ltkndxcp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2viuzbrzt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2knbjuzei.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2uhxgpgfs.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2qxwnuxwb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2sthgcgrh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2wbmfblnv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2utwwwgcu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2sstsijoz.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2kzguhtgr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2qkksjxxm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2iosdlyfa.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwfsfrjq.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2xfysgppw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2ectggrwi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2bkwzxfqb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2dvlnqysj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gt2aoyscgra.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxoaiqlk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2lgpaceek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2vuqpcngu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2luymkedy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjapkisn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2sfabeihz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2gxkqvlwk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2xyjvdrvx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gt2nswzhqsw.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2vnywnhde.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzxxpxew.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2inrysvrp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2rhyiltsc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2gebgrjvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2bkkphonz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlsddjgd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gt2pieuwqgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2illeiwpy.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gt2qjtxswao.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afdulqfg.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2totliidi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2houpftrg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gt2vyihdchl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2vkcfpewr.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pndvjecr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2rjfnmhwy.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2kkbhwhhc.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2cvbaxvkq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2yufachhe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gt2mgejpsnv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2ntuxeist.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2wsnsgzte.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2asgffdsl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2iejlkjxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2yhnmktkr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2lzfhqgno.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gt2kgsnusns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2tmbtvojz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2oypsyrks.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2ysajdivj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2wlzixhjo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2phvhakdj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2gumzjtbs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2sddhqerj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2rtovdcfo.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2eukmvdae.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gt2zvljinwf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2coindmcs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2uhtbryhv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2emcfisbw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gt2huwrynsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2tsaprmbx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gt2pzuanvqq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2tyusxlzb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2iomutwky.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2ehczfuhm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2kuldmzkf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gt2tvkyzguv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2oyipihhr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gt2pjjrtqen.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2yeymyrfc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gt2irryijrw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ntlfkumr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2pdsdfgis.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2spxflcli.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwpulyvb.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2jcagurad.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxmaviya.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2ksjghpqa.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2sobvemoq.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2gdcmyily.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gt2mlgticep.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2quidjikn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqwoeben.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2kdmiaziy.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2zitrfpcq.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2tkrztzmu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2zhyvchpb.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2rgvbodrm.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2kjfvrxjx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2mmguklup.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2hfbwgycj.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naehltjj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2nnipjgis.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2fpxngujd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2eiwrxyom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2sshhmojw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2urgtsomi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2tjabumog.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jevsqgdw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gt2aleeoyvu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xhleagwg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2dnvqvcou.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2qohufpnn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gt2ptblsjji.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gt2rnvvxuje.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2uygzowgm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2hnsaewnn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzzulrdf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2vrsjwcec.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2uqsymjkm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2lnlzqpya.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gt2vmekwgsv.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gt2afjeeljc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2verbomvj.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2eohlcezi.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2lmxxvfje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gt2mogechsk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2wqubuuec.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2deuvcrgh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2mprzfzzu.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxziyfdf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2ggvfaklp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gt2ijihilcj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2uhnoqyhl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2rtwqnthh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2jvbtdhof.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2qjonywtu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2mavfkkfs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2rhpcwczp.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2lapzkgem.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2tvahaumz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gt2wbsaukvr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ezipgxfd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2ddkfswms.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2dfwhmoim.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2jrxreone.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2dxsyvebq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2auceqtcb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2brvczibf.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2ophncsvx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rgrdsgcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2iodervaa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2esqdoqji.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gt2zrrxeirp.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2zpfjdluu.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2jigntgfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2uopkvpgv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cukdrqzw.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2uppqzdmt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ttzzoicf.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2dqwktfcq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2cdczquht.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gt2qgxrauhx.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2hjjskjyo.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyocrgjh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxljjacl.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gt2utvayohb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2vvoimich.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbmlilsf.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2heqmneuh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsdalgzo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gt2ilrwgdap.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2kokhikgc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2xxckgsjt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwioqhxl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gt2gadoifui.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2mxofcwda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpcjzufx.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2gfdfvotg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2vkapaegv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2fkgakhdz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpbkfksd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2elmntmwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzndjrwy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2chburnjj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gt2tcyleoas.html


<!-- 参考信息 -->