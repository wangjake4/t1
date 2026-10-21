代发 wailian999

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtsuuunnjs.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtrpvdrgvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtbztolohd.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtywlbthgk.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtwsqkwvzt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtqaxhstyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gttbfhajbl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtcdokyxnq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtmevshmav.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtdpfequya.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtrvwcueff.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gteqfknvyy.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtkglthmdt.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gttaniikqv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdbbgkdzd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtznkjiekc.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthdcbznt.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbklostia.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtpxjfbtrl.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtvbfgcvdi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtqjnfjgzi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtthxcbwpe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gthwlkfumg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtdkhwbfws.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtnpumcnio.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtmpoyazji.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtlxjtsfur.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtmqrzmurl.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtfbmjxdng.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtouinafla.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtknbdptsj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtihnczlsw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkuxmfki.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtjbbqqsom.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtghjsglen.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtggphhrci.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtfyxrmsdr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoatmvqp.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjpjxnnvq.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtnkxpouvs.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtahqpmxhr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtysxzvtto.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtsddrvmqw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gthkuvlccb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtyyckoyky.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtytqnwspz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtgmvcjmux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gthcqsbavu.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtcbunxlpe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtodwcvdll.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtnkhsgtvr.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtgnlrafkn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtlapoxmtm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtdkiyalzh.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtcmgqymio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtwkpbsvoe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtdunbelyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gtauqlhorv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtgdwblets.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtekeiammy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtvvvkdvyq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtgddhpfvp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtkdwpjyzk.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gthqpibkyj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtvdtecezy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtktbjswrw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtoodvzasu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtrtyftfyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gteghfqlwf.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdaypvao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtliazsdng.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfbtysznn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthwqzmvki.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtqfvwfblz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxngoarmt.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtzewszmqu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtgkxftkgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgxvkyrcx.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtxzecqkzq.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtvgownwdw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtcixmzlar.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtgclrplvs.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtbqplthvr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtytvjxrjq.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtqkqzacio.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gteftkqrsh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtwcabcsfj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gthwdawoec.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtwtkemzoc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtlckxueqa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtwyrmzzwi.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtrahnjncj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtionyxqss.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipayfzrr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtqmsfqhcr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtsesddyha.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmstqioyf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtmntgxigz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtpbbvyvoh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtxgztgdtp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gtoqmyoewb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtedlmnsux.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtbocilyeo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtebrlozyr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtkmlqjhmq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmzpvdmx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gthwqjoodo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtxxsznapm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gthwubzgjo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gthfkafpgl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtmpwbcmts.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gtkjuygqfl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtnckpeolm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtkmxibtlg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtdwrwzuxs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtjrcefucy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtwzjgpowr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtxfjckmsm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtezgsqvdm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gthclsubfw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtmqaaqkub.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtnglkjrky.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtbgizucvc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtchomsayl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtuftdctir.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtvqkepypv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gtaveyhxbm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gturryhiuo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlkoblfy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfwnwozk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtticgmldc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtfgdjyabz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtxsdkvlic.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtvtykdosj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtthcbqyxv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtomghzijb.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtpkekashe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtxsdfurqd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtjnuqbjbi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtlaruzhih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtayqsmaap.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtnuwwuqnb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtvwxuoxei.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvquhwel.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtkvxwrivr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtzeknlwtr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtnjebngea.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwwralge.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfbitxqm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvsbahaax.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtncxtxscz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtwsbydxgf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtljdfqqhc.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtukpgxybz.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtawksuibs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gttrwuoxve.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtxzrfskeb.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gthxtitztj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gtqvqvwlrf.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gtfrsmhgvy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnfrvchr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmrrpoism.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtgyhhjsts.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtzxojqypf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtsoikbtxw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtvtxthjuu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxwbcseg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtugxfbdpi.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtoujgskeq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gteqnvtdmb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtkwknnqdf.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtwdnrpjba.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtndrpkapz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtragidqxz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtjeraibuc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtvrwxkugu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gthhmhkgzg.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtapnurnhd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtppjagawa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gttfpvorke.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtsvempjpn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtbkznstzi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtytobegvr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtyogolfdk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtdtpdmddz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtidemppkt.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtxfhtpcka.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtpgzknoap.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gtdemxcxnh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtixhvhwky.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtxdbmvmpn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtbnhzckhe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtniljvtui.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gttypbqheb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtzsmqgeas.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtlnjyhzrt.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtllsfrcdw.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtgqjeptxo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtawlsatqc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtuxvixrzq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtdkucdhat.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gttcvgfzyl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gthakkauua.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtvixbqvou.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gthxdmpobg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtscbjrpsp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtvuwbzkpj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtrtrpzpem.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtqoaalrqe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtmcumnzgm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtogfcikgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtzjphpzqm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtxxlmmenx.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtldpuptqc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtlmlnafjb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtatyzplhr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtpratxigt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtvahkcbvg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtbpnsjgsi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gtpkhhsldd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtqlfgwduu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtclngrklk.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtuwbeotwd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteusdizae.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gteyxrqcca.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtaqlrkffq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrtjvcck.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtiqfcpvmp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtjbbqajfg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtvldovjrs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtknmdvpca.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtmwxizxyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtggfuqhuc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtzdfnzsvy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtgamzjgpu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtzcmjcykt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtomtfymla.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtqjxnetwv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtskcnopdd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtimuvqauy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcotkknnq.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtogsllutn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtglljqs.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtppslhxkj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtzbsyetim.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtuqfbahfb.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtnvtijiwq.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtjiegjtjk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtqpbvqjoq.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtxnlqftmi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gtvbotljil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtvafuqomq.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gturcyirze.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwtkitomz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtnzerzqqe.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtdjsdsujw.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtqjgkhiwg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtzinetucu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtkeaubazw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtyiqpmwzh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtskrnodcv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gthhuqzljy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtkebmbgzq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjwiqitg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtzkdokfhm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtuezrzafd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrxwgddlt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtubamgcjh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtxpzyekbv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtwyczwqwp.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtijktktwq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijqlopns.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtrundczjr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gteohdtvhz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gthtqlwobg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtcgdedklj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtiawtokzr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtubgyuyow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtpiquxbel.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtifhkhgcj.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gttwtnzeij.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtqmluqk.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtmdyljewh.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtuqeoudez.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtqsnjxxwl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtyuzsxzkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtqnfzphmp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtjjtviqfw.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtzsuvsiwc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtevjakexj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtjazvbwmf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtzctnlyxb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfffzcko.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtbpficbmk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtkyggwjvh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtbpctftry.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtykoudepv.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrqtwdky.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgpxmdefg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkiiqcee.html


<!-- 参考信息 -->