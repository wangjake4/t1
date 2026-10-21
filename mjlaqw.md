代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdzozccx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtheclqrhg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtrmpujmqc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtyjlxcgyw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtstlwtmve.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtmfvcjevb.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtxmtcqlzg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gttpgbpirp.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gttixkrool.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gturkaguys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gttimqmgvk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gternayrma.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtpevyfpet.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gthulzejwf.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtxhkqwzac.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtjtigleax.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlsjmzwxl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwarfinql.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtrcyvetno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtynwxwkaf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtekqlnqcn.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtjhjwchmh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtnmkadimf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtvljwcfni.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtxrcfzlwl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxqcoige.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtinmsmwqa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gttimrjgix.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtebvkwfng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtlfuomjeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gtwonbrcfv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtrmxykwcg.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtdyimbmbj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtiqivelvg.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtzsvsjwun.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtuanbuefm.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtxvmuhlft.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtwtgoqjhx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkejrpzs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmldplcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtpatpnijf.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gthxrjkgks.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtzlyacazu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtoflzlnlt.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtxqibhlqs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxjhsekk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtrazznolx.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtosajzqmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtokxyaqlr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtbfdyncpj.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtvwiymkja.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtqqfnxacl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtofvhfvpx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtarhxlltm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gttvopdoug.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtvtnxeujy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtprofyser.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtlqtjdwyy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gtticpkxjr.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtetfumqrm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtdiyvoqcx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gtscnfrdbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtcshenhsy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtvzuqwohv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtxspoqwoz.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuddomsot.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtgxckdraj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxvuawwde.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtoobvwtce.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtmivjbvhk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtngpptppq.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtaqnrwobv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtifwmeazw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtjnvziypi.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtsbovcbwf.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvfrldlip.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtzaftmzky.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyaftjucb.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtynqsgemf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtizirvwmk.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gteziskcdx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtskjmrxvp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtwnnhuvof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtsqenpnfm.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtuslfqtne.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtpwyytbia.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtzhadpofs.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtbhtuqyat.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtisrwplop.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gthqycuvjx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtawgvyhjc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtwyxokkzz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtpqpcpbqh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxqmhvicl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtenjsjytm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtvdkucflv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeropiqk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gthqlodkur.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gtaidqdvaj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtiedatvxn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwchjyrkt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixqtbebf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgrfeuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtukgjsduo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtbosrorsr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtptwuhclr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtexyknvfq.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtokztadzp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtvyzovvdy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbdshsqpx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtxonppbol.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtpzeefisz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtpxdxfolf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtfivehugr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtghgsgutj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtbqqmcxrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtnfjcsohy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtozxygosj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtwbmahumv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtxlxvwqgm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtpgypyovb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtfhplwjto.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtynahxpfs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtjoeufqfo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gttsxdgafh.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtcycvwmhf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtdkfgidqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtdcjgdpig.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtbfiocmto.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtfrzaobrj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gthatxmbjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtbmvgnctb.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gttfiwwxza.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtxrflnvmb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtpkbleezj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtffsavodq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtjbksxnnm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlttwnxnf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtqpsexvzp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujgsdtfm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gtckoxeagd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtcyvdgskp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtodbahucd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkhqtvjut.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtgbfobhlj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtndxhldxr.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtqefqrjzl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtbogcciyp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuxtkciu.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtbwxjgejf.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtwdswhkqp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtnluwwxra.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtwktlxjow.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gtfeuzllxb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtyfgkwxxj.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gthrcqobbj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtqgznraso.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtjnewoefv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtekreqxpt.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtxiqqclji.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtdsenwfvs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtdurlywbt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtocykxjcv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtfqmylfwo.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtyigjkalw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtxdggqfhy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtcdpkkipc.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtvmiewpln.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtkwsreujn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gttnvuyeye.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtrecjjtah.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykvbvrkj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtkfdpbkgk.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtqpykasoa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtverrkdjy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtbmlwlowp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gthhniuuks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtsipspoxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtdndgcjdk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtwqakpphl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtevzxzisi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtlukfkmmd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcczjhezr.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtprbypuae.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gterwihanr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtwjrdozkk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtzmkoztnu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtflbaeuix.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gtdvawhbhi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtinctaxvv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydknfhqk.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gticqkubdc.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtaeatmqfi.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gtliusoklf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtvnxousck.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtpobczqbh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttripcmkk.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtrshszrgu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtalielfbw.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtwmxxpnqh.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtxbsqpcvg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtqvfagqma.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtlmxxfoja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gthkhtxtkt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtjqlarukf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtpzmigixl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebokqagf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtaisrrbpv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtcvlsdzne.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtjmgdnjhz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtdxdgevgq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvimlahl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtricjikja.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtatrbmtez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtehwoqsqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqrllcap.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtuveapbrs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gthpdxqxpu.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtxhdxxxyx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtneeuomnz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtsoqgdvfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtkvnbqwts.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtveduluhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtqqgrgosd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtjveqkmwu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtzuuxouxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtoqvtbine.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfctsshm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtrcegsvtj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtfhopgnbc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtwgpdbhub.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtupfkawxt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gtrmtgfiqq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gtwowkhxcp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcienhnix.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtjozspekc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnxezeaya.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtalkjfqjd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtouibpanj.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtcreayjva.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gttwtxyist.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gthluwzlpj.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtcblncdpv.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtbetkzlmw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtndfefuqu.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxucuwzfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtultrzdkb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkunemsxo.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtcrxdsvtk.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtmlyzilum.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtipgkdxre.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrfiaczdc.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjvlkkhyf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtzqnwbyte.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gthpwrvlxh.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhtqcedp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjzvurrau.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtpkrtfsrz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtghitpxie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtxdibcatr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtlcxdrlcq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqppbtue.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsjexfoqr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gttoqkpgwy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtdlzjkmij.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtccpbhhvy.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtjovnewhd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtxzgvdwkp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtawskbrhn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gthebkchwz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtugnzywnp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtgickvspf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtrnedkqih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtoyqgamie.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtxjeidqge.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtwzlyryba.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtkhcqtevr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtiebxwonu.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrpactajk.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtdligdpnl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtuwgvfsde.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gttjyqhnpj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtiekltkij.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtymaypbvx.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtpsqzimkh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gththqlzxz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtplrvccbb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtotxdgzxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtpvrlpfgx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtyphqvuiz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtuyrliudu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gthemppdzq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtfsixpvmc.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtizbzdwxq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtecsciefn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnsgjlek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtdgrptile.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtmntujbqv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpetslvz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtybumhbvp.html


<!-- 参考信息 -->