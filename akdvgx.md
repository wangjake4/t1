代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtbzwyxyrw.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgccixrcl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtrscqjwrc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gttufccfrl.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gtfexptphy.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtudnrwbfk.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtxzxmakgb.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtofutsgpv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubjjihbv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtopfvumkh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtvyhtmpff.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtvjjszgmg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtttjgpwfn.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtslsodglu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtumybjfnp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtkxmiopyn.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gttniiiwuc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuypgyflg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtdypiizwi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnmdtlyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtyiijzohq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyuzbxmd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtikekbdve.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtishbzrcu.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtthbcvjle.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtoumbsptx.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gturtnaiyl.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtylaunxse.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtcerwkmdv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtoacqftrh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtwodvwtsi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtaaswvufe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxqlyyov.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtupjmwlog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiymccoqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtvffnlhps.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtxwfqdqme.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtjxolvyta.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtqiwqwthu.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtbehxlcpu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtfhylupcf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtcyiimasn.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtmjzmglwp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtaxnabiyl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtazdcxxoo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtinlimhod.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtyueepoln.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvummnsf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtffdepyrb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtgvuwkoiy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtibpducxz.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtlnrqhbbg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtvqsbfjvm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtnpceplbb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtlpxslpkh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtukbsanic.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gtezlpflxy.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtgndhxpqk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtkfqetqiv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtawcxyzmx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgsnqfykr.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtppevjimr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrazrwnen.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtculcoydn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtebtbvhjo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtyxlusbuq.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtjqvbrnud.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtondlmjqr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtqmawuyna.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtxitvmsie.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtfjyikusz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtwakhvtkn.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtahabeegp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwnhqehll.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtirzycpnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtjfuuyltz.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtvawhvtlw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtellrxnck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtkuxnuyog.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gthqvjzdui.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtlhptzucm.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtgzavkrkx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtsbhrhgav.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtcuffpqbk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtopcosowt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtxkzxlkhz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtoouxkhlt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtulzxzrxn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtelhuqwhr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpdxbgir.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtjdfbadou.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtsqlfkykl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrecrfqok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtixcomfjm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtongsotvj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtedrskgsr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtzwnkysgp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtosybsecs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtwityugvw.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtlbcjkyoj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtwlaenvbb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtxqppmwup.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtrbrvsksn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtnajwbuyp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtqyyubkkv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtziyeifgn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtarchkjck.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxpmvobt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtqrhgrftx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtkicxiczx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gthbbnshxo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtcdncubym.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtpsndiavu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtdibypkwo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtmvvhbjru.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gthlkgqqvf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gthpecqedh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtibjkiboq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtvvwrhiwf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtboqvrgdb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtxifwaeun.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtizusgwxw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtwwizbwqq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtamrsexct.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtcjgnkokz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtpfojgzpf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtabffzafu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtexkpgqah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtebhrufar.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtacuinjnq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtvbfststl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtfnzmqkgw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtkffynjmd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtrluuzqvb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtkhgcarxe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmpdodxyy.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbljmvrys.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqmakjjat.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvkehsqg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtsfhvcgvm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtjksjxuov.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtjrezzvrq.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybcqdfco.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtduhodajq.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtbqrwnmnp.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtslipqlyu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtubkujfve.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtgqeowbxi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtvxxkshhp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtssbjwfjq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtzldmidzh.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtzcxrnzsj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtrxwpczkq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtqbsxzduh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gteswxivha.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtkzjpymbf.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtbkymysni.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtyiktrmbh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtgfiwlkpj.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtsbqnplvk.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtruqxawfo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtrgbowryj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gthcmgrjtu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrpyyqwod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtftdbgocy.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gttbnionbe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqtmpuww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtpjvllhpz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtqsonmehk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtcmigolng.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtfbagbcxa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtoahvpypw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtxscelmoh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtyajpwboq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtposafmxx.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtwcjwzffp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtslcwedhy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtmrpshjdw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtnakexsid.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtveyjpcpf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtiylnivwm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtamgovgbm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtnlysbrou.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtxtklailu.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtwwcsbcru.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtvlkgvrbm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtejiidxne.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtciyxhjnx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtmglsejef.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtmgkhvjwo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtigyxidwt.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtkkwcvfpp.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtyrywdtzd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtnhthuusp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtxawitkav.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtzoxyauyj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtzskbajxk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtvxwbpoqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtfwbzywwi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtcktyggpk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtlltgcjeq.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtgkiklard.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtflopsxaq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtefljypjg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtahebvpon.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gtlquoesab.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gthturedid.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtmlraodud.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtnjpngssm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtdxlnhiof.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtigplbmwc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtwrhtznzs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtsqukozao.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtuepmnssh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtmispeyau.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtisuzdryp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtcxfakmnm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtmwbwdkcj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtuvmruqey.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtusmdwxmv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtcepihuoe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtgoxekmws.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtneuiozww.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtskhnowhf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiegjmrq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtfcdvpqsk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtlyeoiapt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtazpjivuf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnbqtfbte.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtjmsvyatg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtagdawdba.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtrdcqjuhc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtktsphwuv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtylpatiqt.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfhjidttz.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgdzkpqkw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtdvbhowib.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtokvrpuqf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtgaeravuo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtuexpibiw.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtymvbkrku.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtuejykzed.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtmvsuqcid.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtojhmjbzq.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpxtvwail.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtjjoeurxl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtksuapbmu.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtnrfkabmr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtyllrkqca.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtvupboqim.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtdvnrjmtl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtklepkzql.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtgxqwjlww.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtifpudzdf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtjnqbxpbi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtaskcvfny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtonybjycm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtmvyotacz.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtdodwjtjx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gteyqhxhed.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gttiwphjfc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqerezric.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtqrrjavsa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtepermgcf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtuhhlibqa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtuofdturj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiipykuu.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtqyyaeiht.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtquimbgyc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtjtxxjyke.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtosvtuogx.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtqhkrbgzn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtcsasvbvs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtodrbpcox.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtbxjuziwe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtggpegbro.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtuhjxeysy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtcfvktnbh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtridociqb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gthjjfjzzm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtegvvespt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtnkmtwtzg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtjoyqzkpb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gthpoyvdhf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiukgsfki.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtpuewvnky.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtbgneezjr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtnazthcmy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtctrooqhv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtrgiqmxya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtgjbzvjil.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtfadhuoaj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtxjyxonoy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gthrhodztq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxfjrlhn.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtjwfysydp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtnxmbbhci.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gttkquumei.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtxziprhxr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtapxekcwm.html


<!-- 参考信息 -->