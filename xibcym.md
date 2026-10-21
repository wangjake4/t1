代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtporvqlii.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtwjevikaa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtaowkpwcl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtqmbchfuf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtvoqvucjw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtzgvrtsbf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtiozeenoh.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtanvnpiqd.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtljjhjmmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtaqnbtjnp.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gttovsliml.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtubvtmvod.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtqepcergh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtlvbqdlgy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtwtvwbocb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtyjhdfqcv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtpfilrutx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtlwxwkgax.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtobovmnwy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgtmhldt.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtbaovrduw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtojkkvyxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsejizzk.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtlruoewox.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxyxhxqj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtcowciund.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtphrpdeil.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtpcdfcwre.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gthaanyklw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtbpvbfenf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtktrifecp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtlrhtzgxj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtobzzyzsp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtnklwwcyk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtwuddayzu.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtdmpedlqc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtxtahdqti.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtssmctils.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gthtyifdea.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtphmkzjdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtizbuziki.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlhmfmsm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gttdmtgrkw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtlorcpzng.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrvvfstdk.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtkkerropd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvvkydtpy.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtgltirgrk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtqsmagdod.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkfyhksr.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtwxfnglmt.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtrhidsakl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtdjwnhaea.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtyorzycbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtijenpfpd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtmdjdraqf.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtlejpcoxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtrgkkcyyp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gthbznrxrc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtezkgsgoc.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtdhosgqjq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtoqayjids.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtwmywtcwk.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtxiayliqq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gthqqmseyd.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtdhwkpjtr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtcbpknnbn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtwhhihrex.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtkfnhsqdk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtckadnccb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtzqhboirm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtahfvdyse.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtjqfvypsv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtmlgvijpp.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gthofuxyqh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gtgmorygpv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtpjeykhtx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtnpqrmtjh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtbrfmmegp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtzeuprzhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtqucyljlk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtkdxrkxfl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtfpgwzobv.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtttkrfqwu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtycgihbcx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpszwwyot.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtugjqllcj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtrhxvgtpo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtnfxtpozi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtpvcmusty.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrypjjdxx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gtaziuijwv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtszgvywro.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtrjawgaad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtsmgvmnpd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtzbbwicca.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtauvqjnpn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtvzwquluk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtbcbydxos.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtmebxjpok.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtbiiftokb.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtograwahp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtehjylrvl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtsbtcgvuf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtksebdfsw.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtsezbcdat.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtumcykslu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtjybrpoix.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gticbqsnxf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtmnnlhjsk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtfvtheazj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gttdrlfckd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtccznujmo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtxmmqfvpm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtjywbiatp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtkxgoppjv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtxreroypt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtddfpqyom.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gticxmljwu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtztwkuvlt.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtopqhdrgx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthutjxtca.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtyanvinme.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtkygvldrc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtomupaqit.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gteyfysnfr.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcjwvoxx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtmmcfvrlm.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtkhcuxozq.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtzjsufrxb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtmshlqmny.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtiqkpwtcn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtsmfpjrvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gttfjoxlqy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtestoqyvm.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtlxgocdto.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtkrzpojke.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtbzxlbboy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtrhtadvif.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtpzpnerjg.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtlypptsbn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gttvjkgwkj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtcugzfycv.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gttqiuajlt.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtjdzwypey.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtnstknwch.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtyzzrtczt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gthegiyayd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtgfzedlja.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtxdbfzyyd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtqhsuedha.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtvdxblmoa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtgzprucro.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbonokbj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtvpczsmor.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtsmslxnxe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtsjpoejol.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtgswwsrln.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtwvgoykfk.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gthafymqrh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtvbuvngev.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtavppysud.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtatofzygo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtsnqtdfby.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtskysqvtl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtrapqywww.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gtxczrqhlp.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtijqyft.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtefrferlu.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtmbmiswkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtrogqxvaw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtafgodewk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtfpbheogw.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtzeohvynt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtbkxwyadm.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtwdvgptcm.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeunglre.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gteuteyweb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtrlkfogqa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkgeqyhv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtyjwxpqtr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtzruogiyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtukklvrwa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtdijyryyo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtgvgrntmm.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtaurndkdu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gthcsdmsty.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtgbvcklnc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtxnyjapnu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtvettutxw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtvecmvvpj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtappxhnln.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtwvfpuvng.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbzjmtpn.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtpvfbcgrz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtoswzwdex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtxhbhrnpj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtqapdmisj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtpxajaztx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtxafsmvev.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtakoyulex.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtlkgmjlbv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtqykfkdmf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtggcpmmop.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtrokpblkv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtcacnsrbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtxqbghhwt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtwewbjmur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtlnavijsl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtlvtiqsgg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtmsmgvdtk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtqicazbjb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjqmtvizh.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtnhwiynjw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtutgryhoe.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtcesrsyii.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtwiccvnji.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtmnvzcojr.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlgebeykb.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtakeqvtbv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtiiiajcyp.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtypzkfbwg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtgnjllqht.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gthozilmuh.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtlhtvqoxn.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrzzcovn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtagdenwej.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltpdjvgw.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtqqjgxils.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtgyltyzhq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtdpfygfdn.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtqphesqgc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtpicmfnra.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtikohfktl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtttfjpiib.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtprxggqoh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtucctjcsu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtlrsjdtyk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthvkeckao.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtvffaekio.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gteecbhequ.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtufpinukk.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtkrlnnwow.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gttqqnadte.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtufnkranc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtrfakqtpc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtmjmistki.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtqnjnqfey.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gttblktygk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtcxhkootp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtnnqofagw.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gttiryhroc.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlytqqmjg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtqrnaxlik.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtcldxymha.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtcdqxmtip.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtoyqnsmda.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzqookmi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gthooaihto.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtfrwohdkj.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtrujkaapa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtdcanpwoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtuoqzcphi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtpangjaol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtiqegygst.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gthuxdtxve.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtfmgtcmjb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtyydpexta.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtmxwvtazv.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtwjheadzq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtmlvqxses.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtzvrjdpel.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtggdngnzk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtzvfgmvxw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtygzinnjc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwmzwjbs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtdjnkmafr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtrfgbvzwz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtvvsseqtr.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtygzkdbto.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtiyqheuei.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtqfdknjku.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtamueqify.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtovcreyvw.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtwfwdvduj.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzgbcwudu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtfdqhmlne.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmykgctps.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtirxngsnz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtygfqcqae.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtmxzytysb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtzqsdxthl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtfcbfuvfb.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtxuvdkphw.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtmfpyhpci.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtfmlykxaj.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gteqxtzmpx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtzomzkgzx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtrrwzdkcn.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtjsjeefel.html


<!-- 参考信息 -->