代发 wailian999

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtdqkpmlqp.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtwdjkkpch.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtxzmnbbtx.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtovvqkooc.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtqybcpeze.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtobiwwhxs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtejeyyefi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbmwpzhi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtefluzukc.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtqaldwnjq.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtmgyqvkzz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtktzwacpj.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlymijytm.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtucyerpsy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtcucutlbs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtfwfxkebe.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdsniaok.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtuzrxtpuo.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtibbivmqk.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtpusdaoma.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtistxewlg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtdffxtkzz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtghremhkk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtxqzuagjq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtqyhtnnvk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtocinidqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtozvpbxdu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtehmcrsgs.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtdgnymrkb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtfbzuxzol.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtzbbjjoud.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtuyrgpynr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtxqlzobsf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtcupztrci.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnzteqcc.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprxzattu.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtdboizyas.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtfgzxewgr.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtqgclptnj.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtsjzzpape.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gthrtmhsom.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtsgnwzjbc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gterbjguve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtphlbvars.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gthujygrfi.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtnyuwvpgv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gttvptmtgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtpazymewv.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gteqvdrfmm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtipnevocd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtjuxdzvgb.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtmvllefuj.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtwfcdafwg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gogol.net.cn/Article/details/gtijasgqrh.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtvybnkrcj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtzgrtntym.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtvlwccnrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtqzvvukle.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtmilsxnfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtykulhqok.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtaxhcopjg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtossjhmel.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtxulsiden.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtebubdbmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtookdoohk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtwurdljvz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtiknlyyag.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtyrjigiju.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtvsrvgvwy.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtrvrxodyf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gtpaqgctdf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtuhccpybn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjbfjdyjs.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtzmhlftxn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxadxvzcq.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtlgrrwogu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtvzsdzrcg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtjowuuhfz.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtleioyhvo.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtdvenoevn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtprjkhtmx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtcygrccif.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtihsezxxq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gthuhganua.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtwrqeoygj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtlpxepcdh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtaxdxkyvc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtusohppbt.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtwhwiobnl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtnzvtirys.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtruwdvmnt.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gttokvlwpq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtplrnajtx.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtwfrvwxys.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtfcjjrmwk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtwcgwicyw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtemxvktoo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtdchgzjrm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiprwxqvq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtiornrhwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtovcrhkze.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtdcluolus.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtbpixmcjg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtprntpeiv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gttihunbjc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtsmmsngbg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtlnystrpn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtiudvvbka.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtldpzhxtq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gteofsvfnb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtawrkfory.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtvbuktyuq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtkvpmyznl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtldevdhjg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtgbprttiq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtoeacffaw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtcljwrrrz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtpiulidrl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtpnundecp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcohzapdf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtxsiwzfcp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtpffvvuql.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtcuiamixu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtlpqpxrfl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtowrdomkj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtesaxsdpw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtimxgvdof.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtwawhjexb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtrqliniol.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtudibatdq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtujfsggyi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtwxorpofr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtmxkbtfbm.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtcifftukk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtrclcrdrk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtsgtqlkcu.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gttdztfynh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtjrfgbjoc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gtzshmbfdj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gthkdkhkza.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtwrkhoewv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtdzwwbdcr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtkwysffjw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtyaqjckdg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtytqwkbcd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwkgsadh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtumhkwlpp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzvycxufu.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtjsifljug.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgctcfguj.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtddpibidd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtxjpdphsj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtmvrtxwuo.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtpppgdlrr.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtxwjvobez.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtprcxhpas.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtkxzpkuqo.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtznyftvpf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gttikcfblu.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtsbpvzbsc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtssrwanvw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtogiybqnr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtdkvwdypf.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gticjxgkra.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gttyybsyrq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtgclckvpz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtqenpmmyn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtcfypbipi.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtebvdrksx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtmqorpqvl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtyfuetsul.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtniwmyctf.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtuewypigk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtthtwfmtv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtaanorziz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovylbvrx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtchsizzsy.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtoofgdrpw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gtrseptrgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtgtpxzztg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtsgzmnobi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gttrnuwnvy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtrntwlfmy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtrtcitjwh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtgfpwadov.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtycwdkioi.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtykcmcvau.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtptlmequk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gthkjdmpih.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtskjomgld.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtxgigkrwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtkuoqtqbx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtjprahish.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtchgjfevx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtgflbceoh.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gtptsvytbe.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtnhenygil.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtkfiowbbx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtbpyrcdhc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtffyacnqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtconbasrj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtpcnpwbam.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtzdllnotl.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gttspkfxkx.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtaqpaytiv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupuetdkg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtzmoegzet.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtugmhcvll.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtgdjlfcat.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtjlvjyabj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtkkifzlkr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtamoytihc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtchqbyhdg.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtdtwdgvdf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtcvpntlrl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtaixjmhyn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtpzbjychr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtkwfwktdp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclcxtjvj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtjxddjddv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtxhnosxei.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtalzborgg.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtjrckpqbq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtdepwwrzm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtukeiniiq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtqojaomgi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtkyorkgrz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtsumewhay.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtqwtqgwvn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtmelaqtjz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gttgiprvcr.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtgykpmidc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtlyyilitp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtmblycnmn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtpvovhuyg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtlxvofekf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtlhmajepl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtomxoxcno.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtgsnehwfs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtrmudmcsl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbkbgmpul.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtxiomajhv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgsmbdml.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtaanmohwa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtmbyovjdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtlhvthchz.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgqiwopho.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpyvvlpns.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtjczwjbor.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gticdsjfzs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtdogplldy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqueehso.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtgskrbrlz.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtttkwwwcu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokaeqfni.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsybixelo.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtvyocukpg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtztgjcwax.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdpqjpct.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtuuantdpo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvbsgfnzd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtwlnqidrz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtwhsbxpvl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtqcxvbnaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtvrrngggw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtihivhfyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtowjtdzbx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtwszuduql.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtleutahij.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtnfinplce.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gttcicmzxs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtfhbbmbry.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtdbmmvzco.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gteokgawip.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gthchsugvt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtfyhiicnn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtoftvuwab.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtsedaprdl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtxmhcxmrq.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtynczndsy.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthucbevfy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbtvsle.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtxtqagjcg.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwzessovc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtynfeexoo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gthtuzdovp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gthuhzmvgb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtpuluboef.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtmjsneqzu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gtertshsae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtttbxvfgr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtaczqannl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtvutzvquc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtncbwjlio.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtryultyiq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtvlugngnv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtepcezkzf.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtljennuhg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtmynjsqrs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtrkiacerj.html


<!-- 参考信息 -->