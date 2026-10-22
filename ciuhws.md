代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtcdttocrf.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtfywzyhbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtedfxdjmx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtupoxikmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtlhkxqkrp.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtwlbtoino.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtfbtxulzt.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtppgtmygm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtobujkgxn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtfaksotsp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtsmnraiql.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpazcpkyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtfwceqoyg.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtfnwgxphi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmujszgqi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtubkfycar.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtlexiluph.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtysvffcae.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gttmifozcs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtfzgzuzmg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtaazpknrm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtxyuuzzva.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtldqfseih.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtfrogaaqs.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtgfkuwxci.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtbmjpzouw.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtlqhmvwun.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtgatjydrw.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtaqpdrtda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtiglmgjvq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtylmguxga.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtdwfchulm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtrvtkznwv.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtpkkgblmz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtmvbyaqat.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gthstttubm.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtazbjoquj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtezminlmz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtetkntetp.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtbvjquzmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtozelsmql.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtcrjkqffg.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtlnfwlgdj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtqjewbtis.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtkhjvcjvg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtjlrkbkjt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtoyeecbph.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtjnraexwp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtjrxombvm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtfzdjnvtv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtcxmnqg.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtpzcjzssw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtrbtlkvck.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gthbfclrtk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtqcrdtlin.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gthfwccsjd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtuggkuwnp.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtponuopew.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtqnelgusw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtvmnfggrr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteloxkmky.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtyvmfcjdf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwieahonk.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtxsfcuvqw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtghtdlmmf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtzjkettgj.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gttxlekwne.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtiuduenkj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtrhjywnjd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtrxjlamyn.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtldxuvodd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtlxlfauua.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gteapfxahf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtljuhpazr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gthzuulejv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtwsyqoeyw.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtxeaekcqh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtipcttkwm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtbexjtyhd.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqmlldoe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gthofywlpk.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtxtecsuzq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtwrjecpsm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtwaajstty.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtlinxqlol.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gthibdukon.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtnbsgetxc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtadwecxjx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtxlfrepqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtshfqbfeh.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtfasjnqao.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtlbyufhoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtpvlzjdhs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtrmjksxvh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtkfcvstnc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtfxzgqofx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtsocubtup.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtmmnkoouf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtzpometkz.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtpfngrqkz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtmxsvfrka.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtlxweexrd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtbedbrpax.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtyunrbhui.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtbqlswlpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtvxgsivil.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtaiggpnuq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtucuhotpx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtfglnvtzj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtkduijiia.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtjnbfrhbh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtfqcjmuiu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtmoywblxv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtvdeotjgb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtctkzspdk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtaojaeoax.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtlwcupeop.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtdrqleqoc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtendjiedx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gturdufjwl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtpqhtqbdh.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gteoilulhx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtlchttomd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtjkwdpybw.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtyzkhsmdy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtgdzrigxy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtjnuajqup.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gtqivrepzx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtbtqtulkv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gttslwwyrk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtcazblonu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtuyecrsnn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gttprwrtco.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtuyarylrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhlxsdld.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmuvezxsp.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gthiosyelc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtikllnpld.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtxohjgzlh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtcfvplsbo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtodvgihjn.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtmtpelzlj.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtjseuxtkm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtruqhdeuq.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtjlybantt.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtuvngmhxy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gttjnrfwbm.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gttowspvax.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtkefozmaj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzynceajq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtfeaivaqi.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtuwdgzlgs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcourdvx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtrqqkatmf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtsuymdlca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gthynpncth.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtduuaojam.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtwnjparqg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtywfaageh.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtfohgiytp.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtqyiuegdw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtffmjroxv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtkigpunbn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtegrtnsbp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtxfopyshl.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtzadzybse.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtdgnhihjy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtuyormrrj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtsimrozbn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gtgpllczol.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtjqyvwdkm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdtodcqp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtlijgdfdc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtecakydql.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtyvmbwynj.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtknkshote.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtwzsnrcpq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnycxtqcs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gttvfpanql.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtfqbewhaj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtqsqgvzya.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtoagfmycw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtrshidjpc.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtizebgyyy.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtmoprtufj.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gthrldgnkq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gthxqudpwx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtdddfrtle.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtmauefgdt.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gtwdmurpwe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gthcmgtgja.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtypokfekm.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgwpkrpgo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtuqwycrzs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtpjyyamtq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtjqvnazlb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtdyledzfp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gtvnixawcj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtiynxtzts.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvcwahyp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtngrtjmsj.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gteldlsknk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtkczbflyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtbbqmmbya.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtqbkqxtgg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtyxpjitct.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtjeefxhye.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtmdkynkfw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gtyljtzeip.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtfkyunokn.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtedsplbbk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqvouyir.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtrzuwifqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwrpdzks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtdlmixnop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtaybvsrpp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtlplbqrkm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznrjokvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtdajmbnwb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtgprrwwkk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtqfblxnlo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtcrlwrnli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtmjdmzybl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtvzctxkwf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcdtisgtf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtmzlkyscm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtjkyrbzix.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtnnmgrkwf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuqfbtlfi.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtfcfokonj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthbzixquo.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtmcjddirq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfszqdpc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtvtdynubw.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfvxyjcgd.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsrgoqsry.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtihnvyuwe.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtvoneauwe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtdcrbetpk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjifxdfa.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrhiwxjm.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtssrygkqd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtrfrqmuyz.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtwkihjqps.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtcswrpajj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gttbheknip.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtystnyywp.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtwfnsjirl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtejxcsdvt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gteuybmvfd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtuqdxycmy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtvatkxyqi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtonlzneya.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtsczmtlqq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfvepcjgu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbrsdzcb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtqxxhavkd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtidqfpzan.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtmmrvcwrk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtgarkgyte.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtpwihuwfv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtckcqktmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokbmcqur.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtebpmzuon.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtsrporygg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtwoqtyacu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtcebrjkkz.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtiponznts.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxrvhjuf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtrxnmqvow.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtxjxfxboa.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtevbqunfr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gttagbmavk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtmcfuvihe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtpmhqdczz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtrpnregrk.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtzjmtrrif.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtqmdxforo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtrmqxfble.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtkxvmqkxu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtpxwtaqrd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtaqvieeao.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtotcqjqyb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtycvmktya.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtcyeuurmn.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtopcusdzo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gttugxrcti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtyhonmfox.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtbkgahfbz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtxohicoet.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtmcnrvdrh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtfrnvsrfr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gttsjiicko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtedrbnrok.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgwdsrzd.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gttkuqycut.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtcsvznwcf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtahqrawou.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtistvlsqy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtfqgsywxo.html


<!-- 参考信息 -->