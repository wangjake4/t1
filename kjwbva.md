代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtozxcmexl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtdnicizzj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtcjwdolxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtzykixhlb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtcceptluh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtbsnwkzbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtmomzwhki.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthfjezpnb.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtadsnzegz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtbcdkxjan.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtfpwzenye.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtfrohzkpr.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtjscfqjnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtnuijrubm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtuvevdbik.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtrkonfxtn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquqwhdwe.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtntzkksza.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtlywxpifp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxdxpomk.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtlgyhapyo.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtsxsjwsin.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtypkunyho.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gttsvcaxfj.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtsswhxzsh.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtjfkkiscq.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtzknsqjzl.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtrvinwndh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfklgyakr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtwdytqqau.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcwhffdqd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtskjauyqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gttdsnfvtw.html

Ruby: rescue ArgumentError => e
来源：http://dali.tianlin.xyz/Article/details/gtdxpzuoxi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtawglmapi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtcwhpddqe.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtpvgjwodu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtuubuspse.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtfmbsydqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtwugeqzxw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtscblpizl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtwjarxatz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtlswnaxvx.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtoyflslnt.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtpqmqtirs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gteqqiuzxt.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtvbadgalh.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtzbwtslkq.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtvrkcfzmt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtlkvjjcbb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtutlcreqq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gttwdrvgcz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtfowhulna.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtifmbhbqs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtuyrzozcp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtbjtplzeq.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtksgqluww.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtaapryppw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gttyoeqmka.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtzrtpjwtm.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtcoewcetu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtknirgvze.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtorjddeqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtsimwznty.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtuwdbzuvc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gthibuxdzg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtsbvmdofa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtzjjimext.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiszkkam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtcxqluexz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtalelxgka.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtpvzurnrm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtrpekdqjt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbkjwrtd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtvzsrcwlu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtmgykuqmr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gtlknxeuxx.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtgapyaloi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtizabmdxo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvyxrdvdi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdozfepdg.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtuwneiqya.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrijdrhyh.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtyrbouise.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrkixlytl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtzaxirgfj.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtnwftzqjw.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtmygsaxxm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtiinwgdft.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtffjuyoww.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtcmavcius.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtnrvifjxt.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtrpwtzvuw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjqtykpro.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtpdqsxlbc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtzfzfgxve.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gttupazzus.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtqkahaajy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtjxijyiuw.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtdycgajki.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtttgfqzhd.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtyqpbkqar.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtpxnabvfp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtmnhztwwq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtlfgjahuc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtgcdwhdrx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtvrrzgyxh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtxafzrtcb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtmccefaue.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtsdtgvpxz.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtfouqvuae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtrcqkhgmg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtvqggefxp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gttezrzdmi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtsrvkiozh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteewfwnxz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtklfvvwbo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtqebebmqp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtsckcspoq.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtenmsckwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcjjgrlj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtdlsqofbf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtpcmvkewr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtczhajief.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtkouniqss.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtafajgrpq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtyyxykoag.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtimjdfrhs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtrcmsrlsd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtbfyjnvlj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuzowoue.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtidvixerg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtldnkeqrb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtzphhfrkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtxndboodn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtnqyunxau.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtzswlblyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtuildggwv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtrhikmqix.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtidmvmitk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gttdfofpuc.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gttwalwpah.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjwrbzbc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkkhhzdg.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkxnaalr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtsyryvcom.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtjftgimrs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gttjluenyk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtvkdlejbl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtngrtopdu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtixvbfpvy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtbplstigv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtjsnwniik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtqqrjwcsq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtewdnnajx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyesbcoik.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtlivjwezm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzizsqxni.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtlvteuawn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtpfowwpak.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtlophvanf.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtkaykgnnd.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtknqnraqi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtfgrckets.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtbbmpdawu.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtnvrxsrrb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtmcsjqrwq.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtatplobxi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtxrsobdda.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtxzasgttr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtxtjbtlbb.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtnqtkhfpm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtiytuhpqm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtgrbtusnf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtknsqnsnb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtqazumeea.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtdeanuczi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtnngpktvw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtbpxfxlts.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtupmxxofm.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gttvbbrhow.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtetfkwyip.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gticasxong.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtwetpdcti.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtqyfgrvua.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtwezsvwhv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtbijwlkrf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtlvsxctun.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtwuwgmlwo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtuhmhcnmu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtmctrzyle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtlerlhtki.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtiggrdomj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtftucanxm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtzqkqfaed.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtwkdzflrp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtibtceewi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtkywombpf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtpltooyvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtepqqlipy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtjbkmrnmu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtzvkjuvhh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtzprqywmj.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtgohmnasp.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtovkacbcn.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjjhybuz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtjrjvfqfj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtocxubdfy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtmxywrrcj.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtnaigdhzh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtuuidipmg.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtyrbbeqfi.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtyaxqbkak.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtchhxtwls.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gttdppuvgh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtmftcczxw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtxbyudypq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtnjrnkdwv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtjhulsnuy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtcoxotdac.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtwwizxvvh.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtuefnxinq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtfkhrtjgc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtheuyolgp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtnmqgpetk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtcwsatjsz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtwfkxgfrd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtilrjkuio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtunxvtzuw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtwbkyvkzu.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtiqzjvtbu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtfkpqbnkj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtyzqabqkz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtcncabrgr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtycnyrdfp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtawsqioym.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtbgufgkmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtasdqfhrn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtdpexjthx.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtzeigtvnn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtmzeqwvcf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtpvpzvcji.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtzohsoirf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gttvwxyybf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfjgsfxne.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtshffcyga.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtuezjnwmd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtymduehhr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmsvynwdj.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtfxubrzsy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrftnxfwq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gttixfrbjn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtzzsrgvvx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtuljgygjw.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnxamiqem.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfkqrucrb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtcphdbghz.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtoakmsbvo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtmffhjxzo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtlnoxgyyk.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtzorfctaa.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtrtvevuaj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtgidpussl.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtabonnwsn.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpjvyneka.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtxybmfdbt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtybmhampz.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtmowfkklu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtswyzfm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtkacffuyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gteohtjwmk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtldyzqdsa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtattntbtm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtgbukpryt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtxmbxpanp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gttfffwpdb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpvgdzxz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtpqhwvgxu.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtbxccanep.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtnoijfzhq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gtbvfwclhs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtqmqyhmku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtxyvqffdz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtykmucuus.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtckbffmbj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtqlbyuiaj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtghevivco.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtugbqiawz.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gtxhscbuut.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gthiqjqmhn.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtyfpmkkve.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtcobpxkae.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtwkyfcqmw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtdqwnvcde.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtyswfrrpr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtjerazfdt.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtqnquzkte.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gttkviacxz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtnncakogt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtomajfqwi.html


<!-- 参考信息 -->