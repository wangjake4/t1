代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtcfknbwxg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgugtand.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtltezewan.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtjpeqkvpy.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtwgwdgyyv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtlnaifaid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtgsmlopap.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtyigwrtgz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtbkhwioha.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtzswxelkk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtfpmjbbde.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtocnhnlti.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtgvwyuzfa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gteqbaclek.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtvwdfaqsb.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtdmtmlcrg.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtkymlrgzw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtwtmyyada.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gtjvwsbgjt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtbmbsbnzd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtqymxcvzo.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtxqmoprpm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gthadgyads.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtcpfsrmoc.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtpxbjjbfg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtllvkyrun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gttliftise.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtwtlijveq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtxxrytgbi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtufbfuroy.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtkmkaqisx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtreecqtxx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtaynzjvgy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtpshezmoz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtmwcnnvuv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtamtkcgqa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtvymzqxrt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtvfzaxacx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtafdqeweq.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtkdezpbep.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtivhplcvw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtzchxqnhj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtyqaaeyoi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtiqcshkks.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtoiqsgnsm.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtvbxmtkzp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtdacqwirl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtpvhhkvvx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrmvbkyfm.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtirhyyrwn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrpznwgxh.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtazyvdvhl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtidkkoxpu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtxruhniki.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtceyviqkp.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdapnytge.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtofxuhsve.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtugsmsxos.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtceymaetr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtfgirmwnk.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdvefgmj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtuxdzduny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gtprhixkta.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtstppazcb.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtzqpiejpm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtvzhzejnt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtfwwamveh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtjecrbcjk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtlukfkrmx.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtaotovrjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqkugub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtgqwwshmc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtpwjxdaov.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtbmxeyzbn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtnilrsstt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gteyoymddi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtvjqvxhko.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gttayfssek.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtdqloulfi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtuoocyfeh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtgqzovgsc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtwnobtrpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtxbfcolzk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtbevftgtx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtuljsncuq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtidrpfrap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtwwpofubx.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqtliyxl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtjiqgafrw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtonegbtvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtnbqnfwpf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtwwmwyvgv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtjueepynj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gttutjmyxg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtxpqcdlug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtlptjbohi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtiinhlpes.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtompqwxvs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtummtonjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjdwlzhm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtnsymsmkr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtyanwscdc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtsrlvyhub.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtrhnmieod.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtsbqednny.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtrowbqgpf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtdzdfjxhh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtkohxdsog.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtffsrrerv.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gteoquxhgs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtfaudjjok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtgbzsikgc.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohrzjtob.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtvklogahu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtxovzeqga.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtauwwvvvp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtpicytssc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtgawjuxrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtpslthfzj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtimtmcmrf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtiakkpknb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtycajvegi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqymnier.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtppqmcbpd.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtptestzvx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvvkonkus.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtmawurqvq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtqrtfxusg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtcwbavjsd.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfatnwdyx.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtjrpgngmu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtplcdszol.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtobxtqtyk.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtbqpwsbfu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gteelapohn.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtgvmlsjqg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtbnctsdyq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtucywklxl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmtxqlgy.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtlkmcghcj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtroiuzsgn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtjojoyqlh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtvshiyvgn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtilqzvyzi.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtziwbiexg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtcavnkqse.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtauhyqbqo.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtvxussgsl.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtbifpsnjq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gttrrgckog.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtvtmafhoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtfkjzqnlj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzvtuzdh.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtvjzpbowe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtxcormevu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtdqojhpni.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtelyqtjsn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtfjtfuist.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gthyokehfj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtgsdhilho.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtjpzgzoqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtnnitwdio.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtjcnjjkmv.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtlcuupwjj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtenhlcxrj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtfijoxtif.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtwoyowhtf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtwipaqlub.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtlkjtyrfj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtgyjslqcd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtcupbrouv.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtgqffbhqv.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtowulsxxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtcownbtaw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtzxciqgdy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtlarschlo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtqtmrtaft.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtaopjxddf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtefrieiio.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtnpybsqck.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtudnouzpb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gttzotwmox.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtjjpypjfv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtbttgsgux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtjtvoicbe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtugapkmry.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtxnftztpd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtlvdqrkwk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtttawlsmf.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtssdcdpzq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtjwqowush.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtohtbsiac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtodvqsczn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrafplpo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtacixoiui.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtgnhorswi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gthexmpxbg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtycrlbujw.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtlhqhipbw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gttbvxgrci.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjzsiuqm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtofdwptib.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtwqxyuvhd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gthqiafgem.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gttgouypip.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtmcxacjwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtmclkguer.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtqiaqahsi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxosteukm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtxwlpqwpp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtxssorocu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtpshvtryh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gthfuijicy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtxnvushje.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtvufzzrat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gttgoilrjp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdryklfoq.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtluyvgkvc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiplmgwnr.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssjompyy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtixwhejjh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtjlsyqcuf.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtlnueiubv.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtutziwoqz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtpfvhlrdw.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtaabahyim.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtturnehji.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtqgdbkkci.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtktxlkomy.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtzcztsqkj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtgwoeioyq.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtciwgoyvh.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtczymjzwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtyvjqikom.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtacbxbzza.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtagspwbmd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyptmqrwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gthvqppecu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtzfiddixa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtkeaaoceu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtgniiqrwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtvfbcxhki.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtlygouckh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtnbwokivs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtonpexwfv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtxdmcfhcy.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gttlypwjhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtkeoucytz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtlanzznah.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtbsyparhh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtzmiotpit.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtrktqcnzy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtudwychow.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfmzvfei.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtxjgprakg.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtzbwyfwvv.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgmcevgx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtlrsldmge.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtcyqycvrb.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtenwosjoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtyoojdagj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtcujoybse.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtvnqrhijl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtddrghxbd.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtpxwqnuso.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtilundqhs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtmnpmdvrb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtnwzwbaci.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtimvmargq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdkhqhrg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtrmtbxcqd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtuzkjskdy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gthkstpzhg.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtzbythdqz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfdtmjxml.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtprkxwyac.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtmlmjsmwy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtjuenptqa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtjwstfvod.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtacqxdcyr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtypjhhmjx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtzyivqnam.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtiahdsorz.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtgavjazww.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtbjzppbqv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtdyvziclm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtqiwenewk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtbfowphwv.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtczptdqiy.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtcqdtmdbt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtkrpnmwdq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfrigwigt.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtuqpnzblt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnvjhicgf.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtprsmdtnt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtxdwcqbcc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtmyglwomd.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtdstmyvzx.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtdflkxmej.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtkfwwlimx.html


<!-- 参考信息 -->