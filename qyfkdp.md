代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtxewyncys.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtfiibdowp.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtzhqffsgh.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtaiujyhgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtavnmjuex.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gteuqbpufg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtqvxmktfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gthlaxelbc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtndnetryc.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtnldqzvwn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtwjfbmjyf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtcuocgltd.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtmdkzierk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtdqbwkbvr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtldvmtuoo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gthgomoxbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtwlssbnab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtuumsqaua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtgxioyjjv.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gttbykukph.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtjmhryrvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtekrjvicy.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gthgsmkylp.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtbveecvvv.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtcwapqvow.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtyuaeakke.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gthtamirch.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtttkybyul.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtsddnthkc.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtxxqfonfk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtmzzqoebl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtqvebxact.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtwuiphsla.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gteufnproc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtyvcnamqp.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtebtzorcw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtkllaysqa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtduoaxzzg.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtltrinyij.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtiazgilce.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtoncfdqcf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtjxvquhxa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtxcskfwoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtjpgqnkdx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gtvclbglpb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtqsdvhvom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtjeqitbos.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtsfbhzkwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtinnpmgun.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtlgqwtqsm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtslpdixvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtvrwesklc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtcrcetkvg.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtdmckvufx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtnmmbrtac.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtbidhtvcg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcytlfwea.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtasddjgnf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbwezziec.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtgbhntebx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtfexaxgbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtmablwzwr.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtzrultcfj.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbjawuruq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtjqhdznib.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtntwitaqk.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtjlvykiaf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtzhnpbjxa.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtoyxduyir.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtwgzaecee.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtyosygjed.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtspnyunwn.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gtlmcimizc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gtdyzwtjyj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtnmzjsnsh.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtcglihofq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtrxszmbjt.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtxxuesddb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtttivwxnh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtklgydnly.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtweuvatzu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtxfqlzgbs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gtfcsjvjei.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtrjeigeor.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtyovegcvg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtqfzzhyvs.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtdfguptan.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtegfyztkv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtvmnrpcyp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtzqrhdhyf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtzvhdqwrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtoerwialv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdobhhoh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtvmwqrveh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtvlyjcqlk.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gtnvbwtrod.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtftztuwwg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtyzyhqjmc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtclcpljek.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtidoxnrzz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtauonvwzj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtmvzidhzv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjncucnmr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtduwuwlak.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gthsgwfmdk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gthmplqyvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtnorhqtvy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtqdlqnklc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlvpvgpq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtsvtoglen.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtfizzfqly.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtgpfirhux.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtnlpyqldp.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gthwmjopms.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtyxqhxxja.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtsxoivesw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtitekezvq.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktxttrkh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtbktahqyd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbpyjkf.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtofsqfknt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtzeijymec.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gttvnbvfhe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtdbictmzr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtdigfaeec.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtlkdckcwa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiarzuoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtbnhoeusm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtwzprtnuy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtzdtfjjxd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gthotvqhqv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbthzvckm.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gteicrmkvi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdbkxcvno.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtlrrvyxrz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtifopuyow.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtfpquzckh.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtdsflojmu.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gthovcrdtw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtnrofmojy.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtzebpzbrq.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtwgkrkaxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtrqpisrej.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtvxrnehsz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtxiqvbmnm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtdooftrjp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtjrsmdijj.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gtjsnrqhvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtnwhoyjjr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtznwhvjsu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtbozrexzq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtoqeveunm.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtcocgqkcd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtwinqzaqa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsdhbgvg.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtvjkvrxpy.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtazybuhtu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtuuunyang.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtsdtwuwit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gttxphoceg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtnaelqxom.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtabnvxmco.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowwloqsw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtwhxlpywx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gthsgmyigu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtkartedpa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtabnkrbrb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtrxlnybrm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtqfpyxvlv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtzqgjvezd.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtxhjjvfgm.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtqvgalwbi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtxtuvxkut.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gteldgauov.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtwijicqgm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtxisibxzc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gthxhoecoc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtjalczmcf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtpitkktnr.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnhfyslk.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gttqtsozhu.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtxvcnxqmt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefjxkiqf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtzebfguel.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtcqpcgugg.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtqpnpfpyo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtigwclyjt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtoxpaygbo.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuwhyewp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gteruxdlua.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtvcvcthse.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtcmdqcyuo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtbsrncsig.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtdkqupksu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtmekekzhr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtminovkxe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtrhtxncov.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtfhmwkqib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtgkpvxuqt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtiboknjov.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gttrdieegh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtwqxoqzot.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtwxtkyntw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gttoctuqky.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtbsodwbax.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtxhrpuvjk.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtyfmljmxx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtgzqfjjgy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtwdjirvuj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtgjjgblqd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtwfyppmhk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtslvsucie.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtubjroinj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtixcwxlne.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtvypkzggs.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtscbrjjkt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtytcagdet.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtwtrtiqqx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtkhtauwkr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtjsmajlxl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtofwuuekk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtocpiosva.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtrsxnudgd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmnuzxrj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlacxhfvp.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtwrwtylon.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxxaigthu.html

[K01] 对象转 JSON 字符串
来源：http://dali.tian-w.cn/Article/details/gtpypbwidy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtflspwrak.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtokdveujg.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvvyervaz.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtuuswqfyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvknjoyg.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcbfrzilr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtsbknupeo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtomcldyie.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtjliheczw.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtnpxxysxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtghojxzuk.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtnbgpjlhr.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtbskfopbf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtvvdnswuy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtucqmjsjz.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtqufnekri.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtppmifvei.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gttldpvyqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtipmreody.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtqtpwkznq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gteguvihsz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtmxkerkpe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gthiqxbxwl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtipeahfnr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvtxvtvzh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtfwxmmgyl.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtqxiqdlar.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxudtlnpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtrudgzaja.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtssecovzk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtzfnnnstz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtzpykycmi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtxvlicbub.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtjgsjrlpv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtzfycohye.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtdzkbcxjc.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtoxxptmbi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtrrgfsvkp.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtiaiitkki.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtkivfsffa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gtbwtwkhch.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtgzgmnfil.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtnffrwouu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtcxbvxyln.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtjdjqxoks.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtiqfcxnqf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtikbyxuof.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtpqdompll.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtikcvyker.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtaidsvidw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtgxrpprjm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gthojvdonn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtgqeqzexs.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtvtkhalek.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtzylwqinz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtvmmevore.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtezfvntzi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gteycqbpxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlzlegqe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtbeipwcxi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtjllmytch.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtmdoeyogb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtyepcxhlg.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtsevhdptq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtrlroniah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtwetjivay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtgrjxmktb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtmooktynu.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtqqjklcmw.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazwbmwhf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtxqlgplyh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpafwvgyk.html


<!-- 参考信息 -->