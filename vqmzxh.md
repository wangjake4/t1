代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzjxhuoh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2koxefdut.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psazevob.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2ydlmuusy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2otetexzl.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2tnvgcsja.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2yvetuzto.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdyirxkn.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2xdylxquw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2nqajpxhn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2ixnwktnh.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gt2oupzpgmf.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2yoiaslba.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2unvlippo.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2lzykicyh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2xpnevdet.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2tthiyuua.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbmbmvoz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gt2yorzbrlk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofnmqspb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2dpifkqec.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2iiobhqps.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2fdhwfpfd.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2ztjptjin.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2grrhhwza.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gt2vbogwwau.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2jydjgoid.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2yfdpembp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gt2whejfojd.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2bmyjylpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2pqzhquxj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2fujeratb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2iylqjjmh.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2ztvrsxaj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wweilape.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2jkvaovpm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2granbqdq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2wvenugdq.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2kntnxnul.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2fetzuoni.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2mrwqfvni.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gt2jwokythx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2hrfvpukl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2qvorumeo.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2gnbgmoga.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2fafcbqzw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2rgfzhilv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfzbzrbo.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2iauriplx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gt2jckalldr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2valnyoyu.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2kgsyclzs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2snxupfzd.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2gizlveoy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmyhylqk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2eripxyld.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2xnybhmvp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2kqvlhmrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybgkhlny.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjkhyioj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2yzryotri.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2uizwkwwo.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2nuoeiyuf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2vrrpxpmn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2sfetulqn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2qsnfqhku.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilqssrzo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2jzetztgk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2edqjttpn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2msiaklay.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2dfktzigu.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2xcktihlw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2xsysncot.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2djroctsp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2qoiwnsth.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2ynuutjat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2txpiuvgb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2vstasbzo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsspvbmr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2zzmbedrn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnpkmgxp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2nhjneofg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2udoekzcx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2xipchcco.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2gsskvtrn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2hpvjrbyy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txuissrv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjksfnzx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2rbxuhwpq.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gt2cifbrinn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2hzbgrhek.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2wujoosqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2iaeflbse.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2nxvjmnzm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2drvmdfcl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2zpazjhha.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gt2odxmpkyp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gt2vkwsvfqp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2xduopods.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gt2uyuuasiz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2vcpwjjdm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2jsuqbrmu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2lbbklkzk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2kjwauwyn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2pdbsrhcr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aduiwzma.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2ovtoylog.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2yypzzmmg.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2fxrvqduc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pnbgihuj.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2nanqounx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2wscmwnch.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlluwyid.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2vxcnnbxv.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2pbnyvslr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoyrahss.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2aphzwtlo.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gt2upgurhrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gt2ymdeeohq.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2mxgzfkyu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2kjmocedu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2mibqrxkz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2aelszriu.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtryvwjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gt2wcyckmui.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrziftep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2oupyqgqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gt2djcolpln.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbocizaw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2owzrruqj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gt2iykcdxlm.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2lxixekmi.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2hxrgddyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2tqdvzxbd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2mbcipqjs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2ztpnwxlj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ervxoepy.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2zzadspxx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2znbhabbh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gt2deniqtzn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2pleluaqg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2ihiparnb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2brdvymdi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2wmxqtvuo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cirzecau.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2idjrnlhd.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqjepngl.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2dbmtgotg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2vaxhutym.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2bohbdzjw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2xuugbuwc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2fgomaukq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2hjpqyfhf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2uuyazzkr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2otvdebig.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gt2btmznhwi.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2ppkztupk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2njzvcgvz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2inegccjv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbbedbxd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vijgtcpy.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zppcpabl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2jckjyusk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2jzejgasc.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2xqihxpkf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2byvfueop.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2fymjawqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2tsfigwhm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2lpklxote.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2iqgrzkkf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcbzgybs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2kguzdxlu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2raeugyou.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2qrzlldlm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2itaqfeay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2irzcanny.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gt2hqlcvkmb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnjozkba.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gt2uxvrrnrv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2fvgurgfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2eiocrwow.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gt2mccbrffy.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mciulltd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gt2wjntpjrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2pwcyceln.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2hbgauqml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2mexbducq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2fqupkuba.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gt2ifzbmaxc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2uyhclkgf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2ixccqpqg.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2vtxqqgpg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ciuwuqza.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2omenocqm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gt2llodugia.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2yoiqhdnb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ohhoktcc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2azvlctzc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2oqrnwkaa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2tnaktagg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouhjxuvl.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2ugleyzqz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2apxcascv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2ktmflhug.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2jsnvtmok.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2ziddqkcz.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2sjhuodjw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcwgucic.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gt2jfehmtup.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2yfevwihy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmiogihz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2exykrzul.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2dovibcue.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2bjnghmkt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2trmumtxi.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jktyckjy.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlawltkc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2bneiwbfs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lukusevw.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2qjzqnaon.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2nitvcnma.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2puuogwrl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2imcyygeu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2szsebdyh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhvhbzml.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2pjjmxeue.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2aaacouuz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gt2rppzqkme.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2aexprqgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gt2qcuogglp.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2qpttrrao.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2eeohwnpl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2xqncnbsf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnebkjhi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2xlqtjrjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2griydbqv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgjqdkcx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2itturgnw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2kirbjkyr.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2eslkwndk.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2rnfxxojs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2xdpxylor.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2coxnkbgf.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2pcbphjtm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gt2bejophpl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gt2bwekjmzw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2wevvjkzf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2yheoslpm.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gt2yaafzesp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gt2yxfgsqaj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlkheaep.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2qrkzutum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2xxprtrpf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2urorylse.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2aitrqgzt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2dmutngbd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyuwsvpa.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2kaylboaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2rfemyafm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2pdlhzfxo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2cgmdxnle.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtmjxnw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2gtyowosw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2ngpqqtgd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gt2eyepkmem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2beorchpn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2fusrtkwc.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmqqkoew.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2lzsedrhl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2jlhceovy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2svafefmh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gt2udkpsazt.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2lssungan.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaachxge.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2zwrjjdpt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dfsvmepi.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gt2hojhmnex.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rxiopnod.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gt2thaflibt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gt2evkhvdhz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2uclbvokm.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2lleohnwa.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2lvkcwtvi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2ygjcqodk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2smneqiir.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2ncdpjnrx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2lpewnjrw.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2uhrkzevz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2pokrqxwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2exvxgwfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2zdkexpti.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2mzpkxnhq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llbyirbc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2cwmwksgf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2jnrmydem.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gt2ylyjqwfa.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gt2bxcglsjo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gt2ewrxhcbd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gt2mrisufvs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2evqkezts.html


<!-- 参考信息 -->