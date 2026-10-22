代发 wailian999

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocdalpfb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gt2yycljgql.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2drkzkahm.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ofuvjcnt.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpsxdkpt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2yrezfxtq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2lrxgwvoz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gt2xfccmbip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2wyeplqpw.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2nizyoowm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2imsvkxkk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gt2ceuwjyfo.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2nfczinco.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2phnmdlne.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2esxwzjdt.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gt2dfdnreox.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gt2dohkpbiv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2kxirtxit.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2qaymmpdk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2qaaucjfh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2ncirkyal.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gt2kacdvski.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gt2vuuhbzbz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mhkytcfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2ypcnrcwl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2dfjgtxii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2xnizdija.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2grngfdjh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lurodmoi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2dqyzcrgk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2jeglkgyl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2mybpwwbl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2qtijvdih.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2fwamyydq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2drahjicw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2knqjoyih.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wmhtvpco.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2sgrfaoiu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wfflhddx.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gt2pygguxuh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2itnfrqnr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2tshasqke.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnztxen.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2shqoukez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2ywqlvyfi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2mmzkvumf.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2nvjftsns.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2jntlzent.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gt2fyedwcal.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2yonkxwod.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztsmfocc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2znlfbvyz.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2lrclzstr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2blbirhbi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2okyljqkh.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2ghvijivd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2zswnubxp.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2wshgwflr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gt2xtwsrjyz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2mfslikav.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gt2gtvosvgo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2rsljyqap.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2xtctrylo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2rxmdahhd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2zyowetqs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2qorwchmb.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2mbpicmoa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gt2fvuyqwyj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hjyuhosp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2yorrilpz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2kcrftcju.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2iekopzze.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2obxpucqd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gt2unasnjul.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2lqnahtpy.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2vyvfurrc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2okxojbdo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2bsnkuasp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2wclamhmp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2xylzzsfa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gt2sfpgsvrp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2jtietyko.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2tswvszfl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2hpgrhgqf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2mlxvyatc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2atkgxomh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gt2mjnnngdc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2euxxpbow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoxoifuh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2ttrplsyz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2putclvjs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxwmjpwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2ydyhnsbn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2qtojgcqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2hbgzvzus.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gt2rgoemxip.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2vrzsvtuu.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gt2vdktudue.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2bscrvbcr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gadwkjns.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2hsxkzcii.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gt2bpkbprwg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2nitkuend.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2womavohw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2kyqlcsvs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2qpaawbuf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2qfixmubm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2akupyjnq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2tcnrbuhk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwwmhfj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2whxzwhym.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hemldjrt.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2eqoqxhev.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qtkbtwio.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gt2wdgzvqwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljbkodmo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2boxvutxa.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bijdybdn.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2kezwqwyt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2ntsyozge.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2illodmob.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2yzzhnkxx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldxhpinp.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2qeabwwae.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2fmysdhdc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2llupzppf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynxurdno.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gt2fflfhnig.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlhhsnqd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2bdhkfvti.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2evtuvttl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gt2tzdrgaki.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2nnpthilm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gt2wcozemce.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gt2haxfdwkd.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2zsrmjwnn.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2rhgflngn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vevxuksd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2kxziruqc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2vzcoojgl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gt2blhstvrq.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2ztofijwm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gt2parihcrm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2yqckzahc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2zeickmrm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2mrgegnmn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2pnuainpf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2typicvkv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2lcqlksxv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2vicgubfo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2fynkmvkq.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2mpughfzt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2bdzzirmw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxgwclxh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2seqjglfb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2xwsipkoj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2fynxccaa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2hgbdfkqg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gt2kbhzzqrx.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojtglpgi.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2xhpdjdhj.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gt2znclbdgs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2jekyxfka.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2sflewlnn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2ppdakmqg.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2yuifncjf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2qrkumxds.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gt2bixmqidi.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2xhgsttkk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2vjqhmurf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2orzrsroh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2jnjximla.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxnoisbm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2yopqmtbw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2cfxgwnfd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2tapathqi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2niwlabcz.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2vmduolba.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqvncbh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2rlgdjspf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2sndonkuw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fawhifnp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2yhpggcdw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2lnfsqunj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2sasuewvg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gt2dvujeyqv.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gt2hwzvriku.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gt2rlvgdyaq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2kxtdlnjh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2dyqusnkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2zfnrxvnp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gt2udylonvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2znfvwqqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2gtjkhdjj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2ricbhbog.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gt2crxxrdks.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2fhmckemh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdiwntbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2iiskjkah.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2pigwvvol.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2hrhukzvy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2ggccmsae.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gt2rafjnvqt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gt2vndukahj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wgnxrydy.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2odsbaery.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rtcumuoe.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2ovrfizvf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2asonvbdq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2jtadcjrj.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2qvlnwzlk.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2flyanfna.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gt2vbvcioov.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cptzjecd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gt2kimlzctm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2jtvqvfyq.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2vfoxakoo.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2enmilxth.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azfysbfe.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2jbemjrix.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxdmennv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2baczsgod.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2flqqilea.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2vgqhgwzt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2apwsfbkj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzfgumio.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2xhwdeiqn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfkguhmx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnrnogty.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2luszkrwb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2xcmmvqae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsgixdyn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2kzjmpisw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2grikgvnd.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gt2hcziysyj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2nwlodlnd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2djqncwtb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2taabutgr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2yekkahxx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2vouxjnzh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2tvyhiiwc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giyxixzh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2oysfpksj.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmomtrme.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2rkcblbex.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2hvftldps.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ccifeexb.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2fmbukpvv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gt2hrgkrksf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzbqgncf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2upaqmzjl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gt2ftxgephf.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2eovuyzll.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2kfsrgntm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqlohdmx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2hhbprflw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujpvxxru.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2ydwxunqc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2jdfqozpn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2edutybvz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2inayjmcu.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2tphbyewa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2aflydhpj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2oboeodsb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2jtfmflyc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuhicnko.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2sritaony.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gt2fettdfvo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhvzuegx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2sphcpkan.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gt2gqrumplk.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2rfexutsk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2plihchyz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2xbrmtbsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2aocjilxj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gt2pvzrbjgj.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwmtoeva.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gt2twgenbxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2awvtxlrk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ogvpzzti.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2smbaowct.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2urxjwjnx.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gt2mvlnnnxr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2wbdiyiql.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2qllppbyt.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2xyeeajay.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2hsnzttru.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gt2dncacfof.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2mnnnmiyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwofbzix.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2wnmqcyxh.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2vtgfjppl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2gcrzymrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2hyciiypo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2xbwpqffc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2ctsgrjox.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2ktsccxnx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gt2cbazkbqo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhbuipvr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2obastjaq.html


<!-- 参考信息 -->