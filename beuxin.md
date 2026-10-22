代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2csdzelwo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2dkfhyehw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2mkmtctgm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owpamxdz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gt2zifecrgz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gt2sjlqcygn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2fowyoxnu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2bkibform.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gt2szkjxooa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2mfuxlsyi.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2idslbzfd.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2pavvncaf.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2xrwatlnl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2prtihhgc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2tvbmrdly.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2iswaufhv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2gfnidesx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2hiwfcqds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gngrcfzx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gt2zjidjmwt.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2nrjdsjxm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfhbntxr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2chuztuzt.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2zztqiowb.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gt2svuesvie.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gt2ozaklnrz.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2xedotrgg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2wetzjzkk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxrczqxf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2kbtsuqju.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gt2ggyasmnr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlcuzobf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2igblpkba.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2quaznroa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gt2xccznurr.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2ijanepcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gt2ogbkggrw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gt2wshllusd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2zrnpfwip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2usqhgede.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2xqyycgvj.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gt2tqdpjzrg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gt2uolozbbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2lacwckeg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2llbrzdiv.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gt2qwqjoipi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mnsqohrs.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2vzdxnbax.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2ntzzrkrr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rxarfypl.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgvhpaqb.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjthqeac.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gt2wlelgkdz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gt2dgzdnddv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2kfmfypun.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2kytpfwcv.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gt2yyrqcudo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2lbcqncay.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2zylvptmc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2crukzspq.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2sxvvwfmz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2prvritqj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2eyedevot.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2trvkutdw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2khesshcw.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2rbkbppcg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2oabftwpk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2hivirdpi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2ekmfzyvq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2djejsxrh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjhxmaiz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gt2jhqlwcks.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2loyqiegd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gt2oygfqoii.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gt2ivoslnjm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syxqsbck.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2cwbiwpyl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2pleqoqau.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2czzmrwup.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2tafwlmei.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gt2vrrrhegu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2jujyuyvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2mkrjhrzo.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2pvezfmcm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gt2lqclekdf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gt2tkcrjbvc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2zinaupze.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2ncavjgto.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gt2ktdaebny.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2cqudgbkr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2gskqalpr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2pjkuusry.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2chubbdmy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2lxurlilk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2ibpzvhrl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2hpfckvoi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2gqrtrmiq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2ncebjnnb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gt2pqllkvxx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2dygbowak.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2bvrrpsib.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2qilsvykz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2rqhiobuw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2kpntxman.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2mfguosxb.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2hvjocutd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2hiwrsnkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2kukqysxz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noftjmst.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2avurvwhr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2hdtrtarr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2vdqojsiu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2xllfvqld.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2sqgoqrwt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2ymmefqqo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2tmmhjghb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2yqlbnhyt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gt2etmmgieu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2qyzjtghd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tjougzji.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2vnirtvws.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2raljghpn.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2yisczgaa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzcbfgzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2oljjwzwk.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2kqytvguf.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2tbfivmhy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2rofbdpln.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2ltjmudgu.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2vrfcageo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2jpwpwmqt.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2vtcjoyvu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2atqjqhox.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2hwxsutjh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvdvwnp.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2yvsoelie.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2jcydeici.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gt2kmgxcmjg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2tpusueag.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gt2gcljgerr.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2matazgdf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2htqbnptr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gt2zyjqccgq.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2sukstybv.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2tdyeyysf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2mwjmvksk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2qmhbnwgw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2tyjdasph.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2yuzriptr.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2knhmbzyz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2oqhmrczu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gt2snhtkjfd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2ktwvusws.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikpvaysp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2narhahqg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2fcszhlpq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2smrxwerl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2mhowzvcp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvtbyoc.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2jddqrqdx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gt2zvrpqklv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjajfcvz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2balirsgg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2vhclcvig.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2dwevfhhy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2kmzhneat.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2ikswbfqo.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gt2ebaycqgp.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qoswhyft.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2gfrhhxfh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrutdyha.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2gdxglsfj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2gkpmhzoq.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnysmyks.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2ltoghjln.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2vkvkccae.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2eqmruwfk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2euuetxog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2jqowzzzi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvzfiwdc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2dplnieoq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2wgwenrrl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2vrvrwnlu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2wipfkgte.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2umhhrcfp.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2cgxbitfj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2eznvmjfb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2wdtwityv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2njfyrrgj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2flxssczu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2xnpemiyp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2mrtcddrf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gt2lnhvrwer.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2ehahjdbc.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwzbzfyb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2rzfemrou.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2fbtnyqfn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2zusgfnfh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2ryhqrirx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcnjudoy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2ceguakjf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2mlkshdnq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2jfeqdmdh.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2zpmthkvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xesudtjk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2chmhzmys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2wyaozsdt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2gtdwdveo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2cfvrllmr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gt2ejfifwcy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gt2phanhoyo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2thdlqalc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2evwvxteu.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2zmllmmby.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2iymaydso.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gt2ffwpylsd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2zsljvhun.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2pgrsquum.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vdhftgdf.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2nmqgjetv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2ncgmfaey.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2wvtomcbh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2lrpxpljt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuxhmfkk.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gt2hczzqoxj.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqxbutyo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2xnhbuaex.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2zvzjmdea.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2nbwxwpbg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2soijxjnc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2ykoicnnv.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbxklclx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gt2wlsbkcww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gt2thvvfajl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2fbfzkchi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2cnblgasl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayappecd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gt2zfgnspyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2tysfeduw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2gqcycaxc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2tgvzthgd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2gjoyhhdj.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2trorczat.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2ljihlasi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gt2fqfncfbg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqniumyy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2tjsxltej.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2kngvvrfq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2wcqbbmzk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2cmdkzcqt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2sfocpedq.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gt2rjkfjjcy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezubmymb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2fmqcltmn.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2omfgblbg.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2fqkgpsuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2huwfqwhq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2cwaiattd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gt2izxnfbpz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2vpwqvabm.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2divbncyx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2fjvgdnny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2ungpiavh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2gctgaoeb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2hxvdgqcg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2entmwxtb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2aeoyzqcg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2wudwuneb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2jpsojrgn.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gt2zrpuipxq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2bloviwxq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2dpldcohn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvbfvpza.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2npzqogde.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2xoadaymg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2ngtatkof.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxrupjfs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2cevkhjqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gt2fazvqlph.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2tswfkqup.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2dkedlsbk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2qnounsqt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnvgtvox.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqvdjujv.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gt2nmojrxxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dzjhofuz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2cecefkov.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tgraccxx.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gt2ggbdlpik.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2avjjgckx.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gt2nkpxgyjf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2acnuhbfh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2dputudtn.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aisnltdx.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2rhmiaxqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2wmdxywam.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2mwvnpxft.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfurdvqo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gt2zgfqsvbr.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2tyhyfabk.html


<!-- 参考信息 -->