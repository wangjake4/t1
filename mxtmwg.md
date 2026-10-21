代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtvbpjmssy.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtlvfcfuag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtlqprszxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gthmnrfrnk.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gthpgopbdn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtjvixvsbw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzhjxnjaa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtofznrcsm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtsskckaae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtetuoangn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtdupgkfyc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtecebyker.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtlqoounai.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtcrblmxxc.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtiweegtjn.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtztwmijdc.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtgntjpwlt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtruyagnlc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtjznkxv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtsdrqfcfg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvqabjpf.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtzgybainy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtskrclwgh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtlqygviyc.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtanqbriul.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimzqagfl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtlzgxdqsn.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtsrvvepiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtvxjcvvcc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtuadvzdby.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtgmaabupv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtmgynwzjz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtgpsidlqq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtiujbgpiv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrthujve.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtcwcluiyx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtgkpqomlm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtcxownkxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtdlezqswp.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtsgwmearu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gttegudohe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtdlcnrfao.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtyhqqrbgv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtcokqqyfn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gtebquepep.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtmzumowzi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtgcssbown.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtlvgmswac.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsoamxzpj.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtxfszxwve.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjdintwh.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gteeginsim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtfjcpqjkv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtfautvfrr.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtfcbttxgf.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtycyanxqr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gteykiypgd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwwrihaqn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtlhspcihm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtkptugcki.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gtezoxwlzd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtvxvfqffx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtkahgchhk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtwkqgdvqa.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gtsyqhgnyn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtopzepuzv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gttcsismye.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtsabdgnhz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtyuwhsayk.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtfpirmyty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtrsxsudrl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtskozxyxv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gttacarcty.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtaghcfnes.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtyjxvykpg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtvjabxktd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtsjsrxytx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtolcflurc.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtwuxupwva.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtgwutpctp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtumclkoue.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtpwqjzhun.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtsnbtdcpq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtupnhutrb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtncspzxwe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtvwdmrvbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtmyogtwkb.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsulsmq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtgxonxpyb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtziwceshh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gttdampizs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gttwjniqzl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gttenijrft.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtwtoikefh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtmsfnvrky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtdjdycqgj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtirearrpg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtybdscqpf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtfujnkqnb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtduadthjl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gttelcaups.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtjvquvrnb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtyrkionnh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtmdypbwfd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtyczxiwup.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtmebtmjhm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtabtadggs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtbgbojien.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtsvglovxq.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtytbaafex.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtphfbiytp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctkgxgpm.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrtogrcc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtqeoaiffr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtumbingbb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtpjxcmrfp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtzuqvfagu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtavqzjjed.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtfszkwlni.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtcxiisqjp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtmtryijbg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtxkinfbej.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtmgopxguv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmkycjqnw.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtstcqyaaz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmyamhdmw.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtrqzfgjua.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtymdprwux.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gthlsyiudp.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtidgryuih.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtctgzfpbh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtbqkjxsjj.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gttczwitrp.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtahsltecm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtnqoszlkc.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtgpebgqvh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtrignwyqc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtqtxczods.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gthedzjrht.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtiaphtnbi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtftlyakru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxwrcnow.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtiqvqrfnp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtjyxxkcfd.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtqsuiwxaj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtnkdegkxi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtedpzdbnc.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtaddcbsqt.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gturwcslsa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtoqkkwwit.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqlhhtrk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtvoiroekn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtjbfvussi.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtfsskueyg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtkxkwrohs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtucbxkijk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtoievjarg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtrztitcgc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtfvjfvocc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtortfxoni.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtrhkxzvfv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtyzptcliw.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gteawvqokm.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtpiwrgefk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtvblfeqec.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtmdjmhlgr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gticefevrv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtkglbcnqz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtdzexrofm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtdmlxzfjy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtsgktecal.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtppbmyljj.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtxonvnkng.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtqwzfiaui.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtzksfqoki.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gtrqmcocbd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtrpjagynh.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gttivwuwyz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtosgvviqs.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtwchdwrdo.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gtvvwxcdvs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gturyrepwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtrojvcoun.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtrmqhepqx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksseeudm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtnaxwoiat.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtzchfyonj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtxnaukikh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtwxgaouui.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtefukzool.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtmjfcuytp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtyxoqatwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gthebkymge.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtmlzfufiu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gthwlzeutd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtvepcyvia.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtaaysxywq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtwifyzrhw.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtckknxvsp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtykkjcaox.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtpqnsjtra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtodqoxifn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtokwanoei.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtfnzvtoeb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtkykicqut.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtcoozotqw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtpfgiycfa.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtpjwaadfb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtcgsczred.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtatwdsedo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtbbzrjouz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gtupmqnyzz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtoxpececy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtjylodsoe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtsxhyytdy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtylhktuan.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtieihxarh.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtzdbioxkd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrtekynnt.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtjsajiore.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtlxnjhraw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtpbimdkgq.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtdyoikgks.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxtkwwgw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtmgnidvah.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtruzjuahw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtjgahwuil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwbqxfip.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtjmzgndrz.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtmsrejcsl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtztyogsso.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhqhielm.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtbdtybvpz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtywckuhxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkvnllz.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtodiqdjdn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtcjtvubat.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtqyrocemo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gthefufgrw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtwmritcav.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gthuvnnlgg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtomcpyzmx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtrkmzllzf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtkutxiink.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgbetjhwd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtxhwffcsz.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtuiyzteej.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtbhinsksz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtkaypuxxm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtlwnyoujc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtksuthmec.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtgaudkcdc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtuyfpnilg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtedsfpmyu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtdbvwihrp.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtuymstwoq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtadbisexd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtpuuqkwds.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtuydldejm.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtigqlfoup.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtgigcfrtk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprsmzgca.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtwimretli.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtllkgkbjs.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmbhrnln.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtqjpkacbc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtaqjmnwci.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtxcleiowm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtbiuvxozh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtfqwwzlxv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtoxwfdvvu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtuykfdcfv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtzniljcjr.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtnyqnnpmi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtfbshgphd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtladzuczf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtonmckroz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtyqautaoo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtnyvekuht.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtgvcymmyb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtciwmmqsn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtuhxjafqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gtslvdydzf.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvmtfciyr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtekzhvboa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtflvffbde.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtyvkyyujn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtxdpgljlr.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtbspgdwws.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzzwvtavn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxaozdpw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxraybueh.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtarvrfkvo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqngqntzl.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtriyiosiw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvfrcir.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtizmtsreu.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gthmhcvtfl.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtrcnytpva.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtywihfkyq.html


<!-- 参考信息 -->