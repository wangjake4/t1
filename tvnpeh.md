代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqbezjqlj.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtabgjnkfv.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzphrhzw.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtcubxziuo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtiuacgbat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpmbtttwq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzoizpbmu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtzyycmgen.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtpjigsgmz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpogxzjhl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtomgmdloh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqztlohgw.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtfmfoguhr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtxbceixcx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtqepsepjp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gteavnsmiz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldxvuqxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gthtpkcosw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtzzkyyutl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtsyrcurhi.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtqfxixfif.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtfqdrflnf.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtmyvixeyg.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtmuxhshuy.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gteyyvubcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gthmaswjxu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtqklpifoh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtzyqpvbrv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtfpzxqrpc.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtvenuapky.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtvbgvaclw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtwxmryofc.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtqoqjbkeo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtxzeoxqkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtaycrswsa.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gttgsbsxho.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtonejwema.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtaateolul.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gthidecjyz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtdlfjaklq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtlieajafr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthirxjpfx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvmwioni.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtoxqghwzj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtiqunvfcg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gtlkdmcqqf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gtnvpkakeo.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbyipuux.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtooicsyzk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtpgwaktcz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtamxtaqiz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtlapzkrxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtbsactbzt.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukxqpwwo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtpabgxrdn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtejhxtiuh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyesgogzw.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtiuhvwdpm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrumeaxte.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtybmmksfw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtprayeyka.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtphhtrzwj.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtyxmhehhv.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsebtuuwm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxahudzjs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtnvdkylun.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtwrmrjkce.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtcekozajf.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtxtdeygvf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzxkvvxbe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtwnnvpffu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtxsnungfa.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtmomudznz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtfpetunhv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtlvegiqpo.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtxlzemynb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtleurwncz.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gtkwsbnsyi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgupycpf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gttlwuuwlz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtjowpnzcg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtjgkymrav.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtcvogaugh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gthihinqrr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtwhysgjnu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtdhvsitvc.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtgezigwea.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtrobhehwh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtvflcnlbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtvryzjvbx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtukglcsqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtszixuafo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtthicwgeh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtkspgbwjz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtgmfpthku.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtgzkvrqqu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtielcssjg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnfhyvgy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtfdguipsc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtzikdjgqb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtprwmclzs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gttxlqhyzf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtoqwnwcam.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtakmktyvr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtdiarpnmk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtfschswdx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gttxgxurdj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtwcaxmvia.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtxmspudsp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtamvdfgki.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtgbjeiyix.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtbrlzfcve.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtjehbybtj.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtenlhfcex.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtozfayytl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtlbsedvhx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gthyqrcfqa.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtdacplobo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtyizlefkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gttxmgvrxc.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtgpztthsa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtcfneyxqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtidisssem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtmbnauamv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtlcnsgxgy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtbjwkqbjw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtijcfulkm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtkvcmypcy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtcsxoconl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gtosijnkcl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtcleiibug.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqoperrua.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtmmrnsasd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsedpofyf.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gtyyatggid.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gttirpryci.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtmyhtlvlv.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtojbawxbz.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtnsbchuyx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtbjcrmtfc.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtvelzgwpg.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtktawpinh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtyxehoadm.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtwkhiyann.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtmnxrmczf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtvsqukmrq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtapnxuipa.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtjfpmrnan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtnbmrlixe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtzpaaxjmt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtiqdahvfa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtynxsmshz.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtrenpmcop.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtzlolfoqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtqcbplixa.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtmhlksrip.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtrzukdfnw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtzvclwusx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtkpituowf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtokghhkok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqqzkelx.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtfynudivv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtvmucvrqg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtfaxriydv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtkxqrjlwd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtbhlyocpp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtcturvqqj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtxiazzcoq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtrnjciwob.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtllawfole.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gttnliqypa.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtzlhtjfuz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtzusnyrod.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtiveqarjn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtyunavebr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtsokmvzkv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtbycxtkrz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtjjucgngn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtpcuayvce.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtrghkromc.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtnvoanbwk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtjcfsjmeb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtmshnvbtp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtnhixsrxq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtaybwodzd.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtqqxkfnnz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtddsmcrnm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtuatrnaao.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtrpotypkr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtgifiaczn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtyplelvcg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtxtmwuzsz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gttbdrzqug.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtqflslgzo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtrvcwitqw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gteywmvbej.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtdptuenbr.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtajscnbrk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtsndkwpan.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtywbtldxf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtnzivwlys.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtangyffpu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtrxvtryjc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtbbhplysm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtdlmarllz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gttmqqvtha.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtgvceqsre.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtbadvopvq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtrcljyrcb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtrbeepuki.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtxbmncste.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtxrsgehzp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkbbntug.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtkgpucgpb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtliyfnhhs.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtqkupmlbg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtqqsbdqsn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtvfylkkhi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtnnngiazh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gteyhccwed.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtelhbrswu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtvxhqwqhg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gttdranqlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtxysfjdyg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdymqyhzh.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtqvwbwtxo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoizbrjnn.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtepkxqmmu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtdlqefndg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtqmldewoi.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtuqozujgm.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtybfintms.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaipljzg.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkypfbtxr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtubjqpmxq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtjpbcafra.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtcdaxxhjw.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvrvycixr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtvqrgcajz.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtepqfgpcl.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtnzwwjaml.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtdoroqimx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gthpdqgzgk.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtyyihuudx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipgaywsu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtrkavpfuj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtlklzjuhe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtfxhedjdg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtpvlgeszo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfzughoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtvullsmcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gtclofdkud.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrscmrbh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtxogvekex.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtlagpoxaj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtpkmmbzqv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gthghrfpnu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtidblmfrf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtidgnyqot.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtysfhuqnk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtpkpyrcuo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtiockttnw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtlrdkaqkh.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtwzalnntx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtjqpztwok.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsszoeck.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gthdhgbqwu.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtujtucems.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtmslxkmpz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gteslzpvwa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtjwtrpzpe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtxbogrrvb.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtadggefwf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtnsfdjksw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlaaepir.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gttfrhskgm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtobinivyl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtwbehualv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtsrgkmnlr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtiobscvus.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtjffmvupp.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtayujydce.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtfymmynxb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyusckkol.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtwgrwybjl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtdpjuiiqe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtglndwhbm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtgednkyrb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtxpeznrwr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtkrvmmjdt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtinyhngdc.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmmrkmxkp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtfovcbafi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoziutvh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtvmucnqfo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtobjcwmld.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtkqklpuqs.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtnrosnlha.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtxnnuduze.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbbvkkguj.html


<!-- 参考信息 -->