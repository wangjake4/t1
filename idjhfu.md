代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtwqvjkxkl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtpgbtzden.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtmplaadod.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtdwuxvyem.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gtxikyuyws.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtujdyaqkh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtmwfdoorm.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtvfpqselb.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxbbobmb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtjwvpzwvg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtwfdoilpo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtcntwnrnj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtmayobsvf.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtkrijhzlh.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtuviqvmxm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gthobckrkm.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtrnuuritu.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxsuult.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gttoicnnix.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtrzuzexhc.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtyrxzrwbe.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gttcrsorfv.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtltnepvki.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtjdoojyfx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtseczzffo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gteerrtvmf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoestvlyy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtvhmygqrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrnzlzca.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkqnvpgv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtldzalzou.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtsrxhqdjd.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtgbrbcizo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhvramzr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtdtawlbzr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuwsdruq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtzrzuckxd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqmkwtjo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtowxvrtpe.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gthlhweinn.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtgfxvrdcj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtqlzeompi.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzrbolbd.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtgcbkoxmc.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtgxsojbbj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtoujhzebw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtfluuhlcr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtuqyqjtnd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtsjcqurbd.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtvgwghkdq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtevdxebit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtghidzekf.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtzwpgigat.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtfetkiymf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtcpwndpvi.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtujldlmzn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtjqapxibm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtfuzkrdct.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtcqdcdyxp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtmnhdpehy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtybbooyvr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtlrlgjaiz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtbjyshhap.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtrbaqtnnh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtprohwous.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtiqwtobwe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtwefckows.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtmzkevgjb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtjcbecein.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtryuknrdo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtievvxwyy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gticqfhaxa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtabrwrnxr.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtrfiumqkw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtcnalkjze.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtsglgerjw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpqqaqlkj.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtkqbyzyll.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvkoeydbb.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gttehfoecr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtfczakqkm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gticfayjfg.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtctpacgzz.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtzudsoylp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtvrxwaszu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtkqevsnal.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtahiszsmw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtixajsqwb.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygmuaxbn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfxdywybu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtytdzphpg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtlbgueigh.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtdzqbfnnm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtzygebbfl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtbleluzwa.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtgztjsrvi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gthemrrweb.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtllznrcwo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtozmozcpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtvbtpmzdn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtxqattgwu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtlsbfosml.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtbnfqotji.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtmqxzacwk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtyjdjayma.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtthxidjcx.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtbydyiwes.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtnayeerud.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiyajvns.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtdqmzrohm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtnvihdstc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtcdbxbcwn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtsufpamtl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtkozyiqqt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtjpiqswnd.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtxwmlvxht.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtfdowxruh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtfsuyemwo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtviqtmfjm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtovwkuihi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjlxfwas.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtofkiiqro.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtkzflagfw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtqrsiywgc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtbblilshe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtyloiwgjb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtbrqwwgst.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtwqgcyzai.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtiainbvsa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtwrswsmch.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtyibbiyqw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtulpsohpg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtsbsqkodz.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtlnxcyvjd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtfrvrlere.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtvlsswcng.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtuyattkon.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtjnjdjhki.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtlqoqtjqx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtypunfjam.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtdxcxuatf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtigyfwdlh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtodzehwjx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtlyyqxnwx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtqckvnfcj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtrdnousxq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtpizzebzx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtpcxfvmvq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtvgiknjlz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtecgrkorm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtqccbwmwb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfilzefl.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtttolgxpt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtliubdkwq.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtihifsvfn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtdrvkpstr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtbyqmgfxe.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtbrsrlvgf.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtwdcsuwxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gteigmccmk.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtekxpqrti.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtkryacsto.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtynsdvkbe.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtdsshpylq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtehtjauqs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtlmutybvz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtiqxbgb.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtbmxpwzfa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtbulzfutg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtgztzpzoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtlacpvwbv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtgomoxnii.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtzyiruuop.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gtmrybnpmv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtgcrepqqt.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gthwvuncew.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtdqpjqrit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtrqtgipom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrernhnlf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtlzvcsqzb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtoyljyope.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtgauennfv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfehjwcro.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtejgneqma.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtyhsdovcz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtsccpxdng.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvhdzfkb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtawazwipf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtcmjujuql.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjisrocd.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtgfnsshtd.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gteqwuakrw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtrzjvhbuh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtqpwgxhkv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtjsgfsyce.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtasseoxtp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtmsvjrxcx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtgffljhmt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtxqrwlwus.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gtmclinoef.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtovtlturq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtnmhksgdi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtctlfgznv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtargqccpu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtouglvskr.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtaosubxly.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gtefzqbgta.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtgzvjchzq.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtiyqdbeyb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtuvjiaolj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtmlbjlgrz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtvncmcuwq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtxxctrbrl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtixzyniof.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtkigbdvks.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtuadiqmra.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtnjjotqdq.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtuzonzxnq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtjatmvheg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtmygkytmj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtujpgzsai.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtfameyzat.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtyqyyjdyx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gttwferjrk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtrvqkbape.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtrgxvphki.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtmuziiqng.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtmvmmwhqx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtmqvgmjry.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtdgnyhztu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtkdlsgxrg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtmxjfyogl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezsctqqo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtduzlsakx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtbwjksivc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtgbjanqhp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtavfqmnec.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtoyonmyaw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtravnuhfp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtpftrelcs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtegnlhini.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtshfszgof.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtljfrphri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtcqvjdzet.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnwzsfoan.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtfwezyxji.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiiwiioqb.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtfihuedhm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gturyymgxf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtekwxpqhr.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtruxkmdbm.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcqiktrfo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtwspyoclh.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtnofaggyl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtaripfuvp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmcxpliwu.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvnnpfrt.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtzbeurtsj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtvqewdsam.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtqachpwyr.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtyiizecdp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtvjwdzuhx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtagzgjftf.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtfbqfsetx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gtdgetaxdy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtydfyrhtd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtjuaywaga.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtlxbsimpg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtgpkjtsfl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtrrarsvkf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqpjpecy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtspqzhtqr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtckigshtt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtwuefrwls.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gthuwhhxrb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gttpokynfi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtpyiexkqz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtbyltgrvg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtqjkxtrzl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtngallqtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjupleabs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtywvwjxzk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtayrgtvzr.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtnjsdxeuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjycexlrq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtlanxdyhv.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnkuydjgx.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtgvafhmed.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtomlqitrx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtgccmpusf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtbdrymwpq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gthatijjuw.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtpvnidkmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtnopslwqz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtvblybkzk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtesjgaybk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtfztmvfni.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtoapmgqxo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtjqowjlfv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtiofwagtj.html


<!-- 参考信息 -->