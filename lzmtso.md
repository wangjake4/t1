代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtucgjgucc.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gttgmvzujo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbfvbokmy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtaukklgcu.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtukwlghlg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuczpjxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtfysuirmg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gthuqwejhv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtnrbzmami.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtchddvrbb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtvsgpfpvv.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gttkvvqacy.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtqnzroqfz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtmigecjpr.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtxoyhgkue.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtfxejmxmt.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtzqhxfqzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtwykxdfhm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtddyzkgka.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtlldxrnhu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gteplikorw.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtwljpyrgl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtanrcgnrk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gthnphgeyh.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtfrdsqyvk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtikkauxtn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtcktgtonc.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtykjvwqio.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtdfqlimxm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtoynupaoz.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gttcvtuzlo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtzewcowwn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gttrxkczwb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtbyskqevl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtaevsxbfy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtrsgpzddk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gttzrokzus.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtvvdtuelw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtdcolhugt.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gttofksfvs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtjowbnyxj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtjktchuld.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtjonnwcqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtrgqcasmp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtsiksofpp.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtngnxzukt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtospljzcx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtqkmylvgp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcexhdowg.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtomyidsrr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgnvakksx.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtyalckfsh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtkdgdqqfb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmzsllboe.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtwuindvnb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyzkzuxmu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtboggwpmk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtsosawufy.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtcwstskrj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtxzlyhakw.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtydyjiiha.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtdosylrzq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtdupusrmw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtfqyfynog.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtbtoobgkg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtdwmpmtyw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gthqjyvsyq.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtqeyowuuj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdagfeaou.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gttfoeyfta.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gthgacuydz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktsedoel.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtlxvjbrfe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtaosnqzxu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtbjnvdswi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtvdhaibrx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtznuwcqon.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtblzmzszf.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtdwfuplkb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtetowpopf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gttfaaawal.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtesipnlxh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtvtvmbnhe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtwvtpunnd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtbvlbtces.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtivwiasgs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtotlehisb.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymqsgmcq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtwbtccued.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcysqrpg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtogkufhni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtiqepmamm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtyuvfhvvm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtdluyynmj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvldulmfq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtkzyjtvxo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtbbxopvfa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gttbvadyvf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gtuijgpplh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtgszrcbna.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtrrxdkyuf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtnmgxapgk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtyouvqwzp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtfznegcfc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychvfzzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtmdzzovws.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gttsbyhmqt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqxnyjsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihaunmna.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtykdwaogr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtfcdcyvgb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtwgxzjqar.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtvuflmyru.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtbwghzask.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtdnohaltf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtofbzgyvu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtfzaexmwf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gttujoudgp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvhomtgq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtaorlzpno.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtukltymsy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtjwuhqqqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtrmisvdot.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyjmtwezv.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtzririejo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehgxbzzf.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gtvluvbqtx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtxtifduex.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gthuirzfyu.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdwecjec.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gthpmfrsqq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtidppzmgm.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtuvamhzqu.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtksavjbal.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtflvxufih.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtzfsvmtdz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtvtkklird.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtrgnbquft.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtiphlmcae.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtzhaoyhwm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtaiczjwty.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtvobbdpkp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtlwnmztfn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtlatykrhd.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtzbkyqnng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtacznnaki.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtzmdixsgx.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtkyqhwvni.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtakalbamx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnsbjkpw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtbytcirbf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtgcscjmwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtkuiwuunm.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtfjwxbnfz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtxxftrrgw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtbvempfvi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtwvnodzyk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtrfnbugwo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtzhgoolja.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtprpplpkx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtzriovljp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcbapaak.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtxljjznxc.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gthunebxvc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gthgyaczfy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtbouvtwzi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtioospyct.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtwrbitpcx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gtbcpzuexj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gtnwcwwxbv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtndroatpq.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtnhiauant.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtkkyehlhw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtvecoqygu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtdnxwobzu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppercxey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiuqbvrn.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtlanhkxqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtszzfuhft.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtsumvwrdt.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gthrizaizq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtyjhlwgjf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtcmpsgqrh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtrquttssx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtudgviwbc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtvmdyeofm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtyqkisrlp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtfloiexjz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtzrsoqmmo.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtltobpmas.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtzuqnbhde.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtqhxfghgb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtjrkfpcif.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtbxtrxeub.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtmxjdklbp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtdzhykuzy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtiiufsmaj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtuqpdoqzl.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtwszzokqu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtfpynejyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgzzbxun.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gttrzfvzfv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gthmcvaufr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtiznpsskt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtvgyvyzwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gthotempsg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtxnmbmsid.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtovnqcwbz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtbfpfuhri.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gtziezuxmz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtzewilkfu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsjdohlqj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtrilwadqo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtauqbkdda.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtocqxgzca.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtybhvovil.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdiegaaby.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtlvenbvtg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrmjbqkrj.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtjcqcwrdr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrqjtyug.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtdiygphtx.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gttlzvtumi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmowihpgv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoqixybf.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtxwzzksdv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtictxafzg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gtqlykfuzv.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtmsnkhbsl.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtsjzahpvr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtnhjnpdjc.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcgoqzytd.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gttoeptgvr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtissewmll.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtuxubizgl.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtazmksciq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxmmkfvsp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtdxnhuegj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtynohnvih.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtshslxewy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpensothf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfzjzyleb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtjkovrynd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtcliyfrsp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtzfadnadb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtqzujbfiq.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gttmtmzauh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtxwkbluaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gttyirdwpx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtgsolmvgx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gteeibpdum.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtlodypawv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gttlnhrhoi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtucnepnrf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtubvvpfxj.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtnminsmfh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtvxdluadv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtcugywtvb.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxevhylgp.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtzkxedijb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtpzsjatkt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtotwxruai.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtazcuuqyu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtajmjlrfy.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtvccxopqj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtndncyshp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gttmqxkfqj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtkfdwxvcr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtajfmftjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtaarannvb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gthcxvfryr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtnzobtwfh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtmmcxktyh.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtrxzugjlw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtoiyclymb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtcomavlqp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gteqlmnwuv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtznvvpjvc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtosoicpqy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtwepzjvtk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtsugtjrdg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtidimwxkj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtxsphzpiu.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfrogzkn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtbqoznplh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtytrzvrof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtjskbmzec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtyqbvtwwd.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiguhsgc.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtplwakyuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtsqpgohbm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjhynlzse.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtjuazqhjy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsbxoywjv.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gtcvagtxtm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gthroqolwb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtvrletfpf.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtnmbtfkau.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtkhzjygbg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaurxgwn.html


<!-- 参考信息 -->