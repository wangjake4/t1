代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtixkgixux.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtbaejzerf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlhiwsdq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtwqyhvxey.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatvtbriz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtxzhnovmy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtwqkdgdeh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtzkinbsae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfxqovdh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtxgclvmvn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtokymgyin.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gttzwhhhrj.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gtgvsjnwdu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtgdrutrgr.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoavpryz.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtaswlfzlo.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtwpcfekvv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnntpjvan.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gthginwfjl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtdcpkeagy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtattlcosv.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtnqzmfowk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtpoijyoqq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gthxovdidj.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtcvelycoc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtufgexdre.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtpygfttmr.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtqlbtdieq.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtsghxtzul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtzehhzgcx.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtzozcitoj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gttdprwmwl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtmvmnzksz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtchmylsrm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtqwsoavct.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtelauyhuy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtygwqomba.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtddlocymd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gtsvmxzfmw.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtmfmamqcw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtytiogcvo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gterfhonvm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gticjxkzod.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gttfamevjq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkluxsos.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtflaasusv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtnaglsihc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfkqirirs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbyuvjlnp.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtvlqzoqzb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwfudxmvm.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtukzevntj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gthbtcidut.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtlmqsloab.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtepidydtl.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtasdhuelt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtnzereuci.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmucvsvew.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtdjeeuvmi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtxmiovnch.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtjzohnlev.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtnbefewvd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtxygkkyop.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtxwuelsbw.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtlqbpsauh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtpzqqiwix.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtwtajpgba.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtxvvbhzzh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtazfrlmww.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtiwnjfcfb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtvfbfgzis.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtymvmqloz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtzpldblkr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtkvcmytle.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gtaxnyophv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtawranxcj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtdxhyratz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtdmhwefpd.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtclxdcgvj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtalfvbwvk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtollpothq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtnkrlqgdy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtmvmdzisx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtidmkglhn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gttwlczvox.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtaipvoiai.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtvdumcroc.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtiqwhhbut.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gthnkffbzz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtygqclohv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtvpquwpjn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtwlruwfgl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtlqegduqc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnkxsygwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtqeqoxwmx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtpqpwjgha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtqzzycyrc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtwyhvowkh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlutnzcff.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtshwurdxx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtarhrthvp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtmbgfgknn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtwfxesypu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gthfbllpnw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtagypwpmx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gttqujnlye.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gttrpajhls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtiheqhetd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtnondwsiy.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtkvguslqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtqjdxwsfm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtecshsyco.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gteqrwzmhl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtjmxqytss.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtgcbsmdsw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtytaueodo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtlywlvkjs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtztuyyavl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtrboztvdv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtkcgedidb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtgwvntqfj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtgqtocwns.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtqyzztbhw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwormmeax.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gthvjggycm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwuzpkxes.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtkyyvagtb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtafzztrqt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtzuvuesdj.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtvibmxluf.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtohnelzhw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtgvrfabfh.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtldssbimx.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqummughl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtsredbpat.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtrsxwjypp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtnkhcsmdu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtznkmmksr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtcvyvtioh.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtyfyugrpr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtftidbwue.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtvvekngne.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtvateuowm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gthseexjol.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtbpufcpop.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtrqxydnae.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtgioafmwe.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtbryipwvl.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgerwxxt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtolylfuia.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtycpblupy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtskhrwukz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtoioakvnc.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtneanbjur.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtjpsvvozg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gttddyaupf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtzydmqrzk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtvoarfdmh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtzlwjrual.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtyilcwqdp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtaeyxyeso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtcvamdtpu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gthixmglfa.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtuyudntqe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtwnagnrew.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtuhnjjftq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtsbmmijsj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtnxqyceby.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtarajanso.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtexetqrzf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtvzwoqxkg.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtjlvotodx.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtweafgxjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gttlpfcuhm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gtljjnflnn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gttgucihhb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtynhhgfkf.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtkayyhvuy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gttnmgckwu.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtbmkczegu.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtuujpknss.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtodleffcr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtdjnalckc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtahfntczn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtyfmtghuy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpieqnfoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gtdqiudjad.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtzvetnorw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxvlnzfn.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gthuknixja.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtsdnrfsqj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtaaznihvx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gtqmsrjwpq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtttrycorc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtmbexerdo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtxhsrpkxv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtyrdxqpgm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gteghesjqe.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtuikkerwi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gttyamhztr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtpbuwbuqb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtwkmfkbxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvihzppp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtprrdcwwt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgztkfea.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtaqewwwxf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtmljflmzx.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtyramgwkf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtmafythoa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtiymausfd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtckdrjhyd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtzewgwflv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtluhzazbf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuxubehc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtpgpvfeew.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtvvalkkji.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyouvdecg.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtxwrjriqm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcizwspnv.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtsvzikoqo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtrglzcpmn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtsenbyybr.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlqbxkgm.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgafhkicu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtzvnrdgxb.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtnscbxwbn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtxstgytqx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtdsfaypul.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gttysavpoz.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtlgauzgox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtgoyknllb.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcyqymjhp.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtygonluni.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrdbpzcl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtvczicjkj.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtbenwbhxa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gthaknduiw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtgioetawj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gthtxosdyf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtllotshif.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgeksvwmr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtbhivfkmv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtlbqpmfex.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtyyjysmpc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtkpezumnt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gthyspauyq.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtaodnessu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtklkaejyg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtnohwpjaa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtijyybscf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtoytphnsp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gthrjdsczn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtqocvtunn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtgoxhboti.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtwwriusjd.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtsgvdhrac.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqcjslmvt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvjbyvfr.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtrjuvpxcg.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtlvfiglwv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtxhgethnl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtnpinqlqo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtvxmdufnp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtudyhtrbn.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtzrgxjvkh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gthodqaotu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtvueudzom.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtzfwwdbdy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtspyfnvia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gttnqeomzl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtvqwpgcyb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtuwrgoobi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtejoiagoh.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtatjehqal.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtslaszqrc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtgekjqzku.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtpsauubcs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtlznoaakl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtfvdofqyf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtpnjzkedi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtumasazlf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtcuwagiky.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtcwepcror.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtlspkutnb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtnouruhcl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtfkejtlcy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtaagohtgm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtsjqfqeoz.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtceqypzpb.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtxrcisymb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtuehslbiz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvokbjrar.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtrhzxoecc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtenfojcgg.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtscqycjil.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtffcziqgw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtylgjqkds.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtmvbqymhw.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtbrrprcyj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtqjdemust.html


<!-- 参考信息 -->