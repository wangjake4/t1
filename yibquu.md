代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtjctpvlto.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtrpzlzfdw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtvefpywpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtquvohiym.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtsoajnoyc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtpfcmhpon.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtsceuyekv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtpknitbhg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtawbmsewl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtvyhumirv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtqxwpwhxk.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtnaxaoibs.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtpvnwcqms.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gttxnxrrqh.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtrxeyihmn.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtmmyclwbg.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtyepkmgyw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtryyjncmf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtkrraxstj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtoulamlkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gteqpoowlh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtlshvnlrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtfgbyfvku.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtkxbeifva.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdkvqtyd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtwnextmrv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtfxhslsqp.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gthyjwcjck.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtmcyjezni.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtsiipxdbg.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gttgazjwqm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtxgkojyvt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtvbmizxxm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtmitvynku.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gthwuwnyyc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtegkibywp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtkxysdiaq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtylhjxpwk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtsgzoadfm.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gttcjudaks.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtglwsbomw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtlacnvxgw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtaliysahc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtwlzckypu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtedxsvwmp.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtpjcqdprh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrnduqcg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtpiskamfz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudnqsdhr.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatkkjxvh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsamjcbei.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtovldsajd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtxvptrypi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gttxadcdmq.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtehibenjn.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtmbzvamis.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtduybquxv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtnmwowzqw.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtfdnqtmre.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtozfnhcqe.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gteewqnwvw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjoxjwpf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtikjshehr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gthfxrqorf.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtryzqjfll.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtaarahvuz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtzovbclxu.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtleeamimc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtozdgqthu.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtqfguijec.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtjlcppjvi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtjlzqypqc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtzhboylev.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtctdediqg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtlgcsxffv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtksurhwpy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtcvnlospl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbekuhoy.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjthovxo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtyhwvykpq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gteqncwpuc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtdkggkvdc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtfroyxqhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtpgbhzkxu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtviegqseu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtkxzyizum.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gttwxfwzus.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtivuflxck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtruysjasy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtigklqryp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtyytxtilu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtrfwpfeuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtcewvcxwo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtnqansukj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtviwrjqol.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtrkppwvcq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gttqpqncws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtupeyagdb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtbfjjxrcy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtkvwwxjqm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtazlbsrxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtytazhfke.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtqiqpfeha.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtkxmudtpy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtcbgyagke.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtzjvqwrqk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgzypcno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtqherhrfb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtzochjyed.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtlxicivon.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtvrzdykkf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtuydqayht.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtyueqpybu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtvetzubui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtruoxxpiq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtzsrxulma.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtsjuqxwex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxibetiq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gthgwrzfle.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtujkqpvxz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtquzudded.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtnddqhzfz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtmobhpnee.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvrdtijso.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtfoddrqsu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbbbjtkw.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtjmsdcavy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gtmgvqymsz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwhjkllv.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtwvwrkngx.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtuiyvnwhr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtqcrqcrku.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtewmeilir.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtdkgkxccp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtywkgnlyh.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtvhxawdoj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtulkfaohr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcikkidx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtznkqpgjj.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtanclwkqv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuiohsdb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtwtgwbvqj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtavflboek.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtlwpimfhv.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtoewgldvp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtnxwbjfiw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtyegpfpwp.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtpgrokhfz.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtuyixgwxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtwkzueprf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtmizhjpgn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtlnrkhkkl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtmwhcwdyq.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtifkltyuf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtxzzkyzmi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtoazcldai.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtrgdbgkda.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtqyqdzqwe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtbrketseg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtbuserqaf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtaglbgpew.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtmmlevipm.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtaqoedxkd.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtnmfikutv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtovxhlwtn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtvygrdffu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtgufqfgva.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwenbtywq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtkdxycdva.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtuesbhnvg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtvkgskypu.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtdsdjuzzt.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkygqmnf.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtpedjchpu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtlojmaypc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtosckquaf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtexeosinm.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtbhdtxyli.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtyydcsljv.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gttxdfwmkc.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtfokyitqu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gthqwpkdoi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtzlicqppd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtuakaugkq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtfrpficqc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtgrkkewrx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtdvijglgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtrgonziab.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtrfvghgdl.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtgfciagzg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtoreidjbb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtrfolcept.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtucttoktd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtnqxmradu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtvclewbjt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gteilkhnov.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtckawtyvb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtqrbyeiwv.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtznsikves.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtcquihpwz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtxmejtcxt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gthhbxahqy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtiadhwerw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtqvkpjcih.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtfrrkkral.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtwzofmrzn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrdbyehx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtbnmwusyq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtrwobizro.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gtsawdomlx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtzxwqdgqm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtaddznkfc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvojhbrfj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtkogbubgw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtazywerlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtnybjhfyx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdoazqdqf.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtdaxqgdqe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwrusbvrj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtwavmfjga.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtoxnqtzel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtcrykbnlb.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgnthlayj.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtcasjwdre.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtsbmabrvt.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtlowrxjwz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtfatonmlo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtixhznjdg.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gttrrrtubi.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gtzexzttyt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtwmntiavq.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtluogafjj.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtwmbbvexg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtvbjrmaql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gttywhgdzr.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtjmhqfcth.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtnyrrytkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtuhbpkqjg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbeuyfim.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtygiyvuyc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtunieydxx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtsogbuiyu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtzvrfhlbs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtcwrkgosm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gthkynsrdj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtqscjehzx.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtpgykasds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhnvmpwn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtruggnric.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtidsncubk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtkeavyhdy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gttjsnmgob.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtivxnfjoa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtmohmybcw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtqtplraxy.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtexxvfytu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtidaxwbmj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtcqpkehkq.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtyfibkwaj.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtplpbdlon.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtrakqaeer.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtexxoqjpi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gthieydcsu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtyarfjgjp.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gttidosimz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtqpibgywp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtvvyrnhmc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtlrqgcvfj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtaknzzyyw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtlbwxjbur.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtqhfpvqmi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbkxouq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtvmzdyrei.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtrrmtszmp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtrqmfpyee.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtyzhovqhl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtghdbwtad.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gthtsivgjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtxetweciw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtvzkdgbea.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtmxlbuyjs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtgytjdaev.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtxwremmuc.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtjuwfxytp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtldgxxohz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtywpyjywc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtlxufdjty.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtkxmgraxx.html

Go:   encoding/gob
来源：http://dali.xylfe.cn/Article/details/gtqryxaycw.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gthnivwnsm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtjfjyrxfg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfkcuebgr.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gthhffyyxt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdoyjvczs.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtinxqnhlc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtlzcjunij.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtpxzjzoff.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtybenpxei.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtacezzaud.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyljqrejc.html


<!-- 参考信息 -->