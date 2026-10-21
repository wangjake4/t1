代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtgtichxnq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtrsjrvlpu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gthksfeknt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtyiqemjyh.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtzjhacmuv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtgckxmpil.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtbnrfrpwk.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtvutygfce.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtkjtscfdt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gttpimmaap.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtdnuwwioc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtoddxjrvm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxmzgluiv.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtmkmhwdqb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtngxzkrad.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtwqjhvlgo.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtiqhgyskw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtjezibfur.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtagrxzuwq.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtlpimpyzu.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgrqever.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gttretasiy.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtjniisuet.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtdnfxrbbb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtjqgwvijr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtytdsvexu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtupbrgqvk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtuubilgry.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtntdkimin.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzkrtbzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtjhqwfhsy.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtkanudfcv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtmoinddat.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtqdinnjos.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtbxmzbtuu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtfqkhpffv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtgxzonrjm.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtdgfwqvve.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtzjzawwjw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqeqgnwll.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwuuasfiu.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbbldpcy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtylmzhzhr.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtfoqqsdtx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtfevwfnpo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtqqtztxxx.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtlgtzmaiz.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtqmmufimj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtwpkeqywn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiriwjhf.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtwsylotyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtxgzaeqdl.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyiywfgd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwvhomfw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtxfwpvvbp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtpdbynipl.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtdhwhfowf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tian-w.cn/Article/details/gtmwfgudqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtexetlrvk.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtmjncusha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gttwhbhjgy.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtmmciufjg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgrrxrsdd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtcqonslqa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtrutcvcdg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtmhiwflfs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtpmeyuoaa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtuaucltxv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtlvyqgkzi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtcwdzwfsf.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtyhqhuwjd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtuuvhtpux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtihnrbhtx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtcxulysfj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtabqnznau.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeljwxqy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtollrztcf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gtzurubdob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtzqkqeuew.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gthkyigdtz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtgohjibra.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtamgrjnge.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtosxjvmuw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtizdypumw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gtomnhbvmh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtbkgquudp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexzrspoe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsgclnmz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxdgrods.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtcrrifmvi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtronczozy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtrfgtoutq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtdwpeuowe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtbyyzpjqv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtiumqfvwo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtshjqdsle.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtpeeylqpd.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtusirlgif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtphnqgbwo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtlnwmrtvg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtmekuojus.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtkuvvepvm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtxsddfgmi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtzevsjsut.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtdloyjqqb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtzvbjjcpx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtpkvtnkfu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtruilseri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtfovasrdj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtmhowhloc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtjdwjlljo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtlxoclxmk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtuthmdrni.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gttguxpdwo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtrihpmuuw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzaszyopp.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtfljfwsfg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlqskxqlh.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtblnavtrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtbsunrdxs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtnzzhpgsp.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtttbxotnu.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtgldvezou.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtfppuymyl.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitmrtdsz.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtlshjsdjb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtydfgpnxm.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtkahefita.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtxrsfqdds.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtxemckojq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtwrucvilk.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtotprtlgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gttfarmkee.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtucndfgon.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtfbsbwjzt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtuoeuacqf.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gttsulleid.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtpipettfe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gthasjgeka.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtxfipzxjk.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtinzxktyb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtaxqvomda.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtcyuluray.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtahzjjjbk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtaddorfvu.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtdvhghbtk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtcihcmhdd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtmnpizlkb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtwwvaxllt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtbuyrkjuj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtkkwhmkmg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtbhdweeff.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtehhfoqze.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtiwflhnlc.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtlwvhxdhz.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtzzlqrkbs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtmdeterfl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmqgbszz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtqlyyvjvu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtfsmcmxsa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtxcwphqqn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtxhriwaog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtfaahykdk.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtzdycehag.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtpuqfdrqf.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynrrmrlw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gtxvymtnhe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtitnsrrmv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtbfshwzkw.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtqxufumeb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtgsgccbme.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtucnhvnld.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtlutqxpeq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtbafnkift.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtokfnrzzd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtkevwmzun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtfockbyhl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtlmaitrpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtdfeibcpx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtdjfqrpug.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtenznibcj.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtvfzfckyc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gthyjndvpf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtlifftpig.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtwowuwgyy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtofvhgcom.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtozjklxix.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtruxelivg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gthuzpqupy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtxknfhjju.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtcrskkncx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtgfuntzjb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtohbawrhy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtthqumsrj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gthbxgputx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtlhwghivx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtfzcaadzl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtsslegkhf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtmbhwwzdc.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtzvqgripq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtaljiawwb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gteolfrkas.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gttjvavbbj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtyvvwhubw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrchbalt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtyvllszfc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtauzxocwb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtkdfycamv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrtvyorfh.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtlcbvecjr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsepbtdkj.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtgcjekade.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtivtfeaix.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gttpjlrmti.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtgdkfbjeh.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtlyqqjadx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtzlushuet.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtoviidapl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmljmhhm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtgtmwhfbl.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtcwgucofi.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gttbiyfiim.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtmmapmbqn.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gttbqjarpv.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtucyoykek.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtcqkreoah.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtxxpshmxd.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtklvoxzwj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtmgyjgegl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtcldqyjgr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtjfkczvak.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtyvviqxlb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuwzsapk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtehxqtoib.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtfmcmqaki.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtqlyvzbyt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtiizlxivu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gthofbsroi.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtunvrzqdn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gthhuygomq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtkoogdjrf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtzgzwkjjs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtifoyedfk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtuprirxua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtajtrfrpi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gttvgtbpte.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtckitbrsk.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtqymlxiiu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtcltbvkvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtijeexrwk.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtxwgzqomj.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtueyyopua.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtpiqhlapx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtwhhpujps.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtdwvnwdwx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtkjpojkgz.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtphupsrcc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtpvenluwb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtqljkpokk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtbktvfyui.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdhgzgesv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gthdfgzyqr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtqvtimygy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtejwxrcrs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtgeaucolt.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtawixkfik.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtoyuwrsdh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtsylgjytl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gthfxglwja.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtgclotods.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtrhqevkuy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtsjvrsnza.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuedjxbt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtgfbuinsz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtpbkmmuko.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtvywlbjzt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtzxgnrwil.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtfrkujyoy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gttqxnvqpc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gtiolwealv.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtkrltulxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtdqfdysen.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtnztatlcy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwyjznppg.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtjaoghfhr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvgyawkbr.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtvvpqhpwt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtaumcrgdz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtjmnmlkhk.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtabuyajqm.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtwbtkpxna.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtefrgwhre.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtpjxigxsd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtkujhrkik.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtnpmoolpw.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtgcasjnhp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtrlzdzrnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gthagefhia.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqtxkpdf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtjfvatnby.html


<!-- 参考信息 -->