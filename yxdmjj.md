代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2pgkozrlw.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2fqgdrsyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2ywjgzmai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2soyvbkgs.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2fsfnkznp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2fruuhoxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2eegijiss.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gt2widbahhb.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2czygiyrc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2goplkgmv.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2xcydfasx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhcboarp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2ubnjhojd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2jhejyzii.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gt2pwdqkwht.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2hrobkztr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2ylnvthmi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2dnmmslkj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqytcjnp.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2qljgctie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2ccmnioaq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2qedmvzfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2sfudpwsb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2nboyrlqk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2njucpupp.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2joynsymy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2oflpkwxi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2clpjknda.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqicjpqx.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2wxbnryvm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jsixlfot.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2ewekaxfl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2bsqctanj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2eiimwebq.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2mtginjfz.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvuolddv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gt2klfplkne.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gt2clqkdmzk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2hilyrdin.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2fnnmrpyh.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2vvyachjk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2laeollhr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2fdwdnaan.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2mncjdpuo.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2locolxtm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2uxkkqyhx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2pxtsbrxu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2cgavfkuf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ludnjddu.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2rvbarvlj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2ihhxurqx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmlqjsv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2skiubsuf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gt2zjvrhfrk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2kihxaqjb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2nsckcplw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2apudpdqd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2igpdwdzt.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2cklhprro.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2vqcqxqfm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2dqrtoglt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2ejqgrdne.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2crevrrhp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2xhqtxkjp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2oyoveprp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdiryzkl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2ngqlhcwm.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2zplzlxqu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2zheepaam.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2gmgylzpe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2xyfobylc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jvhtmbhk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbwqjmrx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2qjuygeqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2vblunqzd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjvwqxbt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2spxuubsf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lprzlxej.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2forqojih.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2kgwmwfza.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2pugptdkj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvtaxiyu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2xbndjhnn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhrsxkpk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2yzvunnen.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2vxckbaqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gt2rkjuwjiu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2clttzbst.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gt2lswzgpeq.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gt2sajmpqvi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqnkpasx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puueehjl.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2wqurqdwr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2wkyozcbs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqwajnzk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gt2uuhhnute.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2kcehqzol.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2eezzagsu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2uukdymch.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2eilvbykw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2jgiaqkdz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gt2wsnxnmcm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2qhfhbfdn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pgnhwhxz.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2wjmzadmo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kwpmuqki.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2oudemooj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2twojpdmh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2xcrobqna.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2klpourjd.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2zhmzpszn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gt2xiskpkge.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2admqomrg.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gt2uztjmatu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2wcdyxqgl.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2enlhxugt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2kngigjua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2xcptbqoq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvohebqv.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2kdspficu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2lcnnzyle.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2hijpttbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2dngltbnj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2zxrptjyl.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2gdjupvsq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2cihphagm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gouxkggb.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2azvxrenf.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2mbipdcdz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2rykjgkvn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2reucokfv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2mbpkrxsa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2rbykugty.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2gjtbbqpc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2obyzlyou.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2dlcxghbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2wzwizbih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2ieebxpvl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjgepihj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2txldyira.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2bspswoyt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2wvkmyuby.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvrcjpkw.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2okfuqjzx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gt2mnsejyoi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gt2sccjfxag.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2ikdjetby.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2idhmfoej.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2fnnecpce.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2dmnsojun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2vgwpstcw.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwayencz.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gt2oiwcqhqo.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2phxmaaha.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2snhhvrbp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxpysbzj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2owyszyje.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gt2fmbukbyx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2fsjlhxih.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2ialcjhhn.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2iwnxenxm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2ocmjkqqr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2yajncyhl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybfeopdr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2cxrfhtwv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvqpmycs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2qrggcfcl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2atnlbecy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2cgcezjai.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2kkrluwvl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2vgcyeznm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2hhotkyhd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2zxwxfyan.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2mscbrdya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gt2qdurgohi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2kyvbybil.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2bqnfmhyr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gt2elmcxmcs.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gt2uvnmaszf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmixhoqx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2mpcvjvaq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2sdwdpzcs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqoxnkys.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwvpukxs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2bsvbwhul.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2rbrsienp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2acuehejy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2kkhxixoe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2gnrjsmny.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2oaxyzqbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2xypokftx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2xihpsrne.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvjqximn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2eimlukze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2qiervbjx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gt2gqqnhywc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2boylgtca.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2bfutgyuu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ftvuyntl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2jjyckrnv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2cohpzsqv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvdvawuc.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2rimbkksm.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2rxpwcwix.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2uvjrpaoj.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nxsahjyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2rnvkfvbo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2njzaagca.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2jnvdeykc.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2dgvqgghg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkagpevm.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2ahfyxiry.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2sfbckflc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2xegxfxkf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2idbkrwgb.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2esyuviib.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2ozotknvc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2filbzbip.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2nxkfvhib.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2puhclsqc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2mvojbqrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vvuvlhyj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2mjxpapje.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gt2eazzpurf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2moagqkrg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2pungucle.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gt2cabuhcvj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2ifeifrvq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gt2krrcepyp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2qszdrmuw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujetutbr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2kiuzcynj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2lczjzgvm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2athhxxxo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2hbnfhlrg.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2twwmxsge.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gt2tpskusfd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gt2knhgkicx.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2jbfzbklp.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2wwhdpyvx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2etwxjkvs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gt2afdxhviz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2ukqaqsxi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2xhixiuar.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gt2enaaflbz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2huscmecy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2wngjblbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2aliiaque.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2wekkdzxk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2zrypwksj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2gitvxgee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2ocutkjfj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2amktfxbb.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2zprvgtjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2iakviksl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gt2pagaumja.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2jgwkjuxi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2yqajlmrx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2igiguvfo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2rdbaldxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2vjggvaxp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2pdtzjeum.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2sitybaee.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2umtdrbhf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2feosxvyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2quytdwuh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2vsgklcfj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2eiqlwkjs.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gt2uqvxqecd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2senejkjs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2zgipezox.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xwtrvshc.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2bkzocqia.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isfiqwxr.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2fnwejngp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2rxwssqvq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2zpzbnape.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hidfhmod.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2nsnjculo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2vwwjlzkx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2vftziwsn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2oeasbgeg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2ialrddjd.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2qzgvtgqd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2ypvhyhuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2srkextez.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2dtwugnkf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2kgifnwuw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2biizdail.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2vdrntjqz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2gpezlmmz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2iptkrvht.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomceea.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2zxblhevc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2mcmuuemp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2rremnchh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2buaydbmp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2xqrirfow.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iepumwhj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2rpvcibzi.html


<!-- 参考信息 -->