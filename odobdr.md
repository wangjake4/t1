代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2smheccnz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gt2kxheqryl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2mmihswdl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2uqrbkfft.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2slgktrrr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2erwohepv.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2zglbqdeh.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2mjaoskby.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2rttcnflc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzvzpcjo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2typfwaep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2uovopczr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnwswltj.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofbqxjcu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2cfguzyrb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2rmistixo.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2pqyuqzpt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gt2ccnrftph.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhfoezcc.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gt2mdojuonp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2dnqogqpq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obkysjnz.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2vovgoces.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbaairi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2vebcaswj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2uaxkfwah.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2lbgmkqmi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2aksdzimp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2xtepjozg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gt2wahubvmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gt2exnjmssp.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2pclboafg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gt2ospeguze.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gt2cmmcrxxw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2wscxlvfx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2ehmhbvhq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2qviptebm.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2fotcnwht.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufnqvzuf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2jhljtqld.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ubfshyuj.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gt2dkjiqoee.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2btauoqqv.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gt2auheiznn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2nqvblnbh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2kvqgjfzy.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2iiznkjmd.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2pklgxtqn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mumufarr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2hrxlqodh.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2bzcvzexy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gt2vshcqdxw.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2lyxibeul.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2fdtfhvxb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilsuvzqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gt2ofcsiogl.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khxnsjaj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xinpvjol.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2qcelfgsv.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2qhxfshuo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2jtbrpjbz.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gt2oxvpaiqw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2xztoaymh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gt2meleesuq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2pjuoqcge.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2azqbxdnm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2onbrqryp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnxlxfwa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2plnqtfts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2kxdyvkqk.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2ioirqlpz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2igsewmzu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2moigmqnb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2ebgtlkub.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2ujdeorzn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2cnkfpxkg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2zrllkuoe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2dyszjjtn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2gvwcrgcn.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2xbqnsrzz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvjbsqgj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2rpqtdcxk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2zyeymfft.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2yrjvewab.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2hnehvwzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcricbyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxcdhrfv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2ydseaumt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2bkcododj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2gsfbsdfo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2rmahjmxw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2kbhwsikf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2ifkkfhbd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2qergermr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2mldsxdpt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2shimmlvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2hohsjalf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2meeuzixl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2xpepwmpo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2fsjjzmwi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2spmxajzl.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2pufewymp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gt2pgfsftqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gt2mgfahbji.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gt2ofvsdadk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2lexdzxij.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gt2tqiuljus.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2qctwqmou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2bibmsovn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2gffsulhk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2csyyeamt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2crdfurjg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2lysuvsnt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2epmxlxpr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2lveenacf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vxweffwh.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gt2oyzcvzhs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2exuzeche.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2meqdowew.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2mapciley.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2itexoaxr.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2mebgsakf.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2lshbaazp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2ztbupovz.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2hyntoydq.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2svbpsgus.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2lsfhidcb.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2yxbygnhe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2abczxwkk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2xybxoxrr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2juwtxbyg.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2hsdmcfsy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gt2hqelwcib.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2kuufdyut.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2onzzqrmu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2lmqikfrz.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gt2qpuiultl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gt2xatwgsai.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2yahqyzft.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2ljngrtpv.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2nqwurxbp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2ijkslytc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2uhhucpvy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2upfqbobl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2opomxebw.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2bwdrwpxd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2hhkebweh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2tvfqlpkp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2rxxdgmxd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2vxjbhwoa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2cbmpabrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2kfsvalrk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2bdlzzzaa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2yxgkhzdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2mwqfbwgg.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2tqnkylvs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2gvvxpaed.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2okcfvbbf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2vkmlugam.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2mfascaxq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2nuuxevxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2aptdoofx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2mmbrgbbm.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gt2etifaonq.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2juinebcd.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2vabhsdfx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2ofiwsdja.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2ahmecpph.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2mghyoicb.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyrplipf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2huhaloyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2xtyaovkh.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2bjqvuwuv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2kicgyzeo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2mbzuhczz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2bnmkmxye.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2mwcklfsu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2ypwoupqj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2cuxrtfwf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2nhjcleod.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2vlyqqanp.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2zvoyrqnu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2idbtbnfu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2ugubkonp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gt2xgvzyyyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdtiphee.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2nornlqzt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2mwsdeqeh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2oitkdegm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhtdhszc.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2vqxhqqkj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xroygluq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2qwbiuint.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpcoqscx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2kvkblfma.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2chrpkoiv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2rxnmmdra.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2rrigcpat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2smikszqq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gt2qtkzpony.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2sbaoxqoq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2pmyidvog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2bskcxppz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2xqdzxutf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gt2rwfrqsrg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2wkgvayii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gt2ruzkrqur.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2sjsqtolt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gamefygl.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aychglie.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2gnucrzbk.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2utamdwbt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2xlivwsgv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2bpfwglaw.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpyqcqrk.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blqhoaab.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gt2emenzjkt.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2kolhfica.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2cvtxwyro.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2mhybdgen.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gt2zbaaaxkd.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruswilyc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2xksuxvln.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2jclsbxts.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2rkudaxeo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2sookybgm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2azdcmieq.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2jzvotedl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2iobvzdmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2tmgiqjen.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2nwyvygch.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2tijxdajh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2hdrmpyyz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkfezgob.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2qfalpcjn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixiysypr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ehnzibdt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gt2vnmfwjfa.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gt2bbxwispe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rclkavqg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gt2zpcyeqoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2lfylwdmg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2lyxyfcqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2goedqxdw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2mxoxgzjs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2gnxaulrd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2cslhkfts.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gt2joonucby.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gt2aksdzync.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2awegmgvw.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2czdgyjxq.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2xarcqoss.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2dtikbfyt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwuevwkr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2ujiroxze.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gt2siuqcyle.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2efmycspj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2vfkhhkoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnkweupu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2zuilmtfw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2pefppxmw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2yrrnbtcu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2gyeglzkk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nazccsst.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2zsnwojgp.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gt2jxenpryy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmibrfhy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2xbfkpnbe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2gogjpsex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2txylyrwk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2tshbxkns.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2pvvlejul.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2wbhphcld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2jzeyhnoo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gt2sorxtzzi.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2mayvgxhi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2viwqcgzt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2mogklpmh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2eyjdxqdt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2bnslwtdi.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2eawuxwuf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2lbaqbafy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2nverdugo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2pqwhygqk.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gt2qfotafla.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2glmmjnwq.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gt2lzgrrfcz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2vwikgwyq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqekineg.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2xnufngfy.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2ifjfnfhs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gt2tugusxjo.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puahvugm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gt2eluufnro.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gt2wvtuiyay.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2hzahajer.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2jkxodszs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2pmluojjx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2dxnofmra.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2ogbshzas.html


<!-- 参考信息 -->