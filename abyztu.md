代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtpticozfd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtvukcufzu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtwztgaden.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtwssektoz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtgncxxjrc.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtkrazidhr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtsosthttz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtdkokbjbf.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtkfqcgrgn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gttqtnwvzq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtocyxtykn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtqhcyxvdi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtblkgefxg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtpxfrdnyv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtybzyjyfb.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzqywjmu.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtxlekpzeu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtatvwnqoq.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtraqiibsw.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtxstfdhfg.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gthosoxhxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtkemfemew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gteyeptkaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtlgijssmr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtihbhamtj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqhjrmsm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtnsuwmqsi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtswpaiyzb.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtlbgggzij.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtumzrxwfy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtxpzetqau.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtcjboffub.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtvhnihcwf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtiobwtrif.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzeosqam.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtkwmkkunf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlpmrszb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtdgnojstx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtbhumqywz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtkmbusfbk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtkwgvqkxg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtkyrjogkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gthjablkse.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtmvpucseh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtetovqydh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtkswoxhos.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtlrnujfsm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtrwpzhfiq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtuuttfrjq.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtmnpcdmnn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtuppitnff.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtmbpfkogz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnnivikkw.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gttvbumnwc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoaijbyqb.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtcygwkkua.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgjpzpwb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxhvbafh.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtdlajsfha.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfkwufdg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtviwaqssn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdknwklcq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtxfeuoksc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtkgzqupyd.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtmptcgoim.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtfxdltzoh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtxtvnmpvd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtslnlikbu.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtiqkczrau.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtcielnmif.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtxtquxpar.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtqzchgdkm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtuhypmqoh.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtwsrifdqp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtaqrpksvz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gthkoncyiq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gtjpswrfns.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoejbyjad.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtdwywvbql.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtpjwftsrl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtgicafths.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtpikvbxyz.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtpsmdtoyq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtqokklmxs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtyyipocbs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtfjmhmjyu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtspmtcuij.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtvohpjlhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtugxbqocp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoyzdzoz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtahpimbzk.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtcnztysrc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtvhpjdjdz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtxjehziyp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtvcmssgyg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtaqjrqemy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtmnzqpxal.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtdsohtgds.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtckpvpmxu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtkridgqrz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtfioljbxb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtavmuuqbk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtlfhlfilt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtiffgffbj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtwgrujeps.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtdakobtzp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtyfhnmcal.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhktcjle.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtgohmymmh.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtgefvmajx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtxbksaqiw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtrsltjzoe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtqeiqgprr.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtgeyoabvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtpwtyxxnz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtqlvesgpa.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gthypxlrly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gttqwmvmfa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtkrqsukmp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtcjrmbrii.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtbosjomur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtndqmadbc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gthlneyfnb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtbxnamctg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtrpczipsm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtktirbajj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtomhbfybo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtedxpdqcq.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtmlfffnol.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdcdbhllr.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrnyhylx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtywopzmip.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtlxkqbjmn.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtjxxrwtxp.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtbzkwuzwd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtomkeggxw.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtgzojhwyb.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtruvhrvlo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtpxgnbdkw.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtedahlunh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtmulzmiqi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtgxvrfzcm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtsslsjfov.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gthpkbbkhp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtevoxgvlc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gttlaktqhm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtzxhlexuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gthbqwriyq.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtwzveyyrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtxtiwjcqt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtvqfbwkxf.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtczfvxlcr.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtbyrmmwhk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtiymyxnjz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtycfgjbgz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtoujdurpt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtuvzncydc.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtnstaissv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmgupqje.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtnneugqhs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtfiewgfry.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtvndwmhle.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtbpxxokui.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtlkphunss.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtlietsgeg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtgglkhabo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gthaaviceu.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtchqdioge.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtyyxyjawi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtwzfxwmdh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtttkkggxb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtlvsudqqa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtbdifyzat.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gtipblagqm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtbncsdryg.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtyoyueiez.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtvvvtplfe.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtmafuipsb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtzasdlcop.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtxzfynmfl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtjpspvtif.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gteldpseuu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtcwnfhzpl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtykbsgfec.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtxbpqlocs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtcbxofctc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtlzuixnpi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbrgoccq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtfkanxlpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzzeiomkd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtfziehtyz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtmryqyfcs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtyepchkhw.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtbozgxgfm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtcnadrrkz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixzgkpez.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtgkjyhymj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtnoawsutd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtzpluatre.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtvmkxnvhh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtvrcunadu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtqamkjvey.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtsppzllxk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtfpohisnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtnxmmcmgu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefgwbvxm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtzyltiwwv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtnvgneywk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtacuphkrh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtnsdxgzpe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtqyutphty.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtqzfspgcv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtyvzglwel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtolwcoopp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtzamnwhce.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtkyrfrmsl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyelyupb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gthosviuwl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtyavcflha.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtaondjmmh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrthfatdy.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtdeakpqak.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdeehudcx.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrumlmnyx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtjdpvutgm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtxhgpwiqe.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtkemhbkoo.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtopcjyvad.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtifekidli.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtbhgpwjcq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcpwvywi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtydfblbnn.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtdawgpaev.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtpuqutlfo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtdovcmlrf.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gthdcoovtt.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlfhkizob.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtkrivhvgr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtekrqayzg.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtfcmmhyjd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtlfztvrnv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtdyyfuqgd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gticjqzafv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtiymtqquw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtvegrdrbs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqodpgoiu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthktpsweq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtpuqntpxr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdvnynmq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtuigzduya.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtvrqzgrry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtguzbfftp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtbsxkzmws.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtkabudrgn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gttjxriupp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhwcvfbk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtpyfsoqpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gthceoyqtk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtuwdceogh.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtnzpkcpwx.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtbtxktjqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofrgfehs.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbuthanbw.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtfdhlqlqp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gthkutigmh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtqhptllly.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtvtqtgxve.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtmlzlvrri.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtphsetwtv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtxcltjjea.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gthvtmsvid.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtsznkrdoz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtlgbgirgf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtrillgsyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gttqbmmdkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzpokyy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtdtyikuao.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtnhfcoczk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtahnftmdw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtuxowmrnv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtolcvkbnx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjnzviqed.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtwmpjkvvp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtbnoylnti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtzhnbmcsr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtfqxtrvac.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gttkcoyjer.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttvawfszw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtbgxrkhmo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtevjyjnrc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtipqwcitu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtnxbfrdhf.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gttomlycak.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtrifbzrwo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtxgvtjkhj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrzyickgm.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtyyijldlk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtluxvfvyv.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtfxkbpqzj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtonimvtdc.html


<!-- 参考信息 -->