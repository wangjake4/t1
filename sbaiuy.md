代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtoomigllk.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtuyibsohk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtfaretukj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtgaepramh.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtgmmiypcv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gtbdanqpvh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtadigehxo.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtweprxqnf.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtaszgnxgn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtmvqbwkhx.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtqoysevpa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtpjazuzxb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtklprxphm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtliaaprfe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtfwsrdnny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtqdxmtwmq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtqgpdgfkn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtoivebfos.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtperdgzwk.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtqqsrzoii.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtlhuycacl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahqmlrxb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtbqxwspsn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtivvpsvia.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtygguowdo.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtknybrxtm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtcyuonxrc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtdkfsnaks.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrbexxcrj.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtngsrjfft.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtknoclwsu.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtkvwkffny.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtswtofdsu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtyxemceia.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtpkmqejrb.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtndqnenrr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtgxdystmd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtofpcxcof.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtlqculelx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtllnbvxag.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtwzwginfz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtgsfubwdh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtboeovjxv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtxtodbvpt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtrugusbvl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfakpevnt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtjdwwhadk.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtmssquvcu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtppwjjshh.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtlhltbrav.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtrqpejtvy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtaeorzpgy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtynivsmad.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtjirfthsu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gtmeibzmbm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtytlqbxic.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtxfxxugcd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtpwackwpf.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtjgsofjaa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcwxdfkh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtcfamjzbw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtpbkkpfbj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gttnnrznji.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtsuwyuugp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtwkvauook.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtapzrblhm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtvefzlogf.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtcblkgsga.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtrxevanvs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtblbboccn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtkkdnupgh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtxyzsyxsa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtxmixopwc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtlfrvieuv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtleeispfq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gttryaevgl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdadbhmxu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtzxxqorfp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtazsvrsaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtkmstyhqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtjvysrlaa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtaforrdfx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtwzqbmcve.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtmitkdnsq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtslxtbudc.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gtinvsgltm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtgujwuwqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtyfenohia.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtbetxjzth.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtcdjeyuur.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtjrpyyivj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtbdiotepd.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtwfoptfko.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtpwrgmopi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gtyajblobd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtwkhbqtxz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtrxbltflv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmdsjgsq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtdnxnjjcq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtcijhiwgv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtwmgfubyl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtzkkhwuax.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtsbjbcqfi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpgtgbxdc.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtdycyulxv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtekxeawuh.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtsswfmoao.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtgtrfnxof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtzuxvzyez.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtowbfqfyv.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtwamnezct.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtrzsfzacu.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtwngerjdy.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtmcmabtdz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtwseeluav.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtgdhgcvxj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtcwsionqn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtogjyodgi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtyljpvyun.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtrojdfylb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtrrwltbre.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtawjxslzd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtfzkpsvcz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtqyccvnzz.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtniyvqtjn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtpotwneuy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtvzhdowut.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtryvfsdyx.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtqdqysaqs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtkocdineb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtjgwowuqr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtsuitnbee.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtpzdqaall.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtwlqaghvg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtpnkbfjwj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtferlgssa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtfjiyhnyl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtnxkdyfqt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtodphhznd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtkomvcbzk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtaebqksxw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtpqotgpuw.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtgyfvpymi.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtxgwskwne.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtefhaslvn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtilqtmsac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtyjrbtigi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtrlwngrvs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtseckmxtm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtpubvmgtz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtldsljnez.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtuazzkagv.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtvcnuqqfv.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtefqmdeag.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtiyxrpdgk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gthyewvayd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtlvfhlcln.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtdzldylih.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtejezwypz.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtqcqjgdgd.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtzxmlecnj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtwleqkbma.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtjeoxxvne.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtppqajvhe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtonwaajut.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtomcjhqpy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtoiisfath.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtefgdausu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtloiqdcub.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtklurpyvs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtvxxcepal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gtmtpghvru.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtadfnpexc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtbutcvwxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtdlbpkyho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtxgwtbevf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtbljhlduz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtuluiecpi.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtuedsyjrc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gtcwamfywu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtrbaqvevn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtktkqlltg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtykfpzqkg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtiugbcoej.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtrvymcqmx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtmhvvpoeg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtuidysahh.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtrwenyzld.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtevmubseo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gthqhurgut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gttjhxjkba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtsudiekxk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtlhknvqjh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubybigco.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbebqqku.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gttgjtdziq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttmkjbzuq.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtkonuewkb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtltnikrze.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gthswycnhh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtyrkgihpf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtutzcqrym.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtdqzhjhra.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtihjucdhf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtgqzjjrtr.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkpoorzpd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgpckktc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtjijxxcka.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtcrvcnmnc.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtrmchqepb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvhvlsnh.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtrmvlmlum.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtehihjkfr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtaftsshzk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbohmhusu.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtjbmaizuk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsauvwfcy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtbtvtctfm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoalgbcnv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtpbqrcqay.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtogoyqlfw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtblcsuopm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtuesguemh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtbecxidkb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtfmqatjtg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gthmsookxr.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtzhddtteh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtekonubbq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtkiyytvxs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrtjiayvj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtorgluchj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnqwvbmb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtoirhgvkp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtndcjpedz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtqdrsbdrh.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gttpgithhy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcvteuvwe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gthmvmiawt.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtlblsdeiz.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmmeervms.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtxpcdmfrq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtdbeqztcf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtzohgnhdr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtrwmfnwik.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtrhgmkomr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtdlqnpzbt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtmdkncxru.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwibdlslp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtqapykcug.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtcppuzauo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtrzhuhiyx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtcwvssndf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtehvckljo.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtwtpsafsq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtfmauhkqq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtitvevjtf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtinonhdxh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtjoqrtlrb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtcxkuykow.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtxrshxfyx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtcxvjxkjb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtfqtxzfrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtuwuilppt.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjplndheu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtsddcbbgw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtjrkzzbeu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtuklrdpcd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtmklhbdge.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtzknhqafl.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdjrlwvy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtbrtkbtgg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzzckhqah.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtgcughzea.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrbooqaaj.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gthcihhasg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtuxiehzlj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtzlfrbwtt.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtttwgwzkz.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbbieswi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmdcrbcl.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtehibintv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtdmsriqzv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtbzjlxxjq.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtebgngatk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtahnnqjbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtshfrfnyb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtjkimkbea.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtumalgceo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgmasytn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtojcqphsk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtmbgbyimi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtcunwihom.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtpefknoni.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtqemaheru.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtgejscqff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtremqxlke.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfncwwrvy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtypdsnuxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtmdalauot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtzhibyteu.html


<!-- 参考信息 -->