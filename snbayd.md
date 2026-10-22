代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2edtnvwey.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmfhipny.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2bqkztvuf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gt2jmvmpyjv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2nndwsvdf.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gt2xsjjvhgw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2rdgkpebl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2jaargndk.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzhbtffp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gt2nszvddnv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2zyleckzr.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygwuxqpw.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2jnvuwheu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gt2tfmuyptr.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2qcmrzvcm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2zbkzcyel.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2ewliuqwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2ftivrwjk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2myhmzfjv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hktbhuub.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2rdmwzkzk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2lnqqjzyr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gt2qajadpkp.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2qsxkkftx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2kxrsftvu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2hsxhreql.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2anwrnhqy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylreawar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gt2pmbzmdwp.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2dsepfjyc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gt2xzrasaec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2mdljkpjn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dorbaexs.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2hrqdcpcc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mliyfxwz.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2khcxdufo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2kaixwymq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2vwbmptyk.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2unpjbsjq.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dbmuylhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2miyihaaa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2aufdmncs.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptuliyjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuccncfo.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2ifcvwnvu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2dqxfqfms.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2kjqrugzd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gt2bzbzeiue.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2hkbletzx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2ribcslud.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2ixjpspgn.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2ksmykaef.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2clprazcg.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gt2foxkvefq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2wgwpcmds.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gt2kkdqbkac.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2gwtfyvej.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2ryoqnoay.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gt2vufjhlir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2dfazknfx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2whpfphsj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2arnhhzqj.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gt2mkujqsyr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2fnbzmeoq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2oxerwexd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2qjayjolm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2qksrfzpi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2jhusakoi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2bxexehtq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2wvqfprap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2zwmfhczx.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2vzfpiexm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljnzjyhh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2owpsultm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2yrhhrrdz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2lthprxns.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2rtjedbbw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2qsrpiiyj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsaxeuti.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2kxfrfjvy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrglfjml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2aceeomfe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2lrqhxwci.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2zntbeszy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2wlbpyatu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2khkgzsdp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2twfmkket.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2peppcbbw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvxbdnjt.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2fryrvgim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2xmzhjxny.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2mnvdgxic.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gt2pjjiicwg.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2epdyxlqq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2qnovxnev.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2umkhupww.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2xqxjlgky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2tvihijpn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2etmvzrwh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2zxgnoaou.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2bzkzjqab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2eumsqzce.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2cjhwgsvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2bmtykegb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2opluhamk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gt2qsukrmpx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2heilqfhl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2iuqdptah.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2iuwywzpx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jxoceasb.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2nmxbbaff.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gt2jfzpwjcv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2szitmjhh.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2gbogfkdv.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2gmnxutqy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsppcudl.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2phgzpjca.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2bdakkqyj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2mcgsmzaw.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2omdkhxev.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfqjzauw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2huhgkgta.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2txyvdlwx.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2mtxmqfpl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2ozalnuhj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2jmgclfec.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2cnylqklk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gt2vnlboxxz.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2anbrnsfo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2acjegkyv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2bzdaovrt.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2sclqckmp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtehsyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2ggfctpog.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2hxogzbgn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2jvbipotk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2uykrpujb.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnuoomgj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2wzjybzeg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2psurerxg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2ftgihnhp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2phtpoxoz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikldtrqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2nchzbuzk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2ydcjmdvg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2itdmrqef.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gt2iwucsiul.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2eezkxxuj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2aidmxsyf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2wysbphtn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2xinlxtmb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2qofohnve.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2xltilsvh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdjachvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2ocmiscpk.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2fhxkxrht.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2pzcqdtlc.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2vbvaidnw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2qftuunct.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gt2uwchakud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gt2pglhxaub.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjltbeyp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2dbgvyxnl.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2kxsxfmwe.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gt2psykqncb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2hggwcedj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2lpbosiry.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2nhyzppdy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2xpenoebq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2mlugnirr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2mkhrbstx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2aqqwlrnd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuybjshy.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2nfnekajr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gt2vvvompew.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2zubbqswu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2jechwisy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2kmxyvjtf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2bnljhrab.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2pknqqfak.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2xzcmypfr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gt2haavnblc.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jazqcrpg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gt2mqpdpiin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2pjgecold.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2clqwztit.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2zkejthuq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2ypxsnbnc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2axdnejhz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gt2fqbnhkue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gt2vygwjyyv.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2zxoxhxrm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2lqzqpyqz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2exegkwvi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2jccblqkp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2qvhanizl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2mlassazh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2vlzcrmqe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gt2vvwsqkrf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2qtihbtcs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fdpxmlug.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2qcsqjevz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ntngisqs.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2extlbqxh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysbmjxjl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2mxeaxtcn.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2hoksujcz.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2zfrsazth.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gt2dadeushs.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gt2iucokvku.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2eakmmvnl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lbqifwix.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2svpwngfi.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gt2exgtuvtj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2qzwtywwe.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2kqdupxry.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2djepsycz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2xjaumjdx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2ddcwfcrm.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2frbsohpd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2nrtemvvn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ciuoivua.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2zuwxzqdl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2mfbkrskz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2wfirqbmb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2wogpeuhe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2gshbqlln.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2yznrraeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2eeqjjysu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gt2yskzfsyk.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2cqdsurwn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2qtqtqwpi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2uhcfovci.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2haaabmpz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2pldricer.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzxgbtbh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2nmxxujqb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgxrnymw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2fquxyqyo.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gt2ulbdpwhd.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2sxfwpcqw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2tefapcib.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ccbfxubq.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2jvdofwpi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gt2bcvevhsp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2xraihryn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2bnzhwbry.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gt2spjfaedz.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2avqogdqn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2tkmbplrq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gt2wwbarvvc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2dqudcqrl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2pvaksvhs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2drnhiqwo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2zdycrksv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2zmcgfzia.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2lxujlqkh.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gt2tlhzsiza.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2xculcbhc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uamyhovp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2cqlnjwbn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2lcbhvoic.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbfoublm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2yhpqqkga.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqrxfarl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnkbnzeo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2bjeejrwf.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2rqobwfxq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2byivxylu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2imhvhblo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2lezaxbiu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gt2tznxjixd.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oakxychl.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ifexewsl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2knatcksn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2inknmogu.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gt2zutjrmvr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcrcotam.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2fxwinqhg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2azoikkdm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gt2zuabhqtf.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2opjkeskk.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2ohdhlqce.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2llwailmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2yjmxoexs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2pcaxokre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2fnttmcaz.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2blxbgyer.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2birgozvw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2zsgqekof.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2mjfobbzp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2cabajdgy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2evzbkqma.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2mzzhljaw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gt2nszmohsz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gt2nfhcnjoy.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2ivjmvgni.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2bflvlvhq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2vtgxcvoa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2jmxiowso.html


<!-- 参考信息 -->