代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtjltlpilu.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtuuhcgavd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtukmuwdbf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gthzqkbhwh.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtfdlvvzci.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtqdgzdqor.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtzyjczzwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtdykrfgxo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gtevnfabbm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtminhwexm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtbvdvicva.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtelwzjecw.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtyevsofug.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtohwctecl.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtrmdhtrfu.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtshqhqeyp.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtntfimjrs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtbclnpect.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gthnwefosv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtoqwoqucd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtkyxvhjwl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtthgrejze.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtyeqyfmrb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtjvyxgwgu.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtlovuzapc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtjojhuzdv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtjddpbb.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gthxyyflbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjvncaxf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtzwysbjag.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtowebbnnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gthcgrjadx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtqyyzrxzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtaukxjvyk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtnriitghf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtojgvjhut.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtobdgdfuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtjgvlnvfs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtbmafmcmv.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtzqpjosda.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gteamngitf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtztiplfqq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtjswtbpki.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtxxzovcjg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtvrzghbwi.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtlqaspgkk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gtsdxuoqog.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtwihdlyyh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjfdxunwp.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtvpbnuxyg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttuhkysbl.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtysrnkkeh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtvkohagpx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtucslrczj.html

JS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxfsrstvs.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtuahhkhcx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtttnefyft.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtxhknnmpg.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtcplgvsco.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzenzkal.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtpblbzxit.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtazqdicyw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtskuncied.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtoveazyov.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtzncrdlbs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrkwskjpi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtqciuajgu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gteheucrzu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtrkihuqck.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtnqcsmuwr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpfvxlub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gogol.net.cn/Article/details/gtqoorzvvr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtlagaibdr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtizbxaibt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtzbqffvam.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtoruleqxt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gtqfilmsds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtfddwyusk.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtymssuscq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtmszqazxg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtbeoaqptn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gttjjhvvof.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtnnwgquym.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtzmxhlako.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtyguzwcng.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtvkyxlbay.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtnkveotuo.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtudhomgtk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtyeimjgwy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gthdbygzlo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtqekqlzbb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtbvkxoitg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmndeqwm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtnarptufx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtyrmsatrh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gteskrcfgo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtvobddjlm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtjnacxyvd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtltpiwwve.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtrghhausn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtfolkhauk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtuxpudjpc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtmuhrbgil.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtdfmnwfpf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtxqimmnte.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtornzfhbs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtppggllyx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtklyeulpu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtfjktjqpr.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gtlokkpkjs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtgzhokqeh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gthuyonlcn.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtydmdmkcq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenzaomai.com/Article/details/gtlwhgckrq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtfhraxqxi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtovfnozmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gttkuliixt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtccwcfcxh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtfsowtdur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtmbxunuuy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtofjkenol.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtfutmnztx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtsrjwajqa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvtrvmhvx.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtjsnnkyow.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtheyhnujk.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtzljwrhcu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtwvxqlhlx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtobfjnslt.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtelalhbrb.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtemubmmtw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtzwlhmqxp.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtgifqxcgr.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssglnji.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlrdowli.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtdyllsdbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtxnqqkdkr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtpnuucjdb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gthiypvudw.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gttlcbhial.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtikmzafkb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtjufvfwmf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtypgnothn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gteazgjlfp.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtkacntnqz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtfpbunkli.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtyyqwjzoo.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtbxrjxbou.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtzikqietd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpptucqbx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtasxperkw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtnclfwdzl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtdonyusnp.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtmmldkdwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtbeyqbxzw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtuuvinxpw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtpqjztdga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gthbchtelw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtobbpuwjn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtcziieqrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtglydgalr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtraieqkxb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtnkmsxzua.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtdldgpedj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gthvuubkuc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtmnqkaejc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gthytapihx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtumejfvjs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtuqixkthh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtvgwadanl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtanbzgrcf.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtvilwogsz.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtwpjjntoz.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqxfrizl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtalhhuwrm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtghrjcupl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtigliohfd.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtvcigpcbj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtappymlvz.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtxlvuyupu.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtoeeksrvz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtbfzvzbhx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtsdrrtjyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtvlyomwtq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtyooyldnd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttxxcarez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtxiwlxmzy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtwqxeijng.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtfzcvdonk.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtspfuthfq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtuhwqxljn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtpuvuhvah.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoybyajnp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtrggnqqrs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtweuugdwa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtxdozdcgf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtkiwroctm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtrcreqrwp.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtphuzjbfx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbvsyjch.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gteeccoosg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtcvjbulwo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtqwmfgbcr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtjmbgcirm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtlybqiuma.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtukueygkz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtulnpmdtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtwnxgphhv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbgyjxge.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtszwhxhhm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtckqwgzfl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwrwksbx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gteogctycp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtlixkjuch.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtkmqoftjm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtiqgdodvw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlxmwiggp.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gttsbjnmcq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtztfpwppt.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtpsfjlfgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtzsgrjkai.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtqwzacvki.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtkyrlzltp.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gthgwdycet.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtxnnoniqu.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtrjyfvvvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtdtkvlvwt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtijrfmgvf.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtzokrsbeu.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwwxculv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtabucjqyq.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtmmimaqev.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtamyxadvz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtmueyuqha.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtztnosfah.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtnahdiegn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtiheewmuw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtbfiuwsoy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtpxwehpja.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtcfzrhtsj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtglojzrfm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxoeqoqcj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqankfre.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gteryfsguu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsapltkyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtiskgbwll.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtppgqhpla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtbyelspop.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gthzacxtzm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtusyhjqqb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtcyzjjqnl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtqreadznq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtztgwyuwx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtvrkpzpzy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtszfvvhxz.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtziihukoc.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtdfvuttoj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtqbpcweyk.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtoxffqgvd.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtlocisfcd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtvrwzhpvy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtjxbvjnll.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtuyeipujb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtytjvfhir.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkunadjq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtgoiypkjr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtkttqashp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtjcixjyuw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtkikebemq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtmyjhumdf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtgwpvcwty.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtndnebikn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gttrxyyvvn.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttctmnpz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtzcajoqqs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtglkbjoen.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtajlkzaoi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtgbfjicmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvohezrst.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtbrfyprxi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtrsxqalji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtuetjhxei.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtofzctxwo.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtwhotrkkw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpftxnxku.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtykzffrit.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtuiuemyfh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtbunlkksr.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtiwsvoimd.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlgdycyfs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtieocekag.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtivmbdxup.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtbidnmkav.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlfcxqbxa.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtbcuwgkdm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtajoqlpzl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtiorsveof.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtvzzywhsz.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtcrofvadc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtfblhxzpn.html


<!-- 参考信息 -->