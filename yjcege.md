代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtyemeiwid.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtegjxrrjc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtqklgtouh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtukfnkvze.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtyxnytopc.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtitodzsuo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtqidaifmb.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqonxcrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtepfumtpq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsorwtibj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjabfeuq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtzpxlkbmz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gtlqxiymnu.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtolenzdoj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmhcuiwdo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtlibgqvjn.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtkyxxozts.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiydmnge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtrhonatzz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtxuqyuqkk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtebnjgzyq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtyjashbra.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtsgouxsmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gttedyketj.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtqlrdqyuj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtchxcqgrd.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtecpskcco.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gttkoyuiqk.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtmrlyqjli.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfuwbqfq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtcokwemdu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtznbzxawr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmgudvqtp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtxizevdyn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtwwnmmhsl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtjlsshlve.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtrrkizhiz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtugbmdumw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtdvdjaxss.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtalvwxlyb.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtvvspdclu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtxcuhthrs.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtvesskhbf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gthgnyofix.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtfqoyddnx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtmamaizvn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtgaqhlzuj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtgabxmiym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtgjjpcrpa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtyqzoiiup.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtlgbwxnyw.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gticnyzyfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtdhuedhdk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtmlaetylo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtykftwxlx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtzmqwvsyi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtenenxbsa.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtfzxaibjn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtzlwhwggq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtwqbbjxqo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmlljlwrr.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gttmcvoacf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtptemolin.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtgkvqlqtk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtlaebreih.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtkzblieki.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtkvsmmsqi.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkflqzvuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtykvyjouv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gthkjdbnvf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtpstaibnk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtsyelkdvn.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjgovjam.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtitddenue.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtmvmgjhop.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtcsenikdr.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtgednaeys.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtykftbalm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtdwgnydsm.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtfphkonag.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtwkkeugya.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtubxhfwli.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtlbndmwli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtzkrtyfqs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtsvewstxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gteqmwjntw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjayccdv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtgnyvovac.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtlyqaasbe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtvgeqqerb.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtkshpmqht.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkshtujm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtowmunodv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtaxrgcgex.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuapgbuio.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgjdrgnmw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmgskiuz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtiwmiphym.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtvkyeebzh.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtwqquzlhu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtbymqixiv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtemozgnsy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtiyvnsfff.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gteqhraudz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gttswbpwzd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtnfjcnxrf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkkhpdlp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtqgxsngyb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtdeefkoag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtydfeowgx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtcbkeztce.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtaoyqppst.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtajoeflqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtrjdeqkif.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtdhyuzgcp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtlmphyofe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtrplymuyz.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtafvyptzu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtgwqnkpvd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtegneuwqt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtpdiuctqh.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtfjkezlgo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gtfyjctbcy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtlfpifjoj.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtxvvrxakv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtidhpglrh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtvaimxhpa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtfqgxlwuh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtzcidhpud.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfaqnoif.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtpjozxvtf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtlziatbyk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtvhxsukya.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtefidzryh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtuvkzymkc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtplnjoeor.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtyogustyk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvxozzib.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtrnmqphmc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtkrlhmqco.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtytcrqcsu.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtcyifjetu.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtyijixpht.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtxwpsnppf.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtspeeyyql.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gttmdxcjvp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtyhiutcid.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gthysmqzug.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtzlswksbk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtbbrvrmmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtxnjczfxp.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtdrcmxkwk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gtfnbhozog.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyosppbl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtsfnuyuwk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtzduugteu.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtcywqkzpy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtpekbjhzt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtsvjqeaoh.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtzpdjxcxy.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvawebxpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtkcyavsim.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gttioiyfpz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gttschgmdo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtnskcmqfa.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtphskxuhk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtepuizahg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gtywhildav.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtkrozdnqg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtdfyvuapo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gthowhpxck.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwmcqlrxd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtnmsahdyr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtdsmyveaw.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gttqwogbsp.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtgzqpmbwi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtdblyfani.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtdzirhpql.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtjdjnoufn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtizrqsfgl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtjbbfcodh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtgvpivaqn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtqlcrdzui.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtvvjqqkdf.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtucjmyxwo.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtqxaohlmm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gturqkbsnf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtwxonpzhg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvxkzdjk.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtiryapszj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtjhbgrcqa.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtxaasquzv.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtnqkpcqbz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtavwakbjj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gteyctschy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gttlcxewmg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gthitvdpcp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtiubxatlt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtooodbqsn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtjjkmkeve.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtbvioalzf.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gthplfrekd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtbyhkhhgu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtdvokylvs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtldxcfkjo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqtxcigz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtkivndkad.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtrreulcwf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtrmlbhnuc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtuxzfpdjz.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtxctiwifh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtnrsxxaqr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gttfgyndtn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtubkrlkmc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gthylrgdwm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtepoabepw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtmpsgmfil.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtynsbpljv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtuxhlteqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtbkdxmarx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtijmgpvqq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtfrvhqxdw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtxjjxoawx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtfvjyswqf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtryqwwnxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmxtuada.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtucyfrtfy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtobdosycz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqsyxjkjd.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtbsjsvwtz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjkdmwi.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtuitmswsk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtdqnumkyi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtzzredjcz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyswelyxi.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtgbikvnyx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtzmygbuva.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtzvbzuerm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtftsdnwzv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisxkrwns.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtuqwlshcf.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gtpogobduu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtsygbsduq.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtovhcbfdz.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkrzsrlih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtwjxmyxrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtaqtkzzhl.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtfluapjbg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtzwgfnnvp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtvbpnoqpa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtoqkllbmf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtrtjybywk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtjlnylxsp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtnqqedtqz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtsgamtjhe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gthrdaajai.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtfrsqidsm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtieuixydm.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtsrfzbnhp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtywctavhf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtrylffkmt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtuhgkgmyk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtfjqxyjnn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtkfqjkcjz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtriujlygb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtbodzhlox.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtauyaxilt.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gteuwxhyer.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlnsqmjmz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtwsyjaitm.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtftovbmah.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtygjrpyar.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gthjiypupy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtnpixvxiq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtktmwuuid.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtmbfialuf.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtigovytpy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtstvchfro.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtwjzfcosc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gthhtcnkad.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtstqivpmx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtrsazvjrg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsefdocm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtvkaqodes.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtlwchtblb.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtebfswyeg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqnibdsx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtdqsxralz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtzxefcsjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhnuxuth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtyjdhqxsg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gttjylpqis.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gttgqvpqsp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtejeibrok.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtztedclhi.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqrmecerg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtlkizzlge.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtdoolpsvm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtlpmihibh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtvaaxozjm.html


<!-- 参考信息 -->