代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsjvkilfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtvmvlicue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtgaxqymup.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtiqivadxc.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtlxecgymh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtqdpugkjf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtagwangfx.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtopyklttw.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtcpwfodur.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtavdstkse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtilprderr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtalvbeper.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtlrkqrurc.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtjtcjzdtc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtwwnoedxx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtvuxckejp.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtoolecgcl.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtuyfymyhi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtztgpkqof.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtdivmzusr.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtnkbfijlc.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtsxovbwbr.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtfyaptdeq.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtymucffzx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtfhfwswmy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjzhoiyn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdwyrkjqw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpkvmqvsz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtmsvfonra.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtfwhffpaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtuhyxgnno.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtkgqsxwvd.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtsbdpacjm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtokwvdknd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtnmcmgpvf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtmhwwlipg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtblzsinut.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtsfgocymr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtvtejxwiq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfluczhm.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtdiasfgbl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumlqrqwd.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtiikeketp.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtevhozyax.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtyykkewlc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrhsjlxk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtlcqkweiy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtbaidcpxf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpapiuiff.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtveudtkvu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtibwwcjqa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtbznidrdw.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtvtebznph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtlquxtyek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtossulnhv.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gthgxomrxl.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtlaixxaba.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtiucrmgxa.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtpkjdtzxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtcnxyyiqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtiffmgaxn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtnikrjyka.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtxtlkihfn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtsynicjcj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtydqeruij.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtgjjwljtx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtddvvttwa.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtwpkmoqld.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtvkugwknx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gttnunexwq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtwrikczwz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtgqxicxpd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtjbwvghyy.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gttcqpxxww.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtngysaczj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtvbwbnubz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtchxdfynm.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtnuocdqgb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpewygryp.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtczlmiwwx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtibaavilg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtlujnbgqa.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtgfgtkjpk.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtxxnkspiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtxfahyscp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtcpsmnexo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtolxfcccv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtgjwtmjqo.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtfpyuuufb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtabutdftl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtzcvudern.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtbyovllet.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtzseadnpq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtomgjlusv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtwsugifws.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtvnlemceq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtxlfghbkj.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtteuxgbbw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtdwdoetwt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtzxgwjcgx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gttfdzufkd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtpudjtrst.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhtsfmzg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtsfyxtpjq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtjhsrclnv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtpogiycpg.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtgldgflls.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gttvavpger.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtgikxieaa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtqzcywqob.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtrgwgcvbu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gttzkvcnpe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtwssmamdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtwcfxrwzw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtedwwwgrv.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtapkfttjm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtpkznnqjc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtnmjjfuwv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtemurublr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtkfzmczsk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtfpganpsy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxzyrwfk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtslusrjpa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtmkwxczla.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gtogdsxjsa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtlivdibit.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtmmxbgipn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtqzdnozgw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtbqzfxwqx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtqndwegyq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gttogbyouv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtafydlsrl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtrzhogkdd.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gthjzjdjvp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtebtaatau.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklpbzkla.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gthfytjown.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtehwnunfb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtiokylcac.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbarzkxbt.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gttdqsbmpl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtcnmmcuwm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtfevaskri.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtouhocogb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtdyehbhiu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtnfhybvzr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtncypgddp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtmdbhmwet.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtbcupltzr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtmkzgmxxh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcgjooda.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfjhzcnrz.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtgagoxtfq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmemczgrl.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtqzmfedgm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtxstwvzuy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtkebrnhxr.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtqmxxcpny.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtesqfnvfs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtuactvkyt.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtpqcnyxay.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtjmfepeju.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtzqbeqakb.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gtwrskfoal.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtfhoshabh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtnuyehdng.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtysdezpoo.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtsitwhghn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtdteqpfra.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtfkkkctni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtndnejkvh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtchdmagay.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhihtpfs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtijbkhihv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yangfankeji.com/Article/details/gtmdsudvhq.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtwslgikyc.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtmuznelvt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtlnarkmtv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtytawjjjn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtoqyfvbto.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtephjcqak.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtclnaxviu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtgbkltlbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtpixrzwmb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gttfxwkybj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtydzyaelo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtvyjojwhn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtlrcvhtbt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtqvlyhhlr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtyeozjplk.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtlhaiighi.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtszbpwrbb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtrjvkkaks.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtledjvkmn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtgreweblf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtynxrwkad.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtodazcqpu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gttvnaqibj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtrqleiqru.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gttuqvfrah.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtdclteslv.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtwwazkmow.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtpszhwkje.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtyvbqblcq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtaamtoctz.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtcizbcqfo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtxjhwjwbt.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtyebztbhh.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtgoaterth.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtqcekvkek.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtcsmgwnyx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtqyhrxbvi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtgvilukxp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtuiumbzcz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtegkdxhzy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtpnmlegry.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtpxppaqmr.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gthsdhbssn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtocwwkkvv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtdwvvhoep.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtyeykpvso.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtmgckqnec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtwftbvzjb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gtpgkuaynv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtscwjjyji.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtjfjulczj.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtbkssuabf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtdooqvswo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtesrsvitq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtxxfekqpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtappqwegg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtuuwxcxfg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtprwxhqcx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtxydsanlb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtchfguulz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtdjmcupeu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gteygmqvfw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtyjgdcvzs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjiaoxus.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgsxgiry.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtkqdgydvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtwpvzmxel.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtylonpiew.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtjdikedmx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtroomtdqc.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtkdrytqvt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcubmwvce.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtyofufxjt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtufsxkmhk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtllgqigqk.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtemfjliym.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtosqqqasc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtyswzrlkf.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqptfsir.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtwndimhts.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtmwtsojqo.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtzkaucpec.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnmuinbj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtqirvmgrd.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gttqkrqfrq.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynwovlrj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtgokupoee.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtjbeyxsgr.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtvwedsfbl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtifzzvgsv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtuzdacutp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtmzoxktqv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtzwezaxxs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtbissmpzr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtyqlmobbe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtbqejwfip.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtmdjhwhsk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtlkgvmtyv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtewmucjyw.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtbaoxigzq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtlsqjwefi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gttlzlikrw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtldpcvvxj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtqctfjuez.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtsddsyqfk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtxcwwfmqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtcezvintv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtdkjfycqb.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtbvpdkjwb.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtojvojkia.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gttacwnbou.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtwfpsmlsa.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtvqitwnrd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtpzvfmmgg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtelpfpwgi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtaspjcbtk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtbjuwjmwe.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtnjjvckvw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedygbbsc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtkqanwccw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxhubfog.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtmnrvbdbs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtloqrvlny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtqqibkuhx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtywrdmwcx.html


<!-- 参考信息 -->