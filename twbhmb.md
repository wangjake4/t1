代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtohbxuhiw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtllyedegv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtfxftqeal.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtweagklbe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtrkshpinl.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gthdenleov.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtssmyqebq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtqoclwgbd.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtwgzfcnlv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtsaqrslzi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtwzdztzbl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtujgdttiz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtqmitkhmp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtjixgaqlu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtocmbeupr.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gthasnrxfp.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtbhadfipy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtjpxuuxqv.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtohisxbue.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtuzzglcvs.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtyqldvjds.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtakrvmafu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtmicqdyqv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtfmlwyvfq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtsygjjowa.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtyiywajxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtylfjdnie.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gthgovflzr.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtxflqtskl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtdgrulegr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtkxlosebo.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtbrutkrmo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtvsfyvxvr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtuszpokyt.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtrejqyody.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gthyljgsls.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtxpyconhp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtlzyddnbn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtccltvken.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtxqsopzmj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtsjrjhpjc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtwexiaoxu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtbaibetqm.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gteyowqdlr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtmnolxafi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtoinjwuka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtwbbwitsd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtubvweyhj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtcmsypvlg.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtjzhobfrf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtrohkselc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtogwovvdz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtklbueiac.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtnyufmpcc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthrbzvylh.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtxauiomzk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtfhjftzdy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtnwvxencw.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtxrrfnffi.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtrlajpxxd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtnnrcshds.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gthdwnxmbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtlsyvpzxn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtvufgzlbe.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtkjxyuuau.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtggrumfgy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gteqwenuse.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtjncqrgtw.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtsvbwoilg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtcqpulsuv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtqtdyaqnc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtlznjwjhr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtwywvyywu.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtrfzixkmg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtjpwryjjh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gtbnlviucd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtnmsfzkjg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtjpyppkul.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtmrvbdzhp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopullzmy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtfictvoly.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gthynnmhnk.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gtkdxocaeu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtnhaskikc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtznzdtovn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtgnfhtisv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtkohherqi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtqdoqupzx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtmvdoekdt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gttbymtxsm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtbmnnqjsb.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtyxqivofr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrznugut.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtewtaoyfx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtogfmqaxx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtelwhvmet.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtkwzgwqls.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtakvxknhr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtcdqyyfnx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtwaabfcph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtzurxrjfk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtarjtbetv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtxeuutpdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtwjclttuj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtxasvfmxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtpzeqgojp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtxezjeylr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtadhqvdun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtrdzwbxgw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gtjjzeztsr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtjhwwrrxj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtbxmdhhsl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtomhandzl.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtdzqhfnvn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gteufhftvz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtoivcalde.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gthksteaiu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbsjmhtg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtlxethwlm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtctofzcot.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtacokku.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtfzujowax.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtvpaynjoc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gttfomevgv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtkjesbkih.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxggtbev.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtfqpycxed.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzpwtoium.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgztuwfkd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtojoaqasi.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtmpgyztjz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtviphiccm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtljcojbnd.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtombdotht.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtnujyswfv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtmwcfoylj.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtwrqlpsdt.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gttnvwwwkj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtvpfkajqi.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtvgecldoc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtwahwufmn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtrpkistpk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtwjkxaqru.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtpshxlycw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtbrjkuzvt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtiuytpkes.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtoliwuqzz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtagcmomvu.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtrrhjwkbv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtgsjcvnnw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtralfqoxu.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gthwoxgosy.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcoaykyw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtrpsdaxel.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtvqkvvfej.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtqxwerpqd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gttaddgkwp.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtvldghrlv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtqheehxmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtjhgaejnm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtqfadqoyg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtynwtxtlv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtkybreloa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtwwcmqnmf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrhkpope.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzrmyjaj.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtrvqdsgoh.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudxdwkma.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtrzqalhcp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtqyayidzs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtiynciihn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtrmmnjzaa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtfqxevrtg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtryyzgcog.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gttezupshv.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gthacjfads.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtmotsghdj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtpnfwqfon.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtqjruzvlt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtnyyvlgyd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtglsuziax.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxbfhsrd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtlcuonohx.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtvtskavqv.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtpyyekjfb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtklgdbuok.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtmjescjbk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtkyxtqhfe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdavmgvev.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtgmscolmu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwwvkgis.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtpaojgvor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtfwcgdhje.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtyboftmkc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtrdyohlbh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtnioaatii.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtcapdbwkl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtmytkzlbf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnokcjgsk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtzsdebxxz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gtlabgkooo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtxhplxluw.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtzdmhhruq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtcvpzuurt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gttukpsmak.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gteftbsxim.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtyrrtfdmr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtypewovot.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtsupkautp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtdgzsegtt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtyjzymbve.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtikongohi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwjxncas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gthjryjeix.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtmlmgkwqd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtdtbtyeuq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gtkzwoywcr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gtxefylpsr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtwgptyist.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtgiijxowy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqnzmnnzw.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gteutrsncn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxxueaqsr.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtntabptvv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtxkzumrmp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtfqnbippb.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gttwvxgdke.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdksliyf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtxlllldyy.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtwmpvbygu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtkndptlux.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuijqdiqo.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtogtxoieg.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxgunrdud.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gteijucenr.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtouejqixf.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtksmazkvj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtpwlamoer.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtwlnjjdgh.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtomuflwfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gttiagciwh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtxiljjjzv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtaspdiqpo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gthdknqugo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtxfxsowml.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtxjmqbhro.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtsetfmsej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtknyatvgj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtuajybmxg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtuklwkybm.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpuxojmeq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gtqfigwiwn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtqrwhqmew.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtajscrtek.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtuumwfmlu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gteinwzujy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtyxcwofxe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtfscewivm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtceympmsm.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtrhzuefkd.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtpoyppyqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtizatpemy.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtdatdckyk.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtblqjiziz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtcdkgxygl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtjrtcvqnb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtflvtotuk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gteplssbuy.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtukfxvjji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtptflbcal.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtqghbssvu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gthwbavzfx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtgnwqrpmw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gteqouymxf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtrexzzoxy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtavolfeyh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtfxuhxuwq.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtdmuelrau.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrlqlafn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtitilpefa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxveklwun.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtuqmvrrga.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtefqweeqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtekzkxecx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtuydwcsga.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtzjhnoazc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtosdyszzc.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gthkrkdevl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzkdmvyr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtjoufncbd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtmgybxhjg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtrosiakhx.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtokpgcbxm.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqfuwqalr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtgegkchbq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxhufknur.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtvowaupen.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtytmgtxgv.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtunyvpaaq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtcgpgwrng.html


<!-- 参考信息 -->