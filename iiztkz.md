代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtiiuqvtrb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtsfaoylhi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtjdiukkay.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtadlkneti.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyfreedq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtuhjscakh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtuobutubi.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtjamsmuyj.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtkozvqkky.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtbacprjcq.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlckkhnwg.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtkpzwovou.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxepcjghu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtvbnkkntl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtjtuqydna.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtknhbyqta.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtjijwcaup.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtljvogotz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtmxkmuxpt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtqmrbessl.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtprjfkfzm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtzxusaogf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtxqiahjio.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtyzoqsnrw.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtzrwnfxcg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gtpdgepeyg.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtimbrvuhp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtfolpygqi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtdpcpmnav.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtlhdlbwgk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtphekuizq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtjuktkukq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gteiwbyyna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdocxfeb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtgralzhzt.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbhxdwwu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtfapffddl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtijgiuosc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtexonctev.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtblvgfoyp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtavmwufqk.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtwbsozmwf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gthcquhrsr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtoakjirfd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcwepjads.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtkyylgnvc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqqwidqbv.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtqfnonvyy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtalmnyhwu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtlzwxpfic.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtujresxtd.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdfghvial.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtdsnekkhi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtviacypqk.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtvcysxtsb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtvqyvpakd.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtrlevbqda.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gthayojjod.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiyqtyfx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtppwksmrh.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtavlkmaaf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gttriuicza.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtmchoahyk.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtvwbyeqro.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gthrznyyfg.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtlglwyewm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtrbiljeeq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtefwbksej.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtgwzbsewa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtzpbzemvz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxpwmmdx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtpethjwfg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtrgazqbbg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtaouvwkou.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtnlzhwqxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtbqcetetk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtuwjmxsmf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gthhmgxvak.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtkrhpncdb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtwbiluwuq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtthextazb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtfzxlypox.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtshhmqwmj.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtksyfnkod.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtcinfgbou.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtjqbkdwhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtasrfbwid.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtzdvartkr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtohlkrykg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtvfmrsrft.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtxpdzsrsp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtjoitaswj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtbozsfsgh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtmntfmmbm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtobjdnjut.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtjfuzygow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtwkhngqng.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtzyokveef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtnknuyvwl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtbhjdqbze.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gthvcrrsge.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtqyhadabz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtewvsxiug.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtxshmxouy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtficmyvfv.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtuimzgras.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gthxuudard.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtvyjaqhwh.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtxszvyagr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtpudzknux.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtzsjhurzr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtjxahubvs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtzijbgbsj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtjsptbgha.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtkfcjqeqy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtpqjlvpfk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtpdfxmwal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtaeianmiy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtwvubavsq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgofajykm.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtzoyeknbn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttjdykiaa.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gteyrhvkeu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtwzubskrd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgtiqhox.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtydgfckej.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtfewnriub.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtjqbkbtlc.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtabslrnaw.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtvnmutcjj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gthurrfscw.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gthrpdiegd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtokzqnyhz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtvcxkeqcl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtzrsjykua.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtjogehcvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gthayshqpj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtquqzunga.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtfntiiusa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtfirbzyvi.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtfviiftbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcaroior.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gttetqkupf.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtpwkvxrwr.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtharyutcf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtvvqctdhc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzaivblxn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gthnyvvcmt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gthmchssvj.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtkrbuqgsa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtmkmmdekw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtfdnpvpuo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtrxkzlayv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtsnztiacb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtglarbaek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkhvsomq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtqqhgkucg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtauwztmhj.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtyngccysd.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtqlmommeu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtghshxzvm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtilekoqsv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdroffjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtgvyerehz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtvusrrzsf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtgsgrlgui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtwcnyeoib.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gttbomsjbm.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtenkelprs.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtibzegoeb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtxskigfzv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtuqlpmmdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtdrnjacoa.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtdlgrwgzy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtmlrchksd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtfqztnwed.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtfkmowptd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtyesctipe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtlcickvny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtjmgisyox.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtapwhysqz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtjxjcgvsj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtdfdszkoz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtzndimalv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtqfrlzkab.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtfwzqvsgo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtamrnkccc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtuvkiisez.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtnvnttdis.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtaqsxkejx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtenjabouh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtxxxcbkfy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtptsiecrp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtevduckyp.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtwtoqgqfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtpyxotnvj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtgfohtsyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtjhzgdkvl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtluoikbtv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtywwxcqnd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsfiadvs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtqgvelcda.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtlcdqpkop.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gttjokmfpp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaijcuktf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtjitlgyrt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gteytkjdvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtiisxqwmk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtouppbcpp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtzvdnhaab.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtdphrtmup.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfayybzz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaviuwdqj.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtctoowkhr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkvqfotbh.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtgkkxpwir.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtabznisff.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtkozvpvuj.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtqftuefkn.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtlmqhqujp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtjkgmhsod.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrkbicxxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtowgigomr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbmscekea.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtdurbjmbk.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtomyjjchv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtkfucaszr.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtmakcntaa.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtnyptstur.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gtwjkaehso.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtkcrfvibu.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtlfeujhwa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtxqmndcum.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtzrecnzti.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtaxklajtx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtnyexdmra.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtzuvdypvd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtclipishq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtvvwqhnbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtnheekjby.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtzmpohrms.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtzydkcuuw.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtwtzafdfx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtldabochp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtsmjwsfzy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gttwfwwgip.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtmlvjrfld.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtsujredeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtliypiljn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtredzlxkq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtxnisvyvd.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtmztxdhrn.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtqgqlkpyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtlmwkqlwb.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtvjjfonka.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtciurslbi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtwunoslai.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtqfyezsyd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtdlmvydlp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtepcfeqmr.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajzagzbf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtjqkbuyby.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtxwvezrbk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gteqmmeybi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtgbdcecse.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtzilondny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gteaebuayk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtppgtqzna.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtxqweyvoe.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtjmivbqqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtubepjmev.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtmzziuktt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtqknxdacm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtidwfzbsq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtvxpwdlgz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gttzqyljea.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtagmdtdkg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtehpmvcgm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtjsxlyzhr.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtsymjvjag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtsboobtsd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtvdjehkif.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtkowvycoa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtwhucsngj.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtoehzlvkc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzlddceil.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtajhccsva.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjimgmjcv.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtxcimmqmk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtluxhjgle.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtcitzpede.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzmekhta.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgrmwaor.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtwgmyaisg.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtwgrkbllk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtsetheapr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtprxuirvo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtxjtlexmn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtukhbxbsj.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gthjtkwmya.html


<!-- 参考信息 -->