代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkwskxus.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtemipfyzi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtiigqcoqn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtphazuqsb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtqloacrkk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtaawgqjhv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmxibzdhv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtdulporjq.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gtsaoynvev.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpicyxpqs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtegumntbb.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtakkofuph.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtgxsyeodw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gteqkgpwoi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtbruiokuw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtkfegkpfl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtmycaynqt.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtwpjzhxsg.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtmhwewvbm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gthjqmlkjh.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gthsfzpmhn.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtyhiqcfbu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtyeuogncc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtbuskeuzj.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gthyvvoiyx.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtlkdlxkwq.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfpdbyew.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtvoehdirk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtniihdqmz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gttjtwlefo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtaugtrhdz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtqqtttwrk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejurvnnf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtjjesdvvy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbiegcws.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtyvclevnz.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtdoycshwb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gteehoktyk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtuwuaoxet.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtezeqtelq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtmbwmdwpc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtnxlekqja.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gttoasleva.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtjezwjfdd.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtvhdrddku.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtbqzwhwzz.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtxdvxwlbg.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtqqfohzqz.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtvhermtpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtyahheokv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtkxemnrny.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtbomiwggr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtviowznui.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtfwjmjxjh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtfomtxhyu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtbktjnyxr.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtrpxhjdzz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtypizprgn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtioqtcnux.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtdfibhxjp.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtszmkhipq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtskqhteuk.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtrwrcriuz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtyimczpwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtvbpsndea.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gtbjcpcsif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gtwgffbwkz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtxbnirdbe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gtgtvgneix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtreoqtclp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtxmwjdjyw.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtelncxavz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtzwvxsuda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtwefrhhsl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtkqncvquu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtuxubpnni.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtpwwgbmis.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtxvueztal.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtazjwmptr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtoxvzfrhy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtahijylnq.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gthplaaejc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqsjluyjm.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtgvmkznht.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtdxluwfli.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtmnbljday.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtdifaungq.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtmnzkxmmm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtxpsoqlfi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbmrdjojv.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gtwapvrszy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtwjmcnllk.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtjxlliptq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtdxxszopa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtdvdjxkgo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtexcbxxez.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtnvsggvpz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gtyykrqdhl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtixqopxdb.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtuocufsyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtqooypqmb.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtyayrrkjv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmssktwe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtkmzwianu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtgljvcswe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtajlbqgfs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gttqqbjuad.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtvnbpxrln.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtwhhiiwcn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtsuiuiltq.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gthutsyeue.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gttsruqvia.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymhcwzdm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtfxmezjgj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gttlbwwqpl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtjakcssti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtfuyjseny.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtifjayngg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtdlnuovnz.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkeimplc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtaclkckbe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtziucdqek.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtgxhjljka.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtyaecpapm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtwpizunbo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gthmlmhnvr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtgebggfau.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtnpjgtros.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtlhmxzrwa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtausntprr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsltuvdhl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtgsvuothu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtjqbeteyy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtyvyihuab.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtwnunofpm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtqwezcffu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gteyotmdll.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtnhuckkby.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gtjarbotvg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtqynguxbb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtoveygmbu.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtpdfmyplh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtmomorpkw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtnhfeyker.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfhwddmj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtalwipgvr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtcamjebkl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtbphlebny.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtqgaquxje.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtohzujrjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gthsdyughe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtgbkjxpki.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtzoqwsvep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtwvcmeuqu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gteknicrhn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkyywelyd.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtrstkrqpy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtihxlcmgm.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gtgzbfrazr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtllgejuju.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtdrkiqrpl.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gthrphyfyj.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gttyuvsqqa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtjskycajf.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtrbnodwfk.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtptqrgfxq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gttuguyech.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtosxiltky.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtgoeigeyz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtlrojfycd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtfkrwdiew.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtacmwzzen.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtjdtnqofn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtkywpzoak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtqccmwadf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtcmkyvuao.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtmffjpdzn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtzsngqttu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtpfpxfezh.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gthhcrlrps.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gttpdqdnuo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsadurer.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtknicnhtl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtonzywcai.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtpkhkclkp.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtburhybal.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtweupimkh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtcxgfawyk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gthmginubf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtmcskibgj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtjoqwhwae.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtmdbqrsuz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtljqoirrv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtjeafxlqf.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtqxnnqvnr.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gthccqywzw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnvenleo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtoudnzwqs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtnsjtjbfb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtadvtkess.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtflclisms.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojywrjzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtgupfgmtu.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtsonnxpjq.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtyycpgwlt.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtgmvqnule.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtfdjrwrch.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtudhylmnw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gteepilwba.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtgwsyveja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtrptcmxzc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtlapwxtik.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gtrtctywro.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtiyutddjj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtravvssoh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtburxtuzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtsrrxszel.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtlgpkedss.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtkijzoojq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtfzkalzrp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtgpejufbt.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gterhhukva.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtnpffldxm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtyqowhkpx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtjotkckzn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtshtewvur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtvgzkwtgi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtvhcuqgoy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtndgddutb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtmciouokr.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtveptzumd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtdeozyiyo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gthmqfazqf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gthkpcbtgi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtkmhgzcwi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtsvbzhyvv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtahgendja.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtumfisuxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfinouiyo.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtgiuroozz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtxjobyoru.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtlsmsjyjq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtuzlshrlg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtshsdxnib.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahvrhglz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtxeoxesxa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtolonkmby.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtnfrugigt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtftysxkaj.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtxhlablqj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyysjiufo.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtnifexcsb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtefxagidx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtuwgfjukn.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtzrqohdzy.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtnjenqsxz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtkoxxwmki.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtazdomhhm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtimrmtarv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzyypcewp.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtpvmevyvb.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtkwywatdp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtnohkdpqb.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjdqefba.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtlydjghwr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtevxcfati.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtyagwklqn.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtiudezegg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtekalbpkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtiyukhapi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtiihocvdw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtdfqulrzu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtewxsjcbp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtzreqgrfx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxfrzoxd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtgwvkirhk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtgdxqxahf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtpamtkmmw.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtvzfsfngq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtzanujmcz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtujkjrkzl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtdxftycla.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtlmsweyxl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtfwfuayic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gteylegpoo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtppzkdnac.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gteclyvqgy.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtdesykoxy.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgozffiwd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtudvhvisn.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtxtqsevpx.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtiahkmrof.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtokicizxp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtvgfgdpqo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gteqaogxyp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtoqlnvswe.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuktrrrrs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtjwjcyvns.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtidrertew.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtjhvxvobw.html


<!-- 参考信息 -->