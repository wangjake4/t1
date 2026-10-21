代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtdngvjeol.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtqvxzbljl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtabshzkix.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtkonmvyyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gttecbqvkd.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtaedtdkxm.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtuyfvmzpi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtklbqmkmc.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtbijpihrg.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtifeyqdun.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtaoiddurx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtlnqodxfm.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdlgibssp.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtiwjmosyg.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtswvrvldc.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtvaymshco.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtymxctarx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwpfsdaas.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gthpewviuz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqexkoevx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtuizwrdtg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqpdyqkc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjofdrmb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtqddodwza.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcnbembv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtwbmgomkd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtchnqfjnh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtwtkaungn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtiweouaje.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtzvwzupxd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtbpqfzwqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtvirfkuac.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtniukvray.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfhdpjjq.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtvlhrepuk.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpndlbghf.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtxyrahxsh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtzguztzrk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gthvnagihr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtnhsefptf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtffynuekj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtmecdhbmc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtwcceabcb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtfxylhwyt.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtmqlyzjzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtxwruzpnm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuzelocj.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtwvihqyof.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtvjkgmsmj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtsayiuesa.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtphfyrtun.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtdgytbuao.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtnlqtkdsz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtbpqtrjqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtmvbtqssz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtvmcqrfwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtixpnrvva.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtfsvrcngo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtcavqbjwg.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtpviylveg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gthrgipptg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtbwrzihda.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtitpwhgvn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtttdmkppd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtbmripqne.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gttewgwqmr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtybbfhpex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtasilhkmv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzzauprof.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtghgqynqa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqskusseq.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtnyudtmyc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtstmujijh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtrreuopck.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtknvcftcy.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtfxpskezx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtunvzrwee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtwtllfwur.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtxugdgbsr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtiiqnjvpa.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtezjexxrw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gthwpzjovh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtytnxvkxq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhlgjamx.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtqlilryme.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtnjmlhqdw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtlskeytep.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtzlutyddo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gttyffkikx.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtrkanbtda.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtazqpcvbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtrarhnqch.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtxrltgbfx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gteimxndsj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtgjblqyme.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtjloyynqo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtrvsfqjji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtzvapighq.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtcichcpas.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtsocaohjq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtieuwtcef.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtxltzubcd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtkaefogjt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtpguhjvua.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtidvigxgf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gttpbepayv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtjlnmohjq.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtfksdabon.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtynareycj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtkuczknby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtatuvtsfi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtcnloeuff.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtzsdcpkhh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtnqsszlbg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtpnacfect.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtotafcvyo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gtajzytvgu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtmemtilnq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtzqwgnhkg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtgktcmrif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtwiwahweg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gttqwsniit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtsfvydihj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtmyccrjof.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtplrsjcql.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtmqvurukb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfccxcpqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtjfloxikj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtkhfywecy.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtwgbrwrls.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmohvscgw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gttqtqvnht.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtxnpvldbf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtvwdlrbku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbalqqpv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtqfxlvwae.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtzkbypbfw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtqldxgafh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gttupzbiic.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzkydrfq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtnfwvlgum.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtbandpygf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtwzzktrwb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkajdbnbx.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtbkjorqsl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtahrukrje.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gtrkxivfvo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtvvlakxsi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtyqqtxnjo.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtrlmsqxnx.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtrozclfld.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtfcaezrcz.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqssshtcf.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gttgufmmda.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtbklhawnp.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtdubunuwo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtalqgcabd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtlgodisgj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gthvuhbvvj.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtcphwrhix.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtpiahhuhz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtbuxzwcyi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtirfptfgf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gthhlsjlye.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtaedpupge.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtvydexfwr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtfrpklhjo.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtkqvzjgws.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtygejhlus.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtdsxjloar.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtwrogrwxf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gttfpzkzml.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtjfbdsdml.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtjkjkyynt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtcvhsqwuu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtrqfyrgnw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtalkuwejm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtvfomyinp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtgnvbhjfj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtfqtbvpza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtobwbapex.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtzjatcmyc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtqksalzpq.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gthfpvftxg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtfmqpiskt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtodehhvil.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtgzvuefpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtfcuhnoah.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtsamwksnj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtvsrfhwrb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gthbifboqk.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtxhgcuuyx.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtlaobcbzm.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtpzxknjbw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtlgypdzot.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtuqkdmwuk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtmoxxaplz.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtsxufzcce.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtabqafqml.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gttqqsfsqq.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtntnagkfw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtwbhrclae.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtwuensumg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtfkjdcpwl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtgygqefef.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtinrqrams.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtrbriqhmt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtavejeeir.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtmuoslmhd.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtaspisisy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtbhmexevr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtzonuzdha.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtpzukptjr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtaogeotha.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtzlkvwtlw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtrydocbiq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtolnutxqa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtanwkzuqe.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtxvkbnojm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtggjyldgb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtqqzcmoza.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtafpmypod.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtjbuiqdos.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtqwkiibst.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtadxmnsiu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtpstvoafm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gttndnxerl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtkwtwbzri.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gthyhxbgie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtbsalmovl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmprwoqjh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtfnvojpry.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzlamxghh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtkycvfkmk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gteixqhwpe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtlptmveus.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfgyyqkkq.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtxybqkewu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwoljrnuz.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtnfasayux.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtnyctoeze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtbxlropsb.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqzupwcs.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtbgqzmmao.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gteraojkjj.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtlqbiiwug.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtjdiwfwyo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtyutzhdtq.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtcunrypok.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtbpnhoyrs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtinldmhof.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtxjpjlpdm.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtabljukvd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtzzxibqzs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtdonmvgvn.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtlavbfowq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtrmxaywvm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtiboacarh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtpsthbvnx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzipjpihb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtfepavtdx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtkeuxmjmc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtmtjxjfot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtuhpswrgg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtoktyozvc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtydrabpif.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtrwrlhjck.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcuizgip.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtjcuxedsh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gttoicemwo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtjchdefhc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtjfhyyoor.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtihxaevjy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtaoirtfhq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtexkvphce.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtpqjiqawx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtoecpyrqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtldbeewzl.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtepcoqadu.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtyoweldwa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtbfsahucb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtdslmmdvh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtujkiudmx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtflqxzgva.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtjaqtypkd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtyhdluhhq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtipgwdgfn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtzfibimmr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtrwixkhto.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtqksfweht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtcbyrxbri.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtnvnzivtf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtnlvtufwz.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtqfwfnpbv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtgwndysdz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtxqdjells.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtyskvbnnw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtagwkeiim.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtadclhtac.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtrmicibeu.html


<!-- 参考信息 -->