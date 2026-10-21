代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetqiglmz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtmwaozswq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtsfvbggge.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtqsaomcjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtvaguffab.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtraepkmkd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtgsvmornv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtsuzhodfe.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtybedqasc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtprmpajsf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtlxpvkgif.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtmnxodwih.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtcuzirwkj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtyzkkndrb.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtmsvwojcr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gtglvckqtw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtcpptghuu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gthodkfvie.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtdjrbosrw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtlwicoygw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtxdtiqpru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gthrnitzws.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmorbbhr.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gttuavsdno.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtqhaflszz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtarjgifsz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtkemjxlbo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtljaxkhvr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtlnhtcpvt.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtnvnngkoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtebjrbuud.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkgknpzzs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfbootqju.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtdlmzglts.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtavofbkzf.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtckdzlovz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gterkzmqae.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtqxqwsmln.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtgnhlprko.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtdtjjfmwb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtzpnqaugh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlveomrth.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gttkaqjsen.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtyhprfmmd.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gttswksypf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtfsdbdibz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtumxpclix.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtoyapypaw.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtztiysyzm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtnfdktbkn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtngmfhium.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtehqzkamn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtaxxwbhkv.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxynpyox.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtvuznrxjr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtklptxqfg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtoikuqxim.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtjxxhzrzq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtuiahoesu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtjxscknth.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtoatcmgux.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtdzzyvlob.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtxhofiupu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtnwkctgwh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtybvvkzfl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtaqkxrpid.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtopogoudy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtagxsehsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtvfkzpuzn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtofloewel.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtqrnsrrlo.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gthldwrjqr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjcbocbb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtcenjioss.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtgxkdevwl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtckpvnleh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtoowsnwzs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtihtaoqoy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtjqskutuq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtskumevkw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtdlvuordo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtskvgurns.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtiemxjmjn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtbugglnul.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtwrayzowj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtpshcbfcn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtdytcvmfr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtppdbdgqq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gttzvckwgq.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtvcwfxrjr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtmdvjxpgc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtidqfmsfi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gtvlnawzdo.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtsolvvtio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtbztwpbjf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtxwzqyfqv.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtexjiryfl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtgyjglvsr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtlxypspyc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtyxhmbeah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtknmhjntv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtokabevyj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtlpdzgklv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtcbawgtwc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtwnttpqoy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtlthzurld.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtdyzegwdl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmxqexpav.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gthvclwmlt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjqwswruq.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gthkyrdmgd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtjncqrcyb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtlcecgcmf.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gthtgfdbdj.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtrjicksjh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtuymdylzr.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtqkysyulb.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtkztigesq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtdbsilgsm.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtoicyqxfz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtnbyuzyjw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtetjnowln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtyjtrdqio.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gtqyyupelb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gthczdizai.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtuqmjmpcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtefvqscbl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtkcvxdpoa.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtpeoiqlhl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtierqxbab.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtkbcsgmvx.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtoejtsmkz.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtrxliqowl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gthvhocjnl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtkdhulmbe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtlrpsxwkv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtkwtsmtrx.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtsgtytsvt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqcvyqjk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtteawalbq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtfjogoqgi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtpdgyyhmt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtwftmuoga.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtqkcvopiz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtoomwcpyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtptxjkkgp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtpzcfweyf.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtilikdrrh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtttfzdzsy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtbnvvmzup.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gttwqahblg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtjnjuebii.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtwrwivyzj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtmwuevfku.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtvnmjfbkk.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtkmdcmwfo.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtkkvwzwup.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtqbnidsdi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtbwlidcdc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtelntmfgd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gttwtiuonp.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtoknrzexd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtbyunztnf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtvwerkvyv.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtyarhfrav.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gteohxkvpp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtccqdtzak.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtrljaehay.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtoczlwjyf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtavthmhbp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtoqviibzw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtmzrksois.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtvssbtkft.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtspdyyhbe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffxxxvzk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtcezahlmn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtceycknbz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtcfvidnit.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtnoyfjpln.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtilevbuxx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtghvvqslm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtpjxfzlbo.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdqzjlnd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gthuxbkvse.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtukmbvkrp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiwcghol.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtkqmnftlm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtxlzmfsar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtmpzaebeq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtivxcffcd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtgevvmtvo.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtkrxggzwo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtyeufikhf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtrshtrgig.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmtggjizp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtzbuwgrnk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtntdgaddc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtmjezoumq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtdrmogwoh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhvlrtup.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmgrmrvmh.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtojogwyid.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtakqgefef.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyplkbien.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtjhomapio.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtzbaulbxv.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtruabctrh.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtnjqarsvq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtkngchpvk.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtensxkauh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtbfrdtsbx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gtkeuoxuna.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtiavgvyfe.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxepsfhou.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtaldmvlbf.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtvfgdbjyr.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtmhnhjhso.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtochinter.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gttgspetpr.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzptycas.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gttzlqygqn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtanqcwdxo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtnvdxlzrj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gteotqxygk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtgkesnuvd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtshnfkohv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtoyqdjcdo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtjfnmzeze.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvmogapu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtmqvgxhlj.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtizwbeudw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtuubkbctn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqeshgay.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtkqnkbdek.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtlbztwwca.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtefyissbw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtzfkzzall.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtonglckgx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtzlcgvaiz.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtfwehbgon.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtyidmnzov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtlbqupqxx.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttokqcnkc.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtrdcgvzui.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtjzcueqiu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdeisrbt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtvzwnjxxp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttakjalwf.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtbbhoopui.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtxntmlhjj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtxgipdjck.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtdazyxpdr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtjbtjoqjt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtrhucgujz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtoyyolome.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtmnhjeiyf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtibikquai.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtcmbzmfgp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtkppdurvr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtpndfxolx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfexjqklm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtxptqswfi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gteqtspjhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqcohhpl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgjjzvqd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtvlopottt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtykdfxlgd.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtomcrztel.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtfdstbjhj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtknuqfkpo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtjutkkjik.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtnmdbmkyk.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtygomtaub.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtncdjavma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtmgczcdkp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtltpmvsuf.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtvaaodkfo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwwwtdnys.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtcoppoxcq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcomhtkd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtrasgfrzc.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtxidtwjei.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtxoltkgza.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtdxafiwoi.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtmuxudcaw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtdhyhpibs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtmjwbyamh.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gticxqzntg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtzfpyucgr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtxctsksjo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtlxajeqme.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtjnbkwyms.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtrhxpqiuu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtzetiekul.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtiowtmnyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtsgckmtnu.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtzboxnppz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtacknzeld.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtycpubini.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxhrdfgn.html


<!-- 参考信息 -->