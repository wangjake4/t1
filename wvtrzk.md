代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtuplovzde.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtnzqrbcqd.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtwcjhkpek.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtwvxevwnt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtysaxlcvl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gthvymbhwf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtlniqxhcp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqqbbzkqt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtooyedgpl.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtdedfapqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtibwrfegg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtsjrtukeg.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtrxxdhvvv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtxlcgjebn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtxmuvaqmm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtovrlqrjq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtdmowaxch.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtcyvasxdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtscjeeawh.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtwxcnpbyu.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtsmobavkq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtmrjpcguu.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtozyviews.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtntvkwsfc.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtvdjjetrx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gteejkwjdp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtbnmlnmvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtcrbjfodn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtmyoubwir.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtmihntyfn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtmdwmvoyp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtgzrttlrf.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtjdxmumee.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtshroukka.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtwvfgnsol.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtzchujtse.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtndvamuto.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtmtdihnjn.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gtaqczmxiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtvxmrjxbq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtejddyswh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtlxzjcose.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhtptrua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtlcxsxcmj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtjipizczp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gttanifjyg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtcnmwfkpc.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtwxzyrdvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtjhfkzgyu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtkgptppaz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtznixgrrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtbipqskpv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtopfrfkhh.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtupkxawrl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzcaytpa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtmdkudyqt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzigtycee.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gthetkkyno.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtibhhcdyd.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtghbjetxg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtauauqkfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtpgremnsd.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthvprrceq.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtbkkwqipq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gthnxgbwjf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtbfefhcxy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gteyswvctx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtbiggtdgs.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyehqrxm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqffxtlj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gtgzinzitu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtuaqkxvae.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtkmxtdggj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtombfbgvz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtibmsjdkf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtkwgmmrlw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gthqgiayct.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtfhdpwnlq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtoechdubm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtezwicwtw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtfrugxthz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfvefshv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtjfcuijre.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjentflhh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtfwpmyojm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtsuzpkays.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gteocoyabo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpsqbacz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtflpvczig.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtwoztuhwq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtofaekebo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtlonfvuys.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtfhpympkq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpwmkzsp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtbegordsj.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtqccslaiu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gthohnqxwg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gthkazoxjg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtlioniqtz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtcabesskb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gthfmthjsk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gterquhobx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gttindaytz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtdpacphbu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtbhrsqivf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtcfpjrdxt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gtlpsfsiht.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtbqpocwdi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtpdnbpwku.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuorkcmk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtpdgbetnw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtcyhacfeq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtkavtnzbh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtpbpxnrxr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtalmfdibb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtwvyrskgg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtbddvqpnv.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtwtgbzpht.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtpigzlhsg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtzfppmjns.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtjgycrojv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtjefnbocb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtxehrcshg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtudnndkaw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtsfqcmmeu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtmrncjlwb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtbhspmlsb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtxgnmsmod.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtjrcjudqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gthrbdgkkd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzunyzjj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsilfzpb.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtucypozke.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdhoiohee.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtehduubsa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtxcqaejgv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtgtvqpptk.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtrqgrokzl.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtrpcwebdr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtlgwttmlw.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtxcqeumwt.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamzysgxd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtoojrllae.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtzkcejdek.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojogcpvj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtlyhxlknq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtsqcyzdaz.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtfuohabop.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtnnwtflxm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpsibwhe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtafrundps.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtknoxjtro.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtcrbmuvun.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtitnfwtjn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gtsxkmtkbl.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtrehfwspx.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtukyvgntq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtzeozdqnq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtdlipsyif.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtffmbahtg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shangyingyoupin.top/Article/details/gtzuybbzgk.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gtvuixuaun.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtjftzadbx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtqhegeeja.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gttxjvokui.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtfmkcgdsv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtgsygmekn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtbhlrerzm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtykfgssqq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtfzzognpb.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtlbwtslqo.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtaguigpsp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtptknxktc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtqdxlrulz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtjejtzmsk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqdopyes.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtxianhyvb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtmxguuozn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtliuxljdz.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtezeqinhy.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtyxlvwdvb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtwsrzdaof.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjbxarca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtsvszqpcm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtfwffpbkj.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gtrztvwpkn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtpqvwnmqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmdgogqw.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtrtjlhkri.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtvehduuzv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtquqhknik.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtyxjebjsh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtdvaglqlj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtshauadzc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtpnoxdzfb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtsaiqjfkh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gttuoouijb.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtqyhscsrm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtwzojtrhl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtojrbjdau.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtorboubbv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtrlrgaiiy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtryfzlevn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtlankrvul.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtcznabsgw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtaqjwabgt.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpibyxyri.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtgaqeascu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtsjlfzjzo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtnyjncjzz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtbxwjhudb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtsoxgabjh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtpyndmjmd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtewhziquw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtrexadqfu.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtgonrfzre.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtjnekwrkn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtsghgwdpx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtpwzzlncg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtjtgkgfgu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtdcwuysgi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtdxpwyuxt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtntdtznge.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtxsgujbsn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwlzhyyjv.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtfsgoyjrz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrfdbqvuj.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtjerqyyac.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtrrlyjvdk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtdrelfhqc.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtieayrboz.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtlovkpgkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gteynqhcpm.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpyfbaxt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtoqzhkxql.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtejzrgyqf.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtcjwtqmdo.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtxqnhbkvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtbuedhycp.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtohephffo.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtzsetxvyj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtlfhtkbrm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtdxsuzkdi.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqvyolysw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtjjzptdhb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gtuvwzruat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gttacsrzwq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtbkzokaax.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtqdqmfnff.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoothehtw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtrcsjlzqv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtzptaghgr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyujixihj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtnarfaixf.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gtthqrsrfa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtydlecbfs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gthgbxnuno.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtshodftcn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtrpyrfxas.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtfpdqowvi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gthqjaohnf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtsrsfaupl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtwybsjygs.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtwvlthpxf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gttaqpqklw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtquogvdtk.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtvoreyqwh.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gteqrcobsg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtyfmysiyo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtwifnupso.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtxiahljtk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtjajjqqoh.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtwzrqezjl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gttgvbjokb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtwqqjazph.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtmlntvlhk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtwamlfnxw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtrhgqcmcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtkzlqihci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gthfzvvctd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtwzggvcqd.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtqubvjwvr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacycvths.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtwkbjeztt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gticxbrtfc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtponahtjn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtxahunrqt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtyonixuer.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtaqeqizzg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtvklbsoff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtdawhrgzt.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gteawncyxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtnakaffqv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtlsmderdc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtieiddtow.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtztfcvfdc.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtmxrczezq.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxsvjtwt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtwrojudrn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjevyjoxy.html


<!-- 参考信息 -->