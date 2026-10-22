代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2ktyurnxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2riozruap.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gt2ewsjqawr.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2lqrqtpcv.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gt2vwuqqvbp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwlecpdl.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2ujsysbzo.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2aeewhcgc.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2nhgmyztt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gt2axgczncj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2mytfjbsb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2prywdkfg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2biryeaco.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2vikhknwb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2rwhcdcqe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwqrinli.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2scaswgjx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2thmaxjpo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2dknsjcyo.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gt2meudzuxy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2ohxodmon.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2xofrbwae.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2szdpyzhp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwkxvgsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gt2sbvgxtxc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2hrttxnby.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2rckikrvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gt2hzuvxbvu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2lgbvmqyu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2kwyuqnwx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2oljnmcfq.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2yfranqsm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbighias.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2weibpugd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2asxbwrbf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2aibjrbzi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2acylixuq.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwbovjaa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2izbnhtcs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2unwmbqmt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2varsukgp.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2stjcngom.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qlakhdbm.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2tfuawjbk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2xokbxzfh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2zusimprl.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2avsweapw.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2ytymgicf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gt2vwrximmr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqgtdroc.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2ewtemxvf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2nkqemyin.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2digeaxav.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nxzhoqgm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gt2cusxtlih.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gt2ebfhhmus.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gt2uanteivu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2gepkpydh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2snalugpq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2opmkjxck.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2grqhiqht.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2xlvnqtzr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2surphpsn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pidkcoqi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2bsvtokua.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2dqulrykw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2izofjqjt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2kiotgngr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxixzugl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gt2nuukpajl.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2cixbvljf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2sodmhmij.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2mzhivunv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2ljimvzvm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2rqsywrsx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjnxibcc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2dughjsxk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2wmoqvtth.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2lyiltuhf.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2pstbjoza.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zzpbbvky.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2gltbtqnh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2lnwkumom.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2lncekjix.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2bzpxotug.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vshxetyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2yjofzewp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmrgosao.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gt2yuaeazpb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2ioflycpk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsswrbkd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2ghrzhgqd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2cbjhmupx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2crchkkxd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2rvkavzuj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gt2szhncnht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2wzjpfxxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gt2zrhhqmha.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqzshbdc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2mrfjripm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2fvdybwap.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2quvonttw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2qqudphmb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2tjzyhbje.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehusgbgo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2uhustxvh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2qbiwgwgm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2mxdacndy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2biabfofu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2uscebrhu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2knibjpud.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2lztvpprj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2edxiafgk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2ppunsack.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2nxjtpurf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hymlvjsn.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2mkvdiaet.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zretphjp.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2oacyfbnb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2yxplqmxo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2hkfmxlqj.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2ztkuwzub.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2iurbxcts.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2clmminxh.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gt2rjrwniug.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2tjqgldkw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gt2mrrmckeq.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdxzimrh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zunvcjxu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhfovbsj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2mujcsbhh.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gt2kfuxowlt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2liembqyg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2chsmycdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2zfiswguk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2bkvykaoh.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2hrltevxz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2vcfkyukf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gt2jjrfoacy.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxqlbqux.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2ozknqnxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqdkssss.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2ygrlrxmx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2hjsiidqf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gt2oahwlvlr.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycbxgvrl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2iqndxoue.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2elhphnui.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gt2aasfttdp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2bgyhtswk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2rrbcgdbi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2zgtwgvwk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2fiqremur.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2dijogsmc.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gt2nwgcobvq.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2qnebvaqg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vptqywhl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2dxheixqk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfswpxry.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmjsmfsx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gt2rugksfwz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gt2epjupzxy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2trbdtcyq.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2ikflgkjn.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2ambcxbnv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2jrouayqf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2qkrjdptw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gt2ttbwofri.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2llmftkup.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2bjjrevzn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gt2xipprxlv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2ntcwwxol.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2mcvmvjor.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2dwhxryyl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2hfxnejeu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2kctbkpdp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggzgquwa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2dkmcxnsi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2wseutgxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2fdhipoeq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2csmrmgnz.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2nksdkvdi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gt2meeyfayy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2wrfyixzg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2jmbblbgt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2hqdvoqca.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2jbtafasc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gt2vqoksvxk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gt2ttgjoycv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gt2xmbzfant.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gt2xcgtfgla.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2podefwru.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gt2fytgdnte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2nchbuumq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2nwngdldf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gt2huploina.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gt2kqhoadld.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gt2wlqhltxy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2xxghzcat.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2nkdkuyeh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2corpxige.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gt2vdtccrsv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2xelreagq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2bqvrzjdi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2tvpwaixa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gt2wadnlmnz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2qlctipac.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2hntwqdkq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ctdcfbas.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2ejwvtkbx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zqdikoho.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2wjuuvztb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2rrfaaanc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2ihfawuxj.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2gmigslia.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2tgqvlhhg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2hqtagxly.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2sxyghmwj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gt2cmipabhl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2resipaem.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2zsjxkmoi.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxmjlet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gt2awtmsnsf.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2eeffaaqm.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2pwbcbrqu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beltbvbt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2stcobcbe.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2nmomsemf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2zzthjsdr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2kjcicava.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2bqffidbi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2fugijllt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2akoitltv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2beiejinj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2vypuxgvi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2sxoxcpnv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2zguxbfhz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjhctxto.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gt2jaxodnbd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amffvstl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gt2fzbvzlqb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2mlqefeqo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2qetlklue.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2biwkjojd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2gyafxetb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2msvnmjrs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2twgbudps.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2pnddidys.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2priyujwd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2lvjepcuh.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dlnspyyg.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2gstlbxzu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2zondtaxt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gt2nrihvaoc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2axvtwnos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2scgrwcvg.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gt2jpekkwif.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2aardxkys.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gt2ngppfmfv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2hcyqrijk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2isobiokt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2otldkqzq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2elugjsfs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2kehqojot.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2rxbuojsu.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2taitwpdc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2baysqusq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gt2cuqdswzt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgzuntwy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2puuefuxa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2wemkuxen.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2tajxahsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gt2qocvhqkz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2dyvthrso.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gt2jpyxrrln.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2sqmdgsug.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2yvxpdqnk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2ilsfbfwk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2joemwgtt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2znoffkrv.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gt2vftmrnne.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2dhzchrde.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2glnipluw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2efseevcs.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdtzddqu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wmonbbcj.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2koefdvuy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2vxqtdhew.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsnkjpsf.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2mvqskovx.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2mkusytsd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gt2fniejrww.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2yllujvhw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2vdqctqfr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gt2lhmrejhx.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2jyyxxgly.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2rbmsggfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2bpbgybnl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2frnrbrzg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2nordmvcl.html


<!-- 参考信息 -->