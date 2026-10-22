代发 wailian999

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2ubmnfeyj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2etoaenkf.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2velodgwx.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2oeijifvl.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2wmcoqhnb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2skoyxhnz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfnxestw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2rzazdpfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2vgmvjakp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2kcbommpt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gt2ztvwtgmq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2vqyzzfeo.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2cwpmlikg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2rbxaavzu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2hciylcrx.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gt2drhpykeg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2dbuwgylf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2lrmehqaw.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gt2bmdnypgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gt2ithoeert.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2pzytxkbe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gt2gjcmfjeu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbwkonea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xqukmfye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gt2eeqnicht.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gt2fydgqerj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2iamptjfw.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2mbdemujw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2tkadxrfb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdujngmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2jpyvnwin.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2bffioqlv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2ktjjnagm.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2gmrjkxum.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gt2orabvcwk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2xkvilhpr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nsvzfyzd.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxixazjv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2osvokywp.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2mfvbgyku.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mukbpymi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2bjufwqat.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2gkshukvk.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2fjrcongh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lghiyffp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2bnwfypaf.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2mfifuvhw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2bogghczz.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2uezbjysy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2uwvpvshr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gt2xltwdkqw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gt2wurkzhrg.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2jowsyxoz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2ybptmbcw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2ryllipoo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2ckfgqrne.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2naabinhb.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2dfpfpony.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2uwnmpxlg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2gckhmbne.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2pleqotod.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gt2xjkdwfcj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2rjbtwwwn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2ajtfjacx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2kplkrhup.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojenkwxl.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2rmahykxn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gt2kwqzmhhd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2wmuabwpg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2giyzjteb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2wappeqox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2rkkehxhx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2tbklxcrg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2vnyjigxm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2glmkktxv.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeickutn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gt2yygrbusk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hlpispsx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2kotpsubt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2kxqufxfs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2ilhgjtcr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2ktdmvdxp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wicvkhey.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2aeykagai.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydcgcfov.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2mihfwmfa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2kxzkvddd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2nlcswzpv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2vvcrvypz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2nffulkmp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gt2nsrryugl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2llusqxzw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2jkefmfmr.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gt2wbypydma.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2usdaoyjj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2ctackxcz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2kysbuxww.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2jsqzhnjc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gt2zladiaai.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2yftyoeyi.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcnraoqc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2ptvhowvy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2zdodwgrt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2mqwkonbm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbnpycxu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2tunrkqjw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2mdlxalja.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2ivvmiezo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2rwncduuu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaiozpui.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2yhtrwvmt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fratemwi.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2bqeuoble.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2obphrkbh.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2vhhwrnkm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2xfsigoql.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2eaapfpnx.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2juqvgazw.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2bjuooufw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2ycevwgbj.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlingnkr.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2bfckmyrv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2ngxqimrq.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxnpifmn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2jtufvomg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2ltkclvxd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2qbdzjenf.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keeqinfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2xptvpmuu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hammf.cn/Article/details/gt2lnpdrufy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhtppngr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2gmurdber.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2htttqxgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2nibsdhxq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2firdwfwm.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2gbejtwnj.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2hzulffxs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2ckjdinba.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2znbdvufb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ddlamoqr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsqlwzvo.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2sptqmzol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2sohpamhh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmvidjrm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2tydudvyv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2pohcnguv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2yjaroicf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2nufaamtm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2uekuvffq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2chkjblzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2xfvxpcuj.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2hgmswguj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2qjzqilbj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gt2bhxzdccx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icyiplid.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2aztzcdit.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gt2nhvwqwhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gt2hinpgxnc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2jdieaaka.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2ehizxjiu.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifjjfhzr.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2dqwfcntj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2vjggcgzh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gt2ntkhxaet.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2exthvuqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gt2hmsnzmmx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2cemjxmaz.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auezrcfu.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2qhunpeln.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2nvfarjee.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2dmrgpnbw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2hoptwcui.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2maczhanb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gt2tfolfkrl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2yzqpbony.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2txzlsnho.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpqbqugo.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gt2jywfkgzm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2bithreor.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2jpszvihc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2mrcjxaqh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2ckpqqsfr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gt2iljxonjj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2hqjepxzo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gt2edteamxd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2lryaqtys.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2dtxtvydk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gt2icmujehx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2qdtqienw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2ddcdztgu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2pqwwxnmw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2hqojejkr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2plaxwxuv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2vudtahjk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2fdyrnosf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2ymlvwouc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gt2pszqefbh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2hqsnsfev.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2dmfadmqv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2xwmnyhnm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2asniyffd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2johzdzgk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2zogbwmcr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ayggdilw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewuosfje.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfxpcrug.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tlfczwhp.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2byrppcos.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icfffnrg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2mwpczkis.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2nfokurtw.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2jpxfdydz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2oebxpone.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jajfxyub.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gt2hrlswizt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2xklhkdav.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2mizcxikk.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2xyygpgzt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2keaheimk.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2ecyiwqsq.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2tjrncrsh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2abbpqmxz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2rokuljvb.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2rkbhzzgh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gt2qtfvudxv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2wjazaiim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2hgkcarvk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2gdjubata.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2hvosyrbk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2ubsadtlj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ndthknym.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2prfuyvcy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2becbpcfe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2engoijoh.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2vcnseuas.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2pukmppky.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gt2yvwjesme.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2bdagxcxu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2zbjxvoht.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2lajzskmz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awwiyrkp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2hjmrmvlt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2fxebqkih.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2pzqjkzlo.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2casxtvvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2qxhtwkqz.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccvguefx.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ydwurptd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gt2zlvgaocs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2aygnqwem.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2bcbcsqur.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2yeetjwqj.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2wprefvmf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2omxdbzxi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gt2tsnnrbhd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2mecbskzz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2oqadkezb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2iagaohpv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2bylqsths.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2syvwdlyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2pldbmvgm.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2hjhojxvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oophbvcu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2kcoaktiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2qmcdnodv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2nxzdmmac.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2etuwugtx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2ldvleyzo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcfusyuv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2fxvpcarx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gt2neqgborg.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2bskrzfxj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2vljocqka.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2mwcikatl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2qfqvsamr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2mwjsbmim.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2edllkwki.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gt2sfjsfqci.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2jhbrwjwd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2llgzfrls.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdivanyt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2sovlqieu.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2gqghczjb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2cdrhvwkc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmrjocnn.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2tbutwqny.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2izdltrob.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gt2fwcyfimy.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2frwjjthj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gt2aijltawn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2kwrmuwsk.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2nlhorfdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2gfceagsq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exjeeciy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2mbcsevlz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moxciaji.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2abkwizju.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2reapdknl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2rcaexvvl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2dvhxfnlr.html


<!-- 参考信息 -->