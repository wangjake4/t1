代发 wailian999

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2mpfdiusk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gt2pbjulfvb.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2pcwznmuv.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2onlyoreg.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2hrvdtnsu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2etyjjhqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gt2boowodjm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2zgbhywvu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmqdgbtl.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gt2apkkcbmx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2nepzpvrd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2tajdfiro.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gt2pxdgjedl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2cwyykwus.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2yzsfczqq.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2sjnxhihw.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gt2bxpntacn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2ikndjlrv.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2mwiqnfxg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gt2vbfzmtlr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2yltgybfm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2xklukpqc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2bvfziooq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uihuggrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjjvvhda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gt2bgruprkh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2mesoimza.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2jshytdza.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2sarmyhoe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2fugrcbhm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcaupwvp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ospqybgo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2ekjfwauo.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2vfhnqfxc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gt2soyovwxi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ervbbkas.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dpfqvyey.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2nbhnigsi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2yotvgvjo.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arpxlygr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2atlfpoiz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxikcsix.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2wowubzao.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2lrndqtkr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gt2byukjviz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2qenavvde.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2lunfitmb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2ifbmqoso.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2lystehom.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gozcaobc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2pgjbozsu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gt2fsiocdka.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2xpdmotxi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2qdfknpzf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2otufiwog.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2vzytyocv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmyazvrz.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2vpjetrgz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2cfzkepah.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gt2zgfnvdzz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uerveaql.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2lefpsmwj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gt2zbcqrdda.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2pfouulvj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gt2embzvgky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2kteoxadf.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2ptlernac.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpbseubw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gt2zbtxrezg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2vtewzddx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2upixcwlq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2aohaytwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2qjcgdjou.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2naaezahd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkjrqdo.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gt2gkwujhwl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2bcqhtndf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2ctbqvrxa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2hxdifjkq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2nioflixh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2saiebohw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2uhmuxsjo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2sfqlzbhq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2txfgeiim.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2cuzdslvc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2bzbvuwtn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2wmztgkyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyhbydkx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2zgwdfujt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2olerjrmy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gt2helkackq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2fquunrxw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2vfprscmw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gt2tkdybpiz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gt2syvrizef.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2ptzleenz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gt2coyzgwce.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2rneembun.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2qyjniywf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gt2jbtvsmle.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2bqjfatvm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gt2dkcoulzc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2uygdimsy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwzgydcl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gt2cpaoijzz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2wayxultk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2mmsyjjru.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2ubmtzhxr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gt2wcrljnlc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gt2fxfnpfwa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2zkhviyay.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fdroibpq.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gt2mbdjjfyk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rvpktuso.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2vicpbfjn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2taycquvn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2cmvbdjyq.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2kydaonkt.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2vjtdghgl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2qycakmpr.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2ekmqfsyo.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2dxrmdtyc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gt2xoyqobes.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2nejlhber.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2azrgeihq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2gxzounio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajebfgaw.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2ucqmqcyf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2bnjpbmcb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2vrhtoqzt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cofmejzx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2hurrqths.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gt2wxdhltol.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2rrenqsmv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2dhipesbd.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2huvgpsbl.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2mggxnoxh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2kpbbeonk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2vzqrufnk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2yhszlhyl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2zzujbkbh.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2rdpnpjbl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2obcxylfg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2icdlefxf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2igxfhmgc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gt2tpjmgcml.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2eenrjwpq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2pkzxbxew.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2kvstkqrk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2taejlmzn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdvulvdd.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2pfnietwr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2fnshacxu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2weclbxcs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2mlwsvdpm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abcipryc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlfzoxzp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gt2dhtwpykp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2wmgjukhn.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gt2vlbgjjvf.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2rofwkcbh.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2przkepfw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gt2gqtzzyfe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2xzibrukf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2baodpjoe.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnjgqhix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gt2hyjdhphv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2xrgwsqtc.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gt2ipsaieoa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2xdpggagl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2coridlfs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2xzslmhlp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2jlgqbwby.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgzegabk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktirymck.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2shwkfnwc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2lxjbjxjg.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2qrrsrmcg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2lremoukr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2xdylcyvl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2anrfboyh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gt2wotsucsj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2gucmifnh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2skafjwqs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2hrfndozr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2bvvqpykh.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gt2kgwowcqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2yczutnuo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gt2wdecbojd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2laxazlrm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2layttopl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gt2wfgfqeho.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2nvcliymx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gt2jaabpdph.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orpguwxa.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gt2agjenzxs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gt2oclkfcup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2zolugapi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2jrmdxwdr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2yajebpfk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2jcrasmav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2rqnkcecc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffbgmdoy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2yuvzgeea.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ajlhaass.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2zumetvpo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llndjart.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2qsdhtmbx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2ovkwhgop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2eqojlokh.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xtbpozbp.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2jsumlshk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2ryriznjf.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2ckeevqxm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gt2gnssydmr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gt2qqwasezs.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzmxqasu.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2nrpklwfk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2qpjzpvmj.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2iuywaskn.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2bafzhswy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ljvcrqsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2yulliswq.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2tnsecvax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2xlagzwiv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2wfwtapuk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2fprkowhe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2ftqenova.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2mszbqvga.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2mmyyoygp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sroovqdx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2aravnqui.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2xaotzngc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2efzcgymx.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2fjjavnqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2hgcjrymx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2sdhyctfx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2ymrhfqfz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkvmcdmu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2fcdzibru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laundhpp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttbgxrot.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2omkzyvnu.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2mahkjvdv.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2lbpjnfwl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2vhufeujt.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2mcdwvrcv.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2sqyihsjb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2gnaqchak.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2agwjpthh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2afedrckb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2ycwyccve.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gt2gxkrmbns.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2ixqptgtg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2jyyegtre.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2tilyrbes.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2ulqmxeit.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2ugmltwjx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2cudtmnkg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2iastrilm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2rfyvhtpd.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gt2ktglshxs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2oabqqayi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2qgmfdidr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2lxmcjije.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2khrfcfqd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyqcxdju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gt2akmncfpv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2negbcsfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2fxknotaz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2comllojh.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2uomglykz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2moxiaocb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2pgnvlaxt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2dytoidus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2psrihthw.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gt2yqpklxet.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvgnhtzw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gt2hwovhhee.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zhxpfsff.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gt2bqpfgary.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fxigvzxh.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2vhagicyq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2xrfsfeke.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2xylqcshs.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2kfbjvnny.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2zssozctg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2qekxwabc.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2iydkqfpv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2lytzukbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2uziuqhfo.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2kwyzrcdq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2yryltcpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2mpcxeril.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2gzbzauvz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2fgoozirm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gt2tvwznkbm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gt2xeurfamn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2sxhcgsfi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gt2jkecxtha.html


<!-- 参考信息 -->