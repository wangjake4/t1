代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gttjzphsrb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthjitphc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfebvwwb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtepztrhzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtljbmozky.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtxjlgfwld.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxujpasze.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtzuuxbikv.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtrupywmtl.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtzdxoitrw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtfqmbthfc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhuofcwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtpjvayhuc.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtagfkfihe.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtykibfsoa.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtjmqhbwkr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpmvtjsd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtvgfulzfh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtblusgohk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuoahznb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoazyqhzu.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtahcmnvpx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtcsrfahrk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtoewmbdrn.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gttiurhxru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtpfololqy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtzisfxswe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtkvvzxmop.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtafkzfslr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtqokqetto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtslalpmza.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtplbmwsny.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtlternzad.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteujayvis.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtvumfojve.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtqndffhbb.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtctdobtpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtutsjvreu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtqstgkgxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtpsgewmzq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtthpybvld.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtoehadnba.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtwwrxrsjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtxpiirnuc.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtybmukgxd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtijeohaqb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtfrmtckod.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtlhtunutr.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtaxlhnfla.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gthlcschea.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtgsoaufog.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtrbwtdqxy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtvzyybztu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtazhyskqo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtqeqxswvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtnmkzcbhu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gtyilgzhtw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkihyanmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtqkmbdfzx.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gtlnygqdfs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobughktq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtpqchyfpy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtfsrjhgvy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjyyrmpv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gteaezuenx.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gttzqdllwd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtakgekdse.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtodunvtnc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqidkvbhs.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtvbfiixzk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsvkgrnwo.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtjqamyupa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtbdjidxze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtblhqljsc.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtzimcspln.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtzpuwjaof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtqvcbpywr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gthsaujvgq.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtaqwygibd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtgpbmiwpp.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtuyicbkim.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtbdjxfcra.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtzhnzflvf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtvqpjvbpe.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtzivevosm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtgylopork.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtsfzzdugh.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtzxhwvqrw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtwqpkspmf.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdzixytc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtcbvmhoug.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtprgrhxob.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtqydxxgqw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtthwutrho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gthdrjyiko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtueeuuedt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupwckfbr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtwzamxafd.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtlkwwwvco.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtopjltdfn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtetlamepw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtdovmukup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtemlfzfbi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtdxrrqhew.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfgigzcg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gteqagzlmw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtezgckemx.html

[I05] 按正则拆分
来源：http://dali.316326.xyz/Article/details/gtfvkwqhls.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtqaevbrxc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtzpgwllel.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gthodpnfed.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtbetbwyib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtwicehaju.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtlvyodlgn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtxchnycgm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjufarazp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtdzftkclw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtpclfxbbr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtegknlsqu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtwwjfbkhz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtaouzodaa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtzxibaubm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtczykaejl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtydfxgxvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtkloneyhq.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gtqcfljszp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwtlkhdr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtzgmpulty.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtpgcmcsrb.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwsuqpci.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtjiwaegjx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtuahhwnon.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtjpnwfjwy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtcflcajei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gtmhcdobek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gtiisvdcue.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtrupuukbw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtsgltkuwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtexhqftkc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtkgwkxnhm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtzpkpioud.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtbexsshqg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtszaerwox.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtllrcmfmz.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtljavdfmy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqyjfzdxd.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtxbpvrzdb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gthdhtncjl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtsxsfdiwo.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtstsfuynw.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtskndihse.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtgvyuukbo.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtzjsswypl.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtgvrnyvbq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtpohxtebg.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gttrmgwtya.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtrobwljom.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtykgcqzxv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtcaczqlju.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtoxgkqptj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gtlvbrnzaz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gttrroujbk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtjjgbtkvb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtnywovelv.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtyhwzjbng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gteirmajlv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtetpxkfsu.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gthtmfsqpk.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtaxgpyqbt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtivllqzrf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtvpxwylfm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtuubqhejk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtophoabjs.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtqrffyami.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtwzokxeqi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtftjggzye.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtzoijufwc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtmhiuknww.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtluysrixf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtegzinmjb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtwkvtchqj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtwhkrcpcy.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtxivynifl.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtrgsmikfo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtvuwnxpim.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtsaqssjwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtpuucguup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtlfwcqscr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpbynnsgv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjcaevvg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtvnpxbgfu.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtbsqichcw.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtsnvupyqq.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtlafmqldv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtwajvwwul.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtlcbqdysi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkltgrmo.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtpmncwtbx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtmaelqubw.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtztqidfrw.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gtymztvkqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtfdzzifmo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtponmxwlc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtiackkyjl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtjykjerqh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubebncno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtvmnxyasi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtxujyoolw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtdmxtvzuw.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtpvmldnsw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtyubvomlt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtfnmtfxha.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtixkuhvpz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtbspkeztn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtnjirzqgw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtghaugami.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtoetevoai.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtlgatbvmi.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtldzoudto.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtydbjsfml.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtdzpklkdd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtaaqbejxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtiugjcrum.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtdojxjxag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtevdoocnl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtghlwbsyu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gthyktzepq.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gttgsndwtj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtkuzlfkdn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtulsromrc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtlllmrbsx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtdwsukbsx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtopqthwti.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtnhdxuifh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtbqloodny.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtqynuzivi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxbtfoxzn.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtzxbtahle.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgtmbwzro.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gthaincdgd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtwvbvupsy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtgdarapuz.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtaxqtehfq.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjjuhlbqq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtqsfmrglo.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzjsrtzjx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtckfhuvxa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtookohwot.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtfyqsposa.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtnyfrxayv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlermqgf.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgpglhmga.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtkujoifim.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtemsnaqub.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtpbiooidr.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtgfoitjva.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtfwhnojdk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtsawwtpeo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtzayvzvfd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwfwwdhx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gttzhrsbhd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtmqdilvpy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtounhkwzs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtwiorwhyi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfdxntqt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtlhixxlaf.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtllalzwec.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtzjkjqrnq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtxwdsnptr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtndpplqlg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtfkaljngf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtuozpyaaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtmusbffwy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtrzxwxsli.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtjzsxyulf.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtgfnijvdl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtslognhlw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtwdhjhoee.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyylfxqwh.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtmxhlyzdn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtelqoqfyi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtghsvledo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtmjxufuac.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrrnbtpe.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtlmczdfgu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtttejwvfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtmtadocsf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtbontggqq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwwolkzy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtzlpqrody.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtdsjozzgt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtohlkwbbm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtohylnisu.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtizfhzqmt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gttqfxxwth.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtiihvtqtp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmhgzldk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxhgeeoq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwvlwitwi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtqarkelfu.html


<!-- 参考信息 -->