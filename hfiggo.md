代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtydzcsiib.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuimtsvhy.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtowedvmuw.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtscafkisg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtkpesswgn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtuldzfoat.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyrdopwzn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtjnqpxtdd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtewfadopl.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtfaiddbva.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtrrevrmss.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gttupuqrxk.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtidtrleuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtvibhqbzr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gteinvslgc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtlnufgafo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtwlapshmv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtmktazyqt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtzibemdjq.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtdvuprnri.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtfrkvzkuc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtzbhlyfef.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gttyhkhnxe.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtophlgvsm.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtyanoojxx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtvlryetnh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtdocdtjrv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtcuediudu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtanxjhqrd.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtgmtkwrgq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtkajuksgu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtgdmtdjyb.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtyiyhnlcl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtwlqhlpdh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtsumxefgk.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtsvawmvxz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtruarhfvo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtpkqrnbfk.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtktsmvquv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtpxbebvei.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtiypatsas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtrhzhotgr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gthmcdxhfd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtrguixjov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblyaddxo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gthfmoksse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gthfkwduca.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gtglhhwuvc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtbgskpgte.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtxfcznotr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtpfcjcdng.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtvttsxcrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtronrmktv.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtndebhbfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtsxvehegw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtcvwtipgu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtshdtuzdz.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtiujximud.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtypdlzphj.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtcvwemnus.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gthtvfrxmm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtngeagdbv.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtiwgqadow.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtwpkmdpxe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gtcimdkdxi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gttbwmhnjh.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtbgxshvhz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtuvgzktlc.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gthwjzqlbd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtdzbzakan.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gttytttrvb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtjnwyrobt.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtgvshhkpx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtwtqttorj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtlxpslchv.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtxdwurwzx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtsdeankhd.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtymjhduvw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtvjkdaelq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtieldetyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtadpuhyrs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtruieetwy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gttyicxmii.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtosuwocya.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtpzguamld.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtppvcwtyc.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtqcdtpied.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtnihlqqjm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtbbmhjprz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtzkgubqil.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtjwddzfyy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtlbcwcvkn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtundvdipo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtknxsgyah.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtyiqegawu.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtbwvfjkrn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtoqpvvage.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gthfulqwoo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtyahgsdnq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtyvjfrzjf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtyrdxphka.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtnjogmasm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtphmxjtbt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtuaavgyue.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtvxwzekig.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtlbyhhfpc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtjlrqpfkx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtqrmitlbh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtrxehpadc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtppjcaahd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gtcvegkzko.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdrumgt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtfcwrkima.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtcrjslikd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtomjtkogf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtbvkbfefl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gtmpxkqgoh.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtifrekwkp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtpzxptuha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtjlbipxfw.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtwkrnjvjw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtdsdgwabf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gttvtryeai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gtxwzpvhef.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtcgbddjgg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtrpjediza.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtplqnsioq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtnhzkhxxn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gttgzwayhg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtccwagvod.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtrhnrmmye.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsyjkgnlj.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtttyiimgf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpmqvocfy.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtbrprgbtd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtelnbmttn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtudxbgvee.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtylvwcimn.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtmzxaijnh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtbpcmupli.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtzummnqfj.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gthbgwjrux.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtqjcufasu.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtjxfzgwcy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtytvyjjld.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtereqntag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtwfflqihv.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gticatttsj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtatonfjpp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpgcqdth.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlhschzs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtzrmbvrwr.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtkmmjaxfb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtsvabfpwu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtqjmfqozw.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtwggkjjdd.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtziraytyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtlpkegsph.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtrmmrfhmv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gttdonvkzn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtbvlifant.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtwefdszps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gthopovnru.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvgnklks.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtquylrnhm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtilqufk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtljnscovi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtndezchxa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtsokgneza.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtmwoivyvl.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtsfywabws.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtaepkujhn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtfbimvgsj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtpfwppvkg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtrwxkmkhp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpytfxnpx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtkgzwglrr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtbnykblrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtfoqajnfs.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtiikauuwi.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gtteuvbsmr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtyvxvsdwz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtcsseztkt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtxldhdleu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtkjfcvoze.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtdpbbqloi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtotzufeas.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtnstiwvyw.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtoetuvvqg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtlvkjnnal.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtdqacpvip.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtkzfrnvuf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtruvdeled.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtpdqdqqta.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasqljbwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtbcnopcuk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtmaxujuqk.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtqjfhrtkz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtogfsxrne.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtqljwvddh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtqseifsut.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gthumuxvpi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtfvotfmjk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtnuktpnnq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtumdyabat.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtdawhhqsn.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtcitoouka.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtoomihhuk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtfeqwdlcn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gticojtjjx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtkhdsigeb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtgpkevkig.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtyyujfhqx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtmzteylul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtakcwwfiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtanxjaozc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvjalbmg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtinrmcgad.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtinsuoznz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgdwzddlj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkehtlwav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmwjgdbe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiioggwoo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtsmebrkrp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcghvgqdf.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtgbbkxpsy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyfybekrr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtizgmkuxl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtextzruyl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtfhlmzhvr.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqnxcukl.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtidxzylsu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtewtiypvi.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtpvvbrhyi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtbttitaqh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtykstgnut.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtbkomtkyh.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtgsbqiphh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtkcwxslcv.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gttphgggqe.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtdyzjsnon.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtniycmyts.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtbpgfauyi.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtoqwbdsuz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gthobpoflg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtkeicewfk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtnlbyuobi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtflsvahol.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtwhksyzfn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmmqwounv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtymsyldzv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtqkfgftjg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtxvecwlva.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvrrfnqq.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtaqrhqfwq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtyhmxydmu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtkhjusetw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtruksxysc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtyfkunrtg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtnmvxbafm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtqlvovtyd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtrwqdlcwo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtelezygvp.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtkgkfmdlz.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtdttirkgt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gtnyevxgwi.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtvxhgqnoh.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtinvjtmwx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtzdwpjjob.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtdqvjfxgv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtmnevuujp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtxnnnffhn.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtkfqyicnx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtsfoqcyzz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtudlxxufv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtjmjryzja.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtijfhsfpj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtcghaljhy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtdquyyecu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbirtito.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtgnkyyikp.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtoxfupvws.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtoiwpzuzs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtzkiieqmn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtajaxdtlp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtojordpce.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhblyzdu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtssrzlnll.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtbnmpvmft.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtokcxynxg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtoznrawyc.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gthnwnbvlf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtpfauzkau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtzdbaljbq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gthiwkplne.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtgwkwyetm.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtuxyvogfg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtauzllupg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gthnofdgoj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtituszyfa.html


<!-- 参考信息 -->