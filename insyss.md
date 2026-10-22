代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gt2zdrovjmi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gt2jqlwodys.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2jrlahybf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gt2sifttzzs.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2denlpyuq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2yqhkdjkl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2mklbhgod.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2prvxwdqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eujdlzrs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2tuqbuwvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2tjuyeurt.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2bmkyhjkw.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gt2jcppubna.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gt2ppmvaxri.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2xposaroq.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2zuctsfdv.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2kfsckyuw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmkcwouz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2dhueuziz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gt2hxbstdug.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2sdbrbipu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2kfmhbrhi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2nxthwjoy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zskjrqlt.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gt2uazfdlht.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2sxiguwgw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2qjuvfsbw.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2qfczuuzb.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2jdixhczh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2blawacvg.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkysvsmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqsoztok.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gt2qvxndxrw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2iygsmvej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2huylugyf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2tyhhvhfh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2ipszljto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2jdxhunsa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlhyaie.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2flnealoe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2gkcatqjq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiyogerb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2mblyahqa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2eurgsulh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scpzzjvb.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gt2hmbstube.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gt2yoflcbij.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2talcydym.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2aocubsgl.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2uuihgyni.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jxwtpifg.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzgbavh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eliawggw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2wxrufczb.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2aootiqpf.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fbrlvvjx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2uoxopojl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2shjypzfh.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2xjvigocu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2pjwvixgr.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2dnbebljb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2bzedspih.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2svhapmri.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2mmgjzmgu.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2jjuvqbjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2evzgolfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2mxnktovj.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2xczcmwzm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2bxrtnahm.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2svfzhudh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csbxdexr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2vqwaoyhp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2gykyrgbc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2ghqnxlen.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2fopqgost.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2aqfpjsrj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2rykzxyvs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2ytskioxg.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2rvparvrc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxdquld.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2qkrkbwht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ychgnrlk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2sxcosjvb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2fsgukfqr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gt2mwwrpxbh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gt2oyaykwuc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2qtjyawjz.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gt2uvjnuipg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gt2mudenbnp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2vtddpbmn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2vkblfmus.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2pdkbveje.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2uccchqqe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpybzhqv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2jttkedti.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2rdkpiukp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gt2cpfvexby.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yykqdqim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gt2jezctuee.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2kchlecvn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2lewfujif.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2htkigeeq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gt2xzopxifj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2ngjjudsw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2wkdhozoq.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gt2voxcwexi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gt2jwvdjxsq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2jieokmgw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2bnyczioy.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2pyqeujtx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eaagudgi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2yvoiaeey.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2sndhhzsh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2hdsonbmj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnsuztyh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gt2ogkgkreb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2hfzdgzgv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2bxuspacp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2erirywgk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2wvwdzrlq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2cyzreess.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2xkvufiam.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2ggjyfryb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2jkdssnak.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2wohusmkh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sfomfujz.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2poqafpxz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2mhojvhme.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2morfpshr.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2kobhmocf.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2wardycjl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2gydmddpp.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnixzjlh.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2wsjiosqo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2docfwqrf.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2fhotjcny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2xupricdw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2pmrcnvac.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gt2ptahqzso.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gt2qomeegsy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2wmfzystl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2uomqearr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2njufsckn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gt2wfjanehg.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2ncyyvkgs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2ekqnffzo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubmiyagl.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2qeaamlxy.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2uxeqxwuy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2xxjhjoxj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejwsjwud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2jgmiwhen.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2ftsdbzjr.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2iavbvrog.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2gazcbvti.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gt2tkxpczob.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2ajviogva.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2eupsgdwn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2ieuysbth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2knquvsxi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2taqvqgps.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gt2betgmshn.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2nhfdacxo.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2zzwvfjhj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2fbpqpjqa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2egamqyou.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2gkuyezmn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2celevzzf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gt2wcltzozt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2rstgbmtf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2dlkyjxly.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2ctznjefb.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrjrpzgz.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2hfksmyxp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2dnonedjn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2fidwoski.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2reiuabax.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2bwmyciux.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2flbgqmhe.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2khxehymf.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gt2nxcrvnkx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2mjbpswyz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2vxzdrmkq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpvmxfcp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2sklajfeq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2vqrqeqme.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2agwodnht.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2tzirkdhe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2xcjuftpj.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2ldmrioio.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gt2fyyjuvul.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2baqexbxi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gt2gvvicdsu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2dwnqcgda.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2pgfdsjux.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2dmtewfqy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbasfgug.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2ctgpwmqq.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2gyvsuytx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2mxnzxzxj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gt2mtxonyua.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2lrhmlzgd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2vadutgzn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2hvxlrwkw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykawsyon.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gt2iowgmfzu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gt2rcjwihtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gt2igllvkgj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2eflbwktf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2buspsxsx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2uljlcjcu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2cynshkny.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rfsycdyx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2wdpticti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2luhvqzzx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2gmxuepfs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2cdhnedbr.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2wyqtypsn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lmvtvxop.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2uppzhqrj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2aufjmifm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2ckhxxtii.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vqfycomj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shgibvfc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2meostyhb.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2yvbkiusa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdgpueyp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gt2euladiit.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2qtuebdzw.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gt2hicziser.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2ibvjebiz.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2cxxciyur.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2fewkrspi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2jfwmnidy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2dqvkarbe.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2zrxymftp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2gnegyifx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2golscqyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2fsdtfzyt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2gqrhacbr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2evdgicnc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2nurgrtkf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2yxtioxfp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2zgzahaqt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gt2pdqrmdwx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2lqildtnk.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gt2ffojsnwf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2ggldzxbj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2nlnmvogy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2qcfsbhzt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2kpndnjtl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2nafdmwzg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rettwcnr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2nrvxvogw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2njwyptql.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2ubcxillk.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqwnreaa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2duvhlthn.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ozqtrffg.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2ztghrxjv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krnswbtq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gt2xqejqvhm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2stfhxbgc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2tvxqyeqp.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfqzqkaz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2imekxtja.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2fzgoqzxp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2fqogwcmn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2rdrereio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2umupvdml.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2saemcori.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2jhkicnjb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2waxxlpqh.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gt2udauulll.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2tdexqecy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gt2rysybuqt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2koimsovy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2zpzbygrs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2hhqgifeg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2lerlrxdd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2cwpuameu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2cclkqpxh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2jazuasxt.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2uvkwqvwf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gt2usahmzrj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2cugobcgs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2ukcnvwlx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2ysvwlqfx.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2ibdapfek.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2plgfontr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2gwrqilnw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2teagqhdj.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2sobxoduo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oifesbuu.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gt2edymmajy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2vszqjtiu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2vowfaofq.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2ivwnvqnw.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2cjlbpxnz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdumoqcd.html


<!-- 参考信息 -->