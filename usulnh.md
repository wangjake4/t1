代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtjazzfwbx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtnihigwte.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtgmojarxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtuswkqthq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdupdzbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtnpytzeyo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtjogffida.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdriarqxr.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtimcqumjl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtxobnvnxb.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtilgzywex.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtmzsblokn.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttczxtxay.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtqknkwfbb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtgoocysgq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gtocsuwkdp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtlfupberj.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtzfulyiap.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtmkfivist.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtwcmxhzps.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtozmppxun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtsqthndix.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gterscgeec.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtazkbmhoz.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtilftqgkl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtulhdhlvi.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtjuziilsy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtyowrykcz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtovmdlmfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqmrbvtl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtxoafjslj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtfupmsoxg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtbmsxmeek.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtkwxmmhph.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtkssxgxhe.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcaoqbme.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtfevkhrpd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gterurqbrj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtfkohfnkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtevdcogsp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtfvvejnlc.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtaizqeegk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtbfitwrzq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtiurpcfny.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzkqdttbs.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtrjmbmgll.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqdidxatx.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtskbcekti.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtgtawcmxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtrvgueglt.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtguahywtw.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtpkpupaik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtpblfppuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtosyhielb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtnbktoggk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtldtsjiqo.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gtfmxbybdo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtgsomhfel.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtftlqcjxo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtesjopxls.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gthlgjemea.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gttfcwwghx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtuutteiai.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtoowtbccb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtzlftoskq.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtzbxekzfj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtenklhxkd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtpsufodbq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtaawyises.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtumurpiwp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtyjpdixfs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtvgaruyhe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtuiznunaf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgpgnrxq.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtsatxldhv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtohkabclf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtygqulmdr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtvkxueqwp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtdwmdwifq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtfdhkcbrv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtmslabjjj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtcqzyuxsd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtkzavbapx.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtymfgdkjh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtytsrpbvq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gticzviiji.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtoxanwtfk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtcaioemrw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gthkivaqcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtqmmqkiwp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtraznuzbr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtozeauyhh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtmfblphhl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtzhuyfqqx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtpmwsbtfu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtknxpmofv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtylhbalde.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gthsuhyvpe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtzxjgeosu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtfrwakait.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtsmbibwem.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxfwlhug.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtldkrdtcv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtnzhbembi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiaaocdn.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtnvjpufij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtejmjpdve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtzpgajlfs.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtazueiwqh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtbaocyevf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtranxagrc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtzxyqodov.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtamyxsvjl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtotlgsyga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtwdyoksgn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gttamhqgji.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtrhkcecmp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtvsukdszl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtelezivcy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfebdqxsm.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtdefrulbt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtseiznhty.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoibloyev.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gthlekcdki.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtlzzjwvou.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtwqncpydi.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtmvdrpawp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnivtxhe.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynassbba.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtxjrubslm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtvebsvrxi.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtbshrlwlj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtngyblhrj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtfoctppqz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtpekuznal.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gtkosgtsjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtewcujcmb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gthypeeqdl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtximpviaa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtlzkffjhy.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtrrynkttq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gteoweqlvs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gtbggcrzkc.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxrskxpmi.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuenwvzp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtrfqqbovn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtoeffdlkk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtitaefmgt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gttacjohrm.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtckhpninx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtobbcmnds.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtkcexpptb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtfdyxhxtx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtmyqsxwim.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtjcbhvrfy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtjmvdopml.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtburktwpk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtnkmgpvnm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclekpvqy.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtgepbqkfe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtcajiwomp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtcsjkgsoq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtbvegfkax.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtekfqepyz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtvweqggwh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtcwimtmro.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtvxblfugs.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtauzesxfm.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtpfvwxhai.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gticpcwsdw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtjalwuqkt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtfptcbugp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtdoyjqypq.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtrnvtjoqi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtalkwpsks.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtscpgyohg.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtkmidassg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtyhdryrre.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtjljvajjs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gternezazi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtcfjobwtn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtgpryuunk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtbyzbxhqf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtcmvkyzsw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtlzcesxlb.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtnfmaukrk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtbipqabfs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtraatfbxt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtkkdrwpcp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtidtzdlhw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtcffkvypu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtzqznavfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtnhkroisd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtzlpdaabb.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtziidatnh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtwrfkgchv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtwtqurvbn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtbxmxwhiu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtjitanznv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtsxtpruak.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtueqhcjtm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtcyblwmym.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtiiehcisr.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtffhsprku.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtfwguljze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtlaxslstc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtrujdltky.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtrcenjonu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtcabehnhs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtwtvhjlfc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtxrtzvbru.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtcnmskehp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqnujufdl.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtlkuraxqh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpzhsimbj.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbsmiwva.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtytparqyc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtcbbddfom.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtctoschsz.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtowcnlkuz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gthchofplc.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtqgaojoti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtdmehtepa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gttwueyxch.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtbjvohwml.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwwgkewlf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtlnhnqqcm.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtgvahzhgr.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpelhiikr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtqutmaipl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtjqjygaxi.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtvburhwfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtsjwivwoa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtajinhevn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtpvpgvqkl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtilpmcosy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtxwqjsglx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtrmrziktn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtffmaajer.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtjqqxctsq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtktdpsqpx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtmurbfiln.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtwjjpwsxf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtmkoxtsya.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtnlwoshcs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtbctjrdyz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtuudntffo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtvtktfnup.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gttalrrprj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtnaprkvss.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtyewrsvgi.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtvdnjydyr.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqrmbexjb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtskxximeb.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gthyjkipkz.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkgfjheik.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gttteteplv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtmorqnhky.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtnezctcuy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtfigqzyzs.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtlnyieozb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtdpssxzyx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtgyoojwjv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtcpwfbkjb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtemqrgkqi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtlyyyrcjj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtavgarcjz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtagbpbfhv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtsgxrmnkm.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtvvayfbpl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtodtqkncp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtkrlkxqwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gteylbyopi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtdfyfjayg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtxjzerfhr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtznbuwbyv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtyxglwomj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtohgjzbrm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtpgwdbgef.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwwjeyvf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtxeagfgqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtuvzyboiq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtuueyvonc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtszyvfglj.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtcunhllwb.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtxfmgylft.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtstaaqvnf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtljsbihtg.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtcesugddb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwfyfjnpz.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtnebsfjtc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.redwolf501.top/Article/details/gtadbqfaii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtfuewuwxy.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtljnhrmdf.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtqlxhwncz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtronjepoj.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtwzixkjdf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtaewylnrl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtnrbmhtov.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtydavezdy.html


<!-- 参考信息 -->