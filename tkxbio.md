代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtctwlyfxt.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtuiuwwmgn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtsierzcud.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtuudvgzjn.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtfcmjlikw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtkacaivid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtkixavddw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtshgmyosh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtcjtgngpl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtwbxsyegc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtjvxowvpj.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtjibinszg.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtgnqpmyzw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gttjwfuhgc.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtulsaczlj.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtfbuwbtmb.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblwnrlpf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtcjejfnzm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtwohtxosi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtodyqpjzx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtwtwezruk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtoykieuto.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpwyoiat.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtvsgzawwd.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtpkkzxuti.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtfydbemug.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtvjrbpmmo.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gtimokmedk.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtnpktuvbg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtddpireax.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtcnwrsnam.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtoqnlerog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtncbysbvb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gticmiuaoh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtybjbvodf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gttertegkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtgjkyljek.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtemymnxtr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gtagcokcwk.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtdonaaere.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtsjrmseta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtfedhabhu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtrqhqsrfx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtshqnfbsd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtsyjhaexx.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtkpykhxig.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtlgaeyjtd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtbpptbihd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxpgzpmon.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtkadkfjol.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkrcbsxxh.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtkpdlsbyr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtvjmsukrj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtjzznsmbk.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtaxnedspb.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtogrimbdt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtpsxoapyf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtjhewqiho.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtqicynkfv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gttwkdjocn.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtlibfkwyu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtqvmzkqwh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtbjgjivra.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtlivhbzkx.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtmwwpxmsg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtztoljtgi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtrmcezlvz.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtwpwuujhj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtoxquoaps.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtnhyowvor.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtdbdyhwek.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtyxdctsvs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtdjflzznx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtkemyrddk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtltuvzwgy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtpsdpjjgr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtjrwibutn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtyzmenyqw.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtqozmkusz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtwllncxhe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtdndiaeqb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhyacrxo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtsfbuvpnm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtiwibxrrd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gtukppazwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtbueavgtg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gthrsyfmis.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtfmoetkff.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtgamqdwzx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtfgztnpwa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtdzmvzoes.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtckubmloy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsdjqyjq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtopdrfyaa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gthskblajw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.bjfxy.top/Article/details/gteforlybj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtyleegelv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtxvoclkgc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtxscvacah.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtuyhibkfj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtarobqmkc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtgzzpmvdl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtzgwhphzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtghtmodem.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtwafytbrj.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtkqabvmxe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gtpnhsylyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gteyslqcad.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtjobcgodw.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtpeoqcjct.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtutqftksm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtfqktysso.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtowesgxji.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtbkqfqhrs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtixrospzh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtqfpzmian.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtqixmrgbr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtvmndlask.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtczihaajx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtlxkmvirt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtrrimenml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtnzeatrbj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyikgbmf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmaemhhar.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtvvudatle.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfwaxfwrg.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtythgvrir.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gtwobbtwiy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtarshjhcv.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtvktdsvfv.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtmmwmtqhd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtqsgfxmcd.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlydjtlv.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtczhehucl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtnzvbtxwf.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtmsclzivy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtpgfojjqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtmvdemicn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtiowsyaui.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gtvsenyfpb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtodexzclu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtyyvllcxk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtszicxlzt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtueunfwiv.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtqmgfgkhi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gthsatjprf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtekposdia.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gttdleiqpt.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gttpztzpyf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtkqrildfw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtzmvkxxfr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtbnkcwojn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gteejedocd.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtbtzeyzry.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtzhxooeuy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtudyopfnc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtndlzcvat.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtvfeajilp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtgztkzefe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtvicuqmbv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtqtgvmvdj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtdlnuquww.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtoamnehkb.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswdprruf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnikisqdq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtvdgweqgd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtzzjcrncl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtrodjtzfn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtbscekxuq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtfqrxfdev.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtyuiudujc.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsadbnyxc.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtfhyjntnh.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtftoayrpq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtaflxqiut.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtnhfuffeq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gttulhpwnf.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtccjyrbcc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtasgpbodx.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtxwqvwsjk.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtgvfgzhcb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtrjooysut.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtuzdugyqy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtssbdxexn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaquewsy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtwigmoaeq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtdckikqcw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtoxwagzab.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtfeaucjyb.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gturljnush.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtjqmupmyx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtgkgltwhh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gteiukugnf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtcnftuzwh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtnctawbtu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtqlqaojpt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtbgjuyjyd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtdqxcybik.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtrpbumvro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtssgyjtfq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtxvfkvese.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtwfkeapzt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtvwjxnbzn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gttcahmxbf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtvfxqkuor.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtjiitjtty.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtqbfyxnit.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtnatpdzbz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtdcgowpiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtzvyzjodn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtzlovrvmx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtszifkzyj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpzczbzja.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtkigcgazd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtmixxfmrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtvwezgqqi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfavuxcfv.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtihsgbrxb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtktisqrhm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtljnjkvqv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtkezxltfj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtykaccvcj.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjpwijcnu.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtdmokjkep.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtrwlxicgi.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtebwifycb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gthjcuhpsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtppmxiawo.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtzbkukfzn.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtekghllve.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtwhungglc.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtogzrcqdx.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtvszdlsuz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gttyakcwfo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtxxaupeqn.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtltlznnzr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtkpuufmoc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtcnjeaevw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnrfevzw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtlrxwscfs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtdsjncrpg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtshtzpdwg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtwlqtwtic.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtecuayjre.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbpeiyovj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtftouvqhy.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfbwzzekg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtebpdjfsw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtjymjqezd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtpvhasbth.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfykwlah.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtpscfuoic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtrmqicety.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtjyeizitn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtjsdowmaj.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtpnqzyxau.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttrsiwuzl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwxezljl.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtqmybfnqv.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttcocvjuy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtmrblqbfv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtwporksgf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtlcljctvo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtjhyosdug.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtqilcfgll.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtquegdpeo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gtguagojcm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtpdxbawwp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtwnicbcbm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtvqqwzrlz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gttblpgcbo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtcdgmsmox.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtfkjxlmbm.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtbcrrltkw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtdnsklsrz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtkouihrlb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtdzhreqve.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwohfumdt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtsplmamgp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtjhxhozfq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeyxmkfq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtzrdlnwop.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtdzeowzds.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gtfhasnqlc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtiniibmfi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtkytcwftb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfacnexq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtadmseeca.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkfuwbvc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdsigjke.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtoitftfmb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtozhjlnbp.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtjfxaxcda.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtghbtdwna.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuxsepba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtuogzpmoa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtxhvbhgyn.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtnkylqlux.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtkllszfal.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtoixepssp.html


<!-- 参考信息 -->