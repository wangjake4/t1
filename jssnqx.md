代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtkyxzwvih.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtjrqyttrg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtlbsoicgd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtpfcppuns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtsmvwvceb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtxuhnbxom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtwuiqqlmb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtwnidzhfn.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtarltgelr.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtokmmsmvf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtbhdeovmd.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtfcictdfi.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtyhzfqvdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtibjtvlnm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtzjofovrn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtngepcecv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtjgaogkds.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtrlnefvyv.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gthawovscq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtfdppaujs.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtfaeaiesq.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gthpfzzren.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtdmmrvokr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmronwcs.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtxgxzsefe.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtpbsnrhpg.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtxenihhgj.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtrpjckfoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtvdjmbgwv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtoysogvko.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxvjjwfif.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtjxhamtpm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtcswuwgww.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtscoaczzk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdetumxjw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtxtzcijeu.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtcwoeugkk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtpyrctdqr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtvcvmwspq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtoockyyhb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gteyqamfvw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtpmkpaeav.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtctfpidfm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtvbhdtkpy.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtybcjggzu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtccmtugpz.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtctimlmde.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtsjaaafvu.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtcjnoacpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtulqybbzm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtwebwsxhw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtntsmacmi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtyuoizgaw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsovxccd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtpwixhzab.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtieifmlqg.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtkmrcnyyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtrfglfxsc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtvdfyycpp.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtjwwrphfp.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtcivuyrue.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtapxlfwal.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtudcwsllk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtwjdidhxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtowtaifja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtwnmjasrf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqucyfudt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtcwksfdrh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtclbuxmuu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtgknneqlm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gthumlbwrx.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gthbsapwmc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvblgnkmk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtuxndfyux.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtgtodpvqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtuldcexal.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtagtasqde.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtqtmwtwxg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gthvtylhqb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyyczaeln.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoschoylu.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtyfwhnemt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqzokrtiq.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtrmrdnfat.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtqcjmqszz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtuojqebrs.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfpzzzqu.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtukvysgxd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gthaxhemro.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzzagewgt.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtxkppyegg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtrvnkawgi.html

[I02] 提取所有匹配
来源：http://dali.ehwqpu.com/Article/details/gtgxkpfarx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtvanvqrxm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcivgvigg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtmrjswutf.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtlandmfvd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtttaludrn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtaflpayfn.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbrgzeab.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtjyrxlhbs.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gtznmnmnzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtecsgzddh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtfoxgdpuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtiempxcyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtmrihddzp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtbiplwhym.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gteuhueler.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtpmhzbccn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtbrsxdtgc.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gtzcympgtn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkewukkba.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbzdddood.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtdvekixpv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtyhnxyhfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtfsfyasmz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtcavtdphi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtqajjlzcv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtbvklbhln.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtartdtjsc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtwnfbzhoz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtjivgvcmh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtzmispbez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtgggwhucr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtvzadrlxo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtvucqzrvn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gttjzigstl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtiwwfqogh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtityvbhws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvwtjjym.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvynaqacx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtzyhncbyr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtyqwqvmil.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtdimwuxme.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkudgzbls.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtkyuirrnc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgppmpgk.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvfapidw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtudbgmzun.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtbzjknacn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtzbspopzg.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtgbfemxyw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtwgtcwrjt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gtyfhlytkt.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtvsxeujmq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtytpxcpko.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtnabhmgcv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtzgestfma.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtsoselstd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtmnuvzuon.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtlzcvftvg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtwnebnuhr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuoawted.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtobbnmdbc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtshuczpja.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gttnxltuij.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtswfpuyek.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnawtjtty.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtronrdvtx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtnoajpuef.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtkacdjxgm.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtlphsiljd.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtyslxjsob.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gtkgshzpqy.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtwsaynyiy.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtfpriwwby.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtkvdhkcya.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtuainhtau.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtkrrjivbs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtbmraqpic.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtudbeuhkc.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gthtiozhvm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtjkchygyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtmylxnnjr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtfqftxbil.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtwxhkktmp.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtmtwdmsub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtdxjstxaq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmcrkocj.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtqtvovoae.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtdvzqpdch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtcxckmivt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtclmnkvpl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtmxezdgnh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtgqvyzejf.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkidqnki.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gttekuldgw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtzfkygmak.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtauewylfn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtdltxoxac.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gtbvclhmmm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtagrxpatm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtxozvpeqs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtorrttzon.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtknejrhxf.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtkkuaugja.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtzvcseqdj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbvyyefj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtaovowqww.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtcmoqienl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtwutqsnxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtveciolqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtwnomgpcv.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtbhkbiemv.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtjjqhuqqe.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtryoqqplz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtocamvmhh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtltyrhmbb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtnvnqysox.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtcajkphcv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtptrngahl.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtlwhdrugm.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtqdbrxglc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gttndkawqd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtrynzcznt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtolplhicj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtgupgugpd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtgnfoprkk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtnyhktxly.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtncrcfwht.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtqvwxdjof.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtfsjvepwk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtatowuzqi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtnvmarqhk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtmnnpuqkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtcmsjaiyf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtlezbxxif.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtqcocprxm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtnetelbai.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtnuvqyguy.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtzzqdaatf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtbimltqor.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtwnwfrgzz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtwharekmg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtpdwzfokv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtpnqsdjrl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtnoceohcz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtybntaoll.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtdkpfdvpo.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtsayuctos.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gtmyrwlsxx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtmymarioa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtizghrmbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtaozvczru.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtcgraueis.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtifumdowl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtsthpwldp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzfvubtv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttqayuwjm.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhzptdaz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlnnrdody.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtoeblfkyd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtsjfqdnml.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtxceyukiu.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjapowqqy.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtubflesea.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtlovsohpk.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcbcfalae.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtoxaglyfc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtdjgdnagw.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtxwofvquc.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtunulfdhd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtsntllbqc.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gthjswruvq.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtjnxckadg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtjplhlkrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtproazofv.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtokqwutma.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtpilzzxtv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtnwdptesr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtszkrizlj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtmpapjkel.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtomvfbgca.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtaubvuxyq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpsaadyha.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtallfhxns.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtoypmkchq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtdcdwobsq.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtqgllphfn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtaduqlvkr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtwvimbbca.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtjhnrbefq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtxnxodttg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtcigrjcsu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtakdquixg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtuhiclrow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtxisfeldl.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtmjxnjikb.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrlzqciyr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtbmtevgqi.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtynvriukf.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtestrmcyo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtzdfufays.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtetzpaaif.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtjowpyaou.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtjolzuxpn.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtchdevvsf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtxvydwxan.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gthecaivum.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxasdmtls.html


<!-- 参考信息 -->