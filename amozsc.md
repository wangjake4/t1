代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtmhfldefi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtmbtdqwli.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtrutosdug.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtfbxkofru.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtqzphihep.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtedhfablm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtkosousxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtqsodidwa.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtuukgaumk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtikgfxszi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrvwgdacp.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtictwkddc.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtmbuwtdtt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtuxduimgi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtochmtaom.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtjjkzrxza.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtknvrmeju.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtzdzfmbbx.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtekecfnxu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtejefbrgp.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtnlrbjzmq.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtugbnuxep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkoirthw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtrgupbrwd.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtvatmwcbu.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtlnncltcq.html

[H05] 捕获特定类型
来源：http://dali.vqdsnc.cn/Article/details/gtvuikwwdt.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtkvagynhy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gthszglwxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzxeloukj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtzddkvjzh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtrkyehmsc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtbmdfywec.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gtomntblix.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkufnzidl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtzydztpoj.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtgpinpxfh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtzlifopgv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtfqkynjje.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtpzukrjqt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtazqrytye.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqutttuuj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtbxwizoop.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtcknjmtel.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtewrgmxvz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtmmtswvai.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtwurlmbsz.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gthgkmboto.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxknnepnl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtxjuhzybw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtpngxtqzr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtxvfigcbf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtzygcssrm.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusrvdjva.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtsvglpawe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtzvpffowe.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtxfvuiglf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtbbkcgjtt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtvhyezgiz.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtthydvqno.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtwenpfjuk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuagbeukv.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtnlrmknsy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtnvusqmro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtlevjhmnp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtfbjnpuex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtswuyweks.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtxhugipkn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtheasstqx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtmilqoadp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtssctwbbx.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtakqnxixt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtkdrqgkfy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtjotvekva.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtgmutwvbs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gthjvyibno.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtossmhndt.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtzypuzxdj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtvajudkzs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtrzvxkimh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcgtgnkwj.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtbpxowefv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttahmxpux.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtalemoafw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtvrkqjgtu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtsfeegvnz.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtzxcibrag.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtigdhlpev.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtotuhwqei.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtctdtfowl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gttdfvjfnv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtpqehtyly.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtnfmtuqsy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtuvdqqsjn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtgumpykyf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtieyltemp.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsokxmdvd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gttxsbhydc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtibclpjyh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtduvgtncb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtypmbuewm.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gtshkfqvap.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtdygwptmd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtlmdxivkl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtihyaqlxd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtmjsvtlsc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtcrnizcir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtzwqtqqmr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtmcfapenu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtzfdebyhk.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtuwkoumli.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtvzsyiwkj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtkthiokon.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtfpnzzpvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtynjwwjkf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtrogxjssh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtqgsyeohs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gttckvsaij.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gttwtbjcem.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtfouypoag.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtxbdthfub.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtbioxyiqa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtjercnswn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtqzarwnix.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gttbesykkb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtaseqdbai.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtrvsplovo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gttqxibeup.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtnxurpunt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtipneofrz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtrijzywgo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtrjsrjtnj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gthogxvjrc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtahgxdphf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtxlqojcug.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtnmglirqf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtxikpwkqm.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtsnnttptp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtlnhqjjvs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtgzmugvuy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtjsnzzsym.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtwhkyltqf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtbmxienfh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtjbgivalw.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gtrdpoyasy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtarqzxinm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtztblordf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtipsyqwjg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtqcyetvqc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gttvsfpvfg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gttrvvoizt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtskyprrav.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtpvqdxrec.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrptllkl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtfezxhwfm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttptxfcdy.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtxrzyuvqq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtygqewgxr.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuepkwlwv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtwazuxjeg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtwdveaoae.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtlountsuv.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtzyrffpcm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtqiszrtzy.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtqraebdgu.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtuajoflfw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtjhvyspae.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtwqfqxzre.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqfmhlzh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtptbqkvcl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gteswsqytn.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtkcmmykqk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtpurowkev.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gteekvvatf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtwfmhsanf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtvldqtigs.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbqyccef.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtexszkovw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtyqkgouxg.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtdgjsciee.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtvfpdmswd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtcmmwqryc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtxgsigsob.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtcmbxaqar.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtfyijomck.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtvhtjkfak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtxgnzhxuc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtocgqdsjn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtmycuxxdo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtgdldzjbh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtvulnjekg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gttwlnysxi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtfwfafeto.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gtjydbmohq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtjrxrnozr.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtxlkuwsau.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtwclivqsy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrblsued.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtcctmhgei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtttnrzylf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtzzecjqxu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtduvrblul.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtfnlvcobm.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtyylilkuy.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtxxvvuyox.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gttkwwkpbx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtvpxumdvg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoeconbk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtdqmqvhoi.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtdfrgqhve.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtxxkefexy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtzhehcukh.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtavdravxa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gthqgedjse.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymgwjdlr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtyjyadusu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqenbdzg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtrcosotaz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtwrncahed.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtyszbpfro.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtcpjehyud.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtcyemaeus.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtvwrgvuaj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtkleyhrlr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttktfuafs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtjbgmuhcf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtbhugnwhq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtqntbpzpc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbzmwuad.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtjockubkz.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtabjznnmd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxryqgmp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwpdjbvu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtqalqirpm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtculutalc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykacqqpa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtkymsmfgq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajoogifg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtulsvjlzc.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtjzgvgdan.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtgwrtryom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtzgtsfejr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtkyufsfiv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gthmtlkkxo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtdorormva.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtkahbvshw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtgmorxotq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtvajvuksk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfeghjnxw.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtsdzusyoo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtknlmsbmd.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtbesvvytx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gttsjyrfcm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtvoscxxfg.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcbkoefrr.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtbqijtumd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtxupxrure.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmknczsbs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtrzseuzwk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtwhtbxrbm.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gteotnammn.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttmcyougk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gttaadzmzz.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtwpoxlmtg.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtvjsebpeo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtmxdwpvww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gthkwrcffv.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gttozoklvg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtwmnwugxy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtwmodqxji.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtaqkygrou.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtcammakhg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtlrllpnom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtfbgdjpib.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtvdqysudw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtmhgqufgw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtxpnjfcak.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtddecexlg.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtytlfipup.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gthjjirwdv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gthjfqspzs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gttolotjwa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtflharjuz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtayikrbmx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkmkqise.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtujojfphs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtnnzbhylc.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gticcldbfg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtrrhcrfin.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtruswnpta.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtxyysvwio.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtefsluinj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtjfzukxih.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtxpnthrir.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtwhtcwqhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtiwmjdnam.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtxrdhnhvl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtkxoqiehm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtddaevlye.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gteyjbgjvr.html


<!-- 参考信息 -->