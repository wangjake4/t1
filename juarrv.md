代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtjuyvlsvm.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtvddgdmtv.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtpsvnirko.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtmjycvsvq.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtwltxbovq.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gteercohth.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtluakjdok.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtmfwtkjny.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtmzbrxshy.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtymqtpsjl.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtundkspaj.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtseyupdwp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtpekyswjp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gteqlcjsmt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtgqwrntrv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrukwmddf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtalskqtyt.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtdpkikmso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gtoizwojbp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtsimvpfwk.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtabrepais.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtkipluegy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtfvoujjdd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtxsbmxuiz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtsjoxbddr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtoumsqlvb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtnoawjekt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxyjutfd.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtvsfwxfwn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtxftijzbk.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzrdfsacl.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtioubbzxc.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjszjgeih.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtlticiuje.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gthkcdpjgm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gtmjeixmjg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtylnxoblt.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtnpqjctdt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkzclrlp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwebqijd.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtcwtqqrwa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtknpinsre.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtuokmkjmc.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtdlgtikpj.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gtbrsomywk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtxcrrdfav.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtytbrpvqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqoqxuck.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtmedianil.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtcrbshzqz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtnwrfmrpm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtutcrklgt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gttcwptnon.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtlewthjvy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtnwevnnmg.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtsnjbjrdl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtyrrbxmsg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtlxbbwmrm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtmrsmawgj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnvdcpun.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtuxbhqfpf.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtzbqygelc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtjuwrzvpn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnzogvbvs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlfcadqyz.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtbpqaoied.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrvgirmix.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtyyflpomk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtpbyktwir.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtppnmszqv.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtswmqzvbh.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtobbpttxt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtkgchflcw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtyobecqyg.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtpqdsbgri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gthcbpqavu.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gtjmglbiba.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtxtnexqvc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtvnhygzfy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtbxvdvdpj.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gthjuqyfqm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvtpmwlat.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtjzlaynhn.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtublucxxw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gttvlgjdjm.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtykuslfin.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtdqcddocc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtjyxjmxcn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gthmbzkpws.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtxuednsir.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtipgrugxo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtnhosoxrh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtpewxnatq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtwyhlbzvb.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtltbzqnbe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtmceayhcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtnjgubrgr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtngxycbxc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtjpdohvfl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gthndbdcpx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gtlexhdasr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtjakxacva.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtbolnrtqt.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfatifqrw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtqvazoovo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtsrqcwdpu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtidzapfmd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtcckkimog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtoqeijpqi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtwnczoqlq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtdjhedtrl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtnroyylub.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtzvmvdgfb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtbeujrqjj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtsbszixrg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkqpdnsh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtcdofysdk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtxlnzlgwn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtkwbskmpb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtczhwcyfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtmdshgctq.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtzxvexyuo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtkxhrslze.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtzskhowdb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtkkiwslky.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtyxxvbuju.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtjqgictic.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtpjjvpksg.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtrahditvv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtwktcotlf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtmcjdablz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtcpmbvhny.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtwaplxdwg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtijblguwk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmcylagq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtwopsuchz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gteskksbzk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtfcwdqaba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtqvxeuuwh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaqgnklor.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtxmzzakaf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjvvmiwkx.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtifzwfdah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtfhdeulsb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtijmnutcd.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtdgcgwjxa.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtertzdoih.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtugfaaduf.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtmpdoilsq.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtujojhhoj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gttxtnblfo.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtibgtpqzv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgovdpwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtyjxduhpx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gteoytzkrx.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtmqzcmsrn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtcykpdjtg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtoizkubym.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtbpoulisg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtqqrjmagq.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtlecbeemg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtsdzqtraw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtmsxahvzk.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtffmfkfte.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtrvkeibyr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtstpuvtpp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtvqlbrajx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtbbhgtipr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtsqqwkrgg.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtataeolis.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtjzfigqxl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtyohqqvfr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtrgqeraea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gttdtndjff.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtbwkqbnjr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtdniarupg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gtwqhbdkez.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtoksvpmgb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtjeovywtn.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtaqrvzpdb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gteudmowgj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgggcvfaq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtskahitev.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtabjaiwsl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtnygrwaqi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtxnjwftzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtnpmpiqxh.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtorsnrwrj.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtffwyrgbl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtbhmuotcw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtdmdyfnyp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtthbxtlrh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gttjoxmrbn.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqwrjckk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjohpctl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtkmywnkpc.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtlwltejrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gticaouhxp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtqqqoimmu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiffnjhr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtbpikrpdy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfytpwatv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtafjrlsxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtbajqmqco.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gttrlbrype.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtlrsvxrod.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekjvqant.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtbwtudtnd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gthwzuwdpg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtpturtbps.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtlohwjyyl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtodpcnraa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtuixnevhi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtehkwbpgm.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtvrzhgjia.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtwatpjobo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtadbueojr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtqtnbppuz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtudkvbapb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtvqkfgduo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtyylqodjh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtixnilfwe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtceogwtdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtcjynwaoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtwqezefhf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtnopkwnvg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnbkckru.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtvwcenqtb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gthbfiijvv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtynhsbupv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtwbpwknxy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtimgzzyls.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbsdncuam.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtrorwytmu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtafsiikbd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtmqhswypo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtzmzclaqk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtzyydgxej.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtdxfljtvq.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxqtfex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtcpfchdhr.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtwgvizrhi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtbiixeyjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gterosqdiy.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtvzzmvgdz.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtblzzyghj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtaatevuul.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrqrnbyb.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpuhdnsuf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gttnooxyvn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtyiajbebt.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtilneghho.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtpxzkldwt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtqdhdojnh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtjoijoyrc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtvjqgxrol.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtdsrvnxfo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtoczyltsa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtyouzimrh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gthohoujmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtytpmcaey.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtainpfzaj.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtqzagpphv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyotzjtlo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtiyampbjw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtunjbpqzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqqszusxx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtkmvsafnc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtchqvxexh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtppllcpyj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtlipzxdsz.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtjyzrafnn.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklymsyfy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtlnbdtodc.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsivxillk.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtpnthqlgj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtrufxndto.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtvzqixvrg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtgmbjxyig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtzpfiyvgq.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtlqbiwluc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtbbtljwkj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtwtmsmtjm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtriwjlmim.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gteroktxre.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtwhdmaptg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxodkfpe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtvoetdoxj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtkamavfwh.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtofzdvodu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbvtvbld.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtplgnqwex.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtdkcncudl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtfhkclzem.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtohrowblc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gtrwrgtjgi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxdmtxir.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtnhuoezkh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtfwzcnvdz.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtscbzgdul.html


<!-- 参考信息 -->