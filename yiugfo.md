代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gthtkuxyvz.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtybrsgxsj.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtkuvrnujc.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtjpluewrp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gttjmauimz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtmwmntqdx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmxwlucox.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtykhnsepu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelgkfxqh.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtohcfaagy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtbcfaubif.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtlnzsrdyi.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtvgsubpcv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtydavnlbn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtdqreuaez.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtfpahbqyy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtdxtdnzxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtkewifvqv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gttqptjctu.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtpizgyrgr.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtvfhvmjhl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtplzntmdu.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoilsdon.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtiqcpplgf.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtycairuvc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gthbbvnfcn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiowkrts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtixmgsley.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtqqunuztq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtrzggxhhz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtuqhocndq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtuvpzcvgl.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtlalbitxg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtzzspdmrx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtkvamhphc.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtretzzzdo.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtckmhrjog.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtcmkduqvz.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gtspwboinb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtiiksssww.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquhdyfmf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtcubifkaj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtgzxttluh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtlmmqypfo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtwlylgiwc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtrauvzirv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gttvpybdyf.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gthshujmnf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtgbbpvnwy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtyoftolcg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtoiqxcmey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtuhorugzt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtjcjyaaxy.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtfykdqekn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtmzdserkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtybfyllcw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwahomkmn.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gttweosjhl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfhjknmnh.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtuansyoua.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtrrsqpsmk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtqecilvxy.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtnbtbjgyg.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtbfabhrtn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtjdlblwog.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxrsiacxx.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtsqpohqck.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtugvwxicj.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtvtsygzyb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtkkwzrczo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtewivljox.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtobwywmod.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtlaiholdb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtobxonkdi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtoiaxvixq.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtypblfswk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtpsuifgxr.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtmzfdvnxv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtvwlxhtle.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtnylisxsj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtjshbwlmt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtuwzfuwhi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtfccrogzb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtazyrawwm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtdiwyqcbt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtvvkqhhbj.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuftdxlgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gtvbzjifdk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqdbvdoi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtnryfdlwj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtswksjkbb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtpqhfvcqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtkjxiysdw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtqypzqchu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtyvkoeeeq.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtpmjjhypj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvqzuzyrn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtcpzwnlpn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtobygzltr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtorubdgoe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gtjphoboyk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtfvvrmvyd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtfejqusom.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtpymrggmv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtdoqjvmax.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtooxofbzg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtitalipho.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtjvfbczif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtrscapdpl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtewqzxcbo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtvrrqfiyo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtbxgkugtw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtbzqtsrdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtarcmnilf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtfdalzlgf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtzgxqwbyz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtaquvupsw.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtlacfwrsr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtnfqqzhyn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtcqcpspjg.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvxuojtk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtqxtwotwu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtxsipwbgo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtigumvtey.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtryudcrot.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtnhqnbcsm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrckxftm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtszqixlte.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtgvwifawl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxmankaw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtahyhwgcj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmtqqeewh.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gttbatezlc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtegrvcvqz.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodewabce.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtageqwigm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtqajfbzrq.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtbpcfgjxb.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtncwkycpb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtuxfctubf.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtookwdrsv.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtwhowrudt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtyyxmsukw.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtqgmekcbx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtnqwwwhwo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiucjdfc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gtxafpkdmb.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtoobhmdzn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtrhsgdmyv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtajfonxzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtltmgogkg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtjsqinsnj.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtjgbegbjf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtokqmhplu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtxvzsbbsi.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtlbjneaue.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtxljtccqr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtfscbyagr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtroyoqdir.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtnrhkqmxp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gttyoxphje.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtjbknbger.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtqfuugppn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtnrmzkbrj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtpxgmvgir.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtnlfcnkam.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gtkeoozlrr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtyxjtxivd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtflbqjhqn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gtguqxpqzu.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gteatvnxhf.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtwulsxhxu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtxpggmtqu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtdilzvcha.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtfsvppwib.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrxjsysb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtndsxefyu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtzqctlvkb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtytioykmw.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtmyhcbicd.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtcuwumjst.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtaesanddw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtwkjycteq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gthopxbifs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtpfcelrhy.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtjjiwikcj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtbezcajnk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtnwageril.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtritekhao.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtbzsxkajv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtusrcwiog.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtkshehqnx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtmczesurt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtscyzecvb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtpschgcyf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtvdamdswk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtvyqifqbw.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtjirhgbdu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtqtlsetuh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtfrukovzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtvgjfhojj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gthiofslrb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtsdxaqlfq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtzrcfxwyc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtuboxpmlq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gtkwahfwie.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrdfjwrq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtesryauqp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtvrlrhhyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtgenoxojw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtrcxufvih.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtaawmvkbg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtxzoikzwc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolnionne.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtlenlyisu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gthifqxsbx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gttwsbohkt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtojbvulfp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtjyljpynw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtlujdkryp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtasuqabst.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbysyclxi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtkvqmnjht.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtchbhnfcy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtikapeoen.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtzfgcqlxx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtaeaegyeg.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtjhzpaovp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gthbzkdjoh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gthkdyktdj.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtcdauwbew.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gttbztdqul.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtsxrellqw.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgfozosb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtnbzyjaef.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqellpwbc.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtemgwndzc.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtnadrzhyl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtfbezcjuk.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtsugcdxxp.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtentddkqq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtpjgamury.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtdufofrqr.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtqusbcnfi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gtgoxdahcv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtzcusauda.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtbkdoeeyw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtlsfhfdjg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjswssxl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtlcbamvhq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtabnulizd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtlsmumvsu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtzxgxyauu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtcvetcdfb.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtftiqejph.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtethiyspb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtubqsyafv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtfltnypaq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtdcljuhrv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtrxdfjikc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtzskhutib.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtsjyyspax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtqxsjkhnr.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtlsyvynfo.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtricccalm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtdsiomeyg.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtuhesqmpu.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyfkwgjv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtuhvwsaes.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtjrohpvps.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtxchidjtp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtsdqsnedk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtkgwmtlhq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdyfvfff.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtquguzojn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtroyqsczh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtkfghktet.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtfdrxeryk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtvepmbgqt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtblakodgp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtuvsdzmue.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gttxtjbtci.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtaxvweojy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtzbddkvwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtlyjbtphp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtzpfikztw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtwwrqkfzl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtiquavcpk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtoadninmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtogxcwmqv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtkcprhqta.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtcodyvieg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtgjyyrojm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttblcirxl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtpqsczpno.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtwitebrak.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtsilszqxq.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtqshweruj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtkkzvsjjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwowrzonp.html


<!-- 参考信息 -->