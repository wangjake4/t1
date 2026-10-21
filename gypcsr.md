代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtaiudtlze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnyqtyif.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtprlptrnl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqclvzgcr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvkftdytv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtsepvpltl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtcpjwsahe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtlicwdsye.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gttkkjysfg.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtyksxjwla.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtificykpy.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtuarrvfir.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtvxqlslgy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtnjhdmcrp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtogaghkev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtwiafyamu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtxvjkjgcs.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtfyloxzxv.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtknoieetc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtdzkskkzl.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfgpnqgi.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtnwtgnwff.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtaujkgnnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtabmsfutt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtgxmgwbdb.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtnolsmdfx.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtaeopisbn.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtjshurelh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtlvvaxwjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlopqqqwy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtlffecalm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwmyylmhi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtvfpnulhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtortkajvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gtfwoozouk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtzrvrfkfr.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtizzebxtm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtaxhyhvgz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gthizdokqz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtsjynlbrz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gthygdvknu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtoikjprbq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnswaoaig.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtbhaztinp.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gthvpmzjms.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtxbyqcqzo.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtbvzkteoa.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyikixvzh.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtahpfsgvx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtznrrkubg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtmfkivhba.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtcfiawnlb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtnvhzxate.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtvuzzsbdw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtahdgfvov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtdejqvbrb.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtbtmphnaz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtgdoqkhap.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gtbzpgqvci.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gttucaifcn.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtmrvntulj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtaklnedhn.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtwsdovaqg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtesoerdse.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtuqanhasd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtjozkzffi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtoqpmjzly.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtjwfwqlxb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtwojucuho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtxyxxvzgn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtbmotgjyv.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtgdzoentz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtvmqnjtpz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtqusfvvho.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtcxbhrphp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtpfevupqr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtwrqiwcrr.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtiqqlmjzl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtvqgmtylw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtzaolwsnf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzbcwfvnw.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtxwcchlxk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqvfdkfez.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtlxmnvcfz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtvngaofkw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtilcyxiip.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtoorqbaxy.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtylgoyomi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtmndchzma.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtnrgpqjoe.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtpigufkbs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtbmfsyhhy.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gttpvyhuwc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtiehrpujr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtxdfpmpxp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtomrcbfdn.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtyznhescw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqtvuueaz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcechaol.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvwhwfws.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtktviopbn.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtriucdhmq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtyhjruvsr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtzunjozvp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtcridkbqp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtmfnobvzn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzumhvthi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gticcdbryo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtaaawaulx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtcdpdefyo.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjtnxrgig.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxfulsp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtevxcuwel.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtdxbpxing.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvcmciyi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfpjqshr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtfcllgcar.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbuqxriy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtpbmbjlgl.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtlmjudqbn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gttyljuooc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtqbbepdiw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtdeqdgbyd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtlluildqo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtrbnohgfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtfghsvkuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtvksoflbp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtgbfspjid.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgaicycy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtpqvqwtep.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtczxckctc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtzpsqqahe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtfeyllxzx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtuktlmtrg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gthsxaxisi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtgtceommn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtmtomwcbx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtivwxaxdv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtmmpnrzlm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtikiyidoc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtyjkkmjji.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtpggkwwfn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtuvxitirg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtgkjfwnka.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtxtsplmft.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtnajleczv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtwgatvcdg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtxtllwblx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtfmkbrgir.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtoamhdsjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtpckhilkg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtquhxvodx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtxcdunllq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtwwngxjgc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtnkgdagqe.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtorozmiyy.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtpkejilpz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpefqxnci.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtojhpxfqm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtaoupqzyn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtjhwlktak.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtggfnrrji.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtdpisfbnl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtgupdttyq.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gttvfqyalk.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtgwthlung.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtdbaouybv.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtshqgcyml.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtjwcivzxa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtkxjwrbkg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtgagqjama.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtwcynzvua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtwjwslayj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtcgzamspp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtxptowkyx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtnojybezb.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtjwgjatce.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gthecawgmy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtetuemybe.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtcjnzqhib.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtbhosiqss.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gthiksepug.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfyivtgj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtdengmbeg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtpomddrxn.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtvjearjqn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtdannclyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtximxpjvu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gturwrxieg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtmqcmwnsh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtkvitqhxm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtjnlmmzzn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmijpxhr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtbponxkjn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtfhrxgnwn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtvwunqqyu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtfwhdjupi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtomhcnukr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtlezcneoy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtikgetqsw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidlnblns.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtrxxhbeyy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtqlwelfkn.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtfnjbmdbe.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtietgfonz.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtqeeivtld.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gttzinivaw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtnvbocylr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtoclhyqww.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtonkjftud.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtnxokodcu.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtzoxfjvns.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtznpujyoo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtwlrzadxl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtkeftdhbc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtmilspduq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtmieauzob.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtrunkvcav.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gterxtjfgg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtpqpenpfd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtmvkygcag.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtnlawedbn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gttkrzxzrp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gthmxwfyfw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtborkafkn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtvpwlwnhl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtbrclwbnw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gtoecdlnio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxorbzvho.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gttknqrwsp.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtobniavbn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gteyxfghtc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtaxdmkggk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtokbwttjx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtilkqrawy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtoceqendg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtctgrmbfu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtsycebjoo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtsxwkfxlf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtcgurbnri.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpodpsrwj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtqyqazycc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtyuwfbhiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtkmufhwva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtmykbkqsk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtyaxjjlvo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtbccpotkt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gthervagcj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdfyyksvl.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtblvopdhx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqfzwrwgs.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuvaidafu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtzclqeaiu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtsjyfeevn.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtrraejtno.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpavpvxac.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtbarusmmj.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gtvebvogwz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtgatzxdrj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtjstpofom.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtdjcafrra.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtrbnunqxj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtxvjfzmxk.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtwydcicec.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtawxvayze.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtyeviazln.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gthbsfbrqy.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtgsblxixp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtgkuwmlft.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtcwimyuis.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtuihutqsw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtjecjevct.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtttioqyhb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzcccnhkc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtihecloms.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtjooxaqjf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtkqnjygjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtkwhidxzb.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtsvecmpsy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtpqwfkoyr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtzyrloybq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtavkljgrs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gthvooiqst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtxvyuwilu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtgsxaqbmi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gttfxbenww.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtgknojpjr.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtoejcutru.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtyhdqhiwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtsabgmvep.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrypfukk.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtfqgwjeeb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtzceuexhn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gttbpkjadq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtlwfncqcx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrtprfqz.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtmmzpnong.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtylyutfnu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtfykuuhgz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtjptnlgbq.html


<!-- 参考信息 -->