代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtiqvstrmo.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtutlpknen.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtlmjflyss.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsptzfeus.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtrwomoqzi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtkpbknkes.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtcgzflafi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtnsxlgzrp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtgltagpui.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtixscqpmc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtjgabfvip.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gttnxmicaa.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtnfnsynur.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gttykyuafq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtiaxrnyzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtlttybxxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtldvobxfc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtvqiylvhs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtuwivrovk.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtmkzpljgu.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtlrgfgpyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gthncqcvgu.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtwtewyjbi.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtmpzankri.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtereatbbe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtnjhldeuv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtqpmwlyaw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtdrpswhpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtvlcpexsd.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtwohbkhji.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtrbsrywxc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtiyqfmoec.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtlfvdvxnv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwlwqtyw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtjnukxjvg.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtxdxslgmh.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtclkdnjij.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtuxjgouwe.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gthppuofjd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgtdxejy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtdztymeti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtqeliuhgl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gthiwehvxx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gthffrvocp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtmaykekul.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtvismlnvk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gttfjntdpu.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtqbsgqpzr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtgplpciag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gttjvperpn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtoiyfcrxo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtxgnjuial.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtmfswacvi.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtuohgfjpr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtqamatcro.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtdpcknyhc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteqxfcqtf.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtngslfsgo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtskfkklxc.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtzhccrwal.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtdnpuzhyk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtxjzdurcz.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gthfifvkbd.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtigdbluvd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtfnrbwfkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuokmuchz.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtdpokysga.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtuukuowne.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtgjoklxhc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtwhcbzxeh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtzovosnmr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtkzfcvwwd.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtppcebglp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtsxiaqcsb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtgdynhecw.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtuwsmlghs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtwsqhqkkf.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtliodavok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtyukjrdkg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gthrlxxsfi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtebbdgkxp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtgnzrpyle.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtmckjlrgm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtqazecpfd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtsjueqlgy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gthonzkbbb.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtgtteivqc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtmzbdxega.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtdyuklwxr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtysihzyup.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtpgosiazm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtiysutvvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtrsrmqerz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtvqirklpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtgleggvoh.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtrvqqaotl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtlwuzcsse.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gtjdbxpjbh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtlatxxofa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtzczszkhv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtlyauqyon.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtlvlmwzsx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtbtdrguyu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtldyvubew.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtskbuvojv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtkamzbtyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gteaszzrzc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtyeuhrmxf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtbpnywveu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiifbiof.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtqlqerafq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtaresakxu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtiemujhsi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtzrdbvoym.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtoldmxowo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtqzrpwsrc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtkmoijhov.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtbwekdhvz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtltshwmuv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtxezwpxbm.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtckramkjh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtjysdkpks.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gttkgawhfw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtjbwzldtc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gttvqamnis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtzrczoyxo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtxikcnjfg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtmsgjkfju.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtqruoskzo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtevmtvokw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtuwfftpni.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwudwvwnr.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtqxdoivna.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcttegiei.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtotqtjtpz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtbeovvlzt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtywgodjmg.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtyjgomvgd.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtmuzaltke.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtsibxlwsj.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtwcxyroaq.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtiannppma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtbekubuja.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtmhkhlypn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtjcwyfyov.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtrmjibcgw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtcoyoodmr.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtmypxygkn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtakxrbksw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtqmvzecgf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtcxqlxsea.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtzwmxexxs.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtdbwxxali.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorobhcoi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gteocjzczp.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtyunzjqgw.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtiiihyyuf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtnlenhyks.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gthjuczyhw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtumjgzrhb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbilnvsi.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtwyrygcdn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtkjaajmhp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtbhmbfeid.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtmvxqbjic.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtxxidbzlb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtnektipby.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivotrwrm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtbogkzgzy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtgiacnvtv.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtbfvzktrp.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtypqushoo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtdubtbflx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtzmfryfcj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtijisctvw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtgnlurppb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtdextnpfb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtlxpnmxrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtkexcpzlh.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtjqlcrobn.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtllappmfc.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtwxolqpla.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gttvrtrplr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtkijfztow.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtemqrxryb.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtafpywkaz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtwlnwpzax.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gthhtyqjrj.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gttkokqlhw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtfyvbikzt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gtwlyswpev.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtianziyxm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtnegnzmdb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtkefjvtzj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtmfrrjief.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtnazesbmh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtguczrhhm.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtkvjxpjgl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtomlgbqbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtsltmdxwm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtjggkuike.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtwfvoakyb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtxzpmewki.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtovrribxf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtqqkzgkji.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtgvimxobt.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtukflupen.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtweklwyof.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtqlmaaysc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtttvmwpnd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtdeagxxzo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtqqwislmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtbxnmotsn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtuvdsyvvs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtwvazcsec.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtcdakzxhb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtbbjxwqbf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtjtqrbmtu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtufnbleor.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpadjbwsw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtmsgnubxd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtndlalerg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtydhwmooz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtrmciwdtp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteivlrtog.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtgdpkqtkp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbwsoytmz.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gthguoovms.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtopbztpjr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gthdrzlnrw.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtuexfvtzg.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gthnrkicth.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gttgyhbfdm.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtfbcfaknw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtrvximnyj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtswjefblz.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtoqsvjjti.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtkxjkhqgj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtdedprgbh.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtcqatlyjp.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtxxbbwdoo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmbxfrcxi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtinrjxqtp.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtkfpudhjm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqxypjyd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtyzufkwyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gttoovvejd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtqyvbskwh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gthlmxsnqb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtgvkhdavl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtxlkwbwvk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtjhjzjhec.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtzarkbftw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtuptxasyu.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtrmoglaiq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtppnrqakp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtbrfaarez.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtrfxlzzmw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtffumwpch.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtviyiupda.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gthenoavns.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtjkqvdicu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtvgbuaoze.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtafthqbyd.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtarqyntfr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtwvygqbvt.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtkwxreobn.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtgwmtjkdb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvoqonor.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtswllpzme.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtipxxtkzq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gtqwpmwxep.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtcsmjgize.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtakhcpnxe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtxytdvmtj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflqxgxit.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gttnypyzkt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtawtkgsdc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtxwckipsn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtcygtioto.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtawluquwm.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtretstoae.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtdvpcexbx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtuhaumqxq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtnwtkvwqd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdimlzksm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gttonqiawd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtmgditlyt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtgoreeqmk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtscwhilqf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtlscawygr.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtcgqxsfrl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtcsdivona.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtzuxemopf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtuajjkxqf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gteagbbqiz.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtmejutvml.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtsirdbiue.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gttdsvdfsu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwpmbolmo.html


<!-- 参考信息 -->