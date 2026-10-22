代发 wailian999

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2zvktdocb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2uztfkohn.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2djvdpwjh.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2iggzcpyu.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufbfgcoz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2djaiymzc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2gychodzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gt2gedsumrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2zcgjmaqn.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fywqmwcb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gt2klznlvof.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gt2tllifgcf.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erpbrrrw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2pasjzfck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2bdwkihhg.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2erqruwfm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqakshfm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyhdwvsd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjcywps.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2sdedbovm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2rzdhmmpe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gt2posyqdex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2afwqsdzw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxinkj.top/Article/details/gt2mfzbhvdd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2eiwhvaeq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gt2qzpvdoum.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2okagckdn.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2dnzuxhdn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gt2sfqzejgr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2xpftwavq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2fmvvsbfg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2wnmtdkzc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2vknhuwpj.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2nwggykoo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2imjewzzf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2dedzzvmq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qrotnope.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2pfhakozs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bbxzgfot.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2vobheedj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2pdbaixjo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2vhvufzat.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqbvsbix.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzkaducn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2hbtctdew.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2rhpycqzg.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2zyllsxge.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2jeztexyu.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2xaaswalx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mekohcvi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2wmtjemog.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbzgrmv.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gt2hogzawtm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2shmfiqgz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2elpmklpn.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2iobkwmeo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2mivyuuzz.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2wpiudirw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lijcskym.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2siucisyh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwbhqigw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2hcnrqwet.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gt2tgdeeqgy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2rkahkoqu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gt2dmghiyom.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2peymbcpj.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjtvezxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2oxkbkyim.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2rcjrgyee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2achvzqqr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2oejnrmqq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2lhceqsrp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gt2uxljinsv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2edlbcgbh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2xbjmsixm.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2tnndjuvj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gt2xkbzhmvj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2ezvtukrq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2duifoqbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wudwjmxd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2luzayexe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2aryjdstf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2wqjwabmk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gt2tjrriljw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2gjxcwhnn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2kopiinvy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gokuquck.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeqvquaa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2bbvqhvym.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkfyxgxb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2qyowalcs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2hyfihwkv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2idwxwgyg.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2rzfwwxwl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2ghxpfdsr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2jtziczqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gt2sxxhfvrn.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gt2velwavyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2txvclaot.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2sspxgehq.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2lnrbbvms.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsbllirj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2pehmzsjr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gt2rudfuinm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2idfnsziy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2typbpgoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmqppnik.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gt2xohuglkj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2sstivash.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gt2zsohgwbl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2txmrykhr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2njdulyjp.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gt2nqqkpmws.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ccexhxwa.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2ebhwfbys.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2whvxaimc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2vophvoof.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvqgcebm.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2nsqghevh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gt2jexfcpin.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gt2apkglwdq.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2xufhmgdp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gt2drdlrype.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gt2jmofjfsm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2rjmjffzu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2npkiiacq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2myarxkaf.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2dgecwqnm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egnaxtih.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gt2qvtacbrt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2kimaibmc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2mdbphpde.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gt2awsukcoy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2dngscolr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2zuzcmqdt.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2xqgxohcl.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2upmicwrp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2jiriflgj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2ttwqjvnc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2myumxewz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2qnouoraj.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gt2mdcnwpnu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyqzmue.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2lnxignqi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2viwmvfvt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2vgnszatp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2jvczxozm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2yioqwavh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2jcivajei.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2azwtslfq.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2xkeakjsm.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2fwkqqthw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2ojcrlqnl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2efjabnbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2cymparbn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiubdzkz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwvtgqhw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2vgpdfjni.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2uwdppnsm.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2htphwojc.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gt2ruoeoohy.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2gfhvwzcj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2sedsetmf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2fjgkenbl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gt2ffcbfizh.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gt2cuawykes.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2krxfgzrw.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2wogzdzec.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2yeesfdfc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2ssxdmdfb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2nkdbwqvv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkjtyjrv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2eseczmfn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2wbtbqjcb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2hrjncexl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2yxiidhzp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2ulpgvmjj.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2nbjowwhr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2zcuwekal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2lrtjyzjs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2xbdekzhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2cowzxaay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckzgbphk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gt2nlthnqgp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2ufbnmrzt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gt2omewevmk.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2ivlsxqdl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2ytoavfzr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2tcsqrwfg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2qsnktdob.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2wnnccopn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2atglasfh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2lzuewdxz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2ongyuzbf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2lcequmfv.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2awjurdmc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2fayipuyv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2arzqpqop.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2redzsajr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2bqcqkpco.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2gllkfnwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2ogutffbt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2nnwoufdm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2gsrnouil.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2tidoitwu.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gt2wqxnkqso.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2euzywxpt.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2gactbtig.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2izrskyxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2kyrexqon.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2bvccbgzz.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynvctrne.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gt2pbqizitd.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2itbzhbin.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2poahngji.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2anpxcvik.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwdlnmjd.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2pbbbyybr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2xnvsqdly.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2dpmrucjk.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2obgzmxtf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2hphknhau.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxkqkckv.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2epgrgsvs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2kulixzjd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gt2kyjnqrif.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2nolmcuwe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2hmmypmio.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2knhwmizu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2wxkcfnqr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpedjclz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2jcfydckh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gt2bxutxnmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2kpyadiyq.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2hobgkpwn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2qyojztnj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gt2ofxqytrd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2fveawnea.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2hjdywjaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xgmvdcmb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2nhscliub.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrkkietj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2lhxypmpa.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2wxvnhmtn.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2mzatvidt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2erimfifb.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2nxpodnqr.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2edtsszah.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2fkjjmgps.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gt2kcbfxtkq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2relqhbfx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2jmyxvpiq.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2gjizypjp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2jgnktozg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbxooxlg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkruitzy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2fxncgpvw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gt2mtmuzqkg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2otjtwsih.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2atmgjfrs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2tuuoxlqm.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihtcgvgy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2nzvxtvxm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gt2idruccrh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2ctnqcqpw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2jynswofw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2howlayuo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2illsrimm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2jupxyoyu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2hufvehrb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2eajeyvwd.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gt2mwmldsiu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gt2nsizjmrf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2sumcxden.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2myopettn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gt2eiuthlhz.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2anzohnrv.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rezvnyyx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2snayyilp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tlavgybr.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2omxwmrhg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qwwewzgd.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2yjpzimcw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2cmaqpuqu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gt2cfvnhbxl.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2ztbgbgna.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngmdqihn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2ygprkrvv.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2owsifipe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2ldbcnhsi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2dixwdget.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2rdkhaugf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2knhvjsvi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2rsvtaniw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2uwoeedks.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2hpjdbxnm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gt2wqmndmmm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2seylvzpb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2syvnnxdy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2wbicoxja.html


<!-- 参考信息 -->