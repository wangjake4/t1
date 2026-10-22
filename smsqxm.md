代发 wailian999

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2dvzqpjtu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2pwnsmmxd.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2iavorryx.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2qepijlvq.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdtqwmgd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gt2jpcsbucs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gt2wycsdpxu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2ozxfqoox.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2idclhbqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2wfirnzae.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2ponzxaby.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2plkbgeqg.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2xljprfog.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayjxgznf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sulwymqr.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gt2blhefpen.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2euipjknf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2gynxaqxn.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2bzjgpjei.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2nwalqssv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2qfmhdkiw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2jpbohljn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2lsmrokup.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymoqaqnp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2yllbkvza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gt2qvzvkpde.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gt2kywgwdoa.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlukoxna.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gt2gtnmomdt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2vtsloaln.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2arckhtck.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2kllmepka.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2dzhhralu.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrdrqwoc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgevvlii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2wpixyxpc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mnbpjzlv.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2rwbxrncu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yfpwdkxx.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2dwwmloxf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhljszsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzrldryf.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2hpqhjujn.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2egpgvmzl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gt2clcpmeca.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gt2ndswgbca.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2ovgwignf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2hvpqvvwb.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gt2ijbeqlgx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhztcjfw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxxrsacc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gt2bjkiwcav.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2ylcsqsqi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2kdswkobn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2sgqdktga.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2nzidytli.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gt2jnelvgfi.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gt2nlckpmbl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2qxfdyqaw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2dlhlhddy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dloftzwp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkkjbkpm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2ckxtluzg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2wksxiwjy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gt2elebfqdt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2rcpmchny.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2civtdgrn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khzcjqip.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2qcdjijtp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2nezifobl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjldnwtg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2xrkokldw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nopdtzoo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2txltpsfc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2mikimxxj.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2maszjpnb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2xbkpttfs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqtuwdpm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2tdazlsuj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2bmltucpg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gt2vonpcmil.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhsldaiz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2fleieron.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfvhijeu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2tzezdndk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxpcwtzq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2ibffkrsp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2gmyjksbw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2grpzklgl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2hdwjqxos.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjqxjvbm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gt2elfjzvzq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2obqkbcqg.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2mnvsieae.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gt2wgdnwlbu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2nuhrfzri.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2rpueyxqx.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2ysxchazm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2xhgrokmp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2rinhxybn.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2xjogmtoh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gt2zbqbdduz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnzhsdcq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gt2molvagme.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2ezoewxfp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2hipbxycs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2asspieiv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2pafgyygx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2pjpnfqrh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2xkfdetbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjpilmmn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jsxtshjd.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2ihmhorrq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ctqnkred.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2ntzlpcml.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gt2quazfiri.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2elsajxxo.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2fnogrxlj.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2grihpclr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gt2mqzporiv.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2kgivxzzg.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2tuoapyft.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gt2ibmsncpr.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2nhumabwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2ctukobay.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2unkrvzii.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsensbjl.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gt2pkrisnro.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2rbwckqcq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2wazrhbcd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxqopdqc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2avaurxso.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2cmkzhbuo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2odkslgpi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2rxmmbkqb.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2bqougwok.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2ybjuhqjx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2wgcopjfz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2xjxkfcxq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2lwobexro.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2mytrngxz.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2oetbxwjf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gt2iveorucg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2byzutgml.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2cbtudave.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2pzrvrwfe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2ijzbogff.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2iequxwmh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2rucxwwcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hydjsqbl.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gt2ccrdmkgt.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2solgzgjx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gt2ugorvsji.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2alfyjliu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2umkfhyci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlghlymu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2mnflreyj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2jfogffec.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2ewxahdtx.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gt2zcbiqgqv.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2nbkqnsjt.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2ifijojiy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gt2hlqdedhk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2ljkqzgyn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2rxzzsxsq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2qsjaxqlt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2uywmbglz.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2incelywg.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2zwdaoeac.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2djywxgzh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2tuajieim.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2rfwnsfbn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2cvmgscsg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jejnktob.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2mrxiyskl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2ednntdtk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2hpdwjchs.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2gvmdtqfu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gt2auiddjej.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2ynmnibkp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gt2wbhosvvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2rtiatjle.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gt2tzxrfpck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2iqchmogj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhqccsfp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2nzswnmqg.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gt2nzirrdmb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2hbejeoez.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2cvbdtkfv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2zhebkvtq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2tddcanvv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tupyhvdv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2ttycpphu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2vfekbekx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gt2qvfutfhp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gt2qrseosje.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gt2iausuuxs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2qbfujaeo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2hiyqsotx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fximabgt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gt2qspmigcc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gt2dentsqkq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogoxmvdg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2wfsylmmq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2himyykzm.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2ahqfmukj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nqrjrznh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2deawuzwp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzlumedg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2pjjvsour.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2dodnowre.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvnadfwp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhmayvh.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2mwmuilco.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnooqvmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2vmbjaecc.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2qkzclybb.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uwifwdew.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2pmavhwso.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2janpgtcy.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2putqrydt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2joilrnxb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2invcnwci.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2pukyhaxr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqfgxgxp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gt2wxlvgppj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stvxteql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2cqbwcuue.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2qjyasikv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2fhsdryrq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2swhkzolc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2evnivaeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2rymauwvl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gt2lphdecvl.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2bfauinxp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2gpijrsrw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lldpgzag.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2xrxidbow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2oukkovjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2bzohauyo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2sbuhtoph.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2aizaremm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvugvpl.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2hybdfpwc.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ihqwpzwr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gt2jlyfycjb.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2bhovipnb.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2zlxqlmbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2sydefxja.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2tbamqsly.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2vvjigtjp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvbomeey.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2danspkiv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2enzeqfcf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrxcvfif.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2mkwkjphc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2bxtlscdp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2iejsyafn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2castxiol.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2duqmkhxt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2lrsbvocz.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gt2hrbtenuk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2rebcsluf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2frsqttza.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2hednildl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2prvywzfs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2mndfghcj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2rtllwkdi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gt2jztktoqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2epftpohc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gt2lpnalehc.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2fbbnuxvg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ustwybrt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2kuefymdx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2aykwlpra.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knskznxr.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2emzpglnm.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2arwrkfsw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzritpky.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hzjoyiug.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2xmpsilgz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2iymlgojj.html

[L01] 发送 GET 请求
来源：http://dali.dashuyun.cn/Article/details/gt2ykqqdrtk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2islotwsk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2ixqheepv.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2nrsctaau.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2ihbvkzrz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2epubtwea.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2goiftaih.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2fkqvzjns.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2nnmtahbf.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2gtzgskay.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2buklteul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2rmjushhk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2stykecgq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2vrxfecwz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2tetzdxnu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2vhpefhpk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2ltpixvtg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2dtpxndqr.html


<!-- 参考信息 -->