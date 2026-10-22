代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtsfyurikf.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtefthivpg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtehotmola.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtdslmlwof.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtkzofwtti.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtrvxghaey.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtcyzmuklj.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtdjkrfnyt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtwthltcco.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtqaitxyyz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtvaqgvnuy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgocgkobi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtoshuklcr.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtfuzgnvzl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtmfbvmphb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtlfhthtce.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtuydyksxy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtcuqscnjq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtxymdejko.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtolghiqgf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtqgvrszjw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtaadnzbuh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtvqbikqfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtljhdqchr.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtpevnolvr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrazgtzt.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtkhwdvurh.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtyfquzrvf.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtuqwhdaub.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtvaidnbqk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtqlsdbeiq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtfkptqgvs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtjdtorilh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gthjwidcmx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtjaosdbiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtuxyjsoki.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmajmhqem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtbwsvklnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gttppgbsrl.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gttjpzlkzn.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtpknoydcl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtzjalidxx.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtymyniicx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtqimnejbb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtudbieoyb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtvexhmohx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtrirbdgeo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtwftdzrai.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtnetpqzhs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtrdbreyju.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjmgaixk.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlmlkcuz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrtoudyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtriwtgxeh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtnogcukve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtcvivuoiu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtkefhvoiu.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtjgvbdatn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtgikpnbdk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtxleyepug.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbhzllfji.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtemzjmcqz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjmdqcxpa.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtvlboackv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtuuuhnppu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gttnegppey.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtyskdplvh.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtsishzann.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtlrytcyud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtzpkpyads.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtkkxtisdl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtseljazuf.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtftsuyyse.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gthprmarqk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtpnxoxwxm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtsrsonndw.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gttypiorol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtjcbwlvhr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gthvtpqkxi.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtefcspyvl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtylvoykuz.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gtbvhaldxk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gtodgmoccb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtooibnpmy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtecthtjud.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtggftzndv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsueosrw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtinuexovl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtthogjngf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtsrerejdu.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtaajhnueg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtmgukhckk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gthfiuvvme.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtaevjfadk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtvtrxhebd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnpdydfi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtqsddiibb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtyteauxmc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtvnjmyenu.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gttgbzunpn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtstslvzvj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtyocimcsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtxtvhffkx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtimcwpqup.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtrfjjswyu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtrifauqop.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtrpisibso.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtnwnqzfyy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtkvlrojbh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtwgeoajwe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtkprxofor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtxeczhzny.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtldzjdblf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtrdqhmsvb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoibyqnmr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtughckuor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtrwskihwc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtaubjoxms.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszlwswvb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtfgmbzdrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtgichdcqu.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtfmmpfkio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtiyihxhnl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gtqmftrixg.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtzwqoldmh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtwmjufkkr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtskrgddff.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtacpkapbt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gthlzesatb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtbqptzvfc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtqtovoycd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtzoagrpfg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gtrdtxistu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtnotchcde.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtesmosgwz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcehyzmwb.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtsxvpqvwt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtigsmotjo.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtgzpelfth.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtxnwyzrvk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtrpfqyejb.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtzmoyszzq.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtlozsuwbc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gteuqfpqdt.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gthmuenzbc.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtsujqbvbx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtpyttmfni.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtyprbvqfj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsyfghkf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtwlftyabr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtkkbhiyyr.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtftdjrzdj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gthnlwdrtf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtnrmycfdr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtcdclnnvp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtaozizsea.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtrnumghbn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldwjfspm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gtwaotuiiq.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtprvgcsyf.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtrsvntazm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gteozkcuon.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtjeywpzgn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtltzvybul.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtwepbnrhx.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtvsqamfzz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtwcyxuztk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtamljqiaj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtnkdjemgn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gttyfdxzoq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gteklllvnz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtbigpajhn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtkbakjkdu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtvfkqkugd.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtysgeukxe.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtmgyyvqgo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtnxotrimb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyliekfw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtkhrotouy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gteubuajzl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtfyaxwfzj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtrwasexsw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkfbzpqbe.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtaopoyirl.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtcybhdvrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttajjunue.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtvrfaramx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gteyogjimj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtigmqmfdg.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltgehzdd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtcnvmpvld.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtsocmbnec.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtmbqpwlak.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtzjphgcfr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gttazmlsvi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtoccmloco.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtbvbtqnjn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvptrgle.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtmdjqvocv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtdqymusvn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtmpaysjbo.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtzlvkhxdo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljgodlyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtknneowzi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gttlpktdid.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtpzkdvojx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtvjqehadx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtlndusjph.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtaukxaxmd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtbfbnrgyl.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtqtiqfdof.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gttvqcpnrc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtkraitnhc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtixevtsxx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtzquusayy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtiyufogse.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtldppkksj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtkboydvvb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtpausiexl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtbbwfjxmg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtrewhmhgs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtuymaiald.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwiektuex.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtrzbhwnbf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtzhkhxnvl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtudptfqed.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtajaxbnlv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtiyzbyzrp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlgeeycvr.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtndjkqumm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtarwtadwb.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtzjvlnzlp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtswcmihqx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtgapgntod.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxuljcunr.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtxacfynzy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtmrhdljuc.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtbzoupdlx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtlioteepx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gthsiqgmuv.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtqfxuvcvt.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtuzazbnld.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtkjkekzsz.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtrjakxvko.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtrfqeqeuu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtfyxrrqkt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gthfcpkcxf.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtzlanzhmv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbulqmuku.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtkzdgtdhr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrfzrcmv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtbdgdgbvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqpiytpwu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtavmkvxhk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtrsuxmyls.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtlzjwhuov.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gthedhwhqo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gteypczpeo.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtwabbrbam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtmbjzoxpv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtdlorksxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtarrrowdc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtuipxviac.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxsrnvyb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtqakagjuc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtffonoxjg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdcyintiq.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gthcdaifwg.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtjjqaekdh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecgpvesh.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtggdmrfix.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzzkqpiwg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtycurvxbw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtzwwxmpvx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtcgwbqapf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtqxhdnaag.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtevniweyb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtutkgshuc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gttncqfpcd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtgguuepwn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtqpegeqvt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtroxnhrfh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtertfekma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtesfnejem.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtoqdknpnq.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtoxmtasuy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtfnxsraox.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtgetbauka.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdkruyxmy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtcjmjfsmh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtsztyiesf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtbrqcamks.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtnuxubtrw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtkiheogkx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gthgicropb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpvqzeycq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtsjxqegdh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtivvfmawz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtwyzefzrf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtdmsnkctb.html


<!-- 参考信息 -->